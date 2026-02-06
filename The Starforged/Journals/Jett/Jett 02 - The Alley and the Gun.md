
"Are you ready to talk about it now?" asks Jett.

The three of them had made their way back to the ship.  Sofia showered and slept off the booze.  Eventually she joined the others in the lounge. 

Bones looks tense, ready to lash out at the first opportunity.

"Someone stole my ship.  I came here to get Total Immersion recording implants. Shen put me in touch with a gang with a rigger, but when I got undressed for the procedure they saw my tattoos and figured out who I was.  They refused to do the surgery - they didn't want to risk pissing off my father.  When I went back to my ship, it was gone.  I've been stuck here ever since."

"I need to go back to The Snakepit to drop Bones off." says Jett.  "I can give you a ride".

"I can't go back without my ship!  You're not a Cobra, you wouldn't understand.  My dad is already going to be pissed off that I took off without telling anyone, he'll probably throw me out of an airlock if I lose a ship too"

"He'll just be relieved that you're safe, trust me" says Jett.

"Yeah, for all of five minutes" says Bones "You've only seen his good side."

"He tied me to a chair and threatened to throw me out of an airlock!"

"Positively cheerful, by his standards."

"Fine" says Jett as he takes out his Black Iron ring.

"Don't do it"  says Eris.  "You only agreed to find her, there's no need to do this"

"I vow to find your missing ship" says Jett.

"If I had a head, I would be holding it in my hands" says Eris.

```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Jett\/Find Sofia's missing ship.md|Find Sofia's missing ship]]" status="added"
```

---

Since finding the missing ship is probably going to involve leaving the base, Jett decides to deal with Shen's stalker first.  Trusting the two pirates not to steal the ship, possibly not the wisest decision he's ever made, he heads to the market to scope it out.  He makes a note of the layout, various stalls and landmarks, entrances and exits and anything else that may be useful.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Secure an Advantage](datasworn:move:starforged\/adventure\/secure_an_advantage)" {
        roll "Wits" action=3 adds=0 stat=3 vs1=4 vs2=2
    }
}
```

Now familiar with the area, he focuses his attention on places which simultaneously have good line of sight on Shen's stall, but remain secluded from view.  He looks for anyone who may be watching Shen.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Gather Information](datasworn:move:starforged\/adventure\/gather_information)" {
        add 1
        roll "Wits" action=5 adds=1 stat=3 vs1=9 vs2=9
    }
}
```

As he's looking around, he feels the familiar sensation of a gun barrel suddenly being poked into his back.  Someone speaks using a voice modulator to disguise their identity.  "Don't make any sudden moves.  Where's your weapon?" they whisper.

"I don't have one." replies Jett.

"Everyone has a weapon" whispers the voice.

"I guess I'm not everyone" Jet says.

"Fine.  Move to the alleyway now."

Jett follows the figure's instructions.  If anyone notices what's happening, they don't want to get involved.  Once they're in the alleyway the figure frisks Jett and confirms that he does not have a weapon on him.

"Why are you looking for me?" they ask.

"You slipped up.  Shen saw you."

"And he wanted you to kill me?"

"I'm unarmed, remember?  He just wanted to know who you are."

"Get out of here.  If I see you looking for me again I'll kill you."

---

Jett heads to Shen's stall.  "Well, I didn't find out exactly who is following you, but I have some ideas."

"Well?" says Shen.

"From they way they spotted me in a crowd and abducted me at gunpoint, I'd say they're a professional.  Probably a bounty hunter if I had to guess.  The good news is, if they wanted to kill you you'd already be dead so you're safe there.  I'd extrapolate that they're using you to get to the gang you tried to deliver Sofia to, or one of your customers."

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Fulfill Your Vow](datasworn:move:starforged\/quest\/fulfill_your_vow)" {
        progress-roll name="[[The Starforged\/Progress\/Jett\/Find out who is following Shen.md|Find out who is following Shen]]" score=3 vs1=1 vs2=3
    }
}
```

Shen is silent for a long moment.  "Ok then, we're even.  Get out of here."

Jett moves on to his next mission, hopefully with better luck.

---

Jett goes back to *The Irony* and uses his terminal to patch in to the local net.  The ship registration site is accessible by the public, showing all the comings and goings of ships to and from the station as well as which ships are currently docked in which landing bays.  He runs a search on Sofia's ship, *The Revenge*. 

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Gather Information](datasworn:move:starforged\/adventure\/gather_information)" {
        roll "Wits" action=2 adds=0 stat=3 vs1=9 vs2=10
    }
}
```

The computer shows the Revenge never left the station - it's still in Docking Bay 7.  Jett goes to Docking Bay 7 and there is no ship there.  Jett returns to *The Irony* once again and runs another search - this time on the news sites, looking for any other ship thefts or disappearances.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Gather Information](datasworn:move:starforged\/adventure\/gather_information)" {
        roll "Wits" action=1 adds=0 stat=3 vs1=2 vs2=6
    }
}
```

Jett finds dozens of missing ship reports going back years.  Each time, the ship landed but was later found to be missing with no record of it having left.  He asks Eris to help him look for a pattern in the disappearances.  Eris notices that each disappearance happens at around the same time as the disappearance of an individual - usually a solo traveler, usually young.  The only outlier is Sofia - she's the only one whose ship disappeared when she didn't.

Jett gets a sinking feeling in his stomach.  He's starting to connect the dots.

He gathers the others in the lounge once more and presents his findings.

"So, looking at the evidence, it seems like every other missing ship is paired with a missing person.  Except for Sofia, here.  So the question is, what did Sofia do while she was here, and what is different about her?  She came here looking for Total Immersion recording ware.  Lots of young people do, they all dream of making it big by recording themselves living a life of luxury and selling the experience to people stuck in a life of drudgery, a brief escape from the grim reality of their lives.  Only, Sofia was rejected by the gang.  She came back.  I think it's very likely that either Shen or the gang has contacts at the spaceport.  This is a salvage and reclamation yard; their livelihood is breaking down old ships and selling the parts.  They probably took the ship apart right there on the landing pad and wheeled the parts out of the cargo bay doors.  They knew nobody who goes to see the gang comes back, so the ships were basically free money."

"The only question is, what happens to the kids that go to see the gang?"  says a voice.  The speaker is using a voice modulator.  Jett recognizes them immediately as the person from the market earlier.  Now, Jett can get a clear look at them.  They are wearing black body armor and a full-face ballistic helmet, standing in the doorway of the lounge.

"Intruder alert" says Eris

"Yes, we know" says Jett. 

"You figured it out quickly." says the figure.  "It took me quite a bit longer.  My sister went missing here three months ago, I'm here to save her or avenge her.  That's why I'm tailing Shen, waiting for him to make contact with the gang"

"I know where the gang are" says Sofia.  "I can show you where, if you help me get my ship back."

"Your ship is probably in pieces all across the market being bartered for as we speak" says the figure.

"Not necessarily" says Bones.  "They backed out when Sofia's links to the Cobras came out.  Maybe they kept the ship as well."

"Only one way to find out" says the figure.

"Okay, so we go after the gang" says Jett "But we need to call you something.  Do you have a name?  Or at least a callsign?"

The figure sighs, and takes off his helmet.  He whips his hair back revealing his ruggedly handsome face.

"Failsafe??" says Sophia in disbelief.  "What the fuck?"