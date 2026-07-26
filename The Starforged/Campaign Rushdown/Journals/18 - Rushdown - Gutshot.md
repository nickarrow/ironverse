
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 

*Rushdown is sworn to rid the sector of an Ironsail raiding party.  He has found their secret base, but the boarding party is away, perhaps on a raid.  Rushdown is ready and waiting to attack the Ironsail ships as soon as they come out of warp.*

`iv-oracle:Likely|89|No|move.oracle_rollable:starforged/fate/ask_the_oracle.likely` 

`iv-oracle:Begin a Session|42|External factors create new danger, urgency, or importance for a quest|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 

>Did Bigmouth tell Satonaka about Rushdown?  `iv-oracle:50/50|25|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

"Sir, Rushdown is on the other side of the sector chasing an Ironsail raiding party."

"Then it's the perfect time to get rid of the *Rude Awakening*.  Where is it now?"

"Docked at Tranquilo."

"Get in touch with Bigmouth.  Have the ship tailed and taken out.  Make it look like a pirate attack."

"Are you sure we can trust this Bigmouth?"

"He knows how to pick the winning team."

---

Gutshot's frigate slides out of warp, expecting to see the freighter.  Instead, a warning shot from a destroyer's main cannon blasts across their viewscreen.

"Hail them," says Rushdown.

>Do they respond?  `iv-oracle:50/50|92|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

"No response," says Beat.

"They're maneuvering to attack," says Eyeball.  "The rest of the raiding party are coming out of warp.  The frigate, a corvette, and three multipurpose vehicles."

"Very low threat profile, they should be surrendering," says Strongarm.

"Move in.  Main cannons, focus on the frigate.  Turret guns, take out the rest," says Rushdown.

`iv-move:Enter the Fray|Edge|2|3|0|7|4|move:starforged/combat/enter_the_fray` 

`iv-track-create:18 - Gutshot's frigate|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's frigate.md` 
`iv-track-create:18 - Gutshot's fleet|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's fleet.md` 

The frigate is already in range, and the main cannons target it mercilessly.

`iv-move:Strike|Edge|5|3|0|10|4|move:starforged/combat/strike`  `iv-track-advance:18 - Gutshot's frigate|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's frigate.md|0|16|dangerous|2` 

They take the blast in the side, and the frigate starts reeling.  The other Ironsail ships move in to attack.

"A boarding ship just warped in, they're coming straight at us," says Eyeball.

`iv-clock-create:18 - Boarded by Ironsails|The Starforged/Campaign Rushdown/Clocks/18 - Boarded by Ironsails.md` 

"Nothing we can do about it now.  Have all available crew prepare to repel boarders and keep firing."

`iv-move:Clash|Edge|1|3|0|1|10|move:starforged/combat/clash`  `iv-track-advance:18 - Gutshot's fleet|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's fleet.md|0|8|dangerous|1`  `iv-clock-advance:18 - Boarded by Ironsails|The Starforged/Campaign Rushdown/Clocks/18 - Boarded by Ironsails.md|0|1|1|4` 

One of the multipurpose vehicles explodes in a ball of flame as the turret guns do their job.

"Sir, the boarding ship is in range for gravity harpoons," says Eyeball.  "They're targeting airlock six."

"We could swerve sideways and try to ram them," says Strongarm.

"Go for it," says Rushdown.  The pilot pulls the ship hard towards the boarding ship.

`iv-move:React Under Fire|Iron|5|4|0|9|7|move:starforged/combat/react_under_fire`  `iv-meter:Momentum|9|8` 

The ship suddenly lurches to the side and the boarding ship is smashed into dust, the boarding crew left adrift in their EVA suits.  Those that survived will run out of air in an hour or so, their inevitable demise on their mind for every last second.  The maneuver slows the ship down enough for the Ironsail fleet to get into a better position around them.

`iv-clock-resolve:18 - Boarded by Ironsails|The Starforged/Campaign Rushdown/Clocks/18 - Boarded by Ironsails.md` 

The frigate fires at the *Seventh Sun* and the destroyer's main cannon responds in kind.

`iv-move:Clash|Edge|4|3|0|5|10|move:starforged/combat/clash`  `iv-track-advance:18 - Gutshot's frigate|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's frigate.md|16|24|dangerous|1` 

`iv-oracle:Pay the Price|35|Something of value is lost or destroyed|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

The frigate fires on the *Seventh Sun* with its own main cannons taking out a turret gun, incinerating the gunner inside instantly.  The destroyer's own main cannons answer with a devastating blow to the frigate's hull.

`iv-oracle:Combat Action|53|Make a precise or careful attack|oracle_rollable:starforged/misc/combat_action` 

Meanwhile, the corvette is lining up a 'decapitation strike'; a direct hit on the ship's bridge will take out the entire command structure and more or less finish the fight in one go.  "Aim everything at that corvette, now!" screams Rushdown.

`iv-move:Clash|Edge|5|3|0|9|10|move:starforged/combat/clash` 

>Using Crew Commander to make this a Weak Hit

`iv-track-advance:18 - Gutshot's fleet|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's fleet.md|8|16|dangerous|1` 

All of the guns turn their attention to the corvette causing it to avoid the fire with evasive maneuvers and its decapitation strike misses wildly.

`iv-oracle:Pay the Price|84|You are stressed|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

Despite being the superior force, Rushdown finds it hard to keep track of so many opposing ships at once - he feels overwhelmed trying to keep track.

`iv-meter:Spirit|4|2`  `iv-move:Endure Stress|Heart|3|2|0|1|5|move:starforged/suffer/endure_stress`  `iv-meter:Momentum|8|7`  `iv-meter:Spirit|2|3` 

`iv-oracle:Combat Action|25|Destroy something or render it useless|oracle_rollable:starforged/misc/combat_action` 

Gutshot's frigate picks off a second turret gun.

"They're trying to disarm us, main cannons back on the frigate," says Rushdown.  The cannons take aim at the frigate and fire.

`iv-move:Clash|Edge|5|3|0|2|5|move:starforged/combat/clash`  `iv-track-advance:18 - Gutshot's frigate|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's frigate.md|24|40|dangerous|2` 

The shot hits home, and the frigate is damaged badly.  Its weapons power down.

`iv-progress:Take Decisive Action|18 - Gutshot's frigate|10|7|8|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's frigate.md|move:starforged/combat/take_decisive_action`  `iv-track-complete:18 - Gutshot's frigate|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's frigate.md`  `iv-track-advance:17 - Deal with the raiders|The Starforged/Campaign Rushdown/Progress/Vows/17 - Deal with the raiders.md|16|24|dangerous|1` 

One final blast from the main cannons destroys the frigate in a bright ball of flame.

The other ships turn and start trying to flee, firing back at the *Seventh Sun* as they do so.  "Don't let them get away, main cannons on the corvette!" says Rushdown.  The ship starts picking off the fleeing Ironsails.

`iv-move:Strike|Iron|3|4|0|2|6|move:starforged/combat/strike`  `iv-track-advance:18 - Gutshot's fleet|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's fleet.md|16|24|dangerous|1` 

The corvette disappears in a bright flash of light as the main cannons hit it full 
-force.  The turret guns fire on the last two multipurpose ships.

`iv-move:Strike|Iron|3|4|0|5|5|move:starforged/combat/strike`  `iv-track-advance:18 - Gutshot's fleet|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's fleet.md|24|40|dangerous|2` 

The ships desperately try to evade the fire but are overwhelmed.  One goes up in a ball of flame.

`iv-progress:Take Decisive Action|18 - Gutshot's fleet|10|7|10|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's fleet.md|move:starforged/combat/take_decisive_action`  `iv-track-complete:18 - Gutshot's fleet|The Starforged/Campaign Rushdown/Progress/Combat/18 - Gutshot's fleet.md`  `iv-track-advance:17 - Deal with the raiders|The Starforged/Campaign Rushdown/Progress/Vows/17 - Deal with the raiders.md|24|32|dangerous|1` 

>Choosing Marked for Vengence

`iv-clock-create:Barracudas strike back|The Starforged/Campaign Rushdown/Clocks/Barracudas strike back.md` 

Shortly followed by the other.

"Is that all of them?" says Strongarm.

"No, there's still the freighter," says Rushdown.  "We have the coordinates of their fallback rendezvous point, we'll head there immediately."  Moments later, they jump.

`iv-move:Set a Course|Supply|4|5|0|10|10|move:starforged/exploration/set_a_course` 

>Using Crew Commander to make this a Weak Hit

The crew recover the bodies of the two fallen gunners.  The ship stops as they hold a space burial.  The captain says a few words to mark the occasion.

`iv-meter:Momentum|7|5` 

They arrive at the fallback point, and the freighter is there with its escort of three multipurpose ships.

"Gutshot and the others are dead.  Surrender now, or meet the same fate," broadcasts Rushdown to the ships.

`iv-move:Compel|Iron|1|4|0|4|4|move:starforged/adventure/compel` 

"We'll come quietly," comes the reply.

A short while later, the *Seventh Sun*'s brig is full of Ironsail warriors and its cargo bays are full of stolen loot from Ironsail raids.  "We'll let Minami sort all this out," says Rushdown.

`iv-track-advance:17 - Deal with the raiders|The Starforged/Campaign Rushdown/Progress/Vows/17 - Deal with the raiders.md|32|40|dangerous|1` 

`iv-progress:Fulfill Your Vow|17 - Deal with the raiders|10|6|7|The Starforged/Campaign Rushdown/Progress/Vows/17 - Deal with the raiders.md|move:starforged/quest/fulfill_your_vow`  `iv-track-complete:17 - Deal with the raiders|The Starforged/Campaign Rushdown/Progress/Vows/17 - Deal with the raiders.md`  `iv-track-advance:quests|The Starforged/Campaign Rushdown/Characters/Rushdown.md|9|11|epic|2`  `iv-track-advance:Connection Gray|The Starforged/Campaign Rushdown/Progress/Connections/Connection Gray.md|24|28|formidable|1` 

They head back to Minami City.

`iv-move:Set a Course|Supply|6|5|1|10|6|move:starforged/exploration/set_a_course|adds=1` 

The *Seventh Sun* lands and they transfer the prisoners and stolen goods into Minami hands.  Gray calls Rushdown.  "Rushdown, this is important," she says.  "The *Rude Awakening* has been attacked."

"I'll be right there."

---

`iv-noroll:End a Session|move:starforged/session/end_a_session`  `iv-meter:Momentum|5|6` 