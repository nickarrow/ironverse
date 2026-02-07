```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Begin a Session](datasworn:move:starforged\/session\/begin_a_session)" {
        meter "Momentum" from=8 to=9
    }
    move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
        roll "Edge" action=4 adds=0 stat=1 vs1=5 vs2=9
        burn from=9 to=2
    }
}
progress from=0 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Reach the Devil's Chain Sector.md|Reach the Devil's Chain Sector]]" rank="formidable" steps=1
oracle name="[Space Encounter Oracles \/ Space Sighting \/ Outlands](datasworn:oracle_rollable:starforged\/space\/sighting\/outlands)" result="[Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" roll=6
oracle name="[Space Encounter Oracles \/ Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" result="Neutron star surrounded by intense magnetic fields" roll=77

```
>*"Become a Star"*
> *-Common phrase in the Circle of Elder Stars, in the same vein as "Rest in peace"*

It was, perhaps, a bad sign when things began going wrong at the very first anchorage they stopped at. A lone neutron star surrounded by practically nothing, it's peculiarly strong magnetic fields were assumed to be what allowed it to serve as an anchorage.

```
Epathus: Tybalt, mute your comms, I think I can hear your lieutenant committing vulgar indiscretions.

Tybalt: What are you talking about? If it was him, he'd not leave room for doubt

Paxel: Hey.

Epathus: ...Checking current course projections...yes we are listing. You?

Tybalt: ...Likewise, and towards a violent intersection. Magnetic fields might be causing comms interference too.
```

Said magnetic fields were currently wildly fluctuating, and the first obstacle Tybalt and Epathus had to overcome was to not crash into each other's ships. Granted, does communication between the two actually help, or hinder this goal?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.fifty_fifty)" result="Yes" roll=39
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Face Danger](datasworn:move:starforged\/adventure\/face_danger)" {
        add 1 "Actually not butting heads with Epathus"
        roll "Wits" action=3 adds=1 stat=2 vs1=9 vs2=4
        meter "Spirit" from=4 to=3
    }
}

```

The two get to work immediately in the mere minutes they have. And Tybalt feels every muscle in his body tighten into knots (and even imagines he can feel his palms sweating again) as the two ships pass each other by what feels like mere inches. But in the wake of this, there are no serious damage reports, save for someone getting their drink all over himself when the artificial gravity of both ships briefly brushed against one another.
```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Explore a Waypoint](datasworn:move:starforged\/exploration\/explore_a_waypoint)" {
        roll "Wits" action=4 adds=0 stat=2 vs1=6 vs2=4
        meter "Momentum" from=2 to=3
    }
}
oracle name="[Templates \/ Descriptor+Focus](datasworn:oracle_rollable:starforgedsupp\/templates\/descriptorfocus)" result="Mysterious Facility" roll=38 {
    oracle name="[Core Oracles \/ Descriptor](datasworn:oracle_rollable:starforged\/core\/descriptor)" result="Mysterious" roll=67
    oracle name="[Core Oracles \/ Focus](datasworn:oracle_rollable:starforged\/core\/focus)" result="Facility" roll=33
}

```

As they waited for the e-drives to recharge, Tybalt idly decides to take a look at the readings they were getting, to see why the star was behaving differently compared to the existing navigational data.

Most of it is nothing, but then he sees something strange. Something that shouldn't be coming from a neutron star.

A signal.

```
Epathus: Clarion Call, e-drive is recharged.

Tybalt: ...Kaal-Kaaz, e-drive is recharged.

Epathus: Are you experiencing difficulties?

Tybalt: No, no its...just a glitch.
```

They leave the system minutes later.

```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
        add 1 "Learning to cooperate"
        roll "Edge" action=6 adds=1 stat=1 vs1=8 vs2=1
    }
}
oracle name="[Space Encounter Oracles \/ Space Sighting \/ Outlands](datasworn:oracle_rollable:starforged\/space\/sighting\/outlands)" result="Large rogue asteroid" roll=73
oracle name="[Space Encounter Oracles \/ Spaceborne Peril](datasworn:oracle_rollable:starforged\/space\/peril)" result="Meteoroid storm fills the sky" roll=44

```

Then, as if the universe was trying to express immense displeasure with the two Serrato ships not having a collision, the next anchorage they reach was experiencing a massive asteroid storm, and they were presently stuck for as long as it took to recharge. And through the blanket of lesser rocks the ships sensors could detect, there was an especially large one coming their way

```iron-vault-mechanics
track name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Survive the Asteroid Storm.md|Survive the Asteroid Storm]]" status="added"
- "![[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Survive the Asteroid Storm.md|iv-embed]]"
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.fifty_fifty)" result="Yes" roll=15
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Enter the Fray](datasworn:move:starforged\/combat\/enter_the_fray)" {
        add 1 "Both ships can protect each other with overlapping fire"
        roll "Wits" action=6 adds=1 stat=2 vs1=2 vs2=1
        meter "Momentum" from=4 to=5
    }
    move "[Gain Ground](datasworn:move:starforged\/combat\/gain_ground)" {
        roll "Wits" action=4 adds=0 stat=2 vs1=9 vs2=1
        meter "Momentum" from=5 to=7
    }
}

```

But while such things were common enough in their part of the galaxy, much of the *Kaal-Kaaz*' crew currently consisted of scavengers from a grave world, supplemented by what few volunteers Tybalt could find on short notice, so they were ultimately at greater risk than the *Clarion Call* even as they sheltered in it's shadow.

```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Strike](datasworn:move:starforged\/combat\/strike)" {
        roll "Edge" action=3 adds=0 stat=1 vs1=4 vs2=1
        burn from=7 to=2
    }
}
progress from=0 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Survive the Asteroid Storm.md|Survive the Asteroid Storm]]" rank="dangerous" steps=2
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Gain Ground](datasworn:move:starforged\/combat\/gain_ground)" {
        roll "Iron" action=6 adds=0 stat=3 vs1=10 vs2=7
    }
}
progress from=16 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Survive the Asteroid Storm.md|Survive the Asteroid Storm]]" rank="dangerous" steps=1

```

```
Epathus: Tybalt, I am currently contacting you to convey my earnest surprise that the venerable Kaal-Kaaz has not been scuttled under your helmsmanship in this storm. Also, the storm is thinning out, the cannons can be left to cool after the next two volleys

Tybalt: Noted. Also, suck eggs Epathus.
```
```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Gain Ground](datasworn:move:starforged\/combat\/gain_ground)" {
        roll "Wits" action=2 adds=0 stat=2 vs1=3 vs2=8
    }
}
progress from=24 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Survive the Asteroid Storm.md|Survive the Asteroid Storm]]" rank="dangerous" steps=1
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Take Decisive Action](datasworn:move:starforged\/combat\/take_decisive_action)" {
        progress-roll name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Survive the Asteroid Storm.md|Survive the Asteroid Storm]]" score=8 vs1=6 vs2=7
        meter "Momentum" from=2 to=3
    }
    move "[Hearten](datasworn:move:starforged\/recover\/hearten)" {
        roll "Heart" action=6 adds=0 stat=2 vs1=1 vs2=7
        meter "Spirit" from=3 to=5
    }
}
progress from=6 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Find where he stands with Epathus.md|Find where he stands with Epathus]]" rank="extreme" steps=1

```

But, it would be as Epathus says, and the endless hail of space rocks would eventually stop smashing against their hulls, and Tybalt would take the time to offer praise (and token material rewards) to his crew for their performance before they needed to jump again.
```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
        add 1 "Connection Bonus"
        roll "Wits" action=5 adds=1 stat=2 vs1=2 vs2=6
    }
}
oracle name="[Space Encounter Oracles \/ Space Sighting \/ Outlands](datasworn:oracle_rollable:starforged\/space\/sighting\/outlands)" result="[Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" roll=11
oracle name="[Space Encounter Oracles \/ Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" result="Smoldering red star" roll=4
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Explore a Waypoint](datasworn:move:starforged\/exploration\/explore_a_waypoint)" {
        add 1 "Connection"
        roll "Wits" action=4 adds=1 stat=2 vs1=2 vs2=8
        meter "Momentum" from=3 to=4
    }
}
oracle name="[Miscellaneous Oracles \/ Interlude Scene](datasworn:oracle_rollable:sundered_isles\/misc\/interlude_scene)" result="Practice a skill" roll=57
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Secure an Advantage](datasworn:move:starforged\/adventure\/secure_an_advantage)" {
        roll "Heart" action=3 adds=0 stat=2 vs1=1 vs2=9
        meter "Momentum" from=4 to=6
    }
}
progress from=4 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Reach the Devil's Chain Sector.md|Reach the Devil's Chain Sector]]" rank="formidable" steps=1

```

Now bothering to take their time instead of rushing forward at all speed, the two warships reach the next anchorage to find nothing at all waiting for them. Given what happened the last two times, they are not entirely willing to just take this safety at face value, and after a long search that ultimately turns up nothing at all they are left wound up enough to spend the rest of the wait drilling their respective crews on things that *could* happen. Something that has the crews bonding through shared misery, and a shared inability to really say no to the augmented killing machines that they answer to.
```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
        add 1
        roll "Wits" action=4 adds=1 stat=2 vs1=1 vs2=4
    }
}
progress from=8 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Reach the Devil's Chain Sector.md|Reach the Devil's Chain Sector]]" rank="formidable" steps=2
oracle name="[Space Encounter Oracles \/ Space Sighting \/ Outlands](datasworn:oracle_rollable:starforged\/space\/sighting\/outlands)" result="Roll twice" roll=98 {
    oracle name="[Space Encounter Oracles \/ Space Sighting \/ Outlands](datasworn:oracle_rollable:starforged\/space\/sighting\/outlands)" result="[Descriptor](datasworn:oracle_rollable:starforged\/core\/descriptor) + [Focus](datasworn:oracle_rollable:starforged\/core\/focus)" roll=53 {
        oracle name="[Core Oracles \/ Descriptor](datasworn:oracle_rollable:starforged\/core\/descriptor)" result="Lost" roll=61
        oracle name="[Core Oracles \/ Focus](datasworn:oracle_rollable:starforged\/core\/focus)" result="Trap" roll=92
    }
    oracle name="[Space Encounter Oracles \/ Space Sighting \/ Outlands](datasworn:oracle_rollable:starforged\/space\/sighting\/outlands)" result="[Settlement](datasworn:oracle_collection:starforged\/settlement)" roll=38
}
oracle-group name="Settlement: Koshiba Port" {
    oracle name="[Templates \/ Region](datasworn:oracle_rollable:starforgedsupp\/core\/region)" result="Outlands" roll=61
    oracle name="[Settlement Oracles \/ Settlement Name](datasworn:oracle_rollable:starforged\/settlement\/name)" result="Koshiba" roll=40
    oracle name="[Name Suffix](datasworn:oracle_rollable:starforged\/settlement\/name_tags)" result="Port" roll=8
    oracle name="[Settlement Oracles \/ Location](datasworn:oracle_rollable:starforged\/settlement\/location)" result="Planetside" roll=40
    oracle name="[Population](datasworn:oracle_rollable:starforged\/settlement\/population\/outlands)" result="Thousands" roll=87
    oracle name="[Settlement Oracles \/ First Look](datasworn:oracle_rollable:starforged\/settlement\/first_look)" result="Rustic architecture" roll=72
    oracle name="[Settlement Oracles \/ Initial Contact](datasworn:oracle_rollable:starforged\/settlement\/initial_contact)" result="Welcoming" roll=20
    oracle name="[Settlement Oracles \/ Authority](datasworn:oracle_rollable:starforged\/settlement\/authority)" result="None \/ lawless" roll=3
    oracle name="[Settlement Projects](datasworn:oracle_rollable:starforged\/settlement\/projects)" result="Shipbuilding" roll=74
    oracle name="[Settlement Trouble](datasworn:oracle_rollable:starforged\/settlement\/trouble)" result="Overdue delivery" roll=59
}

```

The next leg of their journey is not occupied by shared solitude, but by the chatter of civilian life on all frequencies as they arrive at Port Koshiba, oft touted as the "Port at the End of the Forge" for its role as the last settlement where one can find Terminus-grade ship facilities before venturing into the untamed vastness of the Expanse. Said facilities only exist owing to the combined investments of several noble houses who wish to be the ones selling the proverbial shovels to any prospectors venturing into those nameless stars

```
Epathus: Tybalt, you're a snake-tongued devil right?

Tybalt: Are you trying to pick a fight now?

Epathus: No, I think the merchant collectives in system are all trying to call me first, since the Clarion Call is bigger. Talk to them for what they might know.

Tybalt: Why can't you- Is it because you'll tell them to-

Epathus: Because I'll tell them to plough their own sisters, yes. I think it would offend this...Risen Union the most out of them all though. They sound like the sort to take that bait the hardest.
```
```iron-vault-mechanics
progress from=8 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Tybalt-Yhen Serrato\/Find where he stands with Epathus.md|Find where he stands with Epathus]]" rank="extreme" steps=1
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Compel](datasworn:move:starforged\/adventure\/compel)" {
        roll "Heart" action=2 adds=0 stat=2 vs1=4 vs2=9
        burn from=6 to=2
    }
}

```

Groaning, Tybalt would thumb the requisite buttons on his command-throne to receive all the incoming call requests. But before he could get swept away in a tide of advertising, he put on his best "Woe to the Vanquished" voice before making a broadcast on all frequencies

![[Message 02 - Tybalt-Yhen Serrato]]
```iron-vault-mechanics
progress from=2 name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Progress\/Expose the darkness behind the attacks across the sector and stop it from spreading.md|Expose the darkness behind the attacks across Devil's Chain and stop it from spreading]]" rank="extreme" steps=1
```
Tybalt observed, with mixed feelings, how the attempts to hawk trinkets to him diminished, only to be replaced with new requests to accept incoming files: Annotated cargo manifests, extraction quotas and a host of other things he had no choice now but to at least try and parse.

At least he might get real information on his quarry's habits, and not get dragged into the intrigues of this place

....

Bah, who was he kidding?

---
```iron-vault-mechanics
actor name="[[The Starforged\/Campaign Tybalt-Yhen Serrato\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[End a Session](datasworn:move:starforged\/session\/end_a_session)"
}
```

