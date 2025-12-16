# Guardian Workflow Setup Instructions

The Guardian workflow protects The Foundry's enforcement system from unauthorized modifications.

## How It Works

1. **Protected Branch**: `protected-workflows` contains canonical versions of workflow files
2. **Guardian Workflow**: Monitors `main` branch for changes to `.github/` files
3. **Auto-Restore**: If workflows are modified/deleted, Guardian restores them from `protected-workflows`
4. **Branch Protection**: Only admin (`nickarrow`) can push to `protected-workflows`

## Protected Files

- `.github/workflows/enforce-ownership.yml` - Main enforcement workflow
- `.github/scripts/enforce_ownership.py` - Enforcement script
- `.github/workflows/guardian.yml` - This guardian workflow (self-protecting)

## Setup Steps

### 1. Create Protected Branch

```bash
# Create protected-workflows branch from current main
git checkout main
git pull
git checkout -b protected-workflows
git push -u origin protected-workflows
```

### 2. Enable Branch Protection on GitHub

1. Go to: Settings → Branches → Add branch protection rule
2. Branch name pattern: `protected-workflows`
3. Enable these settings:
   - ✅ **Require a pull request before merging** (optional, for extra safety)
   - ✅ **Restrict who can push to matching branches**
     - Add: `nickarrow` (only the admin)
4. Save changes

### 3. Test the Guardian

Try modifying a workflow file on `main`:

```bash
git checkout main
echo "# test" >> .github/workflows/enforce-ownership.yml
git add .github/workflows/enforce-ownership.yml
git commit -m "Test: Modify workflow"
git push
```

Within seconds, the Guardian workflow should:
1. Detect the unauthorized change
2. Restore the file from `protected-workflows`
3. Commit the restoration

Check the Actions tab to see it in action!

## Updating Workflows (Admin Only)

When you need to legitimately update workflows:

```bash
# 1. Update on protected branch first
git checkout protected-workflows
# Make your changes to .github/workflows/ or .github/scripts/
git add .github/
git commit -m "Update: [description]"
git push

# 2. Then update main
git checkout main
git merge protected-workflows
git push

# Guardian will see the changes match and allow them
```

## Maintenance

- **Guardian runs on**: Every push to `.github/**` + every 6 hours as backup
- **Logs**: Check Actions tab → "Guardian - Protect Workflows"
- **Disable**: Only possible by deleting from `protected-workflows` (admin only)

## Troubleshooting

**Guardian not running?**
- Check that `protected-workflows` branch exists
- Verify branch protection is enabled
- Check Actions tab for error logs

**False positives?**
- Ensure `protected-workflows` has the latest canonical versions
- Guardian compares byte-for-byte, so formatting matters

**Need to disable temporarily?**
- Delete `guardian.yml` from `protected-workflows` branch
- Re-add when ready to re-enable
