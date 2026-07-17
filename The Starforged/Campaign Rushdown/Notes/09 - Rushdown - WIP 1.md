
`iv-noroll:Begin a Session|move:starforged/session/begin_a_session` 

*Rushdown found a derelict and woke the dormant ship's AI.  It told him about its encounter with the Miwako, which led Rushdown to investigate a group of pirates known as the [[Ascendancy of the Awakened Worlds|Ascendancy]].  He is on [[Gallows]] looking for information, but he has been summoned for a meeting with [[Captain Redblood]].* 

`iv-oracle:Begin a Session|79|Unexpected return of an enemy or threat|move.oracle_rollable:starforged/session/begin_a_session.begin_a_session` 

"[[The Spider|Spider]], we have a problem.  The *Rude Awakening* is here, they're docked at Gallows already." says [[Juliana Barbosa|Juliana]].

"Damn.  Rushdown threatened to bring me in if he saw me again.  Still, we can't turn back now.  Call Charlie, we'll pay extra to use one of the secret docking bays.  If we keep a low profile on the station, hopefully our paths won't cross."

"Are you sure?  It's a big risk."

"It's that or abandon the whole mission."

"I've got a bad feeling about this," says Juliana.

---

Rushdown enters the Wessex Saloon.  It's a busy, rowdy drinking spot even at mid-afternoon by station time.  There is a scrum at the bar of people trying to get served, and all the tables are full.  Bar staff are bringing plates of food to tables, and a jukebox is playing loud, raucous music.  Rushdown heads to the bar and elbows his way to the front.  "Redblood's expecting me," he says to a barman who is pouring a drink.

"Upstairs," says the barman without looking up.

Rushdown heads up to the second floor, where there's a metal door flanked by two burly guards.  They stand up from their chairs when Rushdown approaches.

"You can't come back here," says the bigger one.

"I'm Captain Rushdown, he's expecting me," says Rushdown.

The guard knocks on the door and says "Captain Rushdown."

"Let him in," comes a voice through the door.  The door is unlocked from the inside and swings open.  Two more guards flank the inside of the doorway and Rushdown enters.  The door swings shut and is locked and bolted behind him.

[[Captain Redblood]] is a hulking presence of a man.  Clad in thick power armor, seemingly more powerful than Rushdown's, he looks almost comically large sitting behind his desk, although the desk itself is not small by any means.

"You wanted to see me?" says Rushdown.

"Aye.  I heard about [[Tranquilo (City)|Tranquilo]], it seems you know how to handle yourself.  Two things I wanted to say.  First, if you want to start shooting up Gallows, you speak to me first if it's in the spaceport or entertainment districts.  Second, who do you work for?"

"We'll try to give you a heads up if our work brings us to your territory.  And we work for whoever gives us a contract, we don't discriminate."

"See that you do.  Well, we may have work for you - how flexible are you, morally?"

"We're not going to take a contract to go after innocents, if that's what you're asking.  We're not pirates.  No offence."

"Noted."

"If you do have work for us, we have an office in [[Minami City]], you can courier us there.  One other thing, I'm looking into a missing ship case from over a century ago, where can I find information on pirate bands going that far back?"

`iv-move:Gather Information|Wits|3|3|0|8|2|move:starforged/adventure/gather_information`  `iv-meter:Momentum|5|6` 

Redblood laughs.  "I couldn't give you information on all the pirate bands today, let alone from my great grandfather's time."

"You'd remember these ones.  They slaughtered everyone they came across, performed bizarre rituals, wrote strange symbols in blood all over the insides of captured ships."

The smile drains from Redblood's face.  "If you're talking about who I think you're talking about, I'd walk away if I were you."

"I can't do that."

"Nothing good will come of it.  But have it your way.  There's a man who knows about them.  [[Creed Bond]].  He's a little...eccentric.  He was one of their victims, they carved him up and left him for dead, but against all odds he survived.  He became obsessed with them, he's dug up all kinds of information.  Only...he's strange.  When he gets old, he clones himself and uploads his memories into the new body so he can keep on the search even after he dies.  He gives me the creeps.  If anyone knows what happened that far back, it's him."

"Is he here on Gallows?"

>Is he on Gallows?  `iv-oracle:50/50|19|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

"Aye, he has a place in the residential district.  Not my territory."

"I'll check it out, thanks."

`iv-move:Make a Connection|Heart|5|2|0|4|2|move:starforged/connection/make_a_connection`  `iv-track-create:Connection Redblood|The Starforged/Campaign Rushdown/Progress/Connections/Connection Redblood.md` 

"Listen," says Redblood, "You'd better introduce yourself to the leaders of all the gangs.  If they find out you've met with me they might get the wrong idea.  The market and residential districts are run by the [[Flames]], led by [[Inferno]].  She has some kind of fire powers, some say it's magic, some say it's a cybernetic implant, but either way she's dangerous.  The [[Union]] is led by [[Argus Bridger]].  If you want to move freely about the station, especially as your rep increases, I'd at least check in with them while you're here."

"Thanks for the tip.  I'll be on my way."

---

Rushdown heads to the residential district.  He heads to the Flames hangout, an office by the market.  "I want to speak to Inferno," he says to the guard on the door.

"Who's asking?" says the guard.

"Captain Rushdown."

The guard says something into his communicator.  "You can go in," he says.  "She's in the back."

Rushdown goes inside and follows the corridor to the back of the offices.  He finds Inferno in a room with no furniture.  She's flanked by two large men, and a third man is shirtless and tied to a chair.  He's bruised, and bleeding from the nose.

"You're not here for him, are you?" asks Inferno, indicating the man in the chair.

"No, just a courtesy call.  I have business in your territory."

"What kind of business?"

"I need to speak to Creed.  Don't worry, I won't need to tie him to a chair."

"Creed might live here, but he's not one of my people.  Tie him to whatever you want.  What were you talking to Redblood about?"

"He just wanted to warn me about operating in his territory without his blessing," says Rushdown.

"He didn't give you any work?"

"No, and besides, I'm on a job so I wouldn't be able to accept anyway."

"Okay.  Well, if that's all, I really should get back to working this guy over."

"I'll be on my way then," says Rushdown.

---

Rushdown heads to Creed's apartment and knocks on the door.  "We're not interested," comes a voice from within.  Rushdown knocks again.  This time, after a few seconds the door opens a crack and a pistol is pointed at Rushdown.  "I don't care what you're selling, I don't want it."

"I'm not selling anything.  I'm looking for Creed Bond.  I heard he has information I can use."

"Is this some kind of trick?  Who do you work for?"

"I work for the [[Red Suns]].  I'm looking for a ship that went missing a long time ago.  It may be connected to your research."

"Never heard of any Red Suns.  What ship?"

"I'd really rather not talk about the details on the street."

"Come in then.  But one false move and I'll shoot."

Rushdown is ushered into a living room.  There are photos of ships covered in the strange symbols pinned to the walls.

"So, what ship?" asks Creed.  He's an elderly man.

A younger man walks in and sees the gun.  "What's going on?" he asks.

"This man here says he's after information on the Ascendancy," says the older man.

"Who is he?" asks the younger man.

"Says he's with the Red Suns, whoever they are."

"Never heard of them."

"So...both of you are Creed Bond?" interjects Rushdown.

"Yes, that's right," says the younger man.  "We have the same memories up until 16 years ago when I was created and our consciousnesses split.  But now we're two different people."

"So which one do I talk to?"

"It's probably easiest if I deal with it," says the younger Creed.  "I tend to get a bit cranky and paranoid past 60."

"Fine, well if you don't need me I'm going back to combing through these news reports," says the older Creed.

"Couriers come in every day with news from all over the galaxy," explains the younger Creed.  "We look through the reports for any information that might lead to a clue about where the Ascendancy will strike next."

"Well, I'm not after the Ascendancy, I'm hoping to avoid them if necessary.  But they took an Arkship called the Miwako about 150 years ago, and I need to find that ship."

"How do you know the Ascendancy was involved?"

"I found another ship that the Miwako encountered and the ship's AI filled me in, although it didn't know much."

Creed looks confused.  "I don't know of any AI that survived an encounter with the Ascendancy."

"It was aboard a derelict.  It's in Minami City now.  I can probably swing you an interview with it if you give me good information on the Miwako."

"That would be...unprecedented.  Ok, I'll tell you what I know.  The Ascendancy of today is very different from the Ascendancy of a century ago.  I didn't even know they went as far back as 150 years, the earliest records I have are at about 110 years old.  They may not even be the same group, today's Ascendancy may have found the remnants of the original group and decided to follow in their footsteps."

"Anything about an Arkship?"

`iv-move:Gather Information|Wits|5|3|0|7|7|move:starforged/adventure/gather_information`  `iv-meter:Momentum|6|8` 

"Nothing concrete, but they have a habit of creating ship graveyards.  They'll plunder a ship, fly it for a while, and then land it or abandon it in orbit around a certain planet.  Some planets have hundreds of ships orbiting them.  If they took your ship, the chances are it's in one of these graveyards by now."

"So where's the nearest one?"

>Is it in Ashitaba?  `iv-oracle:50/50|90|No|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 
>Is it Pyla?  `iv-oracle:50/50|22|Yes|move.oracle_rollable:starforged/fate/ask_the_oracle.fifty_fifty` 

"The nearest one that I know of is a few sectors away.  It's a planet called [[Pyla]], in the Devil's Chain sector."

---

`iv-noroll:End a Session|move:starforged/session/end_a_session` 

`iv-track-advance:06 - Find the fate of the Miwako and recover any surviving intel|The Starforged/Campaign Rushdown/Progress/Vows/06 - Find the fate of the Miwako and recover any surviving intel.md|12|16|formidable|1` 

`iv-meter:Momentum|8|9` 
