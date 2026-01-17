# Ironvault Test file

## Oracles
`iv-oracle:Begin a Session|10|Flashback reveals an aspect of your background or nature|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 
`iv-oracle:Action + Theme|3|Serve Fame|oracle_rollable:starforgedsupp/templates/actiontheme` 
Cursed result
`iv-oracle:Treasure Location|67|Hidden on an Island|oracle_rollable:sundered_isles/treasure/location|cursed=6` 

## Entity Generation
`iv-entity-create:NPC|Curtis “Mainframe” O'Brien|Curtis “Mainframe” O'Brien.md` 
`iv-entity-create:Planet|Barrow|Barrow.md` 
`iv-entity-create:Faction|Serpents of the Sacred Order|Serpents of the Sacred Order.md` 
`iv-entity-create:Settlement|Meridian|Meridian.md` 
`iv-entity-create:Creature|land-spider|land-spider.md` 

## Moves
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 
`iv-noroll:Set a Flag|move:starforged/session/set_a_flag` 

Strong hit `iv-move:Face Danger|Heart|4|3|0|6|4|move:starforged/adventure/face_danger` Now I'll try for a weak hit `iv-move:Gather Information|Wits|5|2|0|6|8|move:starforged/adventure/gather_information` . How about a match?  `iv-move:Compel|Shadow|4|1|0|4|4|move:starforged/adventure/compel` Okay how about a miss?  `iv-move:Undertake an Expedition|Edge|4|1|0|10|8|move:starforged/exploration/undertake_an_expedition` Now something with a burn `iv-move:Explore a Waypoint|Wits|1|2|0|9|3|move:starforged/exploration/explore_a_waypoint|burn=9:2` 

## Progress Moves
`iv-progress:Finish an Expedition|Traveling to Devil's Chain|0|6|2|The Starforged/Progress/Tybalt-Yhen Serrato/Traveling to Devil's Chain.md|move:starforged/exploration/finish_an_expedition` 
`iv-progress:Forge a Bond|Find where he stands with Epathus|3|7|3|The Starforged/Progress/Tybalt-Yhen Serrato/Find where he stands with Epathus.md|move:starforged/connection/forge_a_bond` 

## Create Tracks
`iv-track-create:Finish Inline PR|The Starforged/Progress/Finish Inline PR.md` and advance?  `iv-track-advance:Finish Inline PR|The Starforged/Progress/Finish Inline PR.md|0|16|formidable|4`  `iv-track-complete:Finish Inline PR|The Starforged/Progress/Finish Inline PR.md`  `iv-track-reopen:Finish Inline PR|The Starforged/Progress/Finish Inline PR.md` 

## Clocks
`iv-clock-create:clocktest|The Starforged/Clocks/Clocktest.md`  `iv-clock-advance:clocktest|The Starforged/Clocks/Clocktest.md|0|2|2|6`  `iv-clock-advance:clocktest|The Starforged/Clocks/Clocktest.md|2|3|1|6`  `iv-clock-resolve:clocktest|The Starforged/Clocks/Clocktest.md` 

## Meters
`iv-meter:Momentum|9|10`  `iv-meter:Momentum|10|9` 
`iv-meter:Health|5|4`  `iv-meter:Health|4|5` 
`iv-meter:Supply|5|4`  `iv-meter:Supply|4|5` 

## Roll dice
`iv-dice:5d10{3+9+9+6+6} + 2|35` 
`iv-action-roll:Iron|4|2|0|5|6` How about a reroll?  `iv-reroll:vs2|6|10|Iron|2|0|5|10|4` 

