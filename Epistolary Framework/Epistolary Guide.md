# Epistolary Play Guide

> A framework for collaborative, asynchronous storytelling in The Foundry

## What is Epistolary Play?

Epistolary play is a style of collaborative storytelling where multiple players contribute to a shared narrative through **letters, messages, or journal entries** written in-character. Each player plays their own game, pursues their own adventures, but periodically writes a letter that advances a **Shared Vow** — a goal that spans the entire campaign and connects everyone's stories.

This format works beautifully with The Foundry's ownership model: you own your letters, others own theirs, and the shared narrative grows organically through addition.

**This guide covers:**
- [For Players](#for-players) — How to join and play in an Epistolary campaign
- [For Organizers](#for-organizers) — How to set up and run an Epistolary campaign

---

## For Players

### The Core Loop

1. **Play your game.** Run your character through adventures, vows, and encounters as you normally would.
2. **Write a letter.** When your character does something that advances the Shared Vow, write an in-character letter describing what happened.
3. **Mark progress.** The Organizer marks progress on the Shared Vow. Other players can take note of the nature of progress, including any story elements or impacts.
4. **Wait your turn.** You can't mark progress twice in a row — someone else must contribute before you write another progress-marking letter.
5. **Repeat.** Keep playing, keep writing, watch the shared story unfold.

### The Shared Vow

Every Epistolary campaign has a **Shared Vow** — a significant goal that multiple characters across multiple locations are working toward. This vow responds to **The Trouble**, a threat or situation affecting the entire region.

The Shared Vow is owned by the Organizer, who tracks progress based on player letters. You can't edit the vow file directly (The Foundry prevents that), but your letters drive its progress.

**Example Troubles and Shared Vows:**
- *Trouble:* A tyrannical faction is consolidating power across the sector
    - *Shared Vow:* "Expose their atrocities and rally resistance" (Extreme)

- *Trouble:* Ancient horrors are awakening across the Ironlands
    - *Shared Vow:* "Discover the source and find a way to stop them" (Extreme)

- *Trouble:* A cursed fleet is preying on trade routes throughout the isles
    - *Shared Vow:* "Hunt down the fleet and end their reign of terror" (Extreme)

### Writing Letters

Your letters are written in-character. They might be:
- An actual letter to another character or faction
- A journal entry or captain's log
- A report to a contact or superior
- A message left at a dead drop
- A recording transmitted across the void

**What to include:**
- What happened — the events, encounters, and outcomes
- How it connects to The Trouble and the Shared Vow
- Whether you're marking progress (did your efforts succeed?)

**What you don't need:**
- A specific format — write however fits your character
- Mechanical details — focus on the narrative, not the dice

### The Pacing Rule

**You cannot mark progress on the Shared Vow twice in a row.**

After you write a letter marking progress on the Shared Vow, you must wait until another player marks progress before you can do so again. This prevents any single player from dominating the shared narrative and ensures everyone gets to contribute.

You can still:
- Play your own game as much as you want
- Pursue your own side questsions, personal vows, and adventures

### The "Yes, and..." Philosophy

Epistolary play runs on trust. While The Foundry's ownership system prevents you from editing other players' files, you can still write whatever you want in your own letters. This is where "Yes, and..." becomes essential.

**What this means for your letters:**
- **Don't narratively destroy what others create.** Avoid writing that another player's character died, their ship was destroyed, or their faction was wiped out. Their creations are theirs to conclude.
- **Build on, don't bulldoze.** Reference others' content as inspiration, not as targets. Add to the shared story rather than subtracting from it.
- **Treat others' creations as living stories.** That character, location, or contact might still be in active play. Write as if the original creator might continue their story tomorrow.
- **When in doubt, go adjacent.** Instead of writing definitive outcomes for others' content, write about rumors, near-misses, or your character's *perception* of events.

**Good:** "I heard the *Crimson Tide* was spotted near the ghost fleet's hunting grounds. Captain Vance is either brave or foolish."

**Bad:** "The *Crimson Tide* was destroyed by the ghost fleet. Captain Vance went down with her ship."

The first leaves threads for others to pick up. The second closes doors that aren't yours to close.

### The Endgame

When the Shared Vow's progress track is **completely full**, the Organizer will make the Fulfill Your Vow move. After that:
- Each player gets to write **one final letter** wrapping up their character's contribution to the story
- The Organizer then writes a closing narrative

The requirement that the track be full (rather than just having enough progress to attempt the move) ensures everyone knows when the endgame is approaching and can prepare their final contributions.

### Where to Find Things

Letters are typically stored in `Lore/Epistolary/` within the campaign folder. Check with your Organizer for the specific location.

The Shared Vow file will be in the campaign's Progress folder, owned by the Organizer.

---

## For Organizers

### What You're Setting Up

As the Organizer, you're creating the stage for collaborative play:
- **The Campaign** — The world, setting, and context
- **The Trouble** — The threat that spans your region
- **The Shared Vow** — The goal players are working toward
- **The Infrastructure** — Folders, files, and documentation

You don't control the story — you facilitate it. Players drive the narrative through their letters; you track progress and maintain the shared elements.

### Step 1: Create Your Campaign

Use Iron Vault to create a new campaign in your folder. Set up:
- Your campaign file with truths/setting details
- Your region (sector, ironlands area, archipelago, etc.)
- Any starting locations, factions, or context you want to establish

**System-specific scope suggestions:**
- **Starforged:** A sector works well as the natural boundary
- **Ironsworn:** A region of the Ironlands, or a specific area with defined borders
- **Sundered Isles:** An archipelago, trade route, or stretch of the Cursed Seas

But don't over-prepare — leave room for players to create their own locations within your region.

### Step 2: Define The Trouble

The Trouble is the inciting threat that the Shared Vow responds to. It should be:
- **Broad enough** that multiple characters in different locations can encounter it
- **Significant enough** to warrant a major vow
- **Open-ended enough** that players can engage with it in different ways

Good Troubles affect the whole region. They might be:
- A faction expanding aggressively
- A supernatural phenomenon spreading
- A resource becoming scarce or contested
- An ancient threat awakening
- A plague, curse, or corruption taking hold

Avoid Troubles that are too localized (a monster in one cave) or too personal (one character's nemesis).

### Step 3: Create the Shared Vow

Create a vow file in your campaign's Progress folder. This is the mechanical heart of the Epistolary game.

**Choosing a rank:** The vow's rank determines the minimum number of progress-marking letters needed to fill the track:
- **Troublesome:** 4 letters
- **Dangerous:** 5 letters
- **Formidable:** 10 letters
- **Extreme:** 20 letters
- **Epic:** 40 letters

**Extreme** works well for most Epistolary campaigns — long enough to feel significant, short enough to actually complete. Go Formidable for a shorter arc with fewer players, or Epic if you want a truly long-running saga.

**The vow should:**
- Directly respond to The Trouble
- Be achievable through varied approaches (combat, diplomacy, investigation, etc.)
- Allow for partial successes and setbacks along the way

**You own this file.** Other players can't edit it (The Foundry enforces this). You'll update progress based on their letters.

### Step 4: Set Up the Letter Folder

Create `Lore/Epistolary/` (or your preferred location) in your campaign folder. This is where players will drop their letters.

Consider creating:
- A brief README or index file explaining the campaign's Trouble and Shared Vow
- A link to this guide
- The Letter Template (optional)

### Step 5: Document Your Campaign

Write a campaign introduction that includes:
- The setting and region
- The Trouble (what's wrong)
- The Shared Vow (what players are working toward)
- How to join (create a character, start playing, write letters)
- Any specific guidelines for your campaign

### Running the Game

**Your ongoing responsibilities:**
1. **Monitor letters** — Read new letters as they come in
2. **Track progress** — Update the Shared Vow when letters mark progress
3. **Track turns** — Note who marked progress last (they can't mark again until someone else does)
4. **Maintain context** — Keep the campaign docs updated if needed
5. **Facilitate the endgame** — When the track is full, make the Fulfill Your Vow move and invite final letters

**You don't need to:**
- Approve letters before they're posted
- Coordinate player schedules
- Write letters yourself (though you can if you have a character)
- Resolve conflicts between player narratives (The Foundry's ownership model handles this)

---

## Quick Reference

| Element | Owner | Location |
|---------|-------|----------|
| Campaign files | Organizer | Campaign root |
| Shared Vow | Organizer | Progress folder |
| Letters | Individual players | Lore/Epistolary/ |
| Character files | Individual players | Characters folder |

**The Pacing Rule:** Can't mark progress twice in a row. Wait for someone else.

**The Endgame Rule:** Fulfill Your Vow only when the track is full. Each player gets a final letter.

**The Foundry Rule:** You own your files. They own theirs. The world grows through addition.

