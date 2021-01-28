---
layout: post
title: Cognito Integration
category: stories
tags: first-chapter
date: 2021-01-27 08:27:12
---

The idea for this book comes from the surge of popularity of the LitRPG genre. For those unfamiliar, this is a fairly recent sub-genre of Fantasy and Sci-fi (either or both). Most books use a fantasy setting, but the premise is almost always sci-fi. The general gist of the genre is to place the main character in a game world, give them a character sheet, and watch them struggle. This often comes about via some kind of advanced virtual reality (near future kind of stuff) or, in some cases, it involves magical parallel realities where everyone has character sheets... for reasons.

As expected, the quality of these books are all over the board. There are some really good ones (see: [Awaken Online](https://www.amazon.com/dp/B074CC5NDX)), and some not so good ones, often involving toxic masculinity and harems [^1]. And some games literally describe the grinding process in a game; their idea of a character arc is reaching the next level.

But, set aside all these misfires, and there are some interesting ideas about society and a lot of opportunity here, especially when exploring how technology can reshape society. For a great example of a book that could (should... was?) have been great, and tried very hard to explore the implication of uploading our consciousness [^2] using a compelling story [^3], see: [Fall or, Dodge in Hell](https://www.amazon.com/dp/B07KL61VYS/).

Mine is a more comedic take on things. I do want to explore some of the more serious implications of how technology affects our society and our very humanity, but I was also annoyed at the utter absurdity in some of these books. A person is thrown, sometimes quite literally, into a game world, and it takes them all of five minutes to accept that this is their new reality? Yeah... I don't think so.

So this is a book [^4] where things go wrong. Where the main character doesn't want to be trapped in a game world; where the game designers don't want the main character to be in the game world; where... you know what? Nobody wants him there. But he's there, and he can't leave.

<!--more-->

Note: Below are two chapters: The Prologue and Chapter 1.

----

## Prologue

```
07:30:00.546 :: INFO :: Core - Initiating user 3GP42X5...
07:32:02.588 :: INFO :: Core - User Initiated: Success.
07:32:02.590 :: INFO :: Core - Initiating User Module: Quantific...
07:32:02.701 :: WARN :: Quantific - No profile found. Using defaults...
07:32:04.188 :: INFO :: Core - Quantific module initiated: Success. 
07:32:04.238 :: INFO :: Core - Initiating User Module: Cognito...
07:32:04.429 :: WARN :: Cognito - Non-standard designation. Searching for custom profile...
07:32:04.592 :: ERR  :: Cognito - No custom profile found. 
07:32:04.798 :: ERR  :: Core - Cognito module initiated: Failure. Aborting load...
07:32:04.990 :: ERR  :: Core - Abort failed. Unable to purge user 3GP42X5. Attempting recovery...
07:32:09.104 :: INFO :: Core - Initiating User Module: Cognito...
07:32:09.450 :: INFO :: Cognito_3GP42X5: Already Loaded
07:32:09.490 :: INFO :: Core - Cognito module initiated: Success.
07:33:09.751 :: WARN :: Core - Deep Integration module detected: Attempting integration...
07:35:34.686 :: INFO :: Core - Deep Integration Success.
07:35:34.701 :: INFO :: Core - Integrating with Cognito...
07:35:34.791 :: ERR  :: Core - Invalid Cognito Interface
07:35:34.798 :: WARN :: Core - Attempting interface reconstruction...
07:35:35.529 :: ERR  :: Core - Invalid Default construction
07:35:35.630 :: ERR  :: Core - Invalid Custom construction
07:35:35.781 :: ERR  :: Core - Invalid Prototype construction
07:35:36.002 :: INFO :: Core - Searching past construction types...
07:36:39.456 :: ERR  :: Core - No valid construction type found
07:36:39.502 :: INFO :: Core - Reconstructing integration protocol...
07:45:34.578 :: INFO :: Core - Integration with Cognito: Success.
07:45:34.701 :: INFO :: Core - Initiating User Module: Interface...
07:45:36.253 :: INFO :: Core - Interface module initiated: Success.
07:45:36.498 :: ERR  :: Core - Interface incompatible with Cognito (DevNote: This can't actually happen... lol)
07:45:36.718 :: ERR  :: Core - Interface Integration: Failure. Aborting load...
07:45:38.005 :: ERR  :: Core - Abort failed. Unable to purge user 3GP42X5. Attempting recovery...
07:45:38.168 :: INFO :: Core - Skipping Interface integration (retry in: 30 seconds).
07:45:38.264 :: INFO :: Core - Calculating Spawn...
07:45:38.687 :: ERR  :: Core - MAC address not found. (DevNote: This error is impossible, but included because the compiler is one fucking nitpicky god.)
10:52:24.175 :: INFO :: Core - Spawn Success. Location: [error]
```

----

"Hey Dan!"

Dan winced, wondering if he could just ignore the idiot that just walked into his office.

"Dan! Hey! I need your help."

Dan rolled his eyes and spun in his chair to face the portly man. "Chris. Techops is the floor below us. I'm sure they can help you figure out your spreadsheets."

"No no, not that," Chris said, either ignorant of Dan's sarcasm or perhaps he really was just an idiot.

"I have real work to do," Dan said and turned back to the array of holo screens dominating the room.

"Yeah about that—"

"Go away, Chris."

"I thought you were done."

"Done?" Dan turned back. "We're months away from being done."

Chris blinked. "But you marked it 'DevComplete'."

Dan snorted, rolling his eyes. "That doesn't mean it's done."

"Of course it does. You just want to spends months fucking around with QA while the company bleeds money."

Dan shook his head at the sheer ignorance. Perhaps the term idiot was too generous. 

"Chris, go back to your numbers and leave me the fuck alone."

Chris stiffened; his jaw clenched. "You know what I found out in those numbers, _Dan_?"

"You know I don't care, right?"

"_You_ are the reason we're bleeding money. You and your entire looser department are consuming over half the company budget. Half, Dan, on a project you finished a month ago. A full freaking month."

Dan sighed and turned back to his screens. "It's not finished, Chris. Go away." He needed to talk to Carla about this. The man was sticking his fingers where they don't belong.

"It is now."

Dan froze; a cold dread spread through his torso. Chris sounded like he was gloating, like he'd won something. He turned back around, again. Chris had smug smile on his face. That should never happen.

"What did you do?"

"I only did what you were supposed to do months ago."

For a moment, Dan's world came crashing down around him, but then he remembered one very important fact. "You don't have the creds."

"You're done, Dan, you and your ridiculous salary, your whole fucking department. With this whole farce over, I'll make sure you never find a job again."

Dan's eyes narrowed. "You don't have the creds. You can't even access those systems."

Chris guffawed an ugly sound. "Please, I do actually know where Techops is."

That dread broke free and sped through Dan's extremities, draining him of what little color he had. It was impossible. There's no way anyone was this stupid. And yet...

He turned back suddenly to his screens, ignoring Chris's smug face while his fingers flew over the keyboard. Floating text was replaced with dashboards, then replaced again with floating text.

"Oh god no," Dan muttered. 

He threw up a chat window filled with text and tapped a button, bringing up the familiar face of their founder and CEO.

"Dan? What's up."

"You need to come down here now, Carla."

"Now? Can it wait? I've got a board meeting in a few."

"_Now._"

Carla hesitated, gave him one terse nod, and the chat video disappeared.

"If you think you she's gonna bail you out—"

"You!" Dan spun around, "stand there and be silent while I try to mitigate the damage." He pointed to the corner of the office.

Carla burst into the room. "Dan, what's wrong?" she said, out of breath.

"This moron," Dan gestured at Chris, who hadn't moved but except for his smile, which faltered, "stole creds from Techops and pushed... actually _pushed_ our project into production."

"What?" she breathed. "Is that even possible?"

"Apparently."

"Mrs. Dorestien," Chris said, his face suddenly earnest, "I don't think you understand how much money this man has—"

"Money?" Carla turned to him. "What are you talking about?"

"He thinks I'm paid too much," Dan said, turning back to his screens. Within a few key stokes, all of them were showing large lists of text.

"Mrs. Dorestien, while I'm sure you're good at your job, I've been doing this my whole life. I ran the numbers. This... project is costing us millions. Millions, Mrs. Dorestien. We're on the verge of collapse."

"So you made the decision for us?" Carla said slowly, seeming unable to process the words.

"Someone had to, and once I explain to the board how—"

"The board?"

"_—how_ you allowed this man," Chris gestured to Dan, "to swindle this company out of millions of dollars, I'm sure they'll see reason."

Carla stared at him, stunned. "You stole credentials from Techops, and used them to release untested software."

"What this company needs is strong leadership, Mrs. Dorestien. Leadership that can make the hard decisions."

Her eyebrows flew up. "You think you're making a play for my job."

Chris tilted his head and pressed his lips together in a suppressed, patronizing smile. "I'm sorry, but it was bound to happen. You've clearly mismanaged the company."

"You'll be lucky to stay out of prison."

"Please, Mrs Dorestien, I hardly think such threats are necessary."

Carla shook off her stupor and turned to Dan, who's fingers were still flying over the keyboard. 

"How bad?"

"Bad... but we've not lost cohesion."

"Did it integrate?"

"Surprisingly yes, but..." he trailed off and squinted at the screen. "Huh."

"Dan?"

Another couple keystroke and a new chat window appeared. He tapped on it, then turned back to another screen with text.

"Dan?" Carla said again, though she didn't seem to expect an answer.

"You'll see," Chris said, "once I turn Prodigy back into the black—" 

"Hey Danno the manno," a face appeared over the chat screen. "fuckin early man, what's haaaaaeeeey Mrs Dorestein! Ah, so nice to see you."

Carla snorted.

"Paul, hey," Dan said, "got a question for you. Let's call it a hypothetical."

"Sure man, shoot."

"What would happen to the user bootstrap process if, say, there was no user hardware?"

"Uh, huh? How would that even be possible? That's like having a user without a body."

"Yeah, exactly."

"It's impossible."

"Let's just say it wasn't impossible.... hypothetically."

"Hypothetical huh? Well, nothing good."

"Would it fail?"

"No... no, we can't allow it to fail. That could strand the user in... like, literally nothing, man. The mind can't handle something like that for long."

"What about boot errors."

"Honestly, they don't happen. I mean, we QA'd the ever living shit out that process. But, hypothetically, if they _did_ happen the process would attempt to extract the user, carefully. Very, very carefully."

"Ah yeah, okay, I see that."

Paul cocked his head. "Y...You see what now?"

"What if it couldn't extract the user?"

"It would have to go on. Like I said, we can't allow a failed boot strap. This ain't like a regular software process, man; you can't just eject it from memory, right? You're messing with people minds here. They need _something_."

"So?"

"Well, I mean, the critical piece here is Cognito—"

"Cognito? Really?" Carla raised an eyebrow.

"Ah... yeah, Cognito is a kind of software envelope that surrounds a person's mind, interacts with the hardware, and basically creates the world for the user. And technically, it's not one envelope; there's like, dozens of them, all matched to hardware designs. A big part of the bootstrap is to figure out which one to use."

"And if it can't find one?"

"Impossible. They're tied to the hardware... unless— oh fuck man, someone tried to hack in, didn't they? Oh god they did. Holy shit man, that's like suicidal or... or I dunno, just monumentally stupid—"

"No, no, nothing like that. But what if nothing matched?"

"Uh you mean like prototype hardware? I mean, those should all be registered."

"No. What if there was no hardware?"

"No hardware?" Paul shook his head, looking consternated. "You're scaring me, Dan. Is someone trapped? Cause, like, that would be horrible. Like really bad, man. We're talking unusual punishment level bad, torture level bad."

"Just tell me what would happen."

"Core would look for anything, and I mean _anything_ that it could use as a Cognito. You just can't not have one. And Dan, man, Carlo wrote that code. You know how he is— fucking neurooooh, sorry Mrs Dorestien."

Carla just rolled her eyes and waved him on.

"Right well, he's fu...uh, he really neurotic about stuff, you know? Like, that's why we hired him and all, and he's really good, but I swear he put logic in there to pull the repo and search the entire goddamn commit history for a viable Cognito. What I'm sayin, Dan, man, is Core _will_ find a Cognito, even if it has to make one up." 

Dan, who'd been scrolling through a list of log entries, stopped and highlighted a line. "Ah, okay, I see it. It used the user..."

Paul blinked. "The _what now_?"

"Okay, so where would it put the user?"

"You know brains aren't actually software right?" 

"Paul," Dan said slowly, "how does Core figure out where to put the user."

"Their last save point, man, you know that."

"No, for first logins."

"Oh, right. No, it uses the MAC address of the hardware. Remember? It was your idea. We've got data encoded in there to tie it to one of the starting spawns."

Dan nodded. "Oh okay, yeah, I remember that. But what if there was no MAC address?"

"Ugh, I dunno, man. Give me a sec." His video disappeared.

While Paul spelunked his code, Dan continued to scroll through an endless litany of logs, muttering occasionally to himself as he stopped and examined individual lines. Carla grew increasingly agitated, but somehow refrained from interrupting him until she suddenly exploded.

"Shit!"

Dan turned to her, wide eyes and startled. "What?"

"Our resident idiot snuck out."

He looked around, only then noticing his idiot nemesis was gone. He shrugged. "Not much more damage he can do now."

"Didn't he steal someone's credentials?"

"No, he somehow got access to a..." he switched screens, "ah, a Joseph Sorla? Huh, yeah, new hire. Might be worth looking into. Anyway, he elevated his creds."

"Wouldn't he still have those?"

"What? Oh no. Shit no, Carla. I revoked them about three seconds after he told me." He shook his head slowly and returned his attention to the logs. "Goddamn fucking moron. Dunno why you hired him."

Carla shrugged. "CFO. It was a board decision and, no, I voted for someone else."

"Ah, politics."

She shrugged. "It's the price of money, especially when you're female." 

He broke away from his screens and looked up at her, head cocked. "Really? Haven't we gotten past all that?"

Her face flattened. "Please, half the board is made up of old white men who still believe their thirty-something wives are home cooking dinner and not fucking the mail man." She paused, then cocked her head. "I bet he's calling his masters now."

He chuckled. "Masters, really?"

"Just a suspicion; it was an odd vote. I just didn't think they'd push someone like him."

"You mean an idiot?"

"Hmm—"

"Oh, this is interesting."

Carla leaned over his shoulder.

"Looks like it really was a full integration."

"That's good right?"

"Well... hold on." He scrolled a little ways down. "Oh, so that's how it did it. Yeah, huh, Carlo really was something. So no, not just a full integration; it was ah... let's call it a dual integration."

"A what?"

"You know how the dev sets allow developers to make permanent changes in game?"

"Yeah."

"We call that integration." He shrugged. "Don't ask me why. Developers are shit at naming. Basically, it's a mode where the game 'integrates' into itself any changes the developer makes, kinda treating them like a god."

"Okay, but wasn't this whole project about integration?"

"A different kind, but yeah. It was supposed to be interactive, learn not just from what people did, but from their very thought processes. The user can't just force changes, like our devs can, but the world _does_ change based on what the user does, or really, more like what they think. It's supposed to fix our NPC problem, you know?."

"Yeah Dan, I know. I'm the one who funnelled you hundreds of millions of dollars, remember?"

"Oh... right, sorry. This whole thing's got me on edge."

"Ya think?"

"_Anyway_, Core completed the interactive integration easily, of course — it's literally been what I've worked on for the last two years. But it couldn't find a valid Cognito to integrate the user." 

"Didn't you just say the user integrated fully?"

"No, that was the interactive integration. That integration is what allows the game's AI to learn from the user's thought processes. But for the user to interact with the game, it needs a Cognito."

"Dammit," Carla pinched the bridge of her nose, "this is why I don't ask for detail. You realize you've used the word integration in at least four different ways."

"But there was no Cognito," he said, ignoring her, "I'm still writing it. So it treated the user as its own Cognito. That, of course, failed, but then it turned to some adaptive algorithm Carlo wrote — that man really needs a raise — which used the developer integration protocol as a template to construct a new set of protocols it could use to interact directly with the user."

Carla squeezed her eyes shut for a second, then opened them. "Dan, I have no idea what that means."

Dan started chuckling. "Yeah, me neither."

"Dan." Her tone held warning.

"No, no, I know!" He held up his hand, still laughing. "It's insane, but I really have no idea. I don't _think_ Core is treating him like a god — it seems to recognize he's not a developer — but it's also not treating him like a user either. Something in between, maybe?"

"So like end-game powers?"

"Ah no, it's different than that. Those powers are all... scripted, for lack of a better term. Predictable, maybe. Or, at least they follow guidelines—" 

"Dan, I know how the game works. This _is_ my company, after all." She frowned and turned a little pensive. "Mostly, my company."

"No, what I'm saying is there are limits. Users are free to experiment within the guidelines, right? A lightening mage can train in water, and then use them both in novel ways—  

"Dan!"

"—no listen! But he can't suddenly be a sand mage."

"A what? There is no sand magic." She cocked her head. "Although, that's not actually a bad idea."

"No, there's not. And the _reason_ there's not is because we never added any guide definitions in the game to make one."

"So, you're saying he could make new magics?"

He shrugged. "Maybe? I dunno. That's kind of my point. But at least he can't just point to a mountain and move it to another continent."

"Okay, well that's good."

"Yeah, but I'm not sure how much it matters."

Carla sighed. "Dan, this game is our lives. Seems it would matter a lot."

"No yeah, I know that. But here, look at this." 

He switched to a different screen which also appeared to be logs, but Carla quickly notice a pattern: it was repeating.

"What's it doing?"

"It's trying to integrate the Interface module with the user. It can't, of course, because there's no hardware, and our hardware is what produces the Interface, and it's simply not as important a module as, say, Cognito, so we never sicced Carlo on it."

"So?"

"So, our newly minted user here won't have an interface."

"Dan," Carla sighed, "please get to the point. I've already got a headache."

Dan paused in thought. "Let's say you could fly. Would you walk off a cliff if you didn't know you could?"

"Of course not."

"That's my point. I don't know what powers he has, he doesn't know what powers he has... hell, I don't think the game even knows. So, if you don't know you can walk off a cliff and fly, you're not going to just go off and walk off the cliff. And to him, he's simply going to wake up in a weird world with absolutely no indication he's in a game."

"Okay, so he won't use powers he doesn't know he has."

"Exactly."

"Why didn't you just say that?"

Dan blinked slowly, then stuck out his hand. "Hi, I'm Dan, a fucking software developer."

Carla broke into a pained laugh. "Okay, point made. Can't we just revert it?"

"You mean revert the over ten thousand quantum servers we have running off a nuclear fusion reactor sitting at the bottom of the ocean? The ones we use to run the most sophisticated AI in all of the world?"

"Yes, please?"

"No."

"Damn."

"Well, actually..." He trailed off, looking thoughtful.

"Please don't mess with me. I just can't take it right now."

"We _could_ wipe the region he's in. It would take him with it; at least, I think it would. But then we'd have to rebuild an entire region from scratch, and I'm not sure how the AI would handle that."

"A _whole region_? Dan, that's like thousands of miles of space."

"Virtual space, but yeah. We're talking months of work."

"Fuck... I'm not sure I could sell it."

"Bill it as an expansion?"

"By removing an entire region? I dunno."

"It could work. Gamers love that kind of mystery. Although it would be better if it were an endgame region."

"Why?"

"Fewer people, less overall content. Rewriting a starting region would be a lot more work."

"Hmmm... you sure there's no other way?"

Dan shook his head slowly. "Carla, this guy was never supposed to be integrated."

"What do you mean? I though you were using him in dev?"

"Yeah, dev. We grabbed him because he had one of the cleanest scans and we never actually integrated him— that would have been inhumane, to say the least. But Carla, you should see his psych profile. The man was a powder puff; he didn't even game in his time. Fuck, they barely had VR in his time. Even his name is powder. I mean, some parents with the last name of Smith thought it was a good idea to name their kid John. Who does that?"

"You're saying he won't react well to waking up in a new world?"

"I'm _saying_ the game AI is going to learn all the wrong fucking lessons, Carla. We don't want it using him as a learning template. That's... just no. We gotta get him out of there before he corrupts the whole goddamn system."

"Ah. Huh. Okay," she said slowly, then took a deep breath, "so we wipe a region. Not the end of the world."

"Not ours, anyway," Dan mumbled, then turned to the chat screen as it started chiming. He tapped on it.

"Dan, man, hey got your info for you!"

"Does he always do that?" Carla whispered.

Dan winced. "Yes, yes he does." He looked at Paul and smiled. "Tell me good news."

"Yeah, about that. So I got good news and bad news."

"Of course."

"So good news is, the MAC address still gets decoded."

Dan cocked his head, lips pursed. "But there's no MAC address."

"Right, well, it still gets decoded."

"That makes no— oh." Dan leaned back in his chair and let out a sigh. "You mean it follows the pointer and decodes whatever is there."

"Aaaaand that's the bad news. So what _is_ this all about anyway?"

Dan ignored him, a vacant expression on his face. Suddenly, he stood up, causing his chair to roll back into the wall. He began walking for the door.

"Dan?" Carla said, "where you going?"

"I need a finger. Or ten."

"Huh?"

"That bad?" Paul said, laughing as Dan walked out.

"Paul, what's he talking about?"

"Oh uh, Mrs. Dorestien... right. I think I should let him explain when he gets back. It won't take long."

About a minute later, Dan walked back in with a large glass of amber liquid. Paul cracked up laughing the moment he saw the glass.

"Damn Dan! Man, that's like two fucking hands. You going for broke?"

Carla watched, curious, as Dan took a deep breath, and then took two large gulps from the glass. He set it down lightly, shuddering. She leaned over and sniffed.

"Holy shit, is that whiskey?"

He nodded, eyes watery. Then, to her surprise, he offered her the glass. 

"Uh, no. No, thank you."

He looked at the glass, then shrugged. "Thought you might need it."

"Why? Why would I need it?" Her voice lilted up in approaching panic.

"Because we have no fucking clue where this guy will end up — fuck, already has ended up — and we have no way to find him."

Her face fell. "You mean we can't wipe a region."

"Nope," he giggled, "not unless you have a magic ball." He paused, looking thoughtful. "You don't have magic ball do you?"

"Dan..."

"Cause at this point, I think that might help." He began to chuckle again. "Magic... yeah, that's what we need. We need magic."

Carla looked at her senior developer, the smartest man she'd ever known, as he went through what she was certain was a mental break down. She stared at him, then at the glass. 

"Fuck," she said, extending her palm out.

He handed her the glass, giggling the whole time.

----

# Chapter 1: A spider this way comes

John winced and slit his eyes just enough to let in blurred sunlight. He stretched out in a languid motion to rid tight muscles of the night's sleep. Had he overslept? It felt like it. The sun was far too bright, his muscles stiff, and the bed was... scratchy? That wasn't right, Egyptian cotton was not scratchy. He felt around for his sheets and found grass.

John bolted upright, forced his eyes open, and found himself in a field.

"What... the... ever-loving shit?"

He squeezed his eyes shut and knuckled them, rubbing out the sleep, hoping this was still a dream, but when he opened them again the field stubbornly refused to go back to wherever dreams go when you're done with them. 

So, okay. Instead of his bedroom, he sat under a clear blue sky from which a nice, warm sun shone. There were so many things wrong with this his mind simply stuttered from the overload. He'd never woken up in a field before, but he was pretty sure it did not bode well. 

"Think it through, John, think it through. There has to be a reason."

Several options presented themselves, none of them palatable. The most likely scenario involved imbibing an ill-advised quantity of low-quality alcohol. Possible, except he had no hangover and hadn't drunk like that since his twenties— thirties... or well, not lately at least. Either way, he recalled last night clearly enough, and it was as boring as it ever was.

So, this wasn't the aftermath of a drinking binge. 

Corporate espionage? That sounded fun, except it didn't, and while he was rich, he wasn't _that_ rich. His biggest concern lately was ramping up enough users on his second company to justify being bought out for millions of dollars, again, and proving that his first wasn't just luck. Also, he would very much like to keep his penthouse; he'd grown quite attached to the view.

A prank then, some friends from the old days kicking up trouble. Right, and they did what then? Drugged him, dragged him to Central Park, and dropped him off in the middle of winter... where it was a balmy seventy degrees? 

Huh.

A sudden heat wave? It wasn't unheard of...

He shook his head, stood up, and looked down, only to see the most horrific view he'd ever encountered in life.

"Oh god, no. What am I wearing?"

It was a brown, scratchy, onesie? He pulled on the clothes and scoffed. It was actually a onesie, except with short sleeves and one pant leg slightly longer than the other. He wasn't sure he'd ever seen clothes this shoddy. Beggars had better clothes. His shoes were little more than thin bags of leather tied up around his ankles. He saw no buttons or even a zipper, but a few panicked seconds later, he found a draw string around the back of his neck. 

A draw string. Who... how?

He let out a weak laugh. It had to be a joke, but he'd begun to hope not. If this was indeed Central Park, his walk home would wouldn't just be humiliating, it would be devastating to his social status.

Oh god, his social status. He pulse jumped and his palms began to sweat. He would literally be the laughing stock of the city.

But no, _how_ you walked was almost as important as what you wore. More important, even. Hadn't he read that? Pretty sure it was backed by research. A lot of research. Commanding presence; pretend like you meant it.

"Okay, okay, this is doable. It's fine; it'll be fine. I'll just walk in my new brown leather... shoes? Oh god." 

Deep breath, in and out, just like that yoga class he took once. It's not like Central Park wasn't surrounded by a city, so it shouldn't be but a few minutes back to civilization and the humiliation — no! Not humiliation. He meant to walk the streets of New York in this... bag-like fabric. 

It'll be fine. He looked up; the sun was almost dead overhead, which made direction a little difficult, but he chose the best he could. 

Wait, the sun was overhead? In winter? That's not right; the sun should not be directly overhead in winter, not even in a heatwave. 

Okay, that was weird but what was he to do about it? It was the sun, right? Not like he could command it to move.

Nope. He pushed down the unease and walked anyway, because it's not like there was anything else to do.

Set aside the baffling circumstances, it really was a nice day for a walk. The sun was warm, the breeze cool, and walking felt more pleasant than he could recall. He'd even begun to enjoy himself after a few minutes. His... shoes — it was hard to think of them as such — while not up to his standards, nevertheless gave him the sense of walking barefoot without the worry of rocks or sticks. It was nice, but within a few minutes he'd arrived at both the forest edge and the conclusion that he couldn't possibly be in Central Park. It didn't have dark, dense forests filled with undergrowth.

He eyed the forest edge with suspicion. 

A new scenario, then: someone drugged him, and flew him — he glanced up at the sky again — to South America? Or somewhere in the Southern Hemisphere, where it was summer and dark, and where creepy forests reigned. Sure, that sounded right. So, South America then. Someone drugged him and flew him to South America for... reasons. 

He sighed. If this really was a joke, he was going to have a very heated conversation with his friends, not that they would care; they were probably laughing their collective asses off.

A shadow darkened the sun and pulled his eyes back up to the sky, where he saw what he would have sworn was a freaking dragon.

"It's just a drone." He closed his eyes and calmed his breath. "Some stupid kid dressing up their birthday present."

He glanced back up at the dra— drone, which just flapped its wings, and decided that the dark creepy forest was his best bet.

He shivered about ten paces in, thought hard about how warm the sun had felt, then about the drone, and finally re-chose the dark creepy forest. Just the idea of being stalked from above was not pleasant, even if it was just some stupid kid playing around. Besides, he had to find civilization, anyone who could tell him where he was and how to get back to his penthouse. Clearly, the dark creepy forest was the best way to get there.

He took a deep breath, and again he walked. 

Sometime later, as the terrain turned difficult, he started to appreciate the coolness of the forest. The ground had angled up, and while the trees provided thicker roots, they were also moist, sometimes slimy, and deceptively slippery. He'd accumulated a nice collection of small scrapes and bruises, but at least he wasn't cold.

He continued to walk, sometimes climb, other times scramble, frequently slip, and mostly manage to avoid thinking about his predicament, which looked worse the further in he went. At one point he decided to turn back, only to realize he had no idea where back was. 

He was lost in a dark, creepy forest.  

Now _that_ was a new experience; it was also a very poor joke. He looked around, thinking someone must be hiding, watching him. They'd jump out and all scream, "Surprise". It was a TV show like they did in the old days. Someone would have a camera or a phone streaming it all on social media.

Could he get Royalties from that? It's not like they asked him. Maybe he could sue.

He almost called out, but would that ruin it? Worse, would that make him look like an idiot?

He glanced down at his cloths. Did he already look like an idiot? 

No no no, it was _how_ you did it, not what you wore while doing it. He'd read that. Research. Scientists said it was true.

He took a deep breath, cracked his neck (that looked cool, right?), and there wasn't really a choice was there? Stay or walk, that's it. He decided to walk, again, for what must have been the hundredth time.

In retrospect, he probably should have noticed the sharp increase in spider webbing, or that the terrain had taken a downturn, the roots become sticky, the forest darker; but at that point his mind had retreated into desperate attempts to not think about his situation or, more commonly, indulge in fantasies about his penthouse and bed and all the freaking money he would get from the idiots who decide this joke was a good idea.. 

Also, and this is important, he was arachnophobic. He never knew why. He'd never been bitten by a spider that he could recall, though he sometimes wondered if he'd been dropped into a nest of them as a child. It was the only reasonable explanation for the kind of fear that would cause most of his girlfriends to eye-roll hard at his reaction to seeing one. It also turns out that the mind, or at least his mind, retreats when presented with overwhelming evidence of one's phobia is, quite literally, all around him. 

Still, it was — again, only in retrospect, as all good knowledge is — somewhat incredible that he managed to avoid noticing all the very obvious signs that he was walking through a spider-infested forest. 

What he could not ignore was the dog-sized spider as it walked across his path a measly five paces in front of him. 

The autonomic fear response (AFR for those inclined to acronyms), is a surprisingly versatile system. Most think of it as only fight or flight, but it has quite a larger repertoire to pull from. It can, for instance, cause the body to freeze, doing more efficiently the kind of paralysis than even the spider's venom was designed for. It's the kind of defense some children use: if I don't move, maybe you can't see me. This is not actually unreasonable. Some predators use motion to track their prey. 

That's far from its only weapon. Another tactic: void the bladder and, if necessary, the bowels. This might also seem odd, but there are quite a few predators that hunt by sense of smell, and would turn away at the unpleasant aroma of shit wafting in the air. 

The spider is not one of them.

It had what can only be described as an autonomic attack response (AAR, because why not), which had a serendipitous relationship with John's AFR. In other words, John quickly found the dog-sized spider attached to his leg.

John's AFR quickly changed tactics. Freeze and shit obviously wasn't working. So instead, it dumped a prodigious amount of adrenaline into his body and gently urged him to flee.

Adrenaline is a powerful hormone, able to push the body into super-human feats of strength and endurance, especially when survival is at stake. It is not, however, strongly associated with self-control and rational thought. So it was, at this point, that John delivered a surprisingly robust, though not well-aimed, kick at the spider and sent it flying back a few paces by luck alone.

That was perfectly fine as these things go, but he also screamed a high pitch sound that he would be hard pressed to replicate even on his best, or perhaps worst day, which is certainly what this day had become.

The spider screamed right back at him. 

He would later reflect that screaming to announce himself wasn't exactly the most rational thing to do. Again, this was all obvious in retrospect, which occurred surprisingly quick as thousands of other spiders screamed throughout the forest in reply. He could never be sure if they'd done so in response to his scream, the spider's scream, or perhaps both.

John's AFR dumped in a whole new bucket of adrenaline into this body.

He fled in a mad scramble back up the path he'd so carefully picked his way down. In his mind, which, let's be honest, was completely fragmented and dribbling by this point, he had climbed for an eternity; but in truth it was only a few seconds. His scramble was not elegant, or efficient, or even all that fast, and it didn't take long for the spider to catch up.

It attached itself to his leg, again, but this time decided to put to use it's god-given venom. John didn't even bother kicking; he just continued to scramble back up the path as best as he could. 

The spider jumped off and gave him room.

He didn't stop to think why. Although, to be fair, he wasn't exactly thinking much at all by this point. His mind had pretty much completely succumbed to fear, and what a now perfectly rational fear it had become. He finally acquired a good reason for his arachnophobia which is, oddly, not actually all that common as far as good reasons go. 

His progress slowed after another eternity (a few more seconds) of mad scrambling. His mind distantly registered the loss of feeling in his leg, and in response dutifully dumped more adrenaline into his body to compensate. This did not, however, help speed up his climb, which had veered closer to spastic thrashing than any real climbing.

Anyway, it didn't matter. He lost his sense of his other leg soon after, and then most of his lower torso. The obvious managed to pierce the panicked haze of John's mind: he wasn't going anywhere.

John's AFR finally decided to fight. It tried to dump more adrenaline but that well had bled dry. He pushed himself over onto his back and tried to sit up, but only the top portion of his abdominal muscles worked, so he only managed a half grunt-induced head raise before those muscles also disappeared from his control.

A million (dozen) spiders closed in.

He actually managed to throw several off before his arms became languid and difficult to control. As they swarmed over him, he had the insane hope that the venom would also cause his lungs to fail. It wouldn't be pleasant, he was sure, but anything was paradise compared the present horror. 

Fate was not kind, and his lungs simply evened out into a slow cadence. He couldn't control his breathing, not even to express the profound sense of panic and terror consuming his mind.  In that moment, he discovered a new truth: breathing without control tricks the mind into thinking it's drowning, slowly, as though each breath was just shy of his need, and so killing him in small increments. 

He was drowning while spiders crawled over him. He'd be forever hard-pressed to describe the sheer panicked induced deterioration of his mental process occurring at this point.

The spiders lifted and turned him over repeatedly. He had an image of being roasted over a fire, turned slowly as the heat boiled him alive. It was a pleasant thought, and he kept his mind on that instead of what was actually happening, which he was certain involved copious amounts of webbing.

He could at least see when there wasn't a spider blocking his vision. This was a curse until one of the spiders sprouted an arrow. Then it burst into flame.

He would have giggled in delight had he been capable, and had the flames not quickly spread to his webbing, which in turn spread the fire to the other spiders. The spiders screamed a delightful noise, and then popped like popcorn. It was beautiful and he wanted to see more, but he'd suddenly become aware of the fact that he too was burning alive, and he couldn't even drop and roll; he couldn't move at all. 

The pain became unbearable when he heard a feminine voice. "Holy shit... you're alive!?" 

A goddess dressed in leather leaned over him with an exasperated look. She had pointy ears on a pointy face that looked drawn back, with big eyes angled upwards.

His goddess was an alien and she was the most beautiful angel he'd ever seen.

"Damn, I hope your pain is set low," she said as she secured her bow to her back and leaned over. Her hands began to glow green and within a few seconds the searing pain diminished. 

She leaned back and looked him over with a confused expression. He became acutely aware he was probably naked. "You're a noob? How the hell did you get out here?" 

He had several questions and no way to ask, though he did try to gesture with the only thing still under his control: his eyes. She didn't notice. 

The... alien looking but somehow perfectly beautiful girl twisted her lips in thought. She glanced down toward the spiders, then back at him as though making a decision.

"You know, I'm tempted to just kill you, but I admit I'm damn curious how a noob managed to get so deep into the Spiderest." She paused, then shook her head and grimaced. "You better have a good story, a damn good story." She sighed and looked him over again. "I can't do anything about the venom, but the arachnids like to eat their dinner fresh, so you'll be fine until it wears off. Until then... ugh, I guess I'll have to carry you." 

He'd died and gone to hell. It was the only reasonable explanation. His admittedly chauvinistic tendencies had circled around in tenfold karmic vengeance. At least he could think of nothing that could make this worse.

Then, in an incredible display of strength, she casually picked him up and threw him over her shoulder.

"Oh god... did you _shit_ yourself?" She immediately thrust him back off to fall face down back into dirt.

She took several steps back. "I... oh god, that's foul. I didn't even know that was a thing here. That's just..." She trailed off and paced back and forth, although all John could see was her feet passing by periodically. 

He realized, then, that one should never assume things can't get worse. They most definitely can, always, and in unimaginable ways. He was lying in the dirt, face down, ass up, shit smeared, and he actually began to wish he had burned to death instead.

Her feet finally stopped in front of him. "You had better have the most epic story of all time." She spoke through her teeth. "I can't believe I'm doing this."

She picked him up, again without any noticeable effort, and began to run.

If John was confused before, it paled against his bafflement at the effortless speed and grace with which his leather-bound goddess ran. She took steps further than he could have ever jumped, even in his twenties. When she did leap, he thought they were flying, then wondered if he would survive the fall, only for her to lightly touch down on the forest floor with no sound he could hear. She ducked, dodged, and weaved her way through the forest in a way that would have made a New York cabbie both nauseous and more than a little envious.

He concluded that this wasn't hell, it was simply a bad trip. Someone had slipped him acid, a lot of it, maybe a whole god-damn sheet of the stuff, and he was stuck in some weird-ass lucid dream. He shoved down a small voice in his head that pointed out lucid dreams never actually felt real.

She ran for hours before stopping for a break, and while John's view was mostly limited to the forest floor, he occasionally caught glimpses of some large beast or another, though not enough to actually know what it was. He considered that a blessing.

She stopped near a river, dropped him, and then, as he was falling, snatched his foot with one hand, allowing his other leg to flail about as his head swung back and forth about an inch off the ground. Every parent occasionally wonders what it would be like to be swung around by their feet, even as they watch their child giggle in delight from the same. John was not a parent, nor had he wondered, but he could say then without hesitation that a grown man wouldn't giggle, not even a little. 

She walked him over to the river and dropped him in.

He still didn't have control over his lungs, so within moments he was breathing water. It was as unpleasant as he might have imagined. At first, he thought she'd dropped him to float down the river, but eventually realized she was actually swinging him through the water like one would dirty clothes. She pulled him out about the time he was inviting death which, in his mind, would hopefully wake him up.

"Oh, that's so much be— shit, I forgot about the venom."

The leather goddess then straddled him, placed her hands on his chest, and cracked his ribs. 

She paused. "Ummm... sorry, I've never had to do this before." 

She pushed again and cracked another. 

"Huh, okay, that's not working."

She paused, rolled her eyes, and said, "Fine... better be worth it." 

She leaned over, pressed her lips to his, and blew air. It wasn't exactly an unpleasant experience, though it could have been under more favorable circumstances. After a few forced breaths, his autonomic system discovered a way to expel much of the water into his savior's face.

"Dammit!" 

She got off him, wiped her face down, cursing to herself. Her eyes widened suddenly. She'd just noticed another autonomic response apparently in full swing. John was, apparently, quite full of them.

"I... I think we should never mention this... ever." She glanced back down toward his legs looking a little flustered. "How about I let you... uh, compose yourself before we go." 

She sat down beside him, facing the river, and watched the water, sparing only an occasional glance back toward his feet. It gave him an opportunity to study her, which was a welcome distraction from the humiliating circumstances he'd found himself in. 

She was clearly elvish, maybe? He wasn't sure. He'd watched the Lord of the Rings like everyone else, so he knew what elves looked like, but where those elves looked mostly human, she looked mostly not. Her ears weren't simply a pretty extension of human ones; they had a completely different shape, both larger than humans and yet somehow more graceful in the way it hugged her head. Her face very faintly made him think of a cat. 

Also, she was perfect. He couldn't find a single blemish on her, not a scratch, a pimple, or even a pockmark. Set aside the elvish thing, he'd still have cried 'photoshop' had he seen anyone look that good.

"If you're done eyeing me, perhaps we can go now?" He quickly averted his eyes to the trees above. "Not that I mind the silent type, but this isn't exactly the place for ogling each other." 

She shot him an amused, if somewhat strained smile, rose her feet, and within a couple seconds had him situated on her shoulder. She then leapt over the entire goddamn river in a single bound, and landed well beyond the bank on the other side, again with no noise and no visible effort. 

They sped through the forest for hours. While the speed was exhilarating at first, it got old quick, and eventually became boring. Everything moved by so fast he could barely tell what he was looking at. The ground was nothing but a blur and her rhythm hypnotic. That rhythm called to him and rocked him gently. 

He fell asleep, fully expecting to wake up in his bed.



[^1]: I'm not kidding. Listen, I like romance done right and a harem is not that. At the first sign of one, I'm usually looking for a new book. 
[^2]: Successfully, I might add. I really liked the way he really explored the implications of humanity basically creating our own afterlife.
[^3]: Not successfully. Very much not. The story line was all over the freaking place and I really tried to follow right up to the point I realized I'd completely lost interest in what was going on. I did not finish the book.
[^4]: Might be a book if, you know, I actually write it.
