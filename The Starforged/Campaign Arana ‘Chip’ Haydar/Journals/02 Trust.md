```iron-vault-mechanics
oracle name="[Begin a Session \/ Begin a Session](datasworn:move.oracle_rollable:starforged\/session\/begin_a_session.begin_a_session)" result="Seemingly unrelated situations are shown to be connected" roll=35
```


Could Arana sense the Assassins were going after [[Paladin Janya Bridger]]?

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.likely)" result="Yes" roll=7

```

As [[Arana Haydar]] and [[Luna Palmer]] started to head for the front, Arana stopped and shuddered.

"Master, the Paladin! Someone is about to attack her!"

Luna looked at [[Knight Jasher]] "Does she have any bodyguards?"

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Unlikely](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.unlikely)" result="No" roll=65
```

The knight's face showed concern "We're spread too thin, we don't have enough for a guard detail."

"Apprentice, we need to go and remove any threats to Paladin Bridger," she looked back at the knight. "send assistance when it is possible, we will do what we can."

Arana pulled out her hilt and made a quick vow.

"I swear we will protect the Paladin from the danger."

```iron-vault-mechanics
move "[Swear an Iron Vow](datasworn:move:starforged\/quest\/swear_an_iron_vow)" {
    roll "Heart" action=1 adds=0 stat=3 vs1=4 vs2=1
}
```
```iron-vault-mechanics
track name="[[The Starforged\/Campaign Arana ‘Chip’ Haydar\/Progress\/Protect the Paladin from the danger.md|protect the Paladin from the danger]]" status="added"
```
The knight saluted with his green sword, "I hear your vow, and acknowledge it. For justice and peace!"

Master and apprentice saluted with their own sabers, "For Justice and peace!"

They split up, and Arana followed her master across the courtyard into the admin building.

Has the fighting started in the office yet?

```iron-vault-mechanics
- "Has the fighting started in the office yet?" {
oracle name="[Ask the Oracle \/ Almost Certain](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.almost_certain)" result="Yes" roll=85
}
```
```iron-vault-mechanics
- "Is Paladin Bridger able to defend herself?" {
    oracle name="[Ask the Oracle \/ Almost Certain](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.almost_certain)" result="No" roll=91
}
```
```iron-vault-mechanics
- "Is she killed?" {
    oracle name="[Ask the Oracle \/ Small Chance](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.small_chance)" result="No" roll=68
}

```

They come up on the room, and kick the door in.

```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:starforged\/combat\/enter_the_fray)" {
    roll "Edge" action=1 adds=0 stat=2 vs1=2 vs2=9
}
```
In Control.

After kicking in the door, Arana saw that she also knocked over a man in a dull Gray full body suit with a knife. Six more figures dressed in the same dull Gray outfits were near the wounded Paladin Bridger, the Paladin looks to have been stabbed at least twice in the back. Three of those assassins near the Paladin were on the ground with various forms of fatal wounds, obviously dead.

Arana attacks the assassin laying on the ground.

```iron-vault-mechanics
move "[Strike](datasworn:move:starforged\/combat\/strike)" {
    roll "Iron" action=4 adds=0 stat=2 vs1=7 vs2=5
}
```

```iron-vault-mechanics
progress from=0 name="[[The Starforged\/Campaign Arana ‘Chip’ Haydar\/Progress\/Protect the Paladin from the danger.md|protect the Paladin from the danger]]" rank="dangerous" steps=1
```

Arana manages to wound the assassin, but the assassin jumps up and locks blades with Arana.

"Apprentice, take this one, and I will start with those near Bridger."

"Yes master."

The assassin swung at Arana:

```iron-vault-mechanics
move "[Clash](datasworn:move:starforged\/combat\/clash)" {
    roll "Iron" action=6 adds=0 stat=2 vs1=10 vs2=5
    progress from=8 name="[[The Starforged\/Campaign Arana ‘Chip’ Haydar\/Progress\/Protect the Paladin from the danger.md|protect the Paladin from the danger]]" rank="dangerous" steps=1
    meter "Health" from=5 to=4
}

```

Arana mostly blocked the assassin's blade, but the assassin's blade cut her arm. The assassin tried stab her:

```iron-vault-mechanics
move "[Clash](datasworn:move:starforged\/combat\/clash)" {
    roll "Iron" action=6 adds=0 stat=2 vs1=1 vs2=1
    progress from=16 name="[[The Starforged\/Campaign Arana ‘Chip’ Haydar\/Progress\/Protect the Paladin from the danger.md|protect the Paladin from the danger]]" rank="dangerous" steps=2
}

```

With blood dripping down her left arm, Arana parried the blow, and swung down in a diagonal slash that ended the assassin's life. Arana turned to go help her master, and saw that one of the other four assassins had been decapitated, and the other two were ferociously swinging at Luna. Arana charged at one of the assassins to end the fight.

```iron-vault-mechanics
move "[Fulfill Your Vow](datasworn:move:starforged\/quest\/fulfill_your_vow)" {
    progress-roll name="[[The Starforged\/Campaign Arana ‘Chip’ Haydar\/Progress\/Protect the Paladin from the danger.md|protect the Paladin from the danger]]" score=8 vs1=3 vs2=4
    track name="[[The Starforged\/Campaign Arana ‘Chip’ Haydar\/Progress\/Protect the Paladin from the danger.md|protect the Paladin from the danger]]" status="completed"
}

```

Paladin Luna saw her apprentice charge in at one of the assailants, and seized the opportunity to incapacitate one of the assassins, while Arana cut the last assassin down. 

"Check on the paladin while I tie up this criminal," said paladin Luna, seemingly barely winded. 

"Yes master."

```iron-vault-mechanics
- "The paladin was still alive, but was she mortally wounded?" {
    oracle name="[Ask the Oracle \/ Unlikely](datasworn:move.oracle_rollable:starforged\/fate\/ask_the_oracle.unlikely)" result="Yes" roll=23
}
```

Master Bridger was breathing shallowly as Arana checked her wounds, as she rolled her over, she could see that the wounds inflicted to the paladin were fatal. 

"Master! There's a lot of blood, can you do anything to stabilize her?"

Master Luna shoves the now tied up assassin to the side. As she begins to try to stabilize the other paladin, bridgers eyes flutter open and looks at Arana 

"Save... her," Bridger said, choking on the blood. "Bring back... my daught... [[Tomiko]]."

She looks at Luna. "I appoint you... as the ranking paladin... to be in... charge of the outpost. I am sorry... for my... hasty words. You... fought well... outsider... I entrust my... assignment to you. For justice... and..."

Her eyes dim, and Luna shuts them. They both kneel over the dead paladin, giving her a respectful moment of silence.

Luna's glare was as icy as the storms of Rosston, causing the immobilized man to blanch in fear.

"You and I," the paladin promised coldly, "are going to be really closely acquainted."



```iron-vault-mechanics
move "[End a Session](datasworn:move:starforged\/session\/end_a_session)"
```

