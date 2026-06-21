---
name: Barille Black
xp_spent: 0
xp_added: 0
momentum: 3
edge: 1
heart: 3
iron: 2
shadow: 1
wits: 2
health: 0
spirit: 3
supply: 5
Quests_Progress: 0
Quests_XPEarned: 0
Bonds_Progress: 0
Bonds_XPEarned: 0
Discoveries_Progress: 0
Discoveries_XPEarned: 0
iron-vault-kind: character
assets:
  - id: asset:starforged/path/brawler
    abilities:
      - true
      - false
      - false
    controls: {}
    options: {}
  - id: asset:starforged/path/bounty_hunter
    abilities:
      - true
      - false
      - false
    controls: {}
    options: {}
  - id: asset:starforged/support_vehicle/snub_fighter
    abilities:
      - true
      - false
      - false
    controls:
      integrity: 1
      integrity/battered: false
      2/victory_marks: 0
    options:
      name: SN27
FailureTrack_Progress: 0
FailureTrack_XPEarned: 0
initiative: false
callsign: Black
pronouns: He/Him
player: NickArrow
description: "Often wearing his dark blue suit, loosened at the neck. Barille has dark curly hair, and the stubble of a beard. Character goal: Gain Riches, Seek Power."
wounded: true
---
# Barille Black
<center><img width=150 src="The Starforged/Campaign Barille Black/Characters/Barille Black/attachments/barille black profile.png"> </center>

```iron-vault-character-meters
```
> [!tip]- ASSETS
> ```iron-vault-character-assets
> ```

> [!abstract]- NOTES
> [[Barille 01 - Beginnings]]
> [[Barille 02 - Reck]]
> [[Barille 03 - Searching Through Reck]]
> [[Barille 04 - Name TBD]]

> [!example]- TRACKS IN-PROGRESS
> ```dataview
> TABLE WITHOUT ID file.link as "Vows", floor(progress/4) as "Progress"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
> WHERE track-type = "Vow"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```
> 
> ```dataview
> TABLE WITHOUT ID file.link as "Tracks", floor(progress/4) as "Progress"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
> WHERE track-type != "Vow"
> WHERE track-type != "Connection"
> WHERE iron-vault-kind != "clock"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```

> [!info]- BONDS
> ```dataview
> TABLE WITHOUT ID file.link as "Bonds"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
> WHERE track-type = "Connection"
> WHERE character = [[Barille Black]]
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
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #complete
> WHERE track-type = "Vow"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```
> 
> ```dataview
> TABLE WITHOUT ID file.link as "Tracks", floor(progress/4) as "Progress"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #complete
> WHERE track-type != "Vow"
> WHERE track-type != "Connection"
> WHERE iron-vault-kind != "clock"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```