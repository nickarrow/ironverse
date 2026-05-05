---
name: Barille Black
xp_spent: 0
xp_added: 0
momentum: 1
edge: 1
heart: 3
iron: 2
shadow: 1
wits: 2
health: 1
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
---
![[barille black profile.png|100]]

```iron-vault-character-meters
```
> [!info]- ASSETS
> ```iron-vault-character-assets
> ```

> [!tldr]- GEAR
> - A compact multitool capable of 'light' matter manipulation
> - Hand terminal
> - Kinetic pistol
> - A leather bound journal and pen
> - A coin of black iron, embossed with an insignia

> [!example]- TRACKS IN-PROGRESS
> ```dataview
> TABLE WITHOUT ID file.link as "Vows"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
> WHERE track-type = "Vow"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```
> 
> ```dataview
> TABLE WITHOUT ID file.link as "Tracks"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
> WHERE track-type != "Vow"
> WHERE track-type != "Connection"
> WHERE iron-vault-kind != "clock"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```

> [!hint]- BONDS
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
> TABLE WITHOUT ID file.link as "Vows"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #complete
> WHERE track-type = "Vow"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```
> 
> ```dataview
> TABLE WITHOUT ID file.link as "Tracks"
> FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #complete
> WHERE track-type != "Vow"
> WHERE track-type != "Connection"
> WHERE iron-vault-kind != "clock"
> WHERE character = [[Barille Black]]
> SORT file.mtime DESC
> ```