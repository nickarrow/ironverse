```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Begin a Session](datasworn:move:starforged\/session\/begin_a_session)" {
        meter "Momentum" from=2 to=3
    }
}

```

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
actor name="[[The Starforged\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
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
actor name="[[The Starforged\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
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
actor name="[[The Starforged\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
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