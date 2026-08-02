---
name: Rowe Darwin
xp_spent: 0
xp_added: 0
momentum: 7
edge: 1
heart: 2
iron: 3
shadow: 1
wits: 2
health: 4
spirit: 5
supply: 4
Bonds_Progress: 0
Bonds_XPEarned: 0
Discoveries_Progress: 0
Discoveries_XPEarned: 0
Quests_Progress: 0
Quests_XPEarned: 0
FailureTrack_Progress: 0
FailureTrack_XPEarned: 0
iron-vault-kind: character
assets:
  - id: asset:starforged/path/firebrand
    abilities:
      - true
      - false
      - false
    controls:
      fire: 0
    options: {}
  - id: asset:sundered_isles/path/swashbuckler
    abilities:
      - true
      - false
      - false
    controls: {}
    options: {}
  - id: asset:sundered_isles/companion/monkey
    abilities:
      - true
      - false
      - false
    controls:
      health: 3
      health/out_of_action: false
    options:
      name: Darwin
initiative: false
---

```iron-vault-character-meters
```
> [!tip]- ASSETS
> ```iron-vault-character-assets
> ```

> [!abstract]- NOTES
> [[Sundered Isles - Patrocia/Campaign - Rowe Darwin/Journals/Session 0|Session 0]]

> [!example]- TRACKS IN-PROGRESS
> ```dataview
> TABLE WITHOUT ID file.link as "Vows", floor(progress/4) as "Progress"
> FROM "Sundered Isles - Patrocia/Campaign - Rowe Darwin/Progress" and #incomplete
> WHERE track-type = "Vow"
> WHERE character = [[Rowe Darwin]]
> SORT file.mtime DESC
> ```
> 
> ```dataview
> TABLE WITHOUT ID file.link as "Tracks", floor(progress/4) as "Progress"
> FROM "Sundered Isles - Patrocia/Campaign - Rowe Darwin/Progress" and #incomplete
> WHERE track-type != "Vow"
> WHERE track-type != "Connection"
> WHERE iron-vault-kind != "clock"
> WHERE character = [[Rowe Darwin]]
> SORT file.mtime DESC
> ```

> [!info]- BONDS
> ```dataview
> TABLE WITHOUT ID file.link as "Bonds"
> FROM "Sundered Isles - Patrocia/Campaign - Rowe Darwin/Progress" and #incomplete
> WHERE track-type = "Connection"
> WHERE character = [[Rowe Darwin]]
> SORT file.mtime DESC
> ```

> [!warning]- IMPACTS
> ```iron-vault-character-impacts
> ```

> [!error]- LEGACIES
> ```iron-vault-character-special-tracks
> ```

> [!success]- TRACKS COMPLETED
> ```dataview
> TABLE WITHOUT ID file.link as "Vows", floor(progress/4) as "Progress"
> FROM "Sundered Isles - Patrocia/Campaign - Rowe Darwin/Progress" and #complete
> WHERE track-type = "Vow"
> WHERE character = [[Rowe Darwin]]
> SORT file.mtime DESC
> ```
> 
> ```dataview
> TABLE WITHOUT ID file.link as "Tracks", floor(progress/4) as "Progress"
> FROM "Sundered Isles - Patrocia/Campaign - Rowe Darwin/Progress" and #complete
> WHERE track-type != "Vow"
> WHERE track-type != "Connection"
> WHERE iron-vault-kind != "clock"
> WHERE character = [[Rowe Darwin]]
> SORT file.mtime DESC
> ```

