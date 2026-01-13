# Echo 01 - From the past
> Well, this took no time at all to come out
```iron-vault-mechanics
oracle name="[Begin a Session \/ Begin a Session](datasworn:move.oracle_rollable:starforged\/session\/begin_a_session.begin_a_session)" result="Flashback reveals an aspect of your background or nature" roll=2
```
```iron-vault-mechanics
oracle name="[Starship Oracles \/ Starship Name](datasworn:oracle_rollable:starforged\/starship\/starship_name)" result="First Light" roll=28
```

#### TWO DAYS BEFORE
INT. THE FIRST LIGHT IRONHOME

[[Echo 'Phantom' Stirling]] stepped past the airlock to the Ironhome for the first time since her escape from the cloning chambers and laid her eyes on the one who'd called her in. 
```iron-vault-mechanics
oracle-group name="NPC: Vesper Savela" {
    oracle name="[Character Oracles \/ Character Name \/ Given Name](datasworn:oracle_rollable:starforged\/character\/name\/given_name)" result="Vesper" roll=93
    oracle name="[Character Oracles \/ Character Name \/ Family Name](datasworn:oracle_rollable:starforged\/character\/name\/family_name)" result="Savela" roll=56
    oracle name="[Character Oracles \/ First Look](datasworn:oracle_rollable:starforged\/character\/first_look)" result="Alluring" roll=13
    oracle name="[Character Oracles \/ First Look](datasworn:oracle_rollable:starforged\/character\/first_look)" result="Adorned" roll=8
    oracle name="[Character Oracles \/ Initial Disposition](datasworn:oracle_rollable:starforged\/character\/initial_disposition)" result="Cooperative" roll=22
}
```
Vesper was as old as he'd ever been, as richly dressed in all esoteric symbols and fabric, smiling his warm smile as long white hair fell loosely on his weathered but still welcoming expression.

````
VESPER
Welcome, my dear, welcome! I must say, it's good to see your face, I remember fondly when your progenitor was as young as you...

ECHO
Progenitor, is this what we're calling it? It's not like I was meant to be her child, or her anything at all. So. What is it?

VESPER
Well, someone in the vaults is feeling talkative, and this is where I'd have called in your progenitor, but she's in the vaults too, now.

ECHO
I'm not her, you know that, yes? I'm a clone, not a replica.

VESPER
You still carry the gift and would have a home here, if you wanted it.

ECHO
The answer is no, once more. But... thank you. Lead on?
````

Echo followed him to the deepest parts of the First Light, where the ones traveling in the Long Voyage had started keeping their dead, preserved, and still continued to do so. Echo completely ignored the remains of her progenitor with aplomb, as she'd done since the first and last time they'd talked since her death, when the spirit had insisted that there was a very powerful relic in the deepest recesses of the galaxy that would awaken forces unknown, and that she, specifically, needed to find it. So she'd sworn to [[Find the lost relic and understand my connection to it]] and she'd walked away, twirling the black iron cards she'd inherited.

They stopped in front of the well-preserved corpse's alcove where Echo could see clear manifestations of unrest, the chill of space now much more prevalent and pungent. 
Vesper gestured to the body, explaining that this was his own grandfather, who apparently had urgent business, even in death.
Echo focused inwards and then out, bringing the eerie sounds of the spiritual winds rushing through the Ironhome, like a cold, damp wind, and suddenly Roman Savela opened his eyes once more and talked, voice creaking like old and dusty paper.

````
ECHO
I am Phantom. You called me. What has awakened you from your rest, spirit? Talk.

ROMAN
The attack, its waves... they spread.

ECHO
Which attack, Roman Vesper? 

ROMAN
Ackriss-2, and its horrors. The waves woke me up, and will wake more. It will wake the Hourglass, too. Take it, Phantom, or someone else will. 

ECHO
I will. I promise this. Where is it?

ROMAN
Vesper knows. 
````

> Well, isn't that a cheery way to end the conversation? 
> Luckily I've learnt to accept it when spirits do stuff like this.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Echo 'Phantom' Stirling\/Echo 'Phantom' Stirling.md|Echo 'Phantom' Stirling]]" {
    move "[Swear an Iron Vow](datasworn:move:starforged\/quest\/swear_an_iron_vow)" {
        roll "Heart" action=1 adds=0 stat=2 vs1=7 vs2=2
        reroll action=6
    }
}
```

Echo spun the dark iron card in her hand, making the Skeleton in the death tarot face Vesper, its eyes glowing an unsettling blue, and waited for the old man to find the information she'd need.

- *Vault and planet creation rolls folded under here in edit mode* 
	```iron-vault-mechanics
	oracle-group name="Precursor Vault Oracles: [[Hourglass_vault|New Precursor Vault Oracles]]" {
	    oracle name="[Precursor Vault Oracles \/ Location](datasworn:oracle_rollable:starforged\/precursor_vault\/location)" result="Orbital" roll=69
	    oracle name="[Precursor Vault Oracles \/ Scale](datasworn:oracle_rollable:starforged\/precursor_vault\/scale)" result="Large, elaborate site" roll=89
	    oracle name="[Precursor Vault Oracles \/ Form](datasworn:oracle_rollable:starforged\/precursor_vault\/form)" result="Incomprehensible" roll=98
	    oracle name="[Precursor Vault Oracles \/ Shape](datasworn:oracle_rollable:starforged\/precursor_vault\/shape)" result="Roll twice" roll=97 {
	        oracle name="[Precursor Vault Oracles \/ Shape](datasworn:oracle_rollable:starforged\/precursor_vault\/shape)" result="Spires or towers" roll=65
	        oracle name="[Precursor Vault Oracles \/ Shape](datasworn:oracle_rollable:starforged\/precursor_vault\/shape)" result="Sculptural or effigy" roll=75
	    }
	    oracle name="[Precursor Vault Oracles \/ Material](datasworn:oracle_rollable:starforged\/precursor_vault\/material)" result="Bone-like" roll=75
	    oracle name="[Precursor Vault Oracles \/ Outer First Look](datasworn:oracle_rollable:starforged\/precursor_vault\/outer_first_look)" result="Dreadful premonitions" roll=25
	    oracle name="[Precursor Vault Oracles \/ Outer First Look](datasworn:oracle_rollable:starforged\/precursor_vault\/outer_first_look)" result="Hazardous readings" roll=50
	}
	
	```
	Is the atmosphere inside the Vault breathable?
	```iron-vault-mechanics
	oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.fifty_fifty)" result="Yes" roll=2
	```
	Is it around Ackriss-2?
	```iron-vault-mechanics
	oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.fifty_fifty)" result="No" roll=85
	oracle name="[Planet Oracles \/ Planetary Class](datasworn:oracle_rollable:starforged\/planet\/class)" result="[Grave World](datasworn:oracle_collection:starforged\/planet\/grave)" roll=31
	oracle name="[Planet Oracles \/ Grave World \/ Observed From Space](datasworn:oracle_rollable:starforged\/planet\/grave\/observed_from_space)" result="Dry seabeds" roll=54
	
	
	oracle name="[Space Encounter Oracles \/ Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" result="Glowing orange star" roll=21
	```

---

#### PRESENT
INT. PRECURSOR VAULT - MAUSEFORT

Vesper had said that this place was called Mausefort, and from the tall spires jutting out of its bulk that she'd seen approaching, the reasoning at least on the 'fort' part was clear - though they had no rhyme or reason, going in any and all directions. 
The vault itself was a large monstrosity made of what looked like bone, sculpted and fused together by hands unknown, with no clear purpose, shining a tepid reflection in the warm light of the Croifols. 
The entrance she'd found was made of a deformed giant skull with its mouth wide open. It looked right at the planet the vault orbited, its oceans, as dead and dry as the bones that were looking upon it from above, disappeared from view as the maw closed behind the tiny form of the Ilex-zed.

Echo breathed in the dry air inside the Vault with a grimace. It smelled both dusty and alive, a little like the farthest chambers of the vaults of the dead inside the First Light, the ones that rarely spoke anymore, and no one visited. Dead, but with a presence. 

 ````
 ECHO

 If I didn't know that this mission came from the dead themselves, this would certainly spell it out. Is there any way to be more thematic than this?
 ````

Relieved when no one answered her, she centered on her breathing and reached out with her other senses, listening to the ever present ghostly wind and what it was telling her, thinking back to what Roman had whispered two days prior.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Echo 'Phantom' Stirling\/Echo 'Phantom' Stirling.md|Echo 'Phantom' Stirling]]" {
    move "[Gather Information](datasworn:move:starforged\/adventure\/gather_information)" {
        roll "Heart" action=2 adds=0 stat=2 vs1=4 vs2=10
        burn from=5 to=2
    }
}
oracle name="[Templates \/ Action + Theme](datasworn:oracle_rollable:starforgedsupp\/templates\/actiontheme)" result="Hold Burden" roll=49 {
    oracle name="[Core Oracles \/ Action](datasworn:oracle_rollable:starforged\/core\/action)" result="Hold" roll=53
    oracle name="[Core Oracles \/ Theme](datasworn:oracle_rollable:starforged\/core\/theme)" result="Burden" roll=10
}
oracle name="[Templates \/ Descriptor+Focus](datasworn:oracle_rollable:starforgedsupp\/templates\/descriptorfocus)" result="Contested Territory" roll=96 {
    oracle name="[Core Oracles \/ Descriptor](datasworn:oracle_rollable:starforged\/core\/descriptor)" result="Contested" roll=23
    oracle name="[Core Oracles \/ Focus](datasworn:oracle_rollable:starforged\/core\/focus)" result="Territory" roll=88
}

```
He hadn't been clear, not really, reminiscing about stories older than even him of a war that had decimated the planet, and how the Hourglass artifact, whatever it was, had been used to keep at bay the monstrosities of flesh and metal created to fight it after the planet had finally ceased to be viable at all. 

```iron-vault-mechanics
oracle name="[Precursor Vault Oracles \/ Interior \/ Inner First Look](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/first_look)" result="Dissonant tones or music" roll=27
```
```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Echo\/Find your way through the Mausefort to the Hourglass.md|Find your way through the Mausefort to the Hourglass]]" status="added"
```
As she thought about that old legend a shiver ran down her spine and she looked up and saw it. There, on the walls of one of the many bone corridors opening in front of her, was a bas-relief representing what could be one such monstrosity. 
As soon as she saw it the ghostly wind chimed for her ears only, with bitter and contrasting bell tones, so low-pitched that they lost their clarity.  

> And who am I to refuse such a clear invitation?

```iron-vault-mechanics
progress from=0 name="[[The Starforged\/Progress\/Echo\/Find your way through the Mausefort to the Hourglass.md|Find your way through the Mausefort to the Hourglass]]" rank="formidable" steps=1
```

