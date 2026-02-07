```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Begin a Session](datasworn:move:starforged\/session\/begin_a_session)" {
        meter "Momentum" from=2 to=3
    }
}

```
>*"It is not paranoia when the Forge really is plotting to destroy you."*
>*- Unknown Serrato Bannersworn, died to a sniper after being convinced to eat without his helmet, at the Siege of Sirona*

Tybalt and Epathus brought their ships down to sandy Audun, where the only relief from the unending glare of its suns were sandstorms that could fry an elephant into a smoking corpse with the sheer static charge held within them. As it was, the only human life that existed upon the planet was found in Port Koshiba, contained within a bubble of esoteric safety bounded by pillars of black iron, of clear Precursor make, from which more conventionally sheltered drydocks extended out via train networks sheltered by an extensive solar grid. The settlement kept itself watered by means of the vast, almost ocean-sized aquifers that existed almost mockingly below the sun-scorched surface, and the diet of the locals consisted of submersible-caught fish (both alien and imported species) and hydroponics-grown crops

```
Epathus: Hmph, I've heard it said that the sponsor houses of Port Koshiba claim a shared heritage from the Homeworld. Hence why they insist on building their city according to dead guidelines.

Tybalt: You sound skeptical.

Epathus: Skepticism implies I even give them a shred of the benefit of the doubt. But they try far too hard for me to believe them, even if it's all true.

Paxel: I thought the Serrato were supposed to be big on tradition?

Tybalt & Epathus: The difference is that we're right.

Paxel: ....Uh huh. Sure.
```

Before they would disembark, however, Tybalt would make sure to hash out a definitive agreement for what is to be done for their ships, lest they have additional costs sprung upon them by overly 'generous' shipwrights and merchants. As it stood, there was nothing they strictly required beyond prudent maintenance and topping off their stockpiles, but Tybalt wished to remind the locals that a lack of interest in commerce did not translate to being easily swindled
```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Secure an Advantage](datasworn:move:starforged\/adventure\/secure_an_advantage)" {
        add 1
        roll "Heart" action=4 adds=1 stat=2 vs1=3 vs2=4
        meter "Momentum" from=3 to=5
    }
}

```

Feeling like he did a rather good job of it, rather easily evading their word-traps by reminding his port liasons that they could be talking to Epathus instead, Tybalt could readily join his fellow Reaver-Chief in making a show of disembarking with their warriors and their crews and dispensing their pay and permitting them to take shore leave.
```iron-vault-mechanics
progress from=10 name="[[The Starforged\/Progress\/Tybalt-Yhen Serrato\/Find where he stands with Epathus.md|Find where he stands with Epathus]]" rank="extreme" steps=1
oracle name="[Derelict Oracles \/ Community \/ Area](datasworn:oracle_rollable:starforged\/derelict\/community\/area)" result="Promenade or overlook" roll=58

```

Half an hour later, with Paxel having slipped off to somewhere (Tybalt guessed the Red Light District, given the things he's seen his second watching on his data-pad) and Epathus stomping through the city (either looking for weapons to either praise or mock, or hoping to stumble upon a lair of the Ascendancy for happenstance bloodletting), Tybalt would make himself the center of attention by meeting all those who have (or would claim to have) suffered the predations of the pirates at a central promenade, right in the shadow of some sort of temple.
```iron-vault-mechanics
clock name="[[The Starforged\/Clocks\/Tybalt-Yhen Serrato\/Meet & Greet concluded.md|Meet & Greet concluded]]" status="added"
- "![[The Starforged\/Clocks\/Tybalt-Yhen Serrato\/Meet & Greet concluded.md|iv-embed]]"
```
```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Tybalt-Yhen Serrato\/Complaint Compiling.md|Complaint Compiling]]" status="added"
- "![[The Starforged\/Progress\/Tybalt-Yhen Serrato\/Complaint Compiling.md|iv-embed]]"
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Face Danger (Scene Challenge)](datasworn:move:starforged\/scene_challenge\/face_danger)" {
        add 1 "Secure Advantage"
        roll "Heart" action=2 adds=1 stat=2 vs1=10 vs2=1
    }
}
progress from=0 name="[[The Starforged\/Progress\/Tybalt-Yhen Serrato\/Complaint Compiling.md|Complaint Compiling]]" rank="dangerous" steps=1
clock from=0 name="[[The Starforged\/Clocks\/Tybalt-Yhen Serrato\/Meet & Greet concluded.md|Meet & Greet concluded]]" out-of=4 to=1

```

Though he knew well enough that the people petitioning him could very well be trying to swindle him with false woes, they had yet to actually attempt it yet and even the Serrato were disinclined to lash out for no reason at all, and so he listened with as much patience as he could muster. But after the first two dozen, he was already feeling the strain. Wondering if his second's abilities extended to sniffing out lies, he attempted to contact the man (wherever he was)

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Unlikely](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.unlikely)" result="No" roll=52
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Secure an Advantage (Scene Challenge)](datasworn:move:starforged\/scene_challenge\/secure_an_advantage)" {
        roll "Wits" action=4 adds=0 stat=2 vs1=2 vs2=5
        meter "Momentum" from=5 to=7
    }
    move "[Face Danger (Scene Challenge)](datasworn:move:starforged\/scene_challenge\/face_danger)" {
        add 1 "Secure an Advantage"
        roll "Wits" action=4 adds=1 stat=2 vs1=7 vs2=2
    }
}
progress from=8 name="[[The Starforged\/Progress\/Tybalt-Yhen Serrato\/Complaint Compiling.md|Complaint Compiling]]" rank="dangerous" steps=1
clock from=1 name="[[The Starforged\/Clocks\/Tybalt-Yhen Serrato\/Meet & Greet concluded.md|Meet & Greet concluded]]" out-of=4 to=2

```

Tybalt could feel his regret for letting Paxel wander off grow by spades, even if having him here might have risked an incident from an unnecessary comment (though he had nothing against warranted violence). But through his growing migraine he managed to thread together a pattern in the disparate complaints and petitions.
```iron-vault-mechanics
oracle name="[Templates \/ Action + Theme](datasworn:oracle_rollable:starforgedsupp\/templates\/actiontheme)" result="Capture Spirit" roll=91 {
    oracle name="[Core Oracles \/ Action](datasworn:oracle_rollable:starforged\/core\/action)" result="Capture" roll=17
    oracle name="[Core Oracles \/ Theme](datasworn:oracle_rollable:starforged\/core\/theme)" result="Spirit" roll=81
}
```

It had seemed like a discrepancy that marked out a lie at first, but the more he heard the less he could deny the picture forming: The Ascendancy was making a habit of ignoring crates of foodstuffs, luxury goods, and even weapons in cases where they were beaten back, in favor of specific types of cargo. That when put together could, as Tybalt mostly knew from random trivia he picked up over the course of his life, was mostly for esoteric rituals. Incense sticks, hallucinogenic herbs, 'psychically-active' materials. This was in conjunction with certain...habits he has noticed in the anecdotes, and observed himself prior to travelling out here. During their raid upon Helia-36, he had seen the results of what had seemed to be the pirates purposely enacting ritual murders, even as their own fleet was being beaten back by the defenders.

It had shaken him more than he thought it would, seeing people killed in ceremony, rather than rage.

And none of it made any real *sense* to Tybalt of course, but it didn't need to. He assumed there would be a more understandable motive at the end of this road, but all he wanted was a way to find these pirates to begin with.

`iv-move:Face Danger (Scene Challenge)|Wits|2|2|0|3|4|move:starforged/scene_challenge/face_danger`  `iv-track-advance:Complaint Compiling|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Complaint Compiling.md|16|24|dangerous|1`  `iv-clock-advance:Meet & Greet concluded|The Starforged/Campaign Tybalt-Yhen Serrato/Clocks/Tybalt-Yhen Serrato/Meet & Greet concluded.md|2|3|1|4`  `iv-move:Face Danger (Scene Challenge)|Wits|3|2|0|8|9|move:starforged/scene_challenge/face_danger`  `iv-clock-advance:Meet & Greet concluded|The Starforged/Campaign Tybalt-Yhen Serrato/Clocks/Tybalt-Yhen Serrato/Meet & Greet concluded.md|3|4|1|4`  `iv-clock-resolve:Meet & Greet concluded|The Starforged/Campaign Tybalt-Yhen Serrato/Clocks/Tybalt-Yhen Serrato/Meet & Greet concluded.md`  `iv-progress:Finish the Scene|Complaint Compiling|6|10|9|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Complaint Compiling.md|move:starforged/scene_challenge/finish_the_scene`  `iv-oracle:Pay the Price|47|A new enemy is revealed|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 
Now at last he could begin asking for the data on where the attacks took place, and the data was promising. To the untrained eye, the attacks would seem to be happening sporadically, appearing and vanishing from nothingness. 

Yet if the pirates allowed themselves to be predictable, potential victims might very well risk sailing uncharted drifts rather than face their guns. So Tybalt guessed that they paced and planned and concealed themselves from commercial scanners as best they could. 

While he deliberated on the matter, all around him a social event seems to have coalesced, for the wealthy always had time to throw away. From powdered ladies with parasols indulging their vanity by showing off the splendour of their attire. To men sipping imported tea as they related outlandish hallucinations about the Serrato to make themselves seem learned. A thousand games of one-upmanship roiled around Tybalt as he strove to present a strong face despite the turmoil in his soul.

`iv-oracle:Starship Type|92|Fleet|oracle_rollable:starforged/starship/type`  `iv-oracle:Fleet|20|Pirate wing|oracle_rollable:starforged/starship/fleet`  `iv-oracle:First Look|9|Bristling with weapons|oracle_rollable:starforged/starship/first_look` Because what had seemed a promising lead had crumbled to dust in his hands, for the pattern he discerned should have been impossible. Throughout dozens of after-action reports the exact same attack wing, in both design and identifiers, of ships appeared again and again, phenomenally well-armed for their weight-classes and thus leading the attacks. Now, it was entirely possible that the Ascendancy simply had several of these fleets waiting across Devil’s Chain, programmed to broadcast the same identifiers to project an illusion of being everywhere at once (Even if it implied an almost frightening scale of industry)

But then he keeps seeing signs of battle-damage that the highlighted ships retain in chronological order of attacks. Despite the fact that they should have needed to travel for weeks along well-charted routes to be present at attacks that were mere days apart.

*”Precursor technology.”* Tybalt curses in the privacy of his mind. They had found something that let them circumvent the limitations that constrained even the Founder Clans. Something like that miracle shield projector he had once raced to acquire ahead of them, that let him survive fighting a pirate crew with dedicated anti-armor weaponry, and live through a free-fall drop from orbit in a malfunctioning shuttle.

`iv-oracle:First Look|92|Well-equipped|oracle_rollable:starforged/character/first_look`  `iv-oracle:First Look|95|Wiry|oracle_rollable:starforged/character/first_look`  `iv-oracle:Number|27|Few|oracle_rollable:sundered_isles/misc/magnitude/number`  `iv-oracle:Combat Action|93|Use an unexpected weapon or ability|oracle_rollable:starforged/misc/combat_action`  `iv-move:Enter the Fray|Wits|4|2|0|3|9|move:starforged/combat/enter_the_fray`  `iv-meter:Momentum|7|9` 

Tybalt was so distracted by the implications of this new information that, as he departed the venue to share his findings with his fellow Bannersworn, he failed to keep his guard up as he headed for where they had quartered themselves in as straight a line as he could manage. Much of that was on the assumption that no alley gang would dare attempt to challenge his passage, let alone possess anything that could pierce his armour.

`iv-oracle:Zones|37|Living|oracle_rollable:starsmith/districts/zones`  `iv-oracle:Area|38|Locker room or storage|oracle_rollable:starsmith/districts/living/area`  It is within a multi-storey carpark, crowded with the personal vehicles of Port Koshiba’s wealthier inhabitants, that he is disabused of this notion. Lost in his thoughts, he attributes the shimmers in the air to heat, taking too long to remember that the building he was in was fully air-conditioned. Tybalt’s lapse costs him, as an invisible blade, sharpened to a monomolecular edge thrust at his neck grazes his gorget and thus goes askew. But it unbalances him enough that he fails to stop four separate bodies leaping onto him, as if to achieve with numbers what precision failed to.

> Is Tybalt the only target? (Match) `iv-oracle:Unlikely|66|No|move.oracle_rollable:starforged/fate/ask_the_oracle.unlikely`  `iv-oracle:Action + Theme|22|Protect Vow|oracle_rollable:starforgedsupp/templates/actiontheme` 

Even as he tried to batter them aside, to make space to draw his weapons or even to smash their bones with his iron hands, Tybalt could see by the ugly gash in his gorget that the assembly-line chainmail protecting his joints and neck would not withstand a direct blow from the blades of his assailants.

But just as one of them was ready to make the Bannersworn choke on steel, the familiar thump of a Serrato Mag-Rifle rings out, and the ensuing hail of bullets either clatters harmlessly against Tybalt’s warplate or flies past him to set off car alarms by punching holes in them. As Tybalt staggers upright he draws his axe, he finally gets a good look at his opponents. Their dull grey bodysuits revealed down to a man the physiques of dancers, slim but strong, and the son of Bertold was willing to bet that those suits possessed layers of synthetic muscle to go with their personalised stealth fields. And for weapons, they bore gleaming, single-edged swords of unassuming design, and carried an assortment of gadgets and pistols on their belts.

Keeping his gaze focused upon the four assassins, he speaks to his lieutenant through the speaker in his warplate.

```
Tybalt: Paxel? I thought you were at some pleasure den?

Paxel: Wasn’t feeling it anymore, decided to take a hike. And didn’t you say this place would be quiet?
```

Before the argument could escalate, one of the four killers addressed Paxel over the shrill shriek of alarms

```
Assassin: Begone from here. Your master is the only one marked to die. You may leave with your throat uncut.

Paxel: OoooOoh, how intimidating. Unfortunately for you, a pretty girl just shot me down hard, and the only way I’m gonna feel better is making it everyone else’s problem.

Assassin: Then die a fool.
```

Right at that moment, both sides had achieved what they were stalling for: Tybalt had sent out a distress signal with accompanying danger assessments, and responses were already filtering in one after the other. While the assassins stealth fields had finished recharging, and so they disappeared at once, to try and finish the job before more interference arrived in response to the gunfire  `iv-track-create:Conflict in the Carpark|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Conflict in the Carpark.md` 

`iv-move:React Under Fire|Wits|3|2|0|4|9|move:starforged/combat/react_under_fire`  `iv-noroll:Lose Momentum|move:starforged/suffer/lose_momentum`  `iv-meter:Momentum|9|8` While he still could, Tybalt cycled through his helmet’s vision modes to see if any of them could pierce their stealth fields. But when he had switched to heatvision, that is when one of them popped a smoke grenade with some additive that rendered the cloud a dizzying mass of blinding stars that forced Tybalt to shut his eyes lest they get damaged.

`iv-move:Clash|Iron|4|3|2|8|8|move:starforged/combat/clash|adds=1(Blademaster),1(Augmented)`  `iv-meter:Momentum|8|10`  `iv-track-advance:Conflict in the Carpark|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Conflict in the Carpark.md|0|12|formidable|3` Blinded, and unable to hear his opponents over the cacophony of car alarms and Paxel’s covering fire, other men might have withdrawn, chosen not to risk themselves in a 4-on-1 to instead go on the backfoot and wait for reinforcements.

But the Bannersworn of the Serrato had a reputation for suicidal bravery, for straddling the line between heroism and foolishness, and Tybalt was no exception to this. He knew his enemies would pounce on any opening he presented. That they would use their numbers to force one into being.

But Tybalt knew his armour, and that there were only so many angles from which his enemies could slice his throat.

Raising *Shattersky* high, as if for a telegraphed downward chop right in front of himself, he sharply turns anti-clockwise half a second later, and is rewarded by the sound of blades scoring lines in inch-thick armour plating rather than maille and rubbery insulation. Tybalt’s roar as he turns his downward chop into a horizontal cleave, which then divorces an assassin’s head from their shoulders, is one of feral satisfaction

`iv-dice:1d6|2`  `iv-oracle:Combat Action|56|Make a sacrificial attack|oracle_rollable:starforged/misc/combat_action`  `iv-move:Strike|Iron|3|3|2|5|7|move:starforged/combat/strike|adds=1(Blademaster),1(Augmented)`  `iv-track-advance:Conflict in the Carpark|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Conflict in the Carpark.md|12|20|formidable|2` Staggering back for but a moment as Tybalt’s gambit sees one of them slain, their attempts to continue the assault and wear him down by attrition fail as the Serrato gains control of the fight and the smoke begins to clear. 

`iv-oracle:Unlikely|78|No|move.oracle_rollable:starforged/fate/ask_the_oracle.unlikely` One of them goes for a strike at Tybalt’s neck, pistol firing point-blank into his visor in a clear attempt to distract him. For his efforts he is split down the middle from his shoulder, and the ally he was making a distraction for is rebuffed by a shoulder shove.

`iv-oracle:Revealed Character Aspect|69|Proud|oracle_rollable:starsmith/characters/revealed_aspect`  `iv-oracle:Combat Action|152|Make a swift and showy attack|oracle_rollable:starsmith/misc/action`  `iv-move:Strike|Iron|6|3|2|2|6|move:starforged/combat/strike|adds=1(Blademaster),1(Augmented)`  `iv-track-advance:Conflict in the Carpark|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Conflict in the Carpark.md|20|28|formidable|2` Reduced to half their number, they wordlessly display their pride by refusing to relent on their acrobatic offensive despite these losses and the diminishing of their stealth fields. As if they could not stand to be beaten in their own field of expertise, and Tybalt imagined he could feel the frustration in their strikes, reverberating through arms that could never grow tired. While every swing he made demanded they dodge it, for attempting to parry would threaten to break their bones.

`iv-oracle:Combat Action|20|Counter or reflect an attack|oracle_rollable:starsmith/misc/action`  `iv-move:Strike|Iron|4|3|2|2|5|move:starforged/combat/strike|adds=1(1),1`  `iv-track-advance:Conflict in the Carpark|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Conflict in the Carpark.md|28|36|formidable|2`  `iv-progress:Take Decisive Action|Conflict in the Carpark|9|10|6|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Conflict in the Carpark.md|move:starforged/combat/take_decisive_action`  `iv-oracle:Take Decisive Action|25|It’s worse than you thought: Make a suffer move (-2)|move.oracle_rollable:starforged/combat/take_decisive_action.take_decisive_action`  `iv-track-complete:Conflict in the Carpark|The Starforged/Campaign Tybalt-Yhen Serrato/Progress/Tybalt-Yhen Serrato/Conflict in the Carpark.md` 

Mere minutes have passed since the fight began, but Tybalt’s relative spotlessness was bought by spending every second of it fighting as hard as his flesh could go. He did not remember when the counter in the corner of his helmet’s HUD, tracking the number of strikes that had been taken by his armour, passed a thousand and he had no desire to tempt fate any further. As his axe cuts down a third foe, the fourth is already leaping to strike at the opening Tybalt had no choice but to expose in that moment. Then another shot rings out, and the blade is shot out of the assassin’s hand, who is in turn sent spinning away from the force of it. Seeing the tables turn, Tybalt seizes this opening to grab his opponent by the arm. And before they could wriggle from his grasp, he yanks hard and swings them right into a nearby charging station, the glossy plastic exterior cracking from the impact.

Then again. And again. Until Tybalt is reasonably sure his new prisoner has been rendered insensate. Dropping them upon the floor, he turns to speak to Paxel, and pauses when he realises they weren’t alone anymore.  `iv-oracle:First Look|292|Unarmored|oracle_rollable:starsmith/characters/first_look`  `iv-oracle:First Look|36|Flashy|oracle_rollable:starforged/character/first_look`  To his surprise, it is not one of his warriors, nor any of the local law enforcement. Instead it is a woman in the attire of a office bureaucrat, worn in a way to flaunt her youth, but her face was presently glancing back and forth between Tybalt and the destruction all around him. Her thumb absentmindedly presses against the screen of the civilian communicator sitting in her hand, presumably sharing what she was seeing.

Trying to shift his mind back to less violent tracks, Tybalt looks around as the battle-haze recedes and really takes in the devastation. Of the vehicles with broken windows and gaping bullet holes. The electrical charger he had smashed the last assassin into (that just caught fire). The dismembered bodies scattered around himself.

Thus, he gives his answer for the camera.

```
Tybalt: Ffffffuuuuuuuuuuuuuuuuck
```

He was going to have to pay so much in reparations.  `iv-meter:Supply|5|3` 

`iv-noroll:End a Session|move:starforged/session/end_a_session` 