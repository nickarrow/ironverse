# [[Barille 02 - Reck]]

> [!question]+ Session Frame
> *Set before play — this is the scaffold that keeps the session on track.*
> - **Opening want:** Get on the ground and work the RU job — find the missing man and whatever the "manifestations" really are.
> - **Driving question:** What is actually happening on Reck, and who is behind the disappearances?
> - **You are here:** Act 1 — Pursuit, heading for the **Tilt**.
> - **Beats to land:** Threshold · Challenge · Tilt · Climax · Resolution. The Tilt is mandatory at the midpoint — don't soften it.

`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` `iv-meter:Momentum|5|6`

```
EXT. UPPER ATMOSPHERE, ACKRISS-2 — SN-27 ON DESCENT — DAY — GRIM

The 27 punches through purple-green cloud, trailing damage. The scans read toxic air and drifting ash from the volcanic ranges below. Somewhere under all that murk is Reck, and the crash site of the attacking raiders.
```

The 27 bursts through the clouds of [[Ackriss-2]]. Scans read a toxic atmosphere thick with ash, likely from regular volcanic activity.

```
BARILLE BLACK
This is SN27 on approach, anyone down there?

NO RESPONSE
```

[[Reck]] is built into the rock walls of a great canyon, the stone shielding it from the worst of the atmosphere. A settlement of thousands, out in the frontier of the Expanse.

Barille circles. On the south side, an impact crater and a spread of wreckage still trailing smoke, the frigate came down right into the settlement. He picks out a landing port nearby and lets the auto-landing sequence take the controls while he pings the transport.

```
BARILLE BLACK
Hey, did you make it down? Anyone injured? This is Barille.

COMMS OFFICER
Reading you, Barille. Yeah, we're all in one piece. That was you in the fighter, right?

BARILLE BLACK
Yeah. Any idea who that was?

COMMS OFFICER
They transmitted a pretty long message. Something about the Ascendancy of the Awakened Worlds? That mean anything to you?

BARILLE BLACK
Nope. Never heard of them. Trouble is, they suicided into Reck, so we can't exactly ask. I can't raise anyone down there, trouble?

COMMS OFFICER
Yeah. The impact shook the whole canyon. It's disaster mode down there. Reck is pretty wild on a good day, but the crash has everyone either panicking or fighting fires.

BARILLE BLACK
Got it. Thanks for the info. Barille out.
```

`So we have a name.` `iv-entity-create:Faction|Ascendancy of the Awakened Worlds|The Starforged/Factions/Ascendancy of the Awakened Worlds.md` `A mouthful, and clearly not a subtle bunch.`

He checks the landing port for an automated repair rig. Nothing. He taps out a message instead.

```
BARILLE BLACK — via hand terminal
Landing bay 17, SN27 - Barille Black, requesting repairs.
```

`Fine. I need to start the RU job anyway. Let's go for a walk.`

Before he leaves, Barille sends out an encoded wideband broadcast. `iv-noroll:Reach a Milestone|move:starforged/quest/reach_a_milestone`

![[Message 01 - Barille Black]]

`iv-track-advance:Expose the darkness behind the attacks across Devil's Chain and stop it from spreading|The Starforged/Epistolary/Expose the darkness behind the attacks across the sector and stop it from spreading.md|0|2|extreme|1`

```
INT. LANDING PORT — BAY 17 — DAY — UNEASY

The 27 sits venting steam, hull scarred from the fight. Barille drops down onto the deck. The RU brief on Reck's "horrors" was three words long "terrifying manifestations", and a name to find: a man gone missing. That's all he has to go on.
```

He sets off, turning the thin briefing over as he walks. Not much to work with. Someone's gone missing, and there are "manifestations" nobody will define. He needs to find whoever's in charge and start asking. `iv-move:Gather Information|Wits|1|2|0|9|4|move:starforged/adventure/gather_information`

What's the dire threat or unwelcome truth? `iv-oracle:Action + Theme|68|Journey Opportunity|oracle_rollable:starforgedsupp/templates/actiontheme` Reck is a frontier settlement with an *obvious social stratification*, and it looks like that pressure is boiling over into open revolt. Barille has just walked into the middle of it. Getting his ship repaired any time soon is off the table, and, `iv-oracle:Pay the Price|98|Your vehicle suffers damage, Your action causes collateral damage or has an unintended effect|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price`, his broadcast has drawn the wrong kind of attention.

Metal screeches behind him. He turns back toward the bay in time to see a heavy grapple hook punch into the flank of the 27. `iv-meter:Snub Fighter / Integrity|2|1` A group of scavengers has gathered around it, and two large persons step into his path.

```
BARILLE BLACK
Hey, friends. Looks like you've gone and put a hook in my ship.

SCAVENGER 1
You mean our ship. You picked the wrong day to show up. We control the east ward now.

BARILLE BLACK
That's fine. *lights a cigarette* You can have the east ward. But I'm going to need my ship back. So how about you unhook it, and we don't turn this into a thing.
```

`iv-move:Compel|Heart|5|3|0|4|5|move:starforged/adventure/compel` `iv-meter:Momentum|6|7`

```
SCAVENGER 1
Huh. Figured you'd go for a gun and we'd have to... look. Stay out of our way and you keep the ship. It's beat to hell anyway. Just remember: east ward's ours.

BARILLE BLACK
Got it. And who's "us," exactly?

SCAVENGER 1
We're with Murad. She owns it. Understand?

BARILLE BLACK
Understood. *long drag* Congratulations to her.
```

The scavengers drop their tools, shove past him hard enough to make the point, and go. Barille eyes the claw still buried in his fighter's flank. `Ugh. This is going to cost me.`

`iv-oracle:Interlude Scene|34|Fight in a sparring match|oracle_rollable:sundered_isles/misc/interlude_scene` He grinds out the cigarette and, for a moment, just breathes, running a fighting form to settle himself, working up a light sweat while the day sorts itself out in his head. Reck on the edge of revolt. A woman named Murad staking claims. A transport nearly gunned down, and raiders who'd rather die than break off. And under all of it, the [[Circle of the Elder Stars|Circle]] and his vow to [[Establish a new noble house in the Circle of the Elder Stars|build a house of his own]]. You never really leave the Circle. But he's done doing other men's dirty work. He rolls his shoulders and sets off. `iv-track-advance:Investigate and report on the rumored horrors of Reck|The Starforged/Campaign Barille Black/Progress/Barille/Investigate and report on the rumored horrors of Reck.md|0|4|formidable|1`

```
INT. CROWDED CORRIDORS OF RECK — DAY — RESTLESS

Foot traffic packs the tunnels, tense and quick. Barille needs a lead — on the missing man, or on whatever these "manifestations" are. He pulls the RU contact file up on his hand terminal.
```

The local contact is `iv-entity-create:NPC|Rowena Jensen|The Starforged/Characters/Rowena Jensen.md`. He starts there. `iv-move:Gather Information|Wits|4|2|0|1|4|move:starforged/adventure/gather_information` `iv-meter:Momentum|7|9` He's still reading her profile when a ping comes in from her directly.

```
ROWENA JENSEN — text message
Mr. Black - RU said you were coming, so I've had a proximity alert running. Reck's always a bit of a disaster, but today's worse than usual. I'm tied up in other work. Here's what I have. Ping me when you've got something.

*data file attached*

-message ends
```

**The missing person.** `iv-oracle:Action + Theme|22|Deflect Religion|oracle_rollable:starforgedsupp/templates/actiontheme` Karthick Hunter, a colleague of Rowena's, has vanished. There's a powerful religion woven through Reck's upper classes, and Karthick was a true believer. Lately he'd been turning up late, unfocused when he was there at all, increasingly consumed by the faith. `iv-oracle:Story Clue|21|Evokes a remarkable anomaly or phenomenon|oracle_rollable:starforged/misc/story_clue` Then one day he was simply gone, and not just gone. *Erased.* His apartment already re-rented, his personnel files deleted, every record of him wiped clean. The local authorities were no help, and in any case they mostly exist to serve the upper tiers. Nobody has any answer for where he went.

**The manifestations.** `iv-oracle:Descriptor+Focus|17|Deadly Portal|oracle_rollable:starforgedsupp/templates/descriptorfocus` There have always been rumors on Reck, it's a frontier settlement carved into a toxic, violent world, and going outside is rare and often fatal. But lately the rumors have narrowed to one shape: voids that open and snatch people clean out of existence. No one has ever documented one. Most write it off as a story. Except now Karthick is missing, and every trace of him is gone.

`iv-track-advance:Investigate and report on the rumored horrors of Reck|The Starforged/Campaign Barille Black/Progress/Barille/Investigate and report on the rumored horrors of Reck.md|4|8|formidable|1`

```
EXT. RECK MARKET — SIMULATED DUSK — BUSY

Overhead lights dim toward an artificial sunset. Vendors fire up their stalls and the market swells with noise. Barille needs to
know where Karthick's trail actually leads, and the crowd is the fastest place to take the settlement's pulse.
```

He leans against a pillar and reads the market, trying to gauge whether the churn is fallout from the crash or just an ordinary Reck evening. He drops into a seat at a place called the `iv-oracle:Name|265|Pinched Penny|oracle_rollable:starsmith/starships/name`, orders one drink, and puts his back to the bar to watch the room. `iv-oracle:Descriptor|83|Ruined|oracle_rollable:starsmith/core/descriptor` It's seen better days. So has the whole settlement a place maybe one bad night from collapse. Or maybe it's just one of those days. ^Pinched-Penny

`iv-ooc:Trying to figure out the next steps for Barille. I am thinking another Gather Information, or possibly even an expedition to go on a clue hunt. `

He pulls up the data file again and studies Karthick's photo. Then he settles the tab and heads for the man's former apartment. `iv-ooc:Is Barille getting closer to the suicide crash site?` `iv-oracle:50/50|14|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty`

```
INT. RESIDENCY DISTRICT — CORRIDOR NEAR KARTHICK'S APARTMENT — EVENING — WRONG

Ten minutes' walk in, warning lights strobe and the hand terminal starts pinging. But the corridor is empty. No fire crews, no
gawkers, no one at all — just Barille, a block from a dead man's door, and the feeling that he's walked past the edge of something.
```

`iv-oracle:Story Clue|186|Uncovers a damaging secret involving a secondary threat|oracle_rollable:starsmith/misc/story_clue` He presses forward and only then registers how completely alone he is. In a residency district, a block from Karthick's old apartment, there should be *someone*. There's no one. `iv-move:Gather Information|Wits|1|2|0|6|4|move:starforged/adventure/gather_information|burn=9:2` That's when the wall ahead of him — solid flex-steel — twists in on itself and a blaze of blue fire tears it open. `iv-oracle:Action + Theme|69|Summon Rumor|oracle_rollable:starforgedsupp/templates/actiontheme`

The portal widens. Inside is first an abyss of nothing, then a craggy rockface resolves, as though he's looking through a window in the side of the building into some other world entirely. Everything goes still. Then something steps out of it: a human, or something shaped like one. `iv-oracle:Descriptor|189|Shocking|oracle_rollable:starsmith/core/descriptor` Whatever it is, Barille's eyes refuse to hold it. The figure ignores him completely, turns down the adjacent hallway, and moves off. ^Otherworldly-portals

In a single flash the portal is gone. The hallway alarms start again.

```
BARILLE
So... that ratchets up the missing-person case a bit.
```

His hand terminal is screaming, radiation alerts, and a spread of unusual isotopes it just logged. Barille's hand drifts to his *kinetic pistol*. So there's a way to track this. Maybe not the entity itself, but the portals, the trail they leave. It's something. `iv-noroll:Reach a Milestone|move:starforged/quest/reach_a_milestone` `iv-track-advance:Investigate and report on the rumored horrors of Reck|The Starforged/Campaign Barille Black/Progress/Barille/Investigate and report on the rumored horrors of Reck.md|8|12|formidable|1`

> [!abstract] Session in Review · Challenge → Tilt
> **Challenge (Act 1).** On the ground, Barille worked the RU job through a settlement fracturing along class lines and pulled a thread on the missing believer, Karthick, and the rumored "manifestations."
> **The Tilt.** The rumor stopped being a rumor: a portal tore open a solid wall and something stepped out. The missing-person case became something far worse and it is now fact, not speculation. Everything after this falls toward an ending Barille couldn't have planned.

[[Barille 03 - Searching Through Reck]]
