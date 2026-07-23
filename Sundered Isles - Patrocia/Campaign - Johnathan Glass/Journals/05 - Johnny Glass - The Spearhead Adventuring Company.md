
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 

`iv-oracle:Begin a Session|40|Seemingly unrelated situations are shown to be connected|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 

"Sir, news just in - someone's found Sally Slaughter's treasure.  Captain Glass of the *Spearhead*."

"So, he actually did it.  Did he encounter Slaughter?"  The man takes out a switchblade and starts calmly slicing an apple.

"Rumors say her and her crew were cursed and still aboard the ship, he had to fight them off."

"He didn't lift the curse, just fought them off?"

"That's what people are saying."

"So she's not gone for good.  Where is the *Spearhead* now?"

"Erast."

"Send an agent to keep an eye on him.  Inform me of any developments."

`iv-meter:Momentum|7|8` 

---

Johnny goes to resupply the ship before taking it in for a refit.

`iv-move:Resupply|Heart|4|3|0|7|3|move:starforged/recover/resupply` 

Johnny finds that the merchants at the market have raised their prices - word has clearly spread about his recent good fortune and everyone is trying to profit off of it.  Johnny, not wanting to waste any of his newfound wealth, has to search high and low for a merchant who'll give him a fair deal, but eventually he finds one he can sweet talk.

`iv-meter:Supply|3|5` 

He goes to the shipwright and discusses the alterations he wants made to the *Spearhead*.  He's going to be in Erast for a while as the shipwright works on the ship.

He meets up with the Ogre and they go for a drink.  The Ogre tells him about the various feuds and rivalries the Ikoban guild has with the various other adventurers guilds and knightly orders in the city.  This gets Johnny thinking - he has all this money from the last job and nothing to do with it, maybe he can set up an adventurer's guild of his own?  Sticky Joe would probably let him use the Three Lillies as a base until he was big enough for his own building.  He mentions the idea to the Ogre who laughs, saying that Johnny has no idea what goes into running a guild, but he's welcome to try.

Two days later it's official, the Spearhead Adventuring Company is open for business.

"You can start by clearing the rats out of the basement," says Sticky Joe, the new owner of the Three Lillies.  "It's tradition."

"What tradition?" asks Johnny.

"An adventuring guild's first job has to involve clearing out rats from a tavern basement.  It's bad luck if you don't."

"You made that up.  You just don't want to pay the ratcatcher," says Johnny.

"Tempt fate if you want, but don't come crying to me when your business fails."

With a sigh, Johnny heads to the basement and spends the next couple of hours skewering rats and poisoning nests.  When he exits the basement, a roar of laughter goes up from the customers of the Lillies.  "I can't believe you fell for that," laughs Sticky Joe.

"You're a prick," says a thoroughly unimpressed Johnny, but that just causes more laughter.

A couple of days later, the shipwright sends word - the alterations to the *Spearhead* are ready.  Johnny heads to the shipyard to inspect the ship - it's immaculate.

>Upgrading to Flagship even though it puts me in XP debt, it fits the story

Johnny sets about recruiting more crew to replace those that retired after the last job, but with his newfound reputation it isn't hard to find volunteers and soon the ship is fully crewed.

The Ogre comes to see Johnny in the Three Lillies.  "What do you know about the undercity?" he asks.

"Smart people stay out," says Johnny.

"Well, in the interest of goodwill we have a subcontracting opportunity for your guild.  Someone knocked through their basement wall and into an old forgotten crypt, and now there's a skeleton wandering about down there.  We want you to head down and clear out the skeleton and whatever else might be lurking about."

"How big is the crypt?"

"Unknown."

"So it might just be the skeleton?"

"Could be.  Or there might be something a hell of a lot more dangerous."

"Alright, I'll take it.  I'll clear out that crypt, by Iron I vow."

`iv-move:Swear an Iron Vow|Heart|6|3|1|4|2|move:starforged/quest/swear_an_iron_vow|adds=1`  `iv-meter:Momentum|8|10` 

`iv-track-create:05 - Clear out the crypt|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Vows/05 - Clear out the crypt.md`  `iv-track-advance:Connection Ogre|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Connections/Connection Ogre.md|0|4|formidable|1`  `iv-track-create:05 - Crypt Expedition|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Expeditions/05 - Crypt Expedition.md` 

Johnny arms himself with a cutlass and a boarding axe, and brings plenty of torches.  He follows the Ogre to the basement entrance, and readies his axe in one hand and a lit torch in the other.  Steeling himself, he makes his way down the stairs to the undercity.

He sees the skeleton wandering aimlessly in the basement.  He moves in to attack.

`iv-move:Enter the Fray|Iron|4|4|0|1|5|move:starforged/combat/enter_the_fray` 

`iv-track-create:05 - Skeleton|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Skeleton.md` 

He walks up to the skeleton and goes to bash it in the back of the head with the axe.

`iv-move:Strike|Iron|1|4|1|5|4|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Skeleton|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Skeleton.md|0|8|dangerous|1`  `iv-track-advance:05 - Skeleton|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Skeleton.md|8|16|dangerous|1` 

The blow cracks the skull, and the skeleton is knocked back into the wall of the crypt.  Johnny brings the axe down again.

`iv-move:Strike|Iron|1|4|1|4|9|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Skeleton|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Skeleton.md|16|32|dangerous|2` 

He bashes the skeleton again, but overextends and stumbles forward giving the skeleton an opportunity to move to the side and flank him.  The skeleton tries to grab Johnny and bite him.

`iv-move:Clash|Iron|6|4|1|3|3|move:starforged/combat/clash|adds=1`  `iv-track-advance:05 - Skeleton|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Skeleton.md|32|40|dangerous|1` 

Johnny bats the skeleton's hands away, then brings the axe down a third time, hitting the skeleton in the ribs and shattering bones.

`iv-progress:Take Decisive Action|05 - Skeleton|10|9|7|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Skeleton.md|move:starforged/combat/take_decisive_action`  `iv-track-complete:05 - Skeleton|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Skeleton.md`  `iv-track-advance:05 - Clear out the crypt|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Vows/05 - Clear out the crypt.md|0|8|dangerous|1` 

The skeleton drops to its knees and Johnny finishes it off with a final blow to the head, and the skeleton drops motionless to the ground.  Johnny continues on into the crypt through the hole in the wall.

`iv-move:Undertake an Expedition|Edge|4|3|0|9|8|move:starforged/exploration/undertake_an_expedition` 

Johnny steps into a large room, with bodies lining the walls.  Two skeletons patrol the room, one with an axe and the other with a greatsword.  Noticing Johnny, they start making their way towards him.  Johnny moves in to take on the one with the greatsword first.

`iv-move:Enter the Fray|Iron|5|4|0|5|8|move:starforged/combat/enter_the_fray` 

`iv-track-create:05 - Two Skeletons|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Two Skeletons.md` 

Johnny swings at his lumbering foe.

`iv-move:Strike|Iron|6|4|1|6|6|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Two Skeletons|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Two Skeletons.md|0|8|formidable|2` 

Johnny cleaves off one of the skeleton's arms, and it drops the greatsword.  Johnny keeps circling, trying to keep one skeleton between him and the other at all times.  He aims another attack at the one-armed skeleton.

`iv-move:Strike|Iron|3|4|1|1|5|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Two Skeletons|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Two Skeletons.md|8|16|formidable|2` 

His axe slams into its head, and it drops motionless to the ground.  Johnny turns his attention to the axe-wielding skeleton.

`iv-move:Strike|Iron|3|4|1|6|5|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Two Skeletons|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Two Skeletons.md|16|24|formidable|2` 

His axe batters the skeleton in the leg, dropping it to the floor.  It continues crawling along the ground towards Johnny.

`iv-move:Strike|Iron|5|4|1|9|8|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Two Skeletons|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Two Skeletons.md|24|32|formidable|2` 

Johnny starts stamping on the skeleton, trying to crush its skull with his boot.

`iv-progress:Take Decisive Action|05 - Two Skeletons|8|3|5|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Two Skeletons.md|move:starforged/combat/take_decisive_action`  `iv-track-complete:05 - Two Skeletons|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Two Skeletons.md`  `iv-track-advance:05 - Clear out the crypt|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Vows/05 - Clear out the crypt.md|8|16|dangerous|1` 

There's a loud crack and the skeleton stops moving.  Johnny checks there's nothing else moving in the room, and moves on.

`iv-move:Undertake an Expedition|Edge|6|3|0|4|2|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:05 - Crypt Expedition|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Expeditions/05 - Crypt Expedition.md|0|8|dangerous|1` 

Johnny exits the room and gets to a corridor that goes in both directions.  He heads left.

`iv-move:Undertake an Expedition|Edge|5|3|0|7|4|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:05 - Crypt Expedition|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Expeditions/05 - Crypt Expedition.md|8|16|dangerous|1` 

He comes to a doorway, and enters into another room like the last one.  It's empty.  He heads back and goes the other way at the junction.

`iv-move:Undertake an Expedition|Edge|1|3|0|3|2|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:05 - Crypt Expedition|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Expeditions/05 - Crypt Expedition.md|16|24|dangerous|1` 

He comes to a third room the same as the first, again unoccupied.  This one has a second doorway leading deeper into the crypt.

`iv-move:Undertake an Expedition|Edge|6|3|0|8|4|move:starforged/exploration/undertake_an_expedition`  `iv-track-advance:05 - Crypt Expedition|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Expeditions/05 - Crypt Expedition.md|24|32|dangerous|1` 

He comes to an altar of some kind, with a stairway leading up.  He heads up the stairs, perhaps there's a second entrance to the crypt.

`iv-move:Undertake an Expedition|Edge|3|3|0|6|8|move:starforged/exploration/undertake_an_expedition` 

He heads up the stairs and there's no second entrance - this is the main burial chamber.  At the end of the chamber is the body of a warrior, seemingly preserved as if he were still alive.  His eyes open, and he sits up.  "You've come to rob my grave?" he says in a dry, croaking voice.

"No, I'm here to clear out the crypt.  The skeletons were bothering people.  I'm guessing you won't leave quietly?"

"I won't leave at all.  And neither will you."  The man stands.  He is enormous, standing a head taller than Johnny and muscular.  He picks up a greatsword and wields it in one hand.  Johnny swaps his boarding axe for his cutlass and charges.

`iv-track-create:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md` 

`iv-move:Enter the Fray|Iron|2|4|0|4|5|move:starforged/combat/enter_the_fray` 

The undead man is bigger, but Johnny is faster.  He swings his blade at the man's midsection.

`iv-move:Strike|Iron|2|4|1|7|4|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|0|4|extreme|2` 

Johnny slashes the creature in the ribs, but it pushes Johnny away, into a wall.  With no space to maneuver, Johnny has no chance of dodging the next blow.

`iv-move:Clash|Iron|5|4|1|6|7|move:starforged/combat/clash|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|4|8|extreme|2` 

Johnny manages to parry the huge strike with his blade, then circle around quickly before the creature can recover from the swing.  He's away from the wall and ready for another attack.

`iv-move:Strike|Iron|2|4|1|10|2|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|8|12|extreme|2` 

Johnny gets another hit in, but the creature advances agressively and Johnny is forced to backpedal away to stay away from the massive monster.

`iv-move:Clash|Iron|4|4|1|1|4|move:starforged/combat/clash|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|12|16|extreme|2` 

Johnny stabs at the monster, sticking his sword deep in its gut, but it doesn't slow down and keeps bearing down on him.

`iv-move:Strike|Iron|1|4|1|4|7|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|16|20|extreme|2` 

The creature shrugs off Johnny's blows despite bleeding profusely, and raises its greatsword to swing at Johnny.

`iv-move:Clash|Iron|2|4|1|5|10|move:starforged/combat/clash|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|20|22|extreme|1` 

`iv-oracle:Pay the Price|77|You are harmed|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

`iv-meter:Health|5|3`  `iv-move:Endure Harm|Iron|6|4|0|8|7|move:starforged/suffer/endure_harm`  `iv-meter:Health|3|4` 

The creature's attack is parried once again, but this time it brings its hand back and hits Johnny with a huge backfist that takes him off his feet.  He scrambles up again before the monster can capitalize.

`iv-move:Clash|Iron|3|4|1|6|9|move:starforged/combat/clash|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|22|24|extreme|1` 

`iv-oracle:Pay the Price|38|Something of value is lost or destroyed|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

Johnny stabs the creature in the foot, hoping to take it off balance.  The creature kicks the cutlass away, sending it skittering off into the darkness.  Johnny grimaces and takes out his axe.  The creature swings at Johnny.

`iv-move:Clash|Iron|3|4|0|5|4|move:starforged/combat/clash`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|24|28|extreme|2` 

Johnny sidesteps the blow, and swings the axe into the creature's face, hitting one of its eyes.  The creature screams in rage, and covers its wounded eye with one hand while wildly swinging its greatsword with the other.

`iv-move:Strike|Iron|6|4|1|3|10|move:starforged/combat/strike|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|28|32|extreme|2` 

Johnny times another strike and hits the creature in the back of the head as it swings.  He feels the skull crack, but notices too late that he is being forced into a corner by the wide swings.

`iv-move:Clash|Iron|6|4|1|6|5|move:starforged/combat/clash|adds=1`  `iv-track-advance:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|32|36|extreme|2` 

Johnny hacks at the creature's sword arm and catches it at the wrist, sending its hand sailing off in an arc and sending the sword claytering to the floor.  The creature screams again, and Johnny sidesteps back into the center of the room.

`iv-progress:Take Decisive Action|05 - Large Undead Fight|9|9|7|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md|move:starforged/combat/take_decisive_action`  `iv-meter:Momentum|10|8` 

Johnny takes another swing at the creature and catches it in the neck, and its head is half hanging off.  It has a shocked look on its face, and Johnny hacks in the same spot again, severing the head completely.  The creature drops to the floor, defeated at last.

`iv-track-complete:05 - Large Undead Fight|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Combat/05 - Large Undead Fight.md`  `iv-track-advance:05 - Clear out the crypt|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Vows/05 - Clear out the crypt.md|16|24|dangerous|1` 

Johnny takes a quick rest to catch his breath, then searches the room for anything interesting.

`iv-move:Explore a Waypoint|Wits|3|2|0|1|6|move:starforged/exploration/explore_a_waypoint`  `iv-meter:Momentum|8|9` 

Johnny inspects the creature's greatsword.  It seems to glow in the dark and is covered in strange blue runes - it seems magical.  He leaves it where it is - he doesn't have a reliable buyer in Erast and doesn't want the trouble.  He retrieves his cutlass, then does one final sweep to make sure he didn't miss anything.

`iv-progress:Finish an Expedition|05 - Crypt Expedition|8|8|7|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Expeditions/05 - Crypt Expedition.md|move:starforged/exploration/finish_an_expedition`  `iv-track-advance:discoveries|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Characters/Johnathan Glass.md|7|8|epic|1`  `iv-track-advance:05 - Clear out the crypt|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Vows/05 - Clear out the crypt.md|24|32|dangerous|1`  `iv-track-complete:05 - Crypt Expedition|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Expeditions/05 - Crypt Expedition.md` 

He realizes that the crypt doesn't have an entrance - aside from the hole in the basement wall, there's no way in or out.  He wonders how many more pockets full of unknown monsters lie buried beneath the city.  He heads back upstairs to tell the client,  `iv-oracle:Given Name|79|Horatio|oracle_rollable:sundered_isles/character/name/given_name`  `iv-oracle:Family Name|63|Blake|oracle_rollable:sundered_isles/character/name/family_name` , the job is done.

`iv-progress:Fulfill Your Vow|05 - Clear out the crypt|8|10|8|Sundered Isles - Patrocia/Campaign - Johnathan Glass/Progress/Vows/05 - Clear out the crypt.md|move:starforged/quest/fulfill_your_vow` 

"It's done," says Johnny.

"And you checked the second level, too?"

"Second level?"

"Yeah, down the trapdoor."

"The job was to clear the crypt, the trapdoor's in the basement."

"But something from the crypt could have gone down the trapdoor.  I can't pay you until you fully clear the downstairs area including the basement."

"Fine, says Johnny, I'll let you know when I'm done."

>Rolling dice to erase from the progress track
> `iv-dice:1d10|10`  `iv-dice:1d10|2` 

---

`iv-noroll:End a Session|move:starforged/session/end_a_session`  `iv-meter:Momentum|9|10` 

