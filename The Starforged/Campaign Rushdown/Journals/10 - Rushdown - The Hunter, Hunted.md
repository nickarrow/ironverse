
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

`iv-track-advance:06 - Find the fate of the Miwako and recover any surviving intel|The Starforged/Campaign Rushdown/Progress/Vows/06 - Find the fate of the Miwako and recover any surviving intel.md|20|24|formidable|1` 
 
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

They come to the isolation area of the medical section.  They notice isolated rooms with big plastiglass windows, housing corpses.  The corpses are withered and dried up due to age.  Some of the corpses appear to have been autopsied, and others have seemingly just been left to die.

"What happened here?" asks Strongarm.

"Hard to tell," says Rushdown, scanning through a wall terminal.  "It seems like the Ascendancy pirates were experimenting with some kind of weaponized disease."

"So are these the original crew?"

"No, this happened later.  Perhaps they captured some kind of medical research vessel.  Either way, we should decontaminate our suits before we go back on board the *Seventh Sun*."

"Roger that," says Strongarm.

`iv-move:Undertake an Expedition|Wits|2|3|0|4|9|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|12|16|formidable|1` 

>The zones chart seems buggy so I'm going to start rolling on it manually

`iv-dice:1d100|95` Research
`iv-oracle:Area|58|Lab|oracle_rollable:starforged/derelict/research/area` 
`iv-oracle:Peril|60|Fragile vault holds a dire threat|oracle_rollable:starforged/derelict/research/peril` 

They progress into a lab, and see a suspended animation crate.  

`iv-oracle:Scale|50|Medium (person-sized)|oracle_rollable:starforged/creature/scale` 
`iv-oracle:Creature First Look|28|Distinctive markings|oracle_rollable:starforged/creature/first_look` 

Inside, they can see some kind of creature.  It's about the size of a human, but has a shiny black exoskeleton and long claws.    Carved into its exoskeleton are the familiar markings of the Ascendancy.  It's floating harmlessly in stasis. 

"It looks like some kind of bioweapon.  I'm guessing that exoskeleton is bulletproof," says Rushdown.

"Let's not wake it up."

"Good idea."

They continue on towards the front of the ship.

`iv-move:Undertake an Expedition|Wits|1|3|0|5|5|move:starforged/exploration/undertake_an_expedition|burn=8:2`  `iv-track-advance:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|16|20|formidable|1` 

`iv-dice:1d100|50` Living
`iv-oracle:Area|71|Restroom or showers|oracle_rollable:starforged/derelict/living/area` 
`iv-oracle:Feature|6|Abandoned pet|oracle_rollable:starforged/derelict/living/feature` 
`iv-oracle:Opportunity|28|Hidden stash of valuable contraband|oracle_rollable:starforged/derelict/living/opportunity` 

They move on to the next area, it's a shower block.  There's a monkey sitting on a bench in the changing room, it shrieks excitedly and climbs up onto Rushdown's shoulder.

"That can't be real," says Strongarm.

"Gotta be robotic," says Rushdown.  "Someone's pet managed to avoid the Ascendancy and has had the run of the place since it was abandoned."

"You keeping it?"

"For now.  it must know its way around this place, maybe it can help us."

The monkey jumps down from Rushdown's shoulder and opens one of the lockers.  It's filled with weapons.  The monkey starts clapping and dancing.

"Whoa, genuine rifles from an Arkship, those are worth a fortune," says Strongarm.

Rushdown sends two of the away team back to the *Seventh Sun* with the guns, and the rest of the group continues on.

`iv-move:Undertake an Expedition|Wits|3|3|0|2|1|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|20|24|formidable|1` 

`iv-dice:1d100|90` Production
`iv-oracle:Area|23|Cargo bay|oracle_rollable:starforged/derelict/production/area` 
`iv-oracle:Feature|17|Disassembled machinery|oracle_rollable:starforged/derelict/production/feature` 

They pass through a cargo bay.  There's an exosuit on the floor, but it's been taken apart and all the pieces have been laid out neatly in order.  The soldiers think nothing of it and move on.

`iv-move:Undertake an Expedition|Wits|6|3|0|1|1|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|24|28|formidable|1` 

Finally, the soldiers arrive at the bridge of the Miwako.

`iv-oracle:Feature|4|Automated warning|oracle_rollable:starforged/derelict/operations/feature` 
`iv-oracle:Opportunity|74|Log offers insight into this site's downfall|oracle_rollable:starforged/derelict/operations/opportunity` 

As they enter the bridge, a warning starts sounding.  "Warning, unauthorized personnel on the bridge.  Warning, unauthorized personnel on the bridge."  The monkey walks over to a console and pushes a button; the warning stops.

There's a datapad with an audio log on it.

"Captain's Log, date unknown.  The pirates have breached our security systems, they have complete access to the ship.  They used some kind of device to compel me to give them the password - they pointed it at me, and the words just came out of my mouth.  It was a pretty weak password in the first place, just my mother's maiden name and my date of birth.  Stupid.  But with that machine, they can get anything out of anyone.  I don't know what they'll do to me next, they don't have any further use for me but they haven't killed me like the others.  For now I'm just locked here on the bridge, all the consoles are disabled so I can't get out.  I guess I'll just wait to see what happens next."

`iv-track-advance:06 - Find the fate of the Miwako and recover any surviving intel|The Starforged/Campaign Rushdown/Progress/Vows/06 - Find the fate of the Miwako and recover any surviving intel.md|24|28|formidable|1` 

"Search the area, let's see what we can find out," says Rushdown to the away team.

`iv-move:Explore a Waypoint|Wits|3|3|0|8|5|move:starforged/exploration/explore_a_waypoint`  `iv-meter:Momentum|2|3` 

"Sir, I think I found Captain Finn," says Strongarm.  Rushdown goes over and sees a body on the floor, lying in a circle of dried, aged blood.  Although the body is decayed with age, the Minami captain's uniform is still recognizable.  It seems that the captain was held down and drained of blood in a ritualistic fashion, with the blood then used to paint Ascendancy symbols around the body.

"That's a shitty way to go," says Rushdown.  He goes to a nearby terminal and tries to find any records or information that the Minami Clan might be interested in.

`iv-move:Gather Information|Wits|5|3|0|2|2|move:starforged/adventure/gather_information` 

He manages to get full access to the ships databanks - everything the ship did both before and after the takeover by the Ascendancy.  He loads the information onto two datapads, one for Minami and one for the Red Suns, then password protects the Miwako's databanks to stop the rebels from doing the same thing.

`iv-track-advance:06 - Find the fate of the Miwako and recover any surviving intel|The Starforged/Campaign Rushdown/Progress/Vows/06 - Find the fate of the Miwako and recover any surviving intel.md|28|32|formidable|1` 

"Anything else we've forgotten before we head back?" says Rushdown.  Nobody speaks up, so they head back to the *Seventh Sun*.

`iv-progress:Finish an Expedition|10 - Explore the Miwako (?)|7|9|6|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md|move:starforged/exploration/finish_an_expedition`  `iv-track-advance:discoveries|The Starforged/Campaign Rushdown/Characters/Rushdown.md|4|6|epic|2`  `iv-track-complete:10 - Explore the Miwako (?)|The Starforged/Campaign Rushdown/Progress/Expeditions/10 - Explore the Miwako ( ).md` 

"Do you want me to order the men to do a full sweep of the ship?  We left a lot of ground uncovered."

"No, let's just focus on the mission.  Minami can send a team if they want.  Knowing them, they'll probably try and recover the ship."

"Understood."

The team returns to the *Seventh Sun* and decontaminates, remembering all too well the room with the medical experiments.  Rushdown heads to the bridge, and they start to make their way back to Minami City.

`iv-move:Set a Course|Supply|1|5|1|10|9|move:starforged/exploration/set_a_course|adds=1` 

>1,2 Ascendency, 3,4,5 Pirates, 6 Resistance  `iv-dice:1d6|6` 

`iv-oracle:Ship Size|60|Medium|oracle_rollable:sundered_isles/ship/size` 

Back in the Ashitaba system, they reach a waypoint and get a distress signal.  They move to investigate, and find a corvette with dead engines floating in space.  They hail the ship but get no response.  As they move closer to investigate, the corvette's main cannon powers on and fires on them suddenly and two Multipurpose vehicles exit the cargo bays through the cargo hatches.

`iv-meter:Flagship / Integrity|5|4` 

With no warning given, the *Seventh Sun* doesn't have time to react and takes the full brunt of the shot.  "Red alert, battle stations" calls Rushdown and the crew rush to their positions.

`iv-move:Enter the Fray|Wits|1|3|0|8|3|move:starforged/combat/enter_the_fray` 

`iv-track-create:10 - Multipurpose Vehicles|The Starforged/Campaign Rushdown/Progress/Combat/10 - Multipurpose Vehicles.md` 
`iv-track-create:10 - Corvette|The Starforged/Campaign Rushdown/Progress/Combat/10 - Corvette.md` 

"Sir, one of those multipurpose vehicles is the ship [[The Spider]] was flying," says Eyeball.

"Don't fire on that ship, we want him alive.  Try hailing him.  All other targets are green to go, scramble snub fighters."

"Aye sir."

The snub fighters start leaving the hangar bays and moving to intercept the multipurpose vehicles.  The *Seventh Sun* focuses on the corvette.

`iv-move:Gain Ground|Edge|6|3|0|4|4|move:starforged/combat/gain_ground`  `iv-track-advance:10 - Corvette|The Starforged/Campaign Rushdown/Progress/Combat/10 - Corvette.md|0|8|dangerous|1` 

They race forward, guns blasting at the corvette.  They score a hit on the thrusters, and the corvette starts spiraling through space, out of control - it's out of the fight for now, until the engineers aboard can fix the thrusters, if ever.  The *Seventh Sun* lines up a shot on the other Multipurpose Vehicle.

`iv-move:Strike|Edge|2|3|1|9|6|move:starforged/combat/strike|adds=1` 

The smaller vehicle evades the bigger ship's cannons and flies in bravely for a strafing run.

`iv-oracle:Pay the Price|18|You face the consequences of an earlier choice|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

The shots go wide.  "Sir, The Spider's ship is answering the hail."

"On screen."

"Rushdown?" asks the Spider.  "We thought you were on the *Rude Awakening*".

"I was.  Now I'm here."

"I don't suppose you'd agree to a truce?  We'll just pretend this never happened and go our separate ways?"

"I'm supposed to bring you in, and I win this fight easily.  Give up and you can save your people's lives."

"For how long?  Minami aren't as reasonable as you are."

"I'm not bringing your whole squad in, only you.  The rest can go free, or they can die fighting an unwinnable battle here."

`iv-move:Compel|Iron|5|4|0|6|8|move:starforged/adventure/compel`  `iv-meter:Momentum|3|4` 

"Shit.  Okay, fine.  Give me a moment to tell the others."  The call ends.

"Hold fire, be ready for another trap," says Rushdown.

A few moments later, the other multipurpose vehicle stops firing and returns to the corvette.  They bring the broken thruster under control, and blink into FTL.  The Spider's multipurpose vehicle, flanked by multiple snub fighters, comes in to land in the destroyer's hangar bay.  Rushdown is there waiting, with an armed guard who are pointing their rifles at the door.  The door opens and the Spider steps out, hands raised.

"Well, this isn't how I expected today to go," says the Spider.

---

`iv-noroll:End a Session|move:starforged/session/end_a_session` 

`iv-clock-create:10 - Rebels try to rescue the Spider|The Starforged/Campaign Rushdown/Clocks/10 - Rebels try to rescue the Spider.md` 

`iv-track-complete:10 - Corvette|The Starforged/Campaign Rushdown/Progress/Combat/10 - Corvette.md`  `iv-track-complete:10 - Multipurpose Vehicles|The Starforged/Campaign Rushdown/Progress/Combat/10 - Multipurpose Vehicles.md` 

`iv-meter:Momentum|4|5` 