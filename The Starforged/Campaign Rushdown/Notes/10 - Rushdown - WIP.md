
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 

*Rushdown is tracking down an Arkship that went missing 150 years ago called the Miwako.  An informant on [[Gallows]] revealed that the ship graveyard around [[Pyla]] is an [[Ascendancy of the Awakened Worlds|Ascendancy]] graveyard where they leave ships that have fulfilled their mysterious duty.*

The next few hours are a blur.  Rushdown returns to [[Minami City]] and is presented with his new ship - a Destroyer class vessel named the *Seventh Sun*.  He makes a trip to the [[Cartographers Guild]] and obtains nav data for Pyla - the best route is to go first to [[Port Koshiba]] and from there on to [[Devil's Chain]], and ultimately Pyla itself.  Rushdown returns to the ship and they depart.

`iv-move:Set a Course|Supply|5|5|0|7|1|move:starforged/exploration/set_a_course`  `iv-meter:Momentum|9|10` 

They reach Pyla, and see the ship graveyard.  Hundreds of ships, from the smallest snub fighters to the largest fleet carriers and dreadnoughts, all abandoned in orbit around the planet.

"Any sign of the *Miwako*?" asks Rushdown.

"None of the ships are broadcasting an ID, impossible to tell if it's here from sensor readings alone," says Eyeball.  "But there is an Arkship.  Putting it on screen."

The ship fills up the viewscreen.  It looks identical to the *Minami* from Minami City.

"That's got to be it," says Rushdown, "Too much of a coincidence not to be.  I'm going over to check it out."

`iv-track-advance:06 - Find the fate of the Miwako and recover any surviving intel|The Starforged/Campaign Rushdown/Progress/Vows/06 - Find the fate of the Miwako and recover any surviving intel.md|16|20|formidable|1` 

"I'll assemble an away team," says Strongarm.  

"I can manage on my own," says Rushdown.

"With all due respect, sir," Strongarm replies, "What's the point having a great big bloody ship like this full of soldiers if you're not going to use them?"

"I can't argue with your logic.  Very well, have an away team suit up."

A few minutes later, Rushdown, Strongarm, and the dozen members of the away team are in a shuttle heading towards what they presume is the *Miwako*.

`iv-oracle:Condition|2|Functional|oracle_rollable:starforged/derelict/condition` 
`iv-oracle:Outer First Look|51|Odd orientation|oracle_rollable:starforged/derelict/outer_first_look` 

"Sir, the ship is fully powered and functional - you shouldn't even need your EVA suits in there," says Eyeball over comms.

"We'll keep them on, just in case.  These guys like to set traps, at least in my experience.  But if power's on, we should be able to get confirmation it's the *Miwako* pretty quickly."

"There's one other thing, sir.  The ship is in orbit backwards.  That is to say, it's moving towards the main thrusters, not towards the front of the ship."

"That shouldn't be an issue, we're not planning on flying it out of here."

"Yes, sir."

The shuttle arrives at the ship and lands in one of the large hangars.

>Are any other ships in the hangar?  `iv-oracle:50/50|95|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

The crew disembark the shuttle and make their way to the airlock.

`iv-track-create:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md` 

`iv-move:Undertake an Expedition|Wits|3|3|0|3|7|move:starforged/exploration/undertake_an_expedition`  `iv-meter:Momentum|10|8`  `iv-track-advance:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|0|4|formidable|1` 

The airlock is jammed and the team has to use the manual override.  Rushdown is glad that he can simply order one of his soldiers to do it rather than having to do it himself.  Soon, the jam is cleared and they are able to continue into the ship.

`iv-oracle:Inner First Look|12|Automated announcements|oracle_rollable:starforged/derelict/inner_first_look` 

>Do the announcements mention the *Miwako*?  `iv-oracle:50/50|40|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

As they walk through the airlock, a hologram appears.  "Welcome to the *Miwako*," it says.  "We appear to be having some technical difficulties.  Please stand by."

"This is it," says Rushdown.  "Now we know we're in the right place, we can start looking for the way to the bridge."
 
`iv-oracle:Area|77|Catwalk or bridge|oracle_rollable:starforged/derelict/access/area` 

The airlock opens out onto a catwalk over a promenade below.  The promenade is lined with shops.  "This isn't it," says Rushdown, "We keep moving."

`iv-move:Undertake an Expedition|Wits|3|3|0|1|10|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|4|8|formidable|1` 

`iv-oracle:Starship|46|Living|oracle_rollable:starforged/derelict/zone/starship`  
`iv-oracle:Area|26|Locker room or storage|oracle_rollable:starforged/derelict/living/area` 
`iv-oracle:Feature|84|Unusual art|oracle_rollable:starforged/derelict/living/feature` 

They move on to the next area - it appears to be storerooms for the shops on the promenade.  The walls are covered with strange geometric patterns and swirls.  "Do these patterns match the ones you found in the *Long Haul*?" asks Strongarm.

"No, these are different.  The other ones were occult symbols, these are almost decorative," replies Rushdown.

`iv-oracle:Peril|11|Distressing written message|oracle_rollable:starforged/derelict/living/peril` 

"Sir, there's something over here," calls out one of the away team.  Rushdown rushes over to take a look.  He sees a datapad hidden behind a crate.  He switches it on, and a message appears.

*I guess this will be my last entry.  We bargained with the pirates for the captain's life, but it was just a trick to get us to let them dock.  They're killing everyone.  The lucky ones died fighting them, they went quickly, but the rest of us are unarmed and in hiding.  They're searching the ship for us.  I can hear the screams of the dying, they're broadcasting the killings over the ship's comms.  I'm going to wait until they're sleeping, make a break for the airlock, and throw myself out of it.  It'll be quicker than whatever these bastards are doing.*

Rushdown logs the message, then returns the datapad to its hiding spot.  "Let's keep moving," he says.

`iv-move:Undertake an Expedition|Wits|2|3|0|4|5|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|8|12|formidable|1` 

`iv-oracle:Starship|59|Medical|oracle_rollable:starforged/derelict/zone/starship` 
`iv-oracle:Area|17|Isolation or containment|oracle_rollable:starforged/derelict/medical/area` 
`iv-oracle:Feature|8|Autopsied corpse|oracle_rollable:starforged/derelict/medical/feature` 
`iv-oracle:Peril|34|Evidence of a virulent disease|oracle_rollable:starforged/derelict/medical/peril` 

