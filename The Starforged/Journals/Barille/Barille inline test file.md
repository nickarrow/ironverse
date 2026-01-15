
# Ignore everything below, these are tests for Iron Vault 

---
# Inline Mechanics Test - All Icons

## Moves (Action Rolls)

`iv-move:Enter the Fray|Heart|1|3|0|10|4|move:starforged/combat/enter_the_fray`  now via sidebar:  `iv-move:Gather Information|Wits|2|2|0|3|2|move:starforged/adventure/gather_information` 

`iv-move:Secure an Advantage|Shadow|1|1|8|10|10|move:starforged/adventure/secure_an_advantage|adds=8(lots of power!!)` 

Strong hit:  `iv-move:Enter the Fray|Heart|4|3|0|4|1|move:starforged/combat/enter_the_fray` sdaf sfa sdf asd fasd dfas  `iv-oracle:Starship Name|67|Reforged Hope|oracle_rollable:starforged/starship/starship_name` 
Week hit: `iv-move:Secure an Advantage|wits|4|2|1|3|6`
Miss: `iv-move:Compel|heart|2|1|0|8|9`
Strong hit with match: `iv-move:Strike|iron|5|3|2|1|1`
Miss with match: `iv-move:Clash|iron|1|2|0|7|7`
With burn: `iv-move:Face Danger|edge|2|3|0|8|9|burn=7:2`
With adds: `iv-move:Gather Information|wits|3|2|2|4|6|adds=1(bond),1(asset)`
## Progress Rolls

`iv-progress:Take Decisive Action|inline test combat|0|9|10|The Starforged/Progress/Inline test combat.md|move:starforged/combat/take_decisive_action` 
`iv-progress:Forge a Bond|Find where he stands with Epathus|2|1|7|The Starforged/Progress/Tybalt-Yhen Serrato/Find where he stands with Epathus.md|move:starforged/connection/forge_a_bond` 

`iv-noroll:Begin a Session|move:starforged/session/begin_a_session`  `iv-noroll:Set a Flag|move:starforged/session/set_a_flag`  `iv-noroll:Set a Flag|move:starforged/session/set_a_flag`  `iv-noroll:Set a Flag|move:starforged/session/set_a_flag`  `iv-noroll:Change Your Fate|move:starforged/session/change_your_fate`  `iv-noroll:Change Your Fate|move:starforged/session/change_your_fate`  `iv-noroll:Change Your Fate|move:starforged/session/change_your_fate` 

`iv-track-create:inline test combat|The Starforged/Progress/Inline test combat.md` 

Strong hit:  `iv-progress:Fulfill Your Vow|Investigate and report on the rumored horrors of Reck|4|3|1|The Starforged/Progress/Barille/Investigate and report on the rumored horrors of Reck.md|move:starforged/quest/fulfill_your_vow` 
Weak hit:  `iv-progress:Take Decisive Action|Survive the Asteroid Storm|8|8|1|The Starforged/Progress/Tybalt-Yhen Serrato/Survive the Asteroid Storm.md|move:starforged/combat/take_decisive_action` 
Miss:  `iv-progress:Forge a Bond|Find where he stands with Epathus|2|6|5|The Starforged/Progress/Tybalt-Yhen Serrato/Find where he stands with Epathus.md|move:starforged/connection/forge_a_bond` 
Miss with match:  `iv-progress:Finish an Expedition|Reach the Devil's Chain Sector|4|10|10|The Starforged/Progress/Tybalt-Yhen Serrato/Reach the Devil's Chain Sector.md|move:starforged/exploration/finish_an_expedition` 
## No-Roll Moves
`iv-noroll:Begin a Session`
`iv-noroll:End a Session`
## Oracles
`iv-oracle:Action|42|Defend`  `iv-oracle:50/50|63|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty`  
`iv-oracle:Theme|73|Mystery`
`iv-oracle:Location|15|Swamp`
With cursed die: `iv-oracle:Action|55|Attack|cursed=10`
## Meters
Increase: `iv-meter:Health|3|5`
Decrease: `iv-meter:Spirit|4|2`
Momentum up: `iv-meter:Momentum|2|5`
Momentum down: `iv-meter:Momentum|6|3`
Supply: `iv-meter:Supply|5|4`
## Burn (Standalone)
`iv-burn:7|2`
`iv-burn:9|3`
## Position/Initiative
`iv-initiative:Position||in control`
`iv-initiative:Position||Bad spot`
`iv-initiative:Position|out of combat|out of combat` 
## Tracks - Create
`iv-track-create:Escape the Ironlands|Quests/Escape the Ironlands.md`
`iv-track-create:Slay the Beast|Quests/Slay the Beast.md`
## Tracks - Advance
`iv-track-advance:Escape the Ironlands|Quests/Escape the Ironlands.md|0|8|Epic|2`
`iv-track-advance:Find the Artifact|Quests/Find the Artifact.md|12|20|Dangerous|2`
`iv-track-advance:Protect the Village|Quests/Protect the Village.md|24|32|Formidable|2`
## Tracks - Complete
`iv-track-complete:Escape the Ironlands|Quests/Escape the Ironlands.md`
`iv-track-complete:Slay the Beast|Quests/Slay the Beast.md`
## Tracks - Reopen
`iv-track-reopen:Escape the Ironlands|Quests/Escape the Ironlands.md`
## Clocks - Create
`iv-clock-create:Storm Approaching|Clocks/Storm Approaching.md`
`iv-clock-create:Enemy Reinforcements|Clocks/Enemy Reinforcements.md`
## Clocks - Advance
`iv-clock-advance:Storm Approaching|Clocks/Storm Approaching.md|1|3|2|6`
`iv-clock-advance:Enemy Reinforcements|Clocks/Enemy Reinforcements.md|0|1|1|4`
With odds (success): `iv-clock-advance:Ritual Complete|Clocks/Ritual.md|2|3|1|8|odds=Likely:35:Yes`
With odds (failed): `iv-clock-advance:Ritual Complete|Clocks/Ritual.md|2|2|0|8|odds=Unlikely:80:No`
## Clocks - Resolve
`iv-clock-resolve:Storm Approaching|Clocks/Storm Approaching.md`
`iv-clock-resolve:Enemy Reinforcements|Clocks/Enemy Reinforcements.md`
## Entity Create
`iv-entity-create:NPC|Theron|NPCs/Theron.md`
`iv-entity-create:Location|The Shattered Vale|Locations/The Shattered Vale.md`
`iv-entity-create:Faction|The Iron Circle|Factions/The Iron Circle.md`

## Dice Rolling
`iv-dice:1d100|7` 
`iv-dice:2d6{4+1} + 9|14` 
`iv-dice:1d100{58} + 9d12{6+1+6+1+11+12+3+2+8} + 55|163` 
Make an action roll  `iv-action-roll:Heart|5|3|0|10|7`  then do a reroll   `iv-reroll:vs1|10|5|Heart|3|0|5|7|5` 


`iv-move:Gain Ground|Heart|2|3|0|2|8|move:starforged/combat/gain_ground`  `iv-oracle:Take Decisive Action|52|Victory is short-lived: A new peril or foe appears|move.oracle_rollable:starforged/combat/take_decisive_action.take_decisive_action` 



`iv-move:Gain Ground|Wits|5|2|0|7|5|move:starforged/combat/gain_ground` 