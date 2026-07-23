
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 

*Rushdown just narrowly escaped from a pirate armada.  He is now on his way to Tranquilo to deal with Skullcrusher.*

`iv-oracle:Likely|40|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.likely`  `iv-clock-advance:11 - Miwako returns to Minami|The Starforged/Campaign Rushdown/Clocks/11 - Miwako returns to Minami.md|2|3|1|4` 
`iv-oracle:Likely|5|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.likely`  `iv-clock-advance:10 - Satonaka Return|The Starforged/Campaign Rushdown/Clocks/10 - Satonaka Return.md|2|3|1|4` 

`iv-oracle:Begin a Session|76|Unexpected return of an enemy or threat|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 

"There's a ship missing."

"What do you mean?"

"Someone has taken one of our ships.  It's gone."

"Which one?"

"The Arkship.  The *Miwako*."

"Let me check...it's been here for eighty years, who'd be looking for it now?"

"You don't think it was a random theft?"

"There are much better ships in orbit than that old thing.  Only someone with a personal interest would take it."

"Maybe its original owner?"

"After, let me see...150 years?"

"Well, maybe not the people, but the clan.  It's an Arkship after all."

"Hmm.  We picked it up in Ashitaba, originally.  Send a couple of scouts over there to take a look.  Nobody steals from the Ascendancy."

`iv-clock-create:Ascendancy scouts arrive in Ashitaba|The Starforged/Campaign Rushdown/Clocks/Ascendancy scouts arrive in Ashitaba.md` 

`iv-meter:Momentum|6|7` 

---

`iv-move:Set a Course|Supply|4|5|1|8|7|move:starforged/exploration/set_a_course|adds=1`  `iv-meter:Momentum|7|8` 

Rushdown arrives on Tranquilo, and sends Florian Angel a message saying "Something's gonna go down in Southside later."

Florian replies, "As loud as last time?"

Rushdown sends back "Shouldn't be.  This time, it's personal."  Then, he goes to see Bigmouth.  "I'm going after Skullcrusher.  What can you tell me?"

Bigmouth thinks for a moment.  "Someone put out a contract on Skullcrusher?"

"He put one out on me."

`iv-move:Gather Information|Wits|3|3|0|1|5|move:starforged/adventure/gather_information`  `iv-meter:Momentum|8|10` 

"That was stupid.  He has an office, I'll ping you the address.  You going in hot like last time?"

"I'm hoping that won't be necessary."

"Shame.  We made out like bandits after your last hit."

---

Later, Rushdown and half a dozen soldiers from the *Seventh Sun* approach Skullcrusher's office.  A full strike squad is on standby nearby, ready to go in hot if things go south.  There are two guards on the door dressed in yellow.  "Who are you guys?  You can't go in there," says one of them.  Rushdown keeps walking and the guard puts his hand on Rushdown's chest.  "I said-" says the guard but stops mid-sentence when Rushdown grabs his hand and twists his wrist.  Rushdown punches him in the face and he drops.  The other guard backs away, barking warnings into his communicator.  The Suns enter the offices.

Inside is a large room, where  `iv-dice:1d10|6` half a dozen gangers are hastily arming themselves with bats and knives.

"Get out, or we're going through you," says Rushdown.

`iv-move:Compel|Iron|6|4|0|10|9|move:starforged/adventure/compel` 

The gangers look at the armored mercs and each other, then run for the door.

"I have to say, you are quite intimidating in person," comes a voice from above.  Rushdown looks up and sees Vanguard, Skullcrusher's second in command, standing on a catwalk above the room.  He's pointing a rifle at Rushdown.  "Seems we have a standoff.  You can't get to me or draw your gun before I shoot you, and I can't shoot you and all your men before I get shot myself.  So let's talk.  Skullcrusher has an offer - you leave now, and he'll call off the hit."

"He sent my crew to the hospital.  It's too late for that," says Rushdown.  His men are slowly getting into cover.  Rushdown suddenly darts behind a pillar between himself and Vanguard.

`iv-move:Face Danger|Edge|4|3|0|7|9|move:starforged/adventure/face_danger` 

He isn't fast enough, and a bullet tears into him.

`iv-meter:Health|5|3`  `iv-move:Endure Harm|Iron|2|4|0|2|3|move:starforged/suffer/endure_harm`  `iv-meter:Health|3|4` 

His squad take out their handguns and start shooting at Vanguard.  Rushdown takes out his own weapon and joins in.

`iv-move:Enter the Fray|Edge|4|3|0|1|9|move:starforged/combat/enter_the_fray` 

`iv-track-create:15 - Vanguard|The Starforged/Campaign Rushdown/Progress/Combat/15 - Vanguard.md` 

Vanguard is trying to run, wildy firing behind himself as he moves.  Rushdown lines up a shot and fires.

`iv-move:Strike|Edge|2|3|0|1|1|move:starforged/combat/strike`  `iv-track-advance:15 - Vanguard|The Starforged/Campaign Rushdown/Progress/Combat/15 - Vanguard.md|0|24|troublesome|2` 

Rushdown's shot hits - not at Vanguard, but at the support holding up the catwalk.  The grate Vanguard is standing on collapses and he falls down a level into the large room.  Rushdown closes the distance as he tries to get to his feet and scramble to cover all at once.  Rushdown flies in with a knee outstretched.

`iv-move:Strike|Iron|5|4|0|6|3|move:starforged/combat/strike`  `iv-track-advance:15 - Vanguard|The Starforged/Campaign Rushdown/Progress/Combat/15 - Vanguard.md|24|40|troublesome|2` 

His knee hits Vanguard clean in the jaw and he goes down.

`iv-progress:Take Decisive Action|15 - Vanguard|10|6|3|The Starforged/Campaign Rushdown/Progress/Combat/15 - Vanguard.md|move:starforged/combat/take_decisive_action`  `iv-track-complete:15 - Vanguard|The Starforged/Campaign Rushdown/Progress/Combat/15 - Vanguard.md` 

Rushdown jumps on Vangaurd but he is already unconscious.  He throws the rifle out of reach and then advances towards the office.  He enters.  Skullcrusher is standing there, waiting.  "Only a matter of time before my guys show up," he says.

"I have a hitsquad waiting if they do," says Rushdown.

"Heh.  Of course you do.  So what now, you and your guys put me in the hospital?  Or are you here to kill me?"

"We can settle this one-on-one," says Rushdown.  "But whoever wins, stop targeting my crew."

"Fine by me," says Skullcrusher.  "You gonna take off that armor?"

"You gonna take off your claw?"

"Fair enough.  Let's get on with it, then."  Skullcrusher dashes forward and swings his massive mechanical arm at Rushdown in an overhead swing.

`iv-move:Enter the Fray|Iron|5|4|0|4|6|move:starforged/combat/enter_the_fray` 

`iv-track-create:15 - Skullcrusher|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md` 

Rushdown grabs the arm in both hands and tries to throw Skullcrusher behind him using his own momentum.

`iv-move:Strike|Iron|3|4|0|9|2|move:starforged/combat/strike`  `iv-track-advance:15 - Skullcrusher|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md|0|8|formidable|2` 

Skullcrusher goes sailing over Rushdown's head and crashes into a potted plant, sending ceramics and soil flying.  He goes through the partition wall, and rolls out of sight.  Rushdown runs in after him, but Skullcrusher is already on his feet swinging at the hole in the wall with his claw.  Rushdown tries to block at the last second.

`iv-move:Clash|Iron|5|4|0|2|9|move:starforged/combat/clash`  `iv-track-advance:15 - Skullcrusher|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md|8|12|formidable|1` 

He's half a second too slow and Skullcrusher grabs him with the claw.  Rushdown yanks at some exposed wires and the claw shudders, which gives him an opportunity to slip free of the claw's iron grasp.

"Hold on, boss, backup's almost there," comes a voice over Skullcrusher's communicator.

`iv-clock-create:15 - Backup arrives|The Starforged/Campaign Rushdown/Clocks/15 - Backup arrives.md` 

"You agreed to one-on-one," says Rushdown.

"Double crossed by a ganger, who would have guessed."

"Barricade the doors," Rushdown shouts to his men.  As he does so, Skullcrusher comes in for another attack.

>Clashing with Armored so 9 vs  `iv-dice:1d10|8`  `iv-dice:1d10|2` Strong Hit

`iv-track-advance:15 - Skullcrusher|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md|12|20|formidable|2` Rushdown uses his armor to absorb Skullcrusher's blow, and fires back with a punch to the jaw that sends Skullcrusher reeling.  He dashes in for a follow-up punch.

`iv-move:Strike|Iron|6|4|0|7|1|move:starforged/combat/strike`  `iv-track-advance:15 - Skullcrusher|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md|20|28|formidable|2` 

His next attack sends Skullcrusher down to one knee.  Rushdown aims a kick at his head.

`iv-move:Strike|Iron|4|4|0|4|5|move:starforged/combat/strike`  `iv-track-advance:15 - Skullcrusher|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md|28|36|formidable|2` 

The kick lands clean, right on Skullcrusher's jaw.

`iv-progress:Take Decisive Action|15 - Skullcrusher|9|10|4|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md|move:starforged/combat/take_decisive_action`  `iv-meter:Momentum|10|8`  `iv-track-complete:15 - Skullcrusher|The Starforged/Campaign Rushdown/Progress/Combat/15 - Skullcrusher.md`  `iv-clock-resolve:15 - Backup arrives|The Starforged/Campaign Rushdown/Clocks/15 - Backup arrives.md` 

Skullcrusher slumps to the ground, unable to continue the fight.  Rushdown goes over to his body and searches for the release mechanism for Skullcrusher's robotic arm.  It takes a minute, but finally he unhitches it and takes it with him.  He doesn't usually take trophies, but this is to send a message to Southside.

As Rushdown and his men leave the building, Skullcrusher's reinforcements show up.  Rushdown holds the arm above his head, and the gangers fearfully back off and let them leave peacefully.

Back at the ship, Rushdown goes to get his bullet wound looked at by Dr. Sloane.

`iv-move:Heal|Iron|2|4|0|9|3|move:starforged/recover/heal`  `iv-meter:Momentum|8|6`  `iv-meter:Health|4|5` 

Sloane is glad he came in; the bullet is close to a vital organ and Rushdown needs surgery to get it removed.  The wound could have easily been a lot more serious.  Once he's all patched up, Rushdown orders the ship to depart for Minami City.

`iv-move:Set a Course|Supply|3|5|1|6|8|move:starforged/exploration/set_a_course|adds=1` 

They arrive, and Gray contacts them.  She has a mission from Minami.

`iv-noroll:End a Session|move:starforged/session/end_a_session`  `iv-meter:Momentum|6|7` 