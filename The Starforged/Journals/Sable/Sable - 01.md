
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session`  `iv-oracle:Begin a Session|3|Flashback reveals an aspect of your background or nature|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 
**+ Add Momentum**
# Flashback - Entering the Courier Guild
"Alright, Courier Route 497, welcome aboard Sable." The women, Kaska, handed Sable her courier signet, a small set of rectangle black iron pieces with four triangles pointed inward. The the back displayed her name, callsign, and courier number... 497. "Weasel?"

Sable instantly burst a breathy chuckle, "My parents gave me that callsign. I had a habit of getting into trouble as a child--as well as the habit of never telling the truth." Sable looked up at the women to meat her concerned gaze, "Don't worry, I've since grown out of the habit."

Another lie. Sable never really knew when telling the truth about anything when the best course of action. Her webs often grew larger than manageable, but she was long gone by the time the trails of her deceit came nipping at her heels.

"Uncoursed sectors can be really dangerous and very unstable. I know you're eager to prove yourself, being a legacy and all, but it's best to pace yourself. That's why your first job is an easy one in this sector before we send you further." Kaska pressed a button on her datapad and Sable's smaller handheld one came to life with the information.

A simple job. Something you could hand to a child. This was how it would start for Sable. One incremental step after another, slowly making her way to higher level jobs until they assigned her to her own sector. Probably something far out of the way, a lawless frontier.

Sables eyes glanced up to the galaxy map wavering in the holo-projector beaming overhead in the facility. Each glimmering node was a courier making their way through galaxy taking all manner of cargo from one place to another. Clusters of moving stars moving steadily, almost like the map was breathing. Her eyes traced the lines until they were scarce, then none existent. The [[Devil's Chain]] poised on the far edge of the map. She already had the request form filled out on her datapad. 

The last known place her parent's [[Find Her Parents Ship|ship]] was located.

---
# Courier of the [[Devil's Chain]]

**INT. ABOARD CR-479 DOCKED ON [[Audun|AUDEN]]**

*beep... beep... beep...* 

The incessant light lit up the surrounding control in a soft red haze as it dimmed and brightened to the tone that rung through the cabin. Sable held her head and and walked through the corridors with one hand fisting a sleepy eye will the other eye saw stars and she blinked it awake. She slammed the toggle and Leela's face came beaming across the screen.

"Good morning sleepy head, you have a package." Sable winced as the young girls voice came through the screen.

Leela was the unfortunate intern assigned to Sable's sector as her handler. Sable had been more than unkind to her in the past. She didn't like the idea of having them assign her babysitter. she made it just fine everywhere else, there was no need to keep her on a leash now that she finally got assigned the position she wanted in the Devil's Chain.
```iron-vault-mechanics
oracle-group name="NPC: [[Leela Asper]]" {
    oracle name="[Character Oracles \/ First Look](datasworn:oracle_rollable:starforged\/character\/first_look)" result="Energetic" roll=35
    oracle name="[Character Oracles \/ Initial Disposition](datasworn:oracle_rollable:starforged\/character\/initial_disposition)" result="Friendly" roll=12
    oracle name="[Character Oracles \/ Character Role](datasworn:oracle_rollable:starforged\/character\/role)" result="Scout" roll=79
    oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Maintain order" roll=40
}
```
"How's the boyfriend Leela?" Perhaps Sable would make nice. Besides she needed a few minutes to get the ship warmed up.

`iv-oracle:Unlikely|84|No|move.oracle_rollable:starforged/fate/ask_the_oracle.unlikely` Leela whipped up her gaze and glared into the screen. Sable averted her gaze and her lips went into a flat line. Sable was missing something--or probably more likely completely forgot something. Sable let the silence hand as heavy as a lead weight.

Her ship warmed, stirring through the startup process as listless as she was. Getting started in Devil's Chain was slow. It would take time before the services of a courier became well established. Until then she would be begging to take literally anything from point A to B for pennies.

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

"You're picking up a Black service package from an orbiting outpost called 'Glimmer Outpost'. It's also marked red." Leela's tone went stale. Seemed the question about her boyfriend made her as stiff in conversation as a board. Her matter-of-fact tone unsettled Sable.

This was a Black service package and marked red for that matter. Black service meant you don't ask about it. You don't open it. You don't even look at it. Red meant urgent. Sable had no time to loose and not a second to waste. 

"Thank you Leela. I'll get going immediately." Sable accepted the request. "Hey, and sorry about your boyfriend." Sable meekly gave a sincere look.

Leela growled a scream in frustration and shut off the comm-link. Maybe she wasn't mad about a boyfriend? Sable shrugged and picked up her discarded courier suit from the floor. Speaking of boys. He must have left early this morning. *What was his name?*. Sable thought as she pulled the pants over her bare legs, donned the arms, and zipped the suit up. The sigil of the Courier Guild was plastered on a patch on her left arm. Her left breast patch showed the colors of her rank, she currently sat at orange. Just two levels down from her legacy. Not that she truly cared about living up the name Rowe.

Sable wiped the memories of her parents from her mind and turned to her counsel. "Glimmer outpost here we come," she murmured to herself.

```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Courier Job Glimmer Outpost.md|Courier Job: Glimmer Outpost]]" status="added"
```
`iv-move:Swear an Iron Vow|Heart|1|1|0|4|5|move:starforged/quest/swear_an_iron_vow`  `iv-oracle:Story Complication|27|Natural disaster is imminent|oracle_rollable:starforged/misc/story_complication` 

Just as Sable began to charge up to leave her dashboard came to light with warnings. Peering outside people were bustling about like ants to shut everything down, tie of loose cargo, and rush inside. Sables sensors beeped with warnings as an electrical storm closed in.

She didn't have time for this. The storms out here were brutal and would last a considerable amount of time. This package was marked red, which meant it was her job as courier to brave ever hardship to rush the job. She picked up her courier hat and firmly placed it on her mop of long brown hair, tugging on the brim of it until it fit snuggly on her head.

`iv-noroll:Begin the Scene|move:starforged/scene_challenge/begin_the_scene`  Survive The Electrical Storm
```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Sable\/Survive the Electrical Storm.md|Survive the Electrical Storm]]" status="added"
clock name="[[The Starforged\/Clocks\/Sable\/The Electrical Storm Overtakes the Port.md|The Electrical Storm Overtakes the Port]]" status="added"

```
Sable rushes to move out, pulling in the landing gear and revving up for takeoff. Her eyes scan the route out and she smiles as she sees her clear shot through a break in the storm. `iv-move:Secure an Advantage (Scene Challenge)|Wits|2|3|0|10|6|move:starforged/scene_challenge/secure_an_advantage` 

**CLUNK** 

```iron-vault-mechanics
clock from=0 name="[[The Starforged\/Clocks\/Sable\/The Electrical Storm Overtakes the Port.md|The Electrical Storm Overtakes the Port]]" out-of=4 to=1
```

"Shit," Sable cursed. The ship was still connected to the fuel line. "shit, shit, stupid, shit, fuck, gah..." Her curses were punctuated with every word as pounded her way outside to disconnect the fuel line. Her hat tried to break free, but she caught the thing shoving it into her suit, letting her hair whip wildly in the wind. The fuel connector clanked on the floor and she slammed the fuel cover closed and locked it. *Don't forget to lock it*.

She sped back up to the cockpit and plopped herself into her chair, exasperated, wind swept, and feeling pretty dumb. She took a breath. She knew she could do this. Sable wasn't about to let months of downtime trip her up. She found her opening and she took it `iv-move:Face Danger (Scene Challenge)|Wits|4|3|0|6|10|move:starforged/scene_challenge/face_danger`.
```iron-vault-mechanics
progress from=0 name="[[The Starforged\/Progress\/Sable\/Survive the Electrical Storm.md|Survive the Electrical Storm]]" rank="troublesome" steps=1
clock from=1 name="[[The Starforged\/Clocks\/Sable\/The Electrical Storm Overtakes the Port.md|The Electrical Storm Overtakes the Port]]" out-of=4 to=2

```

