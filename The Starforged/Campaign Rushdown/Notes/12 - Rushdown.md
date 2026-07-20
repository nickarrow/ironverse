
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 

*Rushdown has tracked down a man who has been attacking [[Red Suns]].  He's confronting the man, and has found out it connects back to [[Skullcrusher]] on [[Tranquilo (City)|Southside]].*

`iv-oracle:Likely|47|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.likely`  `iv-clock-advance:10 - Satonaka Return|The Starforged/Campaign Rushdown/Clocks/10 - Satonaka Return.md|0|1|1|4` 
`iv-oracle:Likely|74|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.likely`  `iv-clock-advance:11 - Miwako returns to Minami|The Starforged/Campaign Rushdown/Clocks/11 - Miwako returns to Minami.md|0|1|1|4` 

`iv-oracle:Begin a Session|68|Key location is made unsafe or becomes mired in conflict|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 

[[Inferno]] and [[Captain Redblood]] are having a meeting.  This is unusual.

"I'm telling you, none of my crew had anything to do with it!" says Inferno.

"Then what was he doing in your territory?  I never gave anyone permission to cross the border."

"I don't know.  We just found him there.  If we'd killed him, we'd hardly have contacted you to tell you about it."

"So you're saying that someone killed one of my lads, then moved the body to your territory?  What for?"

"I have no idea, but I'm telling you, it wasn't us."

"It just doesn't make any sense!"

The meeting continues for quite some time, but in the end nothing is settled.

---

The man rushes at Rushdown and throws a wild punch.

`iv-move:Enter the Fray|Iron|3|4|0|10|8|move:starforged/combat/enter_the_fray` 

`iv-track-create:12 - Mysterious Man Fight|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md` 

Rushdown blocks the blow with his arm, his power armor taking most of the damage, but the man is fast - he must have reflex-enhancing implants.  The man jumps and throws a knee at Rushdown, who lets his armor take the brunt of the damage while throwing a punch of his own at the man's midsection.

>Clash with armored, 9 vs  `iv-dice:1d10|2`  `iv-dice:1d10|5` Strong Hit

`iv-track-advance:12 - Mysterious Man Fight|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md|0|8|formidable|2` 

The man's knee collides with Rushdown's chest and bounces off harmlessly, while Rushdown's own punch collides with the man's ribs and he grunts.  Rushdown realizes the man isn't wearing power armor, he's just wearing regular armor - he must be strong to be carrying that much weight around and moving the way he does.  Rushdown tries to analyze the man's fighting style - so far he's been wild and reckless, but is that all he's capable of?

`iv-oracle:Combat Action|86|Summon aid or reinforcements|oracle_rollable:starforged/misc/combat_action` 

The man looks down at his ribs, surprised that Rushdown landed a hit on him.  He speaks into his wrist communicatior "I need backup."  Realizing he only has a second before the man can give out his location, Rushdown tries to grab the man's wrist.

`iv-move:Gain Ground|Wits|5|3|0|8|1|move:starforged/combat/gain_ground` 

Rushdown grabs the wrist communicator and the men struggle for a second, but Rushdown manages to tear the device away from the man and throw it into the fountain.  He throws an elbow at the man's unprotected head before he can get his guard back up.

`iv-move:Strike|Iron|6|4|1|5|1|move:starforged/combat/strike|adds=1`  `iv-track-advance:12 - Mysterious Man Fight|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md|8|16|formidable|2` 

Rushdown's elbow slams into the man's jaw, sending him reeling backwards.  Rushdown launches himself at the man, trying to grapple him around the waist.

`iv-move:Gain Ground|Iron|2|4|0|8|1|move:starforged/combat/gain_ground` 

He gets his arms around the man's waist and tries to lift him up and throw him backwards into the fountain.

`iv-move:Strike|Iron|5|4|0|10|3|move:starforged/combat/strike`  `iv-track-advance:12 - Mysterious Man Fight|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md|16|24|formidable|2` 

He throws the man backwards towards the fountain, but the man is agile and manages to twist in the air and land on his feet after slamming into the fountain.  Drenched, he jumps up and kicks off the fountain, sending a kick directly towards Rushdown.

`iv-move:React Under Fire|Iron|3|4|0|7|8|move:starforged/combat/react_under_fire`  `iv-oracle:Pay the Price|49|A new enemy is revealed|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

Rushdown pushes the kick away, but he sees a van pull up.  It seems the reinforcements have found him even without a location.

`iv-dice:1d4|4` 

4 gangers wearing yellow and carrying bats and chains jump out of the van and rush towards the scene of the fight.

`iv-track-create:12 - Gangers|The Starforged/Campaign Rushdown/Progress/Combat/12 - Gangers.md` 

`iv-oracle:Combat Action|54|Make a precise or careful attack|oracle_rollable:starforged/misc/combat_action` 

The man cautiously starts kicking at Rushdown's legs, then throws a punch aimed squarely at his head.  Rushdown throws a punch of his own, hoping to take the man out of the fight before the gangers close the distance.

>Using Armored to Clash so 9 vs  `iv-dice:1d10|9`  `iv-dice:1d10|8` Weak Hit

`iv-track-advance:12 - Mysterious Man Fight|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md|24|32|formidable|2`  `iv-oracle:Pay the Price|75|You are harmed|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

The man's punch lands first, and Rushdown feels it even through the power armor.

`iv-meter:Health|5|3`  `iv-move:Endure Harm|Iron|4|4|0|2|6|move:starforged/suffer/endure_harm`  `iv-meter:Health|3|4` 

Rushdown grapples the man and trips him, slamming him into the ground, just as the first of the gangers shows up.  They surround him and start lunging at him with their weapons.  Rushdown targets the one with the bat, and tries to snatch the bat away from him.

`iv-move:Gain Ground|Iron|5|4|0|9|10|move:starforged/combat/gain_ground`  `iv-oracle:Pay the Price|30|Your action causes collateral damage or has an unintended effect|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

As Rushdown struggles with the ganger over control of the bat, the armored man gets up and charges at him.  He pushes Rushdown back, and he tumbles through a large bay window leading into a restaurant.  The patrons, who had been watching the fight from the window, scatter and run into the street, screaming.  The man charges again, and Rushdown picks up a wine bottle and swings it at him.

>Clash with Armored, 9 vs  `iv-dice:1d10|8`  `iv-dice:1d10|7` Strong Hit

`iv-track-advance:12 - Mysterious Man Fight|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md|32|40|formidable|2` 

The bottle shatters over the man's head, and he goes down.  The gangers rush through the broken window, and Rushdown picks up a chair and swings it at the closest one.

`iv-move:Strike|Iron|2|4|0|2|1|move:starforged/combat/strike`  `iv-track-advance:12 - Gangers|The Starforged/Campaign Rushdown/Progress/Combat/12 - Gangers.md|0|16|dangerous|2` 

The swing takes the man off his feet and launches him back through his comrades.  Rushdown is finally able to pick up the man's dropped bat, and he advances on the gangers threateningly.

`iv-move:Gain Ground|Iron|4|4|0|10|8|move:starforged/combat/gain_ground`  `iv-oracle:Pay the Price|95|You are delayed or put at a disadvantage|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price`  `iv-meter:Momentum|7|5` 

The sound of sirens can be heard in the distance coming from outside the restaurant.  The three men surround Rushdown and start taking swipes at him.  The one with the chain swings, and Rushdown tries to intercept it with the bat.

>Clashing with Armored so 9 vs  `iv-dice:1d10|9`  `iv-dice:1d10|2` Weak Hit

`iv-track-advance:12 - Gangers|The Starforged/Campaign Rushdown/Progress/Combat/12 - Gangers.md|16|24|dangerous|1` 

The chain wraps around the bat and Rushdown yanks on it.  The ganger is dragged forward and Rushdown hits him hard in the jaw with an elbow, taking him out of the fight.

`iv-oracle:Pay the Price|14|You face a tough choice|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

Rushdown can hear the sirens getting louder - he should probably get out of here before they arrive, but he wants to send Skullcrusher a message so he decides to try and finish the fight before the Enforcers arrive.

The last two gangers look at each other, then look at Rushdown - they charge in unison, weapons raised high.

>Clashing with Armored 9 vs  `iv-dice:1d10|8`  `iv-dice:1d10|8` Strong Hit with a Match

`iv-track-advance:12 - Gangers|The Starforged/Campaign Rushdown/Progress/Combat/12 - Gangers.md|24|40|dangerous|2` 

Rushdown meets the gangers head on with a flurry of blows.

`iv-progress:Take Decisive Action|12 - Gangers|10|10|6|The Starforged/Campaign Rushdown/Progress/Combat/12 - Gangers.md|move:starforged/combat/take_decisive_action`  `iv-track-complete:12 - Gangers|The Starforged/Campaign Rushdown/Progress/Combat/12 - Gangers.md`  `iv-track-advance:11 - Crew Attacks|The Starforged/Campaign Rushdown/Progress/Vows/11 - Crew Attacks.md|12|24|troublesome|1` 

`iv-oracle:Take Decisive Action|29|It’s worse than you thought: Make a suffer move (-2)|move.oracle_rollable:starforged/combat/take_decisive_action.take_decisive_action`  `iv-meter:Health|4|2`  `iv-move:Endure Harm|Iron|1|4|0|2|2|move:starforged/suffer/endure_harm`  `iv-meter:Health|2|3` 

Rushdown takes the two men down, but catches a nasty blow from a pair of knuckle dusters in the process.

The mysterious man is slowly getting to his feet.

`iv-progress:Take Decisive Action|12 - Mysterious Man Fight|10|6|4|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md|move:starforged/combat/take_decisive_action`  `iv-meter:Momentum|5|6`  `iv-track-complete:12 - Mysterious Man Fight|The Starforged/Campaign Rushdown/Progress/Combat/12 - Mysterious Man Fight.md`  `iv-track-advance:11 - Crew Attacks|The Starforged/Campaign Rushdown/Progress/Vows/11 - Crew Attacks.md|24|36|troublesome|1` 

Rushdown grabs him from behind, hoists him up into the air, and brings him crashing down through a table, knocking him unconscious.

Just then, an Enforcer enters through the front door.  "Enforcers, freeze!"

"It's fine, I'm with the Red Suns.  Paulie the Hook knows me.  These guys attacked me."

`iv-move:Compel|Heart|1|2|0|10|7|move:starforged/adventure/compel` 

"Friend of Paulie's, huh?  Been a while since I heard that one.  Turn around and put your hands behind your head."

More enforcers show up and Rushdown and the five attackers are all arrested and cuffed.  Eventually word comes down from above that Rushdown is to be released, and the Enforcer who arrested him takes off his cuffs.

"Sorry about the misunderstanding you know, but you gotta understand how it looked - you just threw a guy through a freakin' table."

"It's fine," says Rushdown.  "I'd have done the same thing."

"Any idea who these guys are?"

"They're from Tranquilo.  They were here for me."

"So it was a hit?"

"Something like that."

"Well anyway, you look kinda beat up, you should go rest up."

"Yeah, I think I might just do that," says Rushdown.

`iv-progress:Fulfill Your Vow|11 - Crew Attacks|9|2|2|The Starforged/Campaign Rushdown/Progress/Vows/11 - Crew Attacks.md|move:starforged/quest/fulfill_your_vow`  `iv-track-complete:11 - Crew Attacks|The Starforged/Campaign Rushdown/Progress/Vows/11 - Crew Attacks.md`  `iv-track-advance:quests|The Starforged/Campaign Rushdown/Characters/Rushdown.md|7|8|epic|1` 

---

`iv-noroll:End a Session|move:starforged/session/end_a_session` 