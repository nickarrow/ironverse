# Echo 01 - From the past
> Well, this took no time at all to come out

 `iv-oracle:Begin a Session|2|Flashback reveals an aspect of another character, place, or faction|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 
 `iv-oracle:Starship Name|28|First Light|oracle_rollable:starforged/starship/starship_name` 
#### TWO DAYS BEFORE
##### INT. THE FIRST LIGHT IRONHOME

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

Echo spun the dark iron card in her hand, making the Skeleton in the death tarot face Vesper, its eyes glowing an unsettling blue, and waited for the old man to find the information she'd need to `iv-track-create:Take the Hourglass Relic and keep it safe|The Starforged/Progress/Echo/Take the Hourglass Relic and keep it safe.md`.

---
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
```Is the atmosphere inside the Vault breathable?``` `iv-oracle:50/50|2|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty`
```Is it around Ackriss-2?``` `iv-oracle:50/50|85|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty`
```iron-vault-mechanics
	oracle name="[Planet Oracles \/ Planetary Class](datasworn:oracle_rollable:starforged\/planet\/class)" result="[Grave World](datasworn:oracle_collection:starforged\/planet\/grave)" roll=31
	oracle name="[Planet Oracles \/ Grave World \/ Observed From Space](datasworn:oracle_rollable:starforged\/planet\/grave\/observed_from_space)" result="Dry seabeds" roll=54
	
	
	oracle name="[Space Encounter Oracles \/ Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" result="Glowing orange star" roll=21
```
---

#### PRESENT
##### EST.  MAUSEFORT PRECURSOR VAULT

Vesper had said that this place was called Mausefort, and from the tall spires jutting out of its bulk that she'd seen approaching, the reasoning at least on the 'fort' part was clear - though they had no rhyme or reason, going in any and all directions. 
The vault itself was a large monstrosity made of what looked like bone, sculpted and fused together by hands unknown, with no clear purpose, shining a tepid reflection in the warm light of the Croifols. 
The entrance she'd found was made of a deformed giant skull with its mouth wide open. It looked right at the planet the vault orbited, its oceans, as dead and dry as the bones that were looking upon it from above, disappeared from view as the maw closed behind the tiny form of the Ilex-zed.

##### INT. MAUSEFORT ENTRANCE
Echo breathed in the dry air inside the Vault with a grimace. It smelled both dusty and alive, a little like the farthest chambers of the vaults of the dead inside the First Light, the ones that rarely spoke anymore, and no one visited. Dead, but with a presence. 

 ````
 ECHO

 If I didn't know that this mission came from the dead themselves, this would certainly spell it out. Is there any way to be more thematic than this?
 ````

Relieved when no one answered her, she centered on her breathing and reached out with her other senses, listening to the ever present ghostly wind and what it was telling her, thinking back to what Roman had whispered two days prior.
`iv-move:Gather Information|Heart|2|2|0|4|10|move:starforged/adventure/gather_information` `iv-burn:5|2` `iv-oracle:Action + Theme|49|Hold |oracle_rollable:starforgedsupp/templates/actiontheme`  `iv-oracle:Descriptor+Focus|96|Contested Territory|oracle_rollable:starforgedsupp/templates/descriptorfocus` 
He hadn't been clear, not really, reminiscing about stories older than even him of a war that had decimated the planet, and how the Hourglass artifact, whatever it was, had been used to keep at bay the monstrosities of flesh and metal created to fight said war after the planet had finally ceased to be viable at all. 
`iv-oracle:Inner First Look|27|Dissonant tones or music|oracle_rollable:starforged/derelict/inner_first_look` 
`iv-track-create:Find your way through the Mausefort to the Hourglass|The Starforged\/Progress\/Echo\/Find your way through the Mausefort to the Hourglass.md`
As she thought about that old legend a shiver ran down her spine and she looked up and saw it. There, on the walls of one of the many bone corridors opening in front of her, was a bas-relief representing what could be one such monstrosity. 
As soon as she saw it the ghostly wind chimed for her ears only, with bitter and contrasting bell tones, so low-pitched that they lost their clarity.  

> And who am I to refuse such a clear invitation?
`iv-track-advance:Find your way through the Mausefort to the Hourglass|The Starforged/Progress/Echo/Find your way through the Mausefort to the Hourglass.md|8|4|formidable|1` 
##### INT. MAUSEFORRT CORRIDOR - 1 
`iv-oracle:Inner First Look|3|Ascending or descending path|oracle_rollable:starforged/derelict/inner_first_look` 
`iv-oracle:Descriptor+Focus|28|Preserved People|oracle_rollable:starforgedsupp/templates/descriptorfocus` 
`iv-track-advance:Find your way through the Mausefort to the Hourglass|The Starforged/Progress/Echo/Find your way through the Mausefort to the Hourglass.md|8|8|formidable|1`

She walked forward following the low bell tones and their warbling, steps careful and alert. The corridor didn't seem to branch at all, uniform and dull ivory-white, until she noticed the very gradual ascending slope she had been walking when the path twisted suddenly in a spiral, going up. 
Bordering the sudden ascent there were hollow-eyed statues with dust gathering on them, staring straight into the soul of any that dared walk this path. If anyone else were there, they would have though them just unsettling decoration, but Echo could clearly hear their song joining in with the bells. They looked like bone, melted into shape, but they clearly weren't.
Maybe they had something to say.

She looked with her eyes, tasted the air, touched the bone-- stone, with her hands, all to avoid just going to talk with the voices she could now hear whisper in her ears. 
No one wanted to get ambushed because they'd gotten used to listening to spirits first, Vesper had insisted, rightfully so. These particular voices sounded soft, inviting, relaxing.
````
VOICES
don't... don't go... stay... don't move... sleep...
````
`iv-move:Face Danger|Iron|2|1|0|8|4|move:starforged/adventure/face_danger` `iv-burn:5|2` 
Her eyelids lowered down, her body melting on the shallow bone steps under her, surprisingly soft and warm, the ghostly wind finally slowing down, peace after hearing it for all her life, the bells drawing out, their sound warbling and sliding before its pitch became, surprisingly, harmony. 

````
VOICES
...never awake... always asleep... stay.
````
 `iv-meter:Spirit|5|4`
The bells. The vault. Roman had said about something the spirits waking up, hadn't he?
Echo suddenly stood up, shards of what looked like bone enamel falling down from her limbs, shaken: she hadn't even noticed.
> When did I sit down?? 

```
ECHO
Enough!
```

Her voice echoed through the vault and in the winds beyond. `iv-meter:Momentum|2|3`

```
ECHO
I am Phantom, you will listen to me. Tell me of the hourglass or stay silent!
```
`iv-move:Gather Information|Heart|5|1|0|8|10|` `iv-oracle:Pay the Price|30|Your action causes collateral damage or has an unintended effect|move.oracle_rollable:starforged/fate/pay_the_price.pay_the_price` 

> Does the Hourglass have to do with actually freezing time/in time like I've been thinking all this time?  `iv-oracle:50/50|41|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

The hands of the frozen dead around her broke free from the enamel and surged forward, the echoes of Echo's voice and her command still ringing around, but the undeads' voices around her now spoke clearly. 

```
VOICES
...fall under the Hourglass' sleep with us, or die and fall prey to it then.
```

>Trap 'yes', melee 'no' `iv-oracle:50/50|13|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

Echo scanned quickly her exact position, trying to find a way forward: she didn't want to fight these poor, compelled dead people, though she would if she had to. She had to escape. `iv-track-create:Escape the Statues|The Starforged\/Progress\/Echo\/Escape the Statues.md`

`iv-move:Enter the Fray|Wits|1|3|0|10|4|move:starforged/combat/enter_the_fray`  `iv-initiative:Position|in a bad spot|in a bad spot`   

The dead were never spry and fast, not usually, and this time it wasn't different. They tried to grab her with freezing hands, to hold her down. Had she ever said that she'd stay put? No. `iv-move:React Under Fire|Edge|2|0|0|7|2|move:starforged/combat/react_under_fire` 
Echo ducked under the freezing hands and dodged legs, their joints still stiff from their long vigil making it easier, a little. Still, she hissed through her teeth when she saw that her pistol had slipped its holster and was still right there in the middle of the cluster. `iv-meter:Supply|5|4`
She took the collapsible blade out, unhappily, and shook it into place. She wasn't the best with it. She would try and reason with them instead, even if it just slowed them down a little.   

```
ECHO
Listen to me! I am Phantom, you must listen.
```

She made an effort to make her voice less commanding and more entreating in the spirit-winds, while still giving the command.   `iv-move:Secure an Advantage|Heart|5|2|0|1|7|move:starforged/adventure/secure_an_advantage` heart 5 0 2 1 7
The dead faltered, their song in the winds losing a little of their readiness to fight, but still creeping forward.

```
ECHO
I don't intend to use the relic! I was sent here to 'take it, or someone else would' by one of you! 
```

She tried to remember the exact sensation of Roman Vesper's speech as she said it, to evoke the lingering silhouette of that conversation and project it to them.  `iv-move:Compel|Heart|3|2|1|5|8|move:starforged/adventure/compel|adds=1(there must be a benefit to being a necromancer after all)` 
The wind picked up pace so much that she almost expected her hair to blow away in it, so strong was the noise. Then as one the dead surrounded her, even as she stepped back, pushing her to the edge of the staircase and its looming drop.

```
VOICES
Swear on your soul cards then, Phantom, and don't lie or we'll know. Should you live and find the hourglass, find whoever wants it, and stop them.

ECHO
Stop them from doing what?

VOICES
Swear it.

ECHO
I swear, I will!
```

`iv-move:Swear an Iron Vow|Heart|3|2|0|3|6||burn=7:3|move:starforged/quest/swear_an_iron_vow` 
As Echo took her five black iron tarots and pulled out the Death one without looking, facing its pale blue glow towards them, swearing to `iv-track-create:Stop those who want to take the Hourglass|The Starforged\/Progress\/Echo\/Stop those who want to take the Hourglass.md`, the spirits settled and their songs dimmed. She opened her mouth to ask further details-

One glacial hand, encased in enamel, landed on her shoulder and *pushed* her off the stairs.

```
VOICE
Good luck, Phantom.
```

`iv-track-complete:Escape the Statues|The Starforged\/Progress\/Echo\/Escape the Statues.md`
`iv-noroll:End a Session|move:starforged/session/end_a_session` 
> I need to remember: complete the vault and the current vow, yes, but while Echo is here she should probably also look into the mysterious them"
> `iv-meter:Momentum|5|6`

[[Echo 02 - The Bones of Giants]]