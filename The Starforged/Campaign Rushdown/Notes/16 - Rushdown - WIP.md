
>Important Notice: Things are going a little too well for Rushdown, so I'm switching from a 43322 statblock to a 32211 statblock - expect a lot more setbacks!

`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 

*Rushdown has just taken down the gang leader who was targeting him, and found out Minami have a job for him.*

`iv-oracle:50/50|49|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty`  `iv-clock-advance:11 - Miwako returns to Minami|The Starforged/Campaign Rushdown/Clocks/11 - Miwako returns to Minami.md|3|4|1|4`  `iv-clock-resolve:11 - Miwako returns to Minami|The Starforged/Campaign Rushdown/Clocks/11 - Miwako returns to Minami.md` 
`iv-oracle:Likely|49|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.likely`  `iv-clock-advance:10 - Satonaka Return|The Starforged/Campaign Rushdown/Clocks/10 - Satonaka Return.md|3|4|1|4`  `iv-clock-resolve:10 - Satonaka Return|The Starforged/Campaign Rushdown/Clocks/10 - Satonaka Return.md` 
`iv-oracle:Likely|43|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.likely`  `iv-clock-advance:Ascendancy scouts arrive in Ashitaba|The Starforged/Campaign Rushdown/Clocks/Ascendancy scouts arrive in Ashitaba.md|0|1|1|4` 

`iv-oracle:Begin a Session|33|Seemingly unrelated situations are shown to be connected|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 

"Sir, we have arrived in the Ashitaba sector."

"Excellent, check in with our contacts in Minami, Gallows and Tranquilo."

"That would be  `iv-oracle:Given Name|3|Alexis|oracle_rollable:starforged/character/name/given_name`  `iv-oracle:Family Name|6|Wade|oracle_rollable:starforged/character/name/family_name` on Minami,  `iv-oracle:Callsign|7|Basilisk|oracle_rollable:starforged/character/name/callsign` on Gallows, and Bigmouth on Tranquilo.  I'll arrange a courier right away."

"Tell them that we'll pay double for actionable information on the Red Suns."

"Yes, sir.  Will there be anything else?"

"No, we need to find out what's been going on since our last team was here before we come up with a plan of attack.  The last thing we want is the Red Suns realizing Satonaka are back before we get the drop on them."

`iv-meter:Momentum|7|8` 

---

"Minami, under the new leadership of the Board, are trying to negotiate a peaceful resolution with the Resistance," says Gray.  They are in her new Minami office, with Wynne Barrow also in attendance.  "They are returning the Spider as a sign of goodwill.  They want us to handle the prisoner transfer."

"Are they expecting trouble?" asks Rushdown.

"No, they,re just being cautious.  Their ships have been lured into traps and ambushed several times by the Resistance, so they're not taking any chances."

"Ok, that's all I need to know."  He takes out his black iron dagger.  "I vow to hand the Spider safely over to the Resistance."

`iv-move:Swear an Iron Vow|Heart|2|1|0|3|6|move:starforged/quest/swear_an_iron_vow|burn=8:2`  `iv-meter:Momentum|2|4` 

`iv-track-create:16 - Prisoner Handover|The Starforged/Campaign Rushdown/Progress/Vows/16 - Prisoner Handover.md` 

---

Later, the prisoner and his ship are safely on the brig and the ship sets off for the meeting point.

`iv-move:Set a Course|Supply|3|5|0|2|8|move:starforged/exploration/set_a_course` 

When they arrive, the Revolution ship is locked in combat with two pirate vessels.  The *Seventh Sun* moves in to assist.

`iv-move:Compel|Iron|4|3|0|5|10|move:starforged/adventure/compel`  `iv-meter:Momentum|4|5` 

The pirates hail the *Seventh Sun*.  "There's a bounty on that ship, this is legitimate business."

"The bounty is frozen; there's a ceasefire in effect."

"Bullshit."  The ship cuts communication and resumes firing at the Resistance ship.

`iv-move:Enter the Fray|Edge|4|2|0|10|2|move:starforged/combat/enter_the_fray`

`iv-track-create:16 - Pirates|The Starforged/Campaign Rushdown/Progress/Combat/16 - Pirates.md` 

The *Seventh Sun* takes careful aim at the two pirate ships and fires the main cannon.

`iv-move:Strike|Edge|6|2|0|4|9|move:starforged/combat/strike`  `iv-track-advance:16 - Pirates|The Starforged/Campaign Rushdown/Progress/Combat/16 - Pirates.md|0|24|troublesome|2` 

The cannon blasts one ship to pieces.

`iv-oracle:Combat Action|9|Change weapons or tactics|oracle_rollable:starforged/misc/combat_action` 

The other ship starts dropping mines in the *Seventh Sun*'s path as the larger ship pursues it.  They try to weave through the mines and hit the ship.

`iv-move:Clash|Edge|3|2|0|5|1|move:starforged/combat/clash`  `iv-track-advance:16 - Pirates|The Starforged/Campaign Rushdown/Progress/Combat/16 - Pirates.md|24|36|troublesome|1` 

The *Seventh Sun* hits the other ship, but runs afoul of one of its mines.

`iv-meter:Flagship / Integrity|5|3`  `iv-move:Withstand Damage|Flagship / Integrity|3|3|0|3|7|move:starforged/suffer/withstand_damage`  `iv-meter:Momentum|5|4`  `iv-meter:Flagship / Integrity|3|4` 

"We've taken out their e-drive, they can't get away, says Eyeball."

"Focus on avoiding the mines," says Rushdown.

`iv-move:React Under Fire|Edge|2|2|0|1|7|move:starforged/combat/react_under_fire` 

They avoid the rest of the mines, but this gives the smaller ship an opportunity to pull away from them.

"We're clear," says Eyeball.

"Fire!" says Rushdown.

`iv-move:Clash|Edge|6|2|0|9|9|move:starforged/combat/clash` 

>Using Crew Commander to make this a Weak Hit

`iv-track-advance:16 - Pirates|The Starforged/Campaign Rushdown/Progress/Combat/16 - Pirates.md|36|40|troublesome|1` 

The smaller ship takes another hit, but its luck holds out - it continues to pull away from the *Seventh Sun*.

`iv-clock-create:16 - Pirates Escape|The Starforged/Campaign Rushdown/Clocks/16 - Pirates Escape.md` 

"Keep up the pressure!" Rushdown yells.

`iv-move:Clash|Edge|1|2|0|9|5|move:starforged/combat/clash` 

The pirates continue speeding away - they are heading towards an asteroid field where the *Seventh Sun* will be too big to follow them.

`iv-clock-advance:16 - Pirates Escape|The Starforged/Campaign Rushdown/Clocks/16 - Pirates Escape.md|0|1|1|4` 

`iv-move:Clash|Edge|6|2|0|5|4|move:starforged/combat/clash`  `iv-progress:Take Decisive Action|16 - Pirates|10|3|9|The Starforged/Campaign Rushdown/Progress/Combat/16 - Pirates.md|move:starforged/combat/take_decisive_action`  `iv-meter:Momentum|4|5`  `iv-track-advance:16 - Prisoner Handover|The Starforged/Campaign Rushdown/Progress/Vows/16 - Prisoner Handover.md|0|12|troublesome|1`  `iv-clock-resolve:16 - Pirates Escape|The Starforged/Campaign Rushdown/Clocks/16 - Pirates Escape.md` 

Finally, the pirates' luck is at an end, and they get nailed by the main cannon and explode. The Resistance ship hails the *Seventh Sun*.  "Thanks, things were looking grim back there.  This isn't the spot for the handover, just making sure this isn't a Minami trap.  Sending you the coordinates for the handover."  They send a set of coordinates then blink out into FTL.

Rushdown orders the crew to get ready to jump.

`iv-track-create:16 - Journey to handoff point|The Starforged/Campaign Rushdown/Progress/Expeditions/16 - Journey to handoff point.md` 

`iv-move:Undertake an Expedition|Wits|6|2|0|1|2|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:16 - Journey to handoff point|The Starforged/Campaign Rushdown/Progress/Expeditions/16 - Journey to handoff point.md|0|12|troublesome|1` 

`iv-oracle:Outlands|28|Planet|oracle_rollable:starforged/space/sighting/outlands` 
`iv-oracle:Planetary Class|44|Ice World|oracle_rollable:starforged/planet/class` 
`iv-oracle:Outlands|77|Orbital settlement|oracle_rollable:starforged/planet/ice/settlements/outlands` 
`iv-oracle:Outlands|40|Hundreds|oracle_rollable:starforged/settlement/population/outlands` 
`iv-oracle:Settlement Projects|18|Energy|oracle_rollable:starforged/settlement/projects` 
`iv-oracle:Settlement Projects|33|Expansion|oracle_rollable:starforged/settlement/projects` 
`iv-oracle:Sample Names|19|Thule|oracle_rollable:starforged/planet/ice/name` 

They come out of warp near an ice planet named Thule.  There's a mid-sized orbital settlement around the planet, and Rushdown takes the ship in for repairs.

`iv-move:Repair|Supply|6|5|0|7|8|move:starforged/recover/repair` 

`iv-meter:Flagship / Integrity|4|5` 

Despite the size of the ship, the tecnicians are able to repair the damage caused by the mines.  Rushdown continues on with his journey.

`iv-move:Undertake an Expedition|Wits|3|2|0|1|7|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:16 - Journey to handoff point|The Starforged/Campaign Rushdown/Progress/Expeditions/16 - Journey to handoff point.md|12|24|troublesome|1`  `iv-meter:Momentum|5|3` 

They slip out of FTL in deep space.  Rushdown realizes how much time they lost when they stopped for repairs.  They push on.

`iv-move:Undertake an Expedition|Wits|2|2|0|4|6|move:starforged/exploration/undertake_an_expedition` 

>Using Navigator to make this a Strong Hit.

`iv-track-advance:16 - Journey to handoff point|The Starforged/Campaign Rushdown/Progress/Expeditions/16 - Journey to handoff point.md|24|36|troublesome|1` 

They come out in deep space once again.

`iv-progress:Finish an Expedition|16 - Journey to handoff point|9|10|2|The Starforged/Campaign Rushdown/Progress/Expeditions/16 - Journey to handoff point.md|move:starforged/exploration/finish_an_expedition`  `iv-track-complete:16 - Journey to handoff point|The Starforged/Campaign Rushdown/Progress/Expeditions/16 - Journey to handoff point.md`  `iv-track-complete:16 - Pirates|The Starforged/Campaign Rushdown/Progress/Combat/16 - Pirates.md`  `iv-track-advance:16 - Prisoner Handover|The Starforged/Campaign Rushdown/Progress/Vows/16 - Prisoner Handover.md|12|24|troublesome|1` 

