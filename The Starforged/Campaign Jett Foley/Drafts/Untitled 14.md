
`iv-oracle:Begin a Session|16|Flashback reveals an aspect of another character, place, or faction|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 

"Look, I'm with the Courier Guild, I'm not a bounty hunter."

"The Courier Guild?  Who'd send a courier to The Snakepit?"

"Client's name is Jett Foley, it says here you're expecting medical supplies."

"Well, that adds up.  You can dock, but watch yourself in here - they don't call it The Snakepit for nothing."

"I'll be gone as soon as my e-drive recharges."

"Probably for the best."

`iv-meter:Momentum|3|4` 

---

Jett makes his way to Pyla.

`iv-move:Set a Course|Supply|2|5|0|10|8|move:starforged/exploration/set_a_course` 

`iv-oracle:Terminus|47|Starship|oracle_rollable:starforged/space/sighting/terminus` 
`iv-oracle:Starship Name|19|Elara Five|oracle_rollable:starforged/starship/name` 
`iv-oracle:Starship Type|72|Multipurpose|oracle_rollable:starforged/starship/type` 
`iv-oracle:Terminus|74|Smuggle cargo|oracle_rollable:starforged/starship/mission/terminus` 
`iv-oracle:First Look|20|Heavy armor|oracle_rollable:starforged/starship/first_look` 

>Is it giving off a distress signal?  `iv-oracle:50/50|42|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

At one waypoint, Jett receives a distress signal.  He goes to investigate and comes across a multipurpose ship like his own.  It's heavily armored, but aside from that seems like a regular multipurpose ship.

>Does the ship have power?  `iv-oracle:50/50|45|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

The ship seems to be powered, so Jett hails the ship.

`iv-oracle:Initial Contact|92|Destroyed|oracle_rollable:starforged/starship/initial_contact` 

Jett only receives static in reply.  He moves *The Irony* in to dock.

>Are any of the crew still alive?  `iv-oracle:50/50|22|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 
>Multiple?  `iv-oracle:50/50|80|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

`iv-oracle:Given Name|83|Sage|oracle_rollable:starforged/character/name/given_name`  `iv-oracle:Family Name|66|Archer|oracle_rollable:starforged/character/name/family_name`  
`iv-oracle:First Look|81|Tattooed|oracle_rollable:starforged/character/first_look`  `iv-oracle:First Look|25|Augmented|oracle_rollable:starforged/character/first_look` 
`iv-oracle:Initial Disposition|32|Indifferent|oracle_rollable:starforged/character/initial_disposition` 
Character Role: Smuggler
`iv-oracle:Character Goal|79|Undermine a relationship|oracle_rollable:starforged/character/goal` 

After changing into his EVA suit just in case, he goes through the airlock and is greeted by a woman holding a gun.  She is heavily tattooed, and has artificial arms - they look like the expensive kind.  "So, you responded to the distress call.  I got caught in a plasma storm, my e-drive is shot.  Comms too, and a few other systems.  I think I'll just take your e-drive and be on my way; I'm already late as it is," she says.

"You can't just unplug an entire e-drive and put it in another ship without the proper facilities," says Jett, "It at least needs calibration from a proper tech.  Why don't you let me take a look at and see if I can repair your ship?"

"Fine, but any funny business and I'll shoot you," says the woman.

Jett goes to take a look at the e-drive and begins working on it.

`iv-move:Repair|Wits|1|3|0|8|9|move:starforged/recover/repair` 

The e-drive is completely irreparable.  "There's nothing I can do," says Jett, "Why don't I take you back to Port Koshiba and you can come back with a proper tech and a replacement e-drive?"

"Why don't I just take your ship instead?" asks the woman.

"Because the ship's AI won't respond to anyone but me."

`iv-move:Compel|Heart|3|2|0|2|8|move:starforged/adventure/compel` 

"Well, I can't go to Koshiba, there's a bounty on me there.  If you swear a vow to send a tech and an e-drive, and not tell any bounty hunters about this, I'll let you go."

"Fine, I vow to send a tech with an e-drive to fix your ship and not tell any bounty hunters you're here."

`iv-move:Swear an Iron Vow|Heart|4|2|0|5|5|move:starforged/quest/swear_an_iron_vow`  `iv-meter:Momentum|4|6`  `iv-track-create:14 - Send a tech with an e-drive to help Sage|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/14 - Send a tech with an e-drive to help Sage.md` 

"What should I call you?" asks Jett.

"I'm Sage."

"I'm Jett.  I'll be off, then."

"I'll be here."

---

Jett continues on to Pyla, and arrives without further incident.  He brings *The Irony* down next to the ship he wants to examine.  It's a multipurpose ship like his own, but has clearly been sitting in the corrosive atmosphere of Pyla for some time.  He puts on his exosuit and steps outside.

>Is there any reaction from the other ship?  `iv-oracle:50/50|66|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

Jett makes his way over to the ship and uses the manual override to open the airlock and board the ship.  He looks around for any clues.

`iv-move:Gather Information|Wits|1|3|0|4|1|move:starforged/adventure/gather_information|burn=6:2`  `iv-meter:Momentum|2|4` 

`iv-oracle:Descriptor|4|Advanced|oracle_rollable:starforged/core/descriptor`  `iv-oracle:Focus|84|Symbol|oracle_rollable:starforged/core/focus` 

The interior of the ship is much like you'd expect a ship to be - there's a cargo area, an engineering area, a cockpit and a crew area.  Jett is drawn to a recurring symbol - a circle with a fiery corona.

>Does Jett recognize the symbol?  `iv-oracle:50/50|21|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 
>Is it from an already introduced faction?  `iv-oracle:50/50|98|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 
>Does Jett know where he's seen the symbol before?  `iv-oracle:50/50|39|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

Jett recognizes the symbol immediately - the Polestar Institute.  He was working for them when he was kidnapped by the Void Cobras, this must be one of their ships.  But what happened to the pilot?  Jett inspects the escape pod, it is missing.  They'd made it out; no way of finding them now.  The ship has no power so Jett can't interrogate the data banks to find out what happened here.  He heads back to *The Irony*.

`iv-track-advance:07a - Get to Pyla|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/07a - Get to Pyla.md|24|32|dangerous|1` 

"Did you find any clues?" asks Eris.

"It's a Polestar Institute ship.  The pilot ejected."

"So what now?"

"It's far too much of a coincidence to ignore, it has to be related to my mission.  We're going back to Polestar."

"Let me guess, you want to to keep your word to that woman who wanted to shoot you before you leave?"

"I swore a vow.  Let's check the derelicts in orbit for a working e-drive, I don't want to have to buy one out of pocket."

---

Jett is in his EVA suit approaching the derelict ship.  He uses the manual override and opens the airlock.

`iv-track-create:14 - Expedition on derelict|The Starforged/Campaign Jett Foley/Progress/Jett/Expeditions/14 - Expedition on derelict.md` 

`iv-move:Undertake an Expedition|Wits|1|3|0|5|5|move:starforged/exploration/undertake_an_expedition` 

>Using Navigator to make this an automatic Strong Hit.

`iv-track-advance:14 - Expedition on derelict|The Starforged/Campaign Jett Foley/Progress/Jett/Expeditions/14 - Expedition on derelict.md|0|12|troublesome|1` 

Jett makes his way to the engineering section.  He checks to see if the e-drive is salvagable.

>Not sure what to roll for this but Resupply seems closest since it talks about scavenging

`iv-move:Resupply|Wits|6|3|0|2|3|move:starforged/recover/resupply` 

Jett finds the e-drive is intact and scans show it's in working order, just unpowered.  He detaches it and transfers it over to *The Irony*, a maneuver that would be impossible on the surface but is doable in zero-gravity.

`iv-track-advance:14 - Send a tech with an e-drive to help Sage|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/14 - Send a tech with an e-drive to help Sage.md|0|12|troublesome|1` 

Since he's already docked, he decides to take a look around the ship to see if there's anything else useful aboard.

`iv-move:Undertake an Expedition|Wits|4|3|0|6|7|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:14 - Expedition on derelict|The Starforged/Campaign Jett Foley/Progress/Jett/Expeditions/14 - Expedition on derelict.md|12|24|troublesome|1` 

`iv-oracle:Starship|85|Operations|oracle_rollable:starforged/derelict/zone/starship` 

`iv-oracle:Peril|4|Automated defenses target you|oracle_rollable:starforged/derelict/operations/peril` 

There's an autoturret still active in the cockpit - it must have its own power source.  It targets Jett, who ducks out of its line of sight.

`iv-move:Face Danger|Edge|2|2|0|9|6|move:starforged/adventure/face_danger`  `iv-meter:Health|4|2`  `iv-move:Endure Harm|Health|2|2|0|9|2|move:starforged/suffer/endure_harm`  `iv-meter:Momentum|4|3`  `iv-meter:Health|2|3` 

He doesn't move fast enough, and a bullet grazes his upper arm.  He quickly heads back to his own ship, not wanting to risk encountering any further defenses.

`iv-progress:Finish an Expedition|14 - Expedition on derelict|6|10|2|The Starforged/Campaign Jett Foley/Progress/Jett/Expeditions/14 - Expedition on derelict.md|move:starforged/exploration/finish_an_expedition`  `iv-track-complete:14 - Expedition on derelict|The Starforged/Campaign Jett Foley/Progress/Jett/Expeditions/14 - Expedition on derelict.md`  `iv-track-advance:14 - Send a tech with an e-drive to help Sage|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/14 - Send a tech with an e-drive to help Sage.md|12|24|troublesome|1` 

The ship's automated defenses spring to life as Jett sprints back to his own ship and undocks.  He quickly sets a course for Port Koshiba.

---

`iv-move:Set a Course|Supply|5|5|0|6|7|move:starforged/exploration/set_a_course` 

Once at Koshiba, he tries to find a tech who's willing to go and help a stranded ship in trouble.

`iv-move:Compel|Heart|3|2|0|4|9|move:starforged/adventure/compel` 

He finds someone who's willing to go, but not for free - he has to give them the two broken utility droids in trade.

`iv-track-advance:14 - Send a tech with an e-drive to help Sage|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/14 - Send a tech with an e-drive to help Sage.md|24|36|troublesome|1`  `iv-progress:Fulfill Your Vow|14 - Send a tech with an e-drive to help Sage|9|3|3|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/14 - Send a tech with an e-drive to help Sage.md|move:starforged/quest/fulfill_your_vow`  `iv-track-advance:quests|The Starforged/Campaign Jett Foley/Characters/Jett Foley/Jett Foley.md|8|9|epic|1`  `iv-track-complete:14 - Send a tech with an e-drive to help Sage|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/14 - Send a tech with an e-drive to help Sage.md` 

>Just realized I forgot to fulfil my vow to get to Pyla so I'll do that now
> `iv-progress:Fulfill Your Vow|07a - Get to Pyla|8|2|6|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/07a - Get to Pyla.md|move:starforged/quest/fulfill_your_vow`  `iv-track-advance:quests|The Starforged/Campaign Jett Foley/Characters/Jett Foley/Jett Foley.md|9|11|epic|2` 
> Also delivering the nav data from Burrow which I did last update
>  `iv-progress:Fulfill Your Vow|12 - Deliver Burrow Nav Data|6|6|2|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/12 - Deliver Burrow Nav Data.md|move:starforged/quest/fulfill_your_vow` 
>   `iv-track-complete:12 - Deliver Burrow Nav Data|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/12 - Deliver Burrow Nav Data.md`  `iv-track-complete:07a - Get to Pyla|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/07a - Get to Pyla.md` 

---

A few days later, Jett arrives at the Apollo Center, home of the Polestar Institute.  He is cleared for landing and immediately makes his way to the Director's office.

`iv-move:Make a Connection|Heart|3|2|0|2|3|move:starforged/connection/make_a_connection`  `iv-track-create:Connection - Althea Taylan|The Starforged/Campaign Jett Foley/Progress/Jett/Connections/Connection - Althea Taylan.md` 

"Jett, I'm glad to see you.  You just up and vanished, we thought the worst."

"I was captured by pirates, and then things kind of spiraled out of control after that."

"Oh dear.  And you managed to escape?"

"They wanted me to work a case for them, they let me go once I'd cracked it."

"Well, that's good to hear."

"What about here?  I noticed some rather obvious structural damage as I came in - were you attacked?"

"Nothing so dramatic; an experiment went wrong and took a chunk out of the exterior wall.  Fortunately we were able to seal the area with no loss of life; rebuilding efforts are underway.  So.  You're back.  Do you want to go back to work right away or did you need some time to recuperate?"

"There's more to the story," says Jett, "It's kind of a long story, but the reason I came back is I found an Institute ship in a ship graveyard.  I was drawn to it, I think it has something to do with my destiny.  The escape pod was missing, I don't know what happened to the pilot."

"Well, if you give us the route we'll send a team to investigate it thoroughly.  Maybe the pilot is still out there."

"I will.  Have you heard of the Ascendancy of the Awakened Worlds?  I've had a few run-ins with them."

The Director pauses for a moment.  "We...we'd better talk about that another time, Jett.  You've had a long journey; you should rest."

"But..."

"I insist.  You look exhausted.  Your old room is still free, we kept it as it was in the hope you'd be back one day.  Go and take a rest, get settled back in, then we'll talk about the Ascendancy and missions and things like that."

"Ok, Althea.  Thanks."

---

`iv-move:Sojourn|Heart|1|2|0|9|9|move:starforged/recover/sojourn` 

Jett goes for a walk around the station to clear his head.  He runs into a junior researcher with a new invention - it's supposedly a new kind of sensor that records battle data passively in unprecedented levels of detail.  He wants to use it to train a new kind of AI for starship battles, but nobody on the station is willing to try it out - they're researchers and avoid battles wherever possible.  After Eris scans the device to make sure it's safe, Jett vows to use the device until its memory banks are full, then return it to the man.

`iv-track-create:14 - Record Space Battle Data and Return It To Apollo|The Starforged/Campaign Jett Foley/Progress/Jett/Vows/14 - Record Space Battle Data and Return It To Apollo.md` 

He goes to the medstation and has his wounds taken care of. 

`iv-meter:Health|3|5` 

He goes to the bar and catches up with old acquaintances. 

`iv-meter:Spirit|4|5` 

Feeling refreshed, Jett is ready to return to the Director's office to discuss his next move.

---

`iv-noroll:End a Session|move:starforged/session/end_a_session` 

`iv-meter:Momentum|3|4` 

`iv-track-advance:Find and fulfil my destiny|The Starforged/Campaign Jett Foley/Progress/Jett/Find and fulfil my destiny.md|7|8|epic|1` 