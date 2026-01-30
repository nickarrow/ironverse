
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session`  `iv-oracle:Begin a Session|3|Flashback reveals an aspect of your background or nature|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 
**+ Add Momentum**

# Flashback - Entering the Courier Guild

"Alright, Courier Route 497, welcome aboard Sable." The woman, Kaska, handed Sable her courier signet, a small set of rectangular black iron pieces with four triangles pointed inward. The back displayed her name, callsign, and courier number... 497. "Weasel?"

Sable instantly burst a breathy chuckle. "My parents gave me that callsign. I had a habit of getting into trouble as a child—as well as the habit of never telling the truth." Sable looked up at the women to meet her concerned gaze, "Don't worry, I've since grown out of the habit."

Another lie. Sable never really knew when telling the truth was best course of action. Her webs often grew larger than manageable, but she was long gone by the time the trails of her deceit came nipping at her heels.

"Uncoursed sectors can be really dangerous and very unstable. I know you're eager to prove yourself, being a legacy and all, but it's best to pace yourself. That's why your first job is an easy one in this sector before we send you further." Kaska pressed a button on her datapad and Sable's smaller handheld one came to life with the information.

A simple job. Something you could hand to a child. This was how it would start for Sable. One incremental step after another to more complex routes and higher tier jobs, until they assigned her to her own sector. Probably something far out of the way, a lawless frontier.

Sables eye's glanced up to the galaxy nav map projected overhead in the facility. Each glimmering node was a courier making their way through the galaxy taking all manner of cargo from one place to another. Clusters of stars moving steadily, almost like the map was breathing. Her eyes traced the lines until they were scarce, then nonexistent. The [[Devil's Chain]] poised on the far edge of the map. She already had the request form filled out on her datapad. 

The last known place her parents' [[Find Her Parents Ship|ship]] was located.

`iv-entity-create:Faction|Courier Guild|The Starforged/Factions/Courier Guild.md` 

---
# Courier of the [[Devil's Chain]]

**INT. ABOARD CR-479 DOCKED ON [[Audun|AUDEN]]**

*beep... beep... beep...* 

The incessant light lit up the surrounding controls in a soft red haze as it dimmed and brightened to the tone that rang through the cabin. Sable held her head and walked through the corridors with one hand fisting a sleepy eye while the other eye saw stars and she blinked it awake. Sable stumbled into the cabin and slammed the toggle and Leela's face came beaming across the screen.

"Good morning sleepyhead, you have a package." Sable winced as the young girl's voice came through the screen.

Leela was the unfortunate intern assigned to Sable's sector as her handler. Sable had been more than unkind to her in the past. She didn't like the idea of having them assign her babysitter. She made it just fine everywhere else, there was no need to keep her on a leash, now that she finally got assigned the position she wanted in the Devil's Chain.
```iron-vault-mechanics
oracle-group name="NPC: [[Leela Asper]]" {
    oracle name="[Character Oracles \/ First Look](datasworn:oracle_rollable:starforged\/character\/first_look)" result="Energetic" roll=35
    oracle name="[Character Oracles \/ Initial Disposition](datasworn:oracle_rollable:starforged\/character\/initial_disposition)" result="Friendly" roll=12
    oracle name="[Character Oracles \/ Character Role](datasworn:oracle_rollable:starforged\/character\/role)" result="Scout" roll=79
    oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Maintain order" roll=40
}
```
`iv-track-create:Leela Asper|The Starforged/Progress/Sable/Leela Asper.md` 
"How's the boyfriend, Leela?" Perhaps Sable should make nice for once. Besides she needed a few minutes for the startup cycle to finish.

>Does play nice go well? `iv-oracle:Unlikely|84|No|move.oracle_rollable:starforged/fate/ask_the_oracle.unlikely` 

Leela whipped her gaze up and glared into the screen. Sable averted her gaze and her lips went into a flat line. Sable was missing something—or probably more likely completely forgot something. Sable let the silence hang as heavy as a lead weight.

Her ship spooled up, stirring through the startup process as listless as she was. Getting started in Devil's Chain was slow. It would take time before the services of a courier became well established. Until then she would be begging to take any low-tier run the guild forwarded her way.

"Alright, where am I going?" Sable finally asked.
```iron-vault-mechanics
oracle-group name="Settlement: [[Glimmer Outpost]]" {
    oracle name="[Templates \/ Region](datasworn:oracle_rollable:starforgedsupp\/core\/region)" result="Outlands" roll=66
    oracle name="[Settlement Oracles \/ Settlement Name](datasworn:oracle_rollable:starforged\/settlement\/name)" result="Glimmer" roll=31
    oracle name="[Name Suffix](datasworn:oracle_rollable:starforged\/settlement\/name_tags)" result="Outpost" roll=7
    oracle name="[Settlement Oracles \/ Location](datasworn:oracle_rollable:starforged\/settlement\/location)" result="Orbital" roll=53
    oracle name="[Population](datasworn:oracle_rollable:starforged\/settlement\/population\/outlands)" result="Dozens" roll=30
    oracle name="[Settlement Oracles \/ First Look](datasworn:oracle_rollable:starforged\/settlement\/first_look)" result="Intimidating defenses" roll=51
    oracle name="[Settlement Oracles \/ First Look](datasworn:oracle_rollable:starforged\/settlement\/first_look)" result="Built within repurposed ship" roll=19
    oracle name="[Settlement Oracles \/ Authority](datasworn:oracle_rollable:starforged\/settlement\/authority)" result="None \/ lawless" roll=5
    oracle name="[Settlement Trouble](datasworn:oracle_rollable:starforged\/settlement\/trouble)" result="Dangerous discovery" roll=15
}
```

"You're picking up a Black service package from an orbiting outpost called 'Glimmer Outpost'. It's also marked red." Leela's tone went stale. It seemed the question about her boyfriend made her as stiff in conversation as a board. Her matter-of-fact tone unsettled Sable.

This was a Black service package and marked red for that matter. It meant you don't ask about it. You don't open it. You don't even look at it. Red meant urgent. Sable had no time to lose and not a second to waste. 

"Thank you, Leela. I'll get going immediately." Sable accepted the request. "Hey, and sorry about your boyfriend." Sable offered a meek yet sincere look.

Leela growled a scream in frustration and shut off the commlink. Maybe she wasn't mad about a boyfriend? Sable shrugged and picked up her discarded courier suit from the floor. Speaking of boys—he must have left early this morning. *What was his name again?* Sable thought as she pulled the pants over her bare legs, donned the arms, and zipped the suit up. The insignia of the Courier Guild was plastered on a patch on her left arm. Her left breast patch showed the colors of her rank, she currently sat at orange. Just two levels down from her legacy. Not that she truly cared about living up the name Rowe.

Sable wiped the memories of her parents from her mind and turned to her console. "Glimmer outpost here we come," she murmured to herself.

```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Courier Job Glimmer Outpost.md|Courier Job: Glimmer Outpost]]" status="added"
```
`iv-move:Swear an Iron Vow|Heart|1|1|0|4|5|move:starforged/quest/swear_an_iron_vow`  `iv-oracle:Story Complication|27|Natural disaster is imminent|oracle_rollable:starforged/misc/story_complication` 

The engines spooled up, the notable whirring of power resonating through the hull. Her console lit up with hazard warnings, a huge storm flooded her display. Sable peered through the viewport seeing people were bustling about like ants to shut everything down, tie off loose cargo, and rush inside. Sable's sensors beeped with warnings as an electrical storm closed in.

She didn't have time for this. The storms out here were brutal and could last cycles. This package was marked red, which meant it was her job as courier to brave every hardship to rush the job. She picked up her courier cap and firmly placed it on her mop of long brown hair, tugging on the brim of it until it fit snugly on her head.

`iv-noroll:Begin the Scene|move:starforged/scene_challenge/begin_the_scene`  Survive The Electrical Storm
```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Sable\/Survive the Electrical Storm.md|Survive the Electrical Storm]]" status="added"
clock name="[[The Starforged\/Clocks\/Sable\/The Electrical Storm Overtakes the Port.md|The Electrical Storm Overtakes the Port]]" status="added"

```
Sable rushed to move out, pulling in the landing gear and powered up for launch. Her sensors scanned for a break in the storm, but her eyes got there first. `iv-move:Secure an Advantage (Scene Challenge)|Wits|2|3|0|10|6|move:starforged/scene_challenge/secure_an_advantage` 

**CLUNK** 

```iron-vault-mechanics
clock from=0 name="[[The Starforged\/Clocks\/Sable\/The Electrical Storm Overtakes the Port.md|The Electrical Storm Overtakes the Port]]" out-of=4 to=1
```

"Shit," Sable cursed. The ship was still connected to the fuel line, "shit, shit, stupid, shit, fuck, gah..." Her curses were punctuated with every word as she pounded her way outside to disconnect the fuel line. Her cap tried to break free in the wind, but she caught the thing shoving it into the front of her suit, letting her hair whip wildly in the wind. The fuel connector clanked on the port deck and she slammed the fuel cover closed and locked it. *Don't forget to lock it*.

She sped back up to the flight deck and plopped herself into her chair, exasperated, windswept, and feeling pretty dumb. She took a breath. She knew she could do this. Sable wasn't about to let months of downtime trip her up. The break she saw earlier gone she headed into the storm blind, hoping her sensors would pick up something unseen `iv-move:Face Danger (Scene Challenge)|Wits|4|3|0|6|10|move:starforged/scene_challenge/face_danger`.
```iron-vault-mechanics
progress from=0 name="[[The Starforged\/Progress\/Sable\/Survive the Electrical Storm.md|Survive the Electrical Storm]]" rank="troublesome" steps=1
clock from=1 name="[[The Starforged\/Clocks\/Sable\/The Electrical Storm Overtakes the Port.md|The Electrical Storm Overtakes the Port]]" out-of=4 to=2

```
`iv-move:Face Danger|Wits|6|3|0|6|5|move:starforged/adventure/face_danger` Her heart lightened as she saw the perpetual sun break through the oppressive winds. The nav protested, indicating she was off the intended course, headed into the worst of it. She ignored it. The static charge made her hairs stand on edge as she clipped the edge of the storm turning hard along a steep wind pull.
```iron-vault-mechanics
progress from=12 name="[[The Starforged\/Progress\/Sable\/Survive the Electrical Storm.md|Survive the Electrical Storm]]" rank="troublesome" steps=1
```
`iv-move:Face Danger|Wits|5|3|0|5|3|move:starforged/adventure/face_danger`  Sable Laughed as she pulled out of the electrical storm and broke free of the planet’s atmosphere. 
```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Sable\/Survive the Electrical Storm.md|Survive the Electrical Storm]]" status="completed"
clock name="[[The Starforged\/Clocks\/Sable\/The Electrical Storm Overtakes the Port.md|The Electrical Storm Overtakes the Port]]" status="resolved"

```
Sable could feel her heart pounding in her ears. These past few weeks scrapping along on the meager allowance she got from the Courier Guild without a job in sight left her joints rusted. She felt oiled. Broken free of the stagnation that had anchored here in a melancholy rust. She made course for Glimmer Outpost.
`iv-move:Set a Course|Supply|2|5|0|10|1|move:starforged/exploration/set_a_course` 

The journey there was short and quiet. Glimmer was outfitted from an old outpost ship, that now orbited Audun like some jewel in the planets pull. Sable softly exhaled as the sight of the outpost was something truly to behold. Reflective panels glittering in the eternal sun that haloed it, spires of coiled masses shimmering like diamonds jutted out in every direction. As Sable got nearer, she saw the glitz in its entirety. The docking station was lined with personal ships that were worth an armada. At first Sable wondered if the pirates would target this place, but between the spiraling pillars of shining plates were more guns and turrets than a fully kitted out warship. 

Then came the fighters. Sleek, fast, and deadly. Two swooped in so fast she blinked and missed them, if it weren't for their bright chrome finishes. Before she realized it they were on either side of her, like shimmering bullets.

Her console rang as she was hailed. “Dock’s closed. You have 1 minute to leave.” The voice clipped over the comms.

“CR-497 requesting—“

“I didn’t ask,” the voice cut her off.

“No, but someone did. I’m a hired courier here for a job!” She shouted over the voice as they attempted to cut her off again. She couldn’t tell if the voice was male or female, some sort of synthetic modulation made them seem almost AI. “Now, let me in.”
`iv-move:Compel|Iron|3|1|0|1|9|move:starforged/adventure/compel` 

A long pause had Sable wiping her brow, wondering if they would turn her away or just shoot her down for not leaving.

“Wait here.” The voice finally came. And one shuttle broke off and headed towards Glimmer.

So Sable held position, just waiting for an agonizing amount of time. By the time she saw movement again she had thoroughly cleaned her nails—which meant she chewed them to the quick. A small transport shuttle approached, flanked by two more fighters including the one who had left her a while ago. Sable pulled her hat out of the front of her suit, quickly finger combed her hair and placed the cap on her head. She smoothed out her courier suit and prepared herself to meet whoever the client was.

"Prepare for cargo transport." The voice crackled over her comms.

"Opening cargo doors now, ready for transfer." Sable hesitated before clicking the comm key again. "Is the client present? I would like to speak to them."

"All the information you need has been given to the Courier Guild. No need for a meeting." The voice cut the comms and before Sable could protest a mass shook the hull as they loaded the cargo.

Sables raced down to the cargo hold and the efficient workers already had the crate aboard and were shuffling away with their heads down. She stood at the top of the railing, not hiding her presence—they wouldn't look at her. Just placed the large crate and slipped away like unseen servants.

Sable feel an unease gripe and twist her stomach. She messed this up already. She needed to meet with the client, represent the Courier Guild, secure more jobs. After all that's what she was here for for. To extend the Guilds reach to more sectors. She held her datapad to the crate and it scanned, beeping with confirmation that this was indeed the package. She swallowed, her mouth dry, something about this package set her on edge. 

`iv-oracle:Descriptor|86|Sealed|oracle_rollable:starforged/core/descriptor`  `iv-oracle:Focus|62|Person|oracle_rollable:starforged/core/focus` 

The crate itself was locked and sealed up tight. Multiple layers of banding and reinforced locks gave it a menacing look. The majority of the weight must have been dedicated to just the amount of security measured they had bolted to it.

> Is the person alive?  `iv-oracle:50/50|58|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

"Don't touch it, don't look at it, don't ask questions. Just do your fucking job forge-dammit." Sable scolded herself. She quickly made sure the hover mode was turned off on the crate and it was firmly locked onto the platform. She held her breath and internally walked herself through her operating procedure. She had to get this right.

`iv-noroll:End a Session|move:starforged/session/end_a_session` 

---
```
Post Session Notes
 So, I've decided to end of session zero here. I wanted to get my thoughts down on what I have so far. Think of these as author notes, reflections, or whatever. This is also where I will note any End Session move relevance
 
 Yay, we have met Sable! Characters for me, inform me of who they want to be as I start to play them--which leads me to a practice that I've taken on with my Ironsworn/Starforged games and that's the session zero refresh. I let myself change stats and assets to better inform narrative. Of course only once and only at the end of session zero before I feel like the narrative starts really taking off. 
 
 We've also learned some about the Courier Guild, which I will fully flesh out for people to know more about. With learning these things about Sable and the Courier Guild I've decided to make some changes.
	 Edge: 2>3
	 Heart: 1
	 Iron: 1>2
	 Shadow: 2>1
	 Wits: 3>2
 I feel like this spread better defines who Sable is, what her goals are, and how she fits into the greater narrative.
 Now for Assets, I thinks she's pretty well there, though I am switching Outcast for Ace. It just makes more sense she is a fantastic pilot. Even though she's bad with people, she's not necessarily a loner.
 Thank you so much for reading Sable. I'm excited to see what happens to her next.
```