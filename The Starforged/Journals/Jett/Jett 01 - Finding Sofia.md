
```iron-vault-mechanics
track name="[[The Starforged\/Progress\/Jett\/Find Sofia Legrand.md|Find Sofia Legrand]]" status="added"
```

Jett enters Sofia's quarters and checks in all the obvious places - the back of the closet, under the bed, her computer terminal.

"Find anything yet?" says Bones.  Bones is new.  [[Machete]] had told Jett that he was there as a bodyguard, but Jett suspected he was also there to make sure he didn't forsake his vow and run.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Gather Information](datasworn:move:starforged\/adventure\/gather_information)" {
        roll "Wits" action=6 adds=0 stat=3 vs1=7 vs2=8
    }
}
```

"Yeah, I know where she was headed.  She was supposed to meet someone at the diner on a settlement called [[Paxton Memorial]].  Did you guys seriously not check her emails?"

"Funnily enough, we don't have a resident detective aboard.  Why was she headed to that scrapyard, anyway?"

"Dunno.  Let's head there and find out."

---

"So, why is your ship called 'The Irony'?  Seems like a funny name for a ship"

"I chose it" says Eris, the ship's AI. "I don't know how much you know about Jett here, but some great scientists built a machine to create the perfect hero to save the galaxy from chaos.  Jett is what it spat out."

"It's a little bit more complicated than that, but essentially yes, I have a preordained destiny."  said Jett.

"What's your destiny?" asks Bones.

"I'm sure I'll recognize it when I see it" replies Jett.

"That machine was probably faulty.  The scientists all died of old age decades ago." says Eris.

"You'll see." says Jett.

---

Paxton Memorial is slightly more depressing than you'd expect a salvage and reclamation yard to be.  Perhaps it's the specific shade of gray the designers chose for the station's walls, but it's just a sad place to be.

In contrast to the environment, the people are friendly and welcoming.  The trade module - the only habitation module open to the public - contains a number of docking bays, a diner, a bar, and a market where traders are selling salvaged goods to interested buyers.

"Where to first?" asks Bones, as he and Jett step off the ship.

"The diner.  After four straight days of ship rations, I'm ready for a proper meal"

"We have a job to do."

"Trust the process" says Jett.

They enter the small diner.  There's only one server, and presumably a cook in the back, and Jett and Bones are the only two customers.  Jett takes a seat on one of the high stools at the counter and Bones follows suit. 

"Hi fellas, I'm Darlene and I'll be taking care of you today.  What can I get you?"

"Any local speciaties?" asks Jett.  

Darlene laughs.  "I don't know if vat-grown soy counts as a specialty"

"Just give us two plates of the greasiest thing on the menu" says Bones.  Darlene walks to the kitchen to process the order.  "Why are we wasting time chatting to waitresses?  The boss expects results."

"If Sofia was here, she probably ate something" replies Jett.  "We want Darlene on our side.  She might know something."

Jett chats to Darlene as they eat and finds out about her life - her family own the diner, she's the server and her husband is the cook, her sons operate a tugboat hauling the lost ships to the station to be stripped.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Gather Information](datasworn:move:starforged\/adventure\/gather_information)" {
        roll "Wits" action=4 adds=0 stat=3 vs1=7 vs2=3
    }
}
```

As he eats, Jett takes in his surroundings.  He notices a 'Wall of Shame' - security footage stills of dine-and-dashers.

"Hey, Darlene.  I'm actually not here to buy scrap, I'm looking for a girl"

"I'm afraid you're in the wrong place for that" replies Darlene with a cheeky grin.

"Funny.  No, I'm looking for a specific girl.  In fact, I'm looking for *that* girl".  Jett points at one of the pictures on the wall.  It's unmistakably Sofia Legrand.

"Oh, her.  She showed up not so long ago.  Sat in that booth by the window every day for three days.  She ordered a single cup of coffee each time and just sat there staring out the window.  On the third day, a man showed up.  Didn't order anything.  He left after a couple of minutes.  She left five minutes later without paying her bill."

"Did you recognize the man?  Do you have a picture of him?"

"I don't have a picture, the security footage gets scrubbed weekly, but I know him.  I don't know if I should be getting involved if that's where this is headed, though."

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Compel](datasworn:move:starforged\/adventure\/compel)" {
        roll "Heart" action=5 adds=0 stat=2 vs1=2 vs2=10
    }
}
```

"She's just a kid.  She could be in trouble.  What if one of your boys went missing on a job?  Wouldn't you want someone to tell you what they know?"

Darlene lowers her voice.  "He's Shen, he sells VR games at the market.  But under the counter, he sells Total Immersion stuff.  You know, the stuff they record live so you can experience it for yourself.  It's banned on the station but he pays the right people off."

"Okay, thanks Darlene.  Don't worry, your name won't come up.  We'll pay for the kid's drink too."

---

Jett and Bones head to the market.

"See?  I told you, trust the process" says Jett as they walk.

"That was just luck.  What are the odds that her picture would be plastered on the wall?"

"Zero.  Unless fate intervenes."

Bones gives a derisive snort.

The market is surprisingly large and diverse.  There are stalls selling everything from replacement hull panels to exotic pets.  Eventually, they arrive at a stall selling VR equipment and software.

"In the market for a bit of entertainment?  We've got all kinds of games old and new, as well as the equipment you need to get started." says the vendor.

"It all looks very interesting" replies Jett.  "But I was looking for something a bit more...*immersive*...if you get my drift?"

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Compel](datasworn:move:starforged\/adventure\/compel)" {
        roll "Heart" action=5 adds=0 stat=2 vs1=4 vs2=8
    }
}
```

"Oh, I get your drift.  I don't know who you've been talking to but I don't just do business with anyone who walks in off the street.  If you want to take a look at that stuff you're going to have to do something for me to prove you're on the level."

"I'm tired of this" says Bones suddenly.  "Look, we're not here to muck about.  You've been seen with Sofia.  Tell us where she is or I'll beat it out of you."

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Compel](datasworn:move:starforged\/adventure\/compel)" {
        roll "Iron" action=2 adds=0 stat=1 vs1=7 vs2=2
    }
}
```

The man laughs.  "Sofia?  She's in the bar, last I saw her, looking for leads.  But you can't talk to me like that, I pay my protection money.  You're going to do this job for me, or I'll call the guards over here."

Bones steps forward, fists clenched.  Jett puts a hand on his chest.  "Hold up, we don't want to wind up in the brig"  Turning to the merchant he says "What's this job?"

"Someone's been following me.  They're good, I only see glimpses of them, but I want to know who they are."

"Ok, sounds simple enough" says Jett.

"You're going to help him, just like that?" says Bones, incredulous.

"It's that or face the guards.  And besides, he did tell us where Sofia is."

"Well?" says the merchant.

Jett holds the Black Iron ring that's hanging from a chain around his neck.  "I vow that IF I find Sofia where you said she would be, I will discover who has been following you".

"Not sure I like that 'if' but it'll do." says the merchant.  "Now, if you're not going to buy something, kindly piss off"

---

Jett and Bones enter the bar.

```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Jett Foley\/Jett Foley.md|Jett Foley]]" {
    move "[Fulfill Your Vow](datasworn:move:starforged\/quest\/fulfill_your_vow)" {
        progress-roll name="[[The Starforged\/Progress\/Jett\/Find Sofia Legrand.md|Find Sofia Legrand]]" score=8 vs1=5 vs2=9
    }
}
```

The bar is somewhere between empty and full; there are still empty tables but the barman is pouring drinks not polishing glasses.  Without much effort, they find Sofia.  She looks up at them, tears streaming down her face.

"Oh, Bones, thank God you're here.  I'm in trouble.  Deep trouble."