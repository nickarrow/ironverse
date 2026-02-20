
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

Jett continues on to Pyla, and arrives without further incident.  He brings *The Irony* down next to the ship he wants to examine.  It's a multipurpose ship like his own, and looks to be in perfect condition despite sitting in the corrosive atmosphere of Pyla for an untold amount of time.  He puts on his exosuit and steps outside.

>Is there any reaction from the other ship?  `iv-oracle:50/50|66|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

Jett makes his way over to the ship and uses the manual override to open the airlock and board the ship.  He looks around for any clues.

`iv-move:Gather Information|Wits|1|3|0|4|1|move:starforged/adventure/gather_information|burn=6:2`  `iv-meter:Momentum|2|4` 

`iv-oracle:Descriptor|4|Advanced|oracle_rollable:starforged/core/descriptor`  `iv-oracle:Focus|84|Symbol|oracle_rollable:starforged/core/focus` 

The interior of the ship is much like you'd expect a ship to be - there's a cargo area, an engineering area, a cockpit and a crew area.  But Jett is drawn to a recurring symbol - a horizontal line with an arrow pointing up and a semicircle over the top.

>Does Jett recognize the symbol?  `iv-oracle:50/50|21|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 
>Is it from an already introduced faction?  `iv-oracle:50/50|98|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 
>Does Jett know where he's seen the symbol before?  `iv-oracle:50/50|39|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

