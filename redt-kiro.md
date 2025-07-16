Skip to main content
Amazon's Cursor Competitor Kiro is Surprisingly good!! : r/cursor


r/cursor
Current search is within r/cursor

Remove r/cursor filter and expand search to all of Reddit
Search in r/cursor
Advertise on Reddit

Open chat
Create
Create post
Open inbox
2

User Avatar
Expand user menu
Skip to NavigationSkip to Right Sidebar

Back
r/cursor icon
Go to cursor
r/cursor
•
13 hr. ago
Just_Run2412
Analyze Icon

Amazon's Cursor Competitor Kiro is Surprisingly good!!
Question / Discussion
I’ve spent a few hours exploring Kiro and I’m genuinely impressed. Whenever a new AI or coding model comes out, my first move is always to hit it with my toughest bug, the one every other tool has failed to crack. While Kiro didn’t completely fix it, it got closer than anything I’ve tried in Cursor or Claude Code.

Kiro’s standout feature seems to be what it does before it writes code; it carefully analyses your codebase, develops a thoughtful plan, and only then executes. Seems to work a bit like a permanently built-in plan mode from Claude code.

From what I can tell, it seems to be completely free and includes full access to Claude 4 Sonnet and Claude 3.7. This makes sense as I believe Anthropic and Amazon are in some kind of partnership.

How are others finding it?


Upvote
158

Downvote

60
Go to comments


Share
Share
Join the conversation
Sort by:

Best

Search Comments
Expand comment search
Comments Section
vivainio
•
13h ago
Analyze Icon
Copy pasting my mini review:

Mini-review:

It's slow as sin (when talking with AI, not UI responsiveness) compared to Claude Code (well duh) but also Cursor. This may be an artifact of it being free while in preview, so they don't want to go broke before being able to charge the users. Maybe 2x slower than cursor and 4x slower than Claude Code? I didn't measure it, subjective bs.

Cursor writes out the thinking process in gray text, no such thing here. You only see the "polished" answer from AI, like with Claude Code

On Windows, it's using Powershell for cli interactions like Cursor. This sucks, and commands easily fail. They should switch to Bash like Claude Code does.

It's essentially Claude like the others, so you see similar problem analysis and euphoric feedback when something works (or doesn't work in a way that Claude thinks is a-ok)

The UI is more "polished" and less buggy than Cursor, which you'd expect from AWS I guess.

Verdict: you can use it for free, so download it while it lasts! In any case this is worlds better than the competing free choice Gemini-cli. No doubts this will be seen as "Cursor killer" if they can keep the price competitive and increase the performance (which is likely just about $$$).

Disclaimer: I didn't try any of the "novel" design time innovations of Kiro, just vibing to fix a bug in .NET code. I'll try the design/spec features when I start a new project.



Upvote
40

Downvote

Reply
reply

Award

Share
Share

u/ai_product avatar
ai_product
•
10h ago
Analyze Icon
Hey — I’m a PM on Kiro. Thanks for all the feedback! We’re aware of the slowness issues some of you have hit. The response from the community has been incredible (thank you!), and we’re actively working to smooth out these early hiccups. Really appreciate your patience as we fine-tune the experience.



Upvote
41

Downvote

Reply
reply

Award

Share
Share

Just_Run2412
OP
•
9h ago
Analyze Icon
Chat check points would be great as well please!! just like in Cursor.

Comment Image


Upvote
13

Downvote

Reply
reply

Award

Share
Share

u/ai_product avatar
ai_product
•
9h ago
Analyze Icon
Ack. Checkpointing is an important capability and is on our radar.



Upvote
13

Downvote

Reply
reply

Award

Share
Share

u/RIPT1D3_Z avatar
RIPT1D3_Z
•
8h ago
Analyze Icon
Please, add a function to create or select venv. Also, drag-n-drop folders and files into the chat window would be great!

Thanks!


Upvote
4

Downvote

Reply
reply

Award

Share
Share

Just_Run2412
OP
•
9h ago
Analyze Icon
Awesome! I'm pretty sure Cursor just used Git for their checkpoints.



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/subzerofun avatar
subzerofun
•
9h ago
Analyze Icon
i haved checked the cursor user files - it does not use git. it just saves different versions of your files and puts them into uuid-coded folders with a database holding the time of creation. you can just look in those folders, you will find a complete snapshot of every modified file at a specific time. i think it is under User/AppData/Local or Roaming/Cursor



Upvote
3

Downvote

Reply
reply

Award

Share
Share

u/KillyP avatar
KillyP
•
3h ago
Analyze Icon
Really??? What a waste of disk space when working on massive projects….



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Im-cracked avatar
Im-cracked
•
1h ago
Analyze Icon
If they used git, it might not revert git ignored files when you would want it to?


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/enantiodromeda avatar
enantiodromeda
•
20m ago
Analyze Icon
Maybe consider using jujutsu. It could be a really nice way of handling checkpoints if you also allow users to interact with it. For example, if you want to pick and choose the changes from one prompt and lots of agent calls. It could be really powerful.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/pipeaalzamora avatar
pipeaalzamora
•
4h ago
Analyze Icon
También que se pueda trabajar con dos proyectos a la vez en el mismo entorno de trabajo como se puede hacer en cursor



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/jungle avatar
jungle
•
3h ago
Analyze Icon
Por qué en castellano?



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/pipeaalzamora avatar
pipeaalzamora
•
2h ago
Analyze Icon
porque existe ese idioma y también el traductor de reddit con solo un botón me traduces lo que escribo


Upvote
1

Downvote

Reply
reply

Award

Share
Share

0LoLoLoL0
•
9h ago
Analyze Icon
Just wanted to say that you guys did a surprisingly good job. It obviously requires more polish but actually coming up with a tool that's not more of the same with the spec-driven flow isn't easy 😅


Upvote
3

Downvote

Reply
reply

Award

Share
Share

Glittering-Koala-750
•
2h ago
Analyze Icon
Please for god’s sake don’t put this into aws login like Q! It is a nightmare and complete chaos. Even the support agents don’t know how to navigate it.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

umstek
•
9h ago
Analyze Icon
Looks like a great product, but I'd like to know about pricing. I can't afford to give up on another editor. 😅


Upvote
1

Downvote

Reply
reply

Award

Share
Share

vivainio
•
8h ago
Analyze Icon
Thanks for listening, truly appreciated! Please pretty please consider ditching powershell for git bash on windows, see how they did it in claude code. So far I haven't seen Kiro screw up as badly as Cursor with powershell, but haven't had enough time to use it yet


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/deadcoder0904 avatar
deadcoder0904
•
10h ago
Analyze Icon
Design/spec feature goes too deep & over-engineers a lot for simple things.

Ik this is a prompt bug but still. I hated it but i didnt prompt well. But yeah agreed on being slow as fuck.



Upvote
2

Downvote

Reply
reply

Award

Share
Share

Typical-Positive6581
•
8h ago
Analyze Icon
It toke all day to build a shit component for me way to verbose and over egineerd lol



Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/deadcoder0904 avatar
deadcoder0904
•
7h ago
Analyze Icon
Samsies but hey it atleast worked.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/SCourt2000 avatar
SCourt2000
•
9h ago
Analyze Icon
I doubt it's better than Gemini 2.5 Pro for free in AI Studio. So what if I have to cut/paste. At 1M token input context I get to have 50-100 requests a day (dunno exact number, haven't exceeded request limit yet). Kiro can't do that.

Editor integration just feeds the addiction to make excessive requests, not think for yourself.



Upvote
2

Downvote

Reply
reply

Award

Share
Share

Glittering-Koala-750
•
2h ago
Analyze Icon
Gemini is awful for coding. It gets things badly wrong then won’t accept that it was badly wrong. I started out using Gemini because of the massive context window but it doesn’t actually read most of it and just summarises.

As for the code stubs it leaves everywhere along with … instead of actual code!!



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Thejoshuandrew avatar
Thejoshuandrew
•
2h ago
Analyze Icon
Or it does accept that it got it wrong and shame spirals.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

laffingbuddhas
•
13h ago
Analyze Icon
Second that - download it while it lasts!


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/beebop013 avatar
beebop013
•
8h ago
Analyze Icon
You dont get the reasoning in claude code? I usually see it thinking


Upvote
1

Downvote

Reply
reply

Award

Share
Share

cloroxic
•
4h ago
Analyze Icon
It has only two models too, which while free are very limiting since it’s only Sonnet 3.7 and Sonnet 4.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Valuable_Season_8650
•
11h ago
Analyze Icon
I think it's great ! Bad timing for Cursor et their new pricing. Like really bad.



Upvote
18

Downvote

Reply
reply

Award

Share
Share

Picacco
•
11h ago
Analyze Icon
That’s probably why Amazon waited to release it now; they don’t do things by accident.

Amazon can play this game in a way Cursor can’t: They can eat the cost of Anthropic while still bumping up the service, and still undercut Cursor’s pricing model until Cursor withers away.

It’s anticompetitive AF, but this administration isn’t going to do anything about it.



Upvote
5

Downvote

Reply
reply

Award

Share
Share

u/sanz0 avatar
sanz0
•
11h ago
Analyze Icon
They waited for a cursor price increase before releasing? Like they had this in the cabinet for months but it was blocked pending a price hike? Because they couldn’t undercut the previous cursor pricing, but now they can?



Upvote
9

Downvote

Reply
reply

Award

Share
Share

Picacco
•
10h ago
Analyze Icon
To some degree. Internally, I imagine they probably had a sense of what Cursor was going to have to do. They know Cursor’s funding, API costs, etc. and that they’d eventually have to do this.

And I think you underestimate how cutthroat this game is played and what Amazon is willing to do.

Do the research: they’ve done it to countless other businesses and specialty online retailers in the past. This is right out of their playbook.



Upvote
-1

Downvote

Reply
reply

Award

Share
Share

u/deadcoder0904 avatar
deadcoder0904
•
10h ago
Analyze Icon
While you are overthinking this, Amazon is definitely known to hijack brands that rank #1 on Amazon.com.

See this 48-min doc:

Amazon — Market. Power! Monopoly? | How Amazon Hikes Prices & Copies Product | 48 Minute Documentary


Upvote
4

Downvote

Reply
reply

Award

Share
Share

imatygahrawr
•
9h ago
Analyze Icon
Knowing the team personally, this is the soonest they were confident enough to release it after several delays. The timing is coincidental.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

fergthh
•
10h ago
Analyze Icon
Not necessarily because of the price itself. I think that if this hypothesis is true (that they waited until this moment for Cursor), I see it more as something that was expected to be unsustainable over time, and that at some point it was going to have to make some changes due to the recent investment fundraising. Kiro isn't that far from what Cursor has to offer; I haven't tried it, but from what I can see, it's still just another Wrapper among the bunch with a few features, but nothing too different. Waiting for the moment when the AI editor that had cornered the market is shaky, even if only a little, is a better time than when it's completely solid


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Master_Ad_5291 avatar
Master_Ad_5291
•
13h ago
Analyze Icon
it looked really promising, writing up all of the designs and tasks - but execution, it kept corrupting my components and blade files that it was writing, I'll push through because I like it and it's free but, I'll see if this continues..

I can see the issue - there's some corrupted content at the end of the file. Let me fix the Blade template by rewriting it cleanly:



Upvote
6

Downvote

Reply
reply

Award

Share
Share

hatepoorpeople
•
5h ago
Analyze Icon
It'd also be nice to resume from within a particular step in a task. It's failing on dumb things (like not recognizing a successful build) and then you have to start that step over.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

ianbryte
•
12h ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
This is my current issue with it as well. But I really like it workflow as it similar with my workflow used in cursor. Plan, design, task list, execute.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

hatepoorpeople
•
6h ago
Analyze Icon
No corruption, thankfully, but execution was slow and ultimately got stuck in a loop and completed nothing of substance.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/lifegame123 avatar
lifegame123
•
10h ago
Analyze Icon
Couldn't this just be reproduced in cursor or any other tool just with a set of four prompts?

Plan, design, spec, To-do list?


Upvote
4

Downvote

Reply
reply

Award

Share
Share

LuckEcstatic9842
•
13h ago
Analyze Icon
Just installed it for testing, going to try it out on a real work project soon. Does anyone know what the context window size is for Kiro?



Upvote
2

Downvote

Reply
reply

Award

Share
Share

Just_Run2412
OP
•
13h ago
Analyze Icon
I’m not sure about the model’s context length. The chat context feels quite limited—it forces you into a new chat with a summary of the previous conversation, probably around the same point Claude Code would compact its context.


Upvote
3

Downvote

Reply
reply

Award

Share
Share

u/Dependent_Baker_9839 avatar
Dependent_Baker_9839
•
9h ago
Analyze Icon
No, it’s not. It’s quite bad. Half-baked VSCode clone at best. You can’t launch a product on a concept of a different markdown. Use it if you really need Sonnet 4 for free but it’s basically $20/month elsewhere.



Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/Signal-Banana-5179 avatar
Signal-Banana-5179
•
6h ago
Analyze Icon
Lol. 20 usd for sonnet 4? Just read cursor and windsurf sub 


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/No_Edge2098 avatar
No_Edge2098
•
9h ago
Analyze Icon
just tried kiro recently and was honestly surprised too feels way more intentional than cursor like it actually thinks before spitting out code planning step is solid and makes a big diff for tricky bugs if it stays free with full claude access this might be a serious game changer curious how it holds up with bigger projects though


Upvote
0

Downvote

Reply
reply

Award

Share
Share

mcncl
•
2h ago
Analyze Icon
It’s terrible. The planning phase is nice, but I’m using those documents and giving them to Claude. Kiro is just ridiculously slow and doesn’t actually complete the tasks it’s given, just ensures there are no errors when it runs tests, npm run dev etc



Upvote
0

Downvote

Reply
reply

Award

Share
Share

speedtoburn
•
1h ago
Analyze Icon
lol


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/SamuelQuackenbush avatar
SamuelQuackenbush
•
1m ago
Analyze Icon
I think it is good for planning but not for coding. So slow it is unusable.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Unfair_Tiger_2942
•
10h ago
Analyze Icon
I been using spec made it’s been impressive so far! I am trying a really big change atm - building end to end testing ground up! We see how it does! No Ai has been able to do that so far for my app



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Demijiji avatar
Demijiji
•
7h ago
Analyze Icon
Can't wait to see the result!


Upvote
1

Downvote

Reply
reply

Award

Share
Share

asifkabeer1
•
9h ago
Analyze Icon
Good timing, my Cursor credits are over in 7 days


Upvote
1

Downvote

Reply
reply

Award

Share
Share


No-Tension-9657
•
9h ago
Analyze Icon
realcul
•
9h ago
Analyze Icon
All these tools start off great and when adoption increases they try to optimize and without controlling the underlying models , one of the jet ways to optimize is thru reducing context windows and tool calling and then users see a degraded performance.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

enly11
•
7h ago
Analyze Icon
Will be good to see how it develops.

I like the concept of actually forcing decent planning and specification which all drives context.

First impressions were the performance wasn't there - but sure that's just teething problems and launch demand. I also struggled with when it would and would not progress through testing - just seemed to get lost with some of the command execution - sleep 3 for example - never really continued even though the process had completed.

Back to cursor for now (until sub expires) but will continue to look into Kiro alongside.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

hatepoorpeople
•
6h ago
Analyze Icon
My first attempt, it did the planning and task list items OK, but when it came down to implementation it failed miserably and was miserably slow at failing. I tried to help it along by doing things for it, but ultimately it just got stuck in an infinite loop and I gave up. I'll try and find another task for it later or maybe use it's planning items as input for other AI editors that can do the work much better.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/TerriblyCheeky avatar
TerriblyCheeky
•
6h ago
Analyze Icon
Does it use AWS Bedrock behind the scenes? Full AWS coms is a killer feature for compliance. Maybe my industry can finally go all in on AI IDE’s.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Hard_Squirrel
•
5h ago
Analyze Icon
Had a what I thought would be a quick play…gave it a simple bug to fix…over 1 hour later and it’s still implementing task 3 of 5


Upvote
1

Downvote

Reply
reply

Award

Share
Share

isarmstrong
•
4h ago
Analyze Icon
Hey OP, have you tried shift-tab to enter planning mode in Claude Code?


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/delphianQ avatar
delphianQ
•
27m ago
Analyze Icon
That new favorite fast food item is always good. 2 years later it's squishy brown lettuce on a day old bun.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Community Info Section
r/cursor
Join
Cursor
The AI Code Editor - cursor.com
Created Feb 21, 2024
Public

Community Guide
82K
Members
52
 Online
Top 2%
Rank by size 
Community Bookmarks
Forum
Docs
Status Page
r/cursor Rules
1
Keep it relevant
2
Be civil
3
No rants
4
No misinformation
5
Provide context
6
Limit self-promotion
7
No paid content
8
No spam
9
Write quality titles
10
Use flairs
11
No slop
Moderators
Message Mods
u/IveWastedMyLifeAgain avatar
u/IveWastedMyLifeAgain 
Mod
u/IndraVahan avatar
u/IndraVahan 
Founding Mod
Indra
u/dev-andrew-healey 
Mod
dev-capybara
u/shaoruu avatar
u/shaoruu 
Dev
u/cursor_dan 
Mod
Dan
u/freshkoala 
Mod
u/ydaars 
Dev
u/mntruell 
Dev
u/eric-cursor avatar
u/eric-cursor
u/NickCursor avatar
u/NickCursor 
Mod
Nick Miller
View all moderators
Reddit Rules
Privacy Policy
User Agreement
Accessibility
Reddit, Inc. © 2025. All rights reserved.

Collapse Navigation
解释


Skip to main content
Amazon's new Claude-powered spec-driven IDE (Kiro) feels like a game-changer. Thoughts? : r/ClaudeAI


r/ClaudeAI
Current search is within r/ClaudeAI

Remove r/ClaudeAI filter and expand search to all of Reddit
Search in r/ClaudeAI
Advertise on Reddit

Open chat
Create
Create post
Open inbox
2

User Avatar
Expand user menu
Skip to NavigationSkip to Right Sidebar

Back
r/ClaudeAI icon
Go to ClaudeAI
r/ClaudeAI
•
1 day ago
HumanityFirstTheory
Analyze Icon

Amazon's new Claude-powered spec-driven IDE (Kiro) feels like a game-changer. Thoughts?
Coding
Amazon just released their Kiro IDE like two hours ago which feels like Cursor but the main difference is its designed to bring structure to vibe-coded apps using spec-driven development built-in by default.

It's powered by Sonnet 4.

The idea is to make it easier to bring vibe-coded apps into a production environment, which is something that most platforms struggle with today.

The same techniques that people on here were using in Claude Code seem to be built-in to Kiro. I've only been using it for the last hour but so far it seems very impressive.

It basically automatically applies SWE best practices to the vibe-coding workflow to bring about structure and a more organized way of app development.

For instance, without me explicitly prompting it to do this, it started off creating a spec file for the initial version of my app.

Within the spec file, it auto-created a:

Requirements document

Design document

Task list.

Again, I did not prompt it to create these files. This is built-in.

It did a pretty good job with these files.

The task list it creates is basically all the tasks for that spec. You can click on each task individually and have the agent apply it.

Overall, I'm very impressed with it.

It's in public preview right now, not sure what the pricing is going to look like.

Curious what you guys think of it, and how you find it compares to Claude Code.


Upvote
319

Downvote

113
Go to comments


2

Share
Share
u/monday_com avatar
monday_com
•
Promoted

Can you relate to the feeling of swimming upstream at work? Oh, the struggle is real! That's why 180K+ customers choose to use monday.com as their work management platform so they can efficiently manage all their work. Try it now!
Sign Up
monday.com
Thumbnail image: Can you relate to the feeling of swimming upstream at work? Oh, the struggle is real! That's why 180K+ customers choose to use monday.com as their work management platform so they can efficiently manage all their work. Try it now!
Join the conversation
Sort by:

Best

Search Comments
Expand comment search
Comments Section
infinitejester7
•
1d ago
Analyze Icon
Sounds exactly like BearClaude. There are a million GUIs and IDEs built on top of Claude code coming out. Many, like Bear and the one you mentioned, are spec-driven.

IMO I’d rather stick to open source offerings, and you’d have to hold me ant gunpoint to use Amazon’s. Look to the heap of discarded crapware they’ve produced over the years. Lumberyard, Storywriter…

There are more of these tools than time to try them, and I dedicate a lot of time to trying out CC related tooling. My advice: start with open source and tooling created by organizations you want to support.



Upvote
93

Downvote

Reply
reply

Award

Share
Share

theagnt
•
1d ago
Analyze Icon
I checked out bearclaude - just their website.

First of all - incredibly odd that it uses Apple Intelligence instead of Claude to write the documents. That is a recipe for failure. I can't tell if they just use Apple Intelligence to REVIEW the plan or write the plan. In any event, this is a meaningless step.

Second and more importantly, it then just dumps you into a hosted terminal with Claude Code with the plan.

The documents and the plan are NOT the problem in executing a large project in Claude Code. You can get Claude.ai or Claude Code to create the plan today. You don't need a new app for this. The real problem is that Claude Code Cannot Execute a Plan End-to-End.

Claude Code as it exists today is great if you're incrementally building interactively. A spec can help, but you quickly deviate from the plan during this kind of implementation due to both Claude's assumptions and... well, human nature.

I've done extensive testing trying to build a complete product autonomously in Claude Code with and without clear orchestration instructions, specs, workplans, orchestration logic, etc. and invariably Claude goes off the rails, makes assumptions, hallucinates, fabricates test results instead of running tests, etc. when things get complex regardless of how simple your claude.md setup, additional scaffolding, etc. or how detailed it is, or if there's none at all.

I'm working on a system to enable this for my own use. I started by methodically seeing where Claude went off the rails and implemented guardrails in claude.md. I tried many models, linear execution, orchestration using subtasks. None worked in the base Claude Code instance.

So I'm building an orchestration harness that will (hopefully) implement the whole SDLC. It independently launches a new Claude Code instance for each step of the SDLC, manages the project context automatically, leverages some special techniques to prevent hallucinations, "success theater", and other fabrications. verifying the work as it progresses.

I have no idea it will work, but I'm pretty sure any solution that does anything less than this, like Bear Claude, will not.



Upvote
19

Downvote

Reply
reply

Award

Share
Share

u/arbornomad avatar
arbornomad
•
1d ago
Analyze Icon
Our web site isn't keeping up with our development. We're not using Apple Intelligence to author planning docs. We're experimenting with a combination of Claude Code itself and OpenAI models.

I agree with you that executing a plan, keeping everything up to date and staying on the rails is a major challenge. For some, authoring planning docs is also a challenge based on the background they're coming from. We'll start here but ultimately want to help with both.

If you're open to it, I'd love to learn from the experiences of the full SDLC workflow and toolset you're building out. I dropped you a DM to see if you're up to chat.


Upvote
8

Downvote

Reply
reply

Award

Share
Share

scalpol
•
13h ago
Analyze Icon
That’s very interesting. What guardrails would you recommend to implement in Claude.md for starters?


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/HumanityFirstTheory avatar
HumanityFirstTheory
OP
•
1d ago
Analyze Icon
BearClaude is cool but it's a little to "open" and too flexible if that makes any sense.

Great for LLM power users and developers, but not guided enough for non technical users (i.e the Lovable crowd).

If someone doesn't know what test driven development is, what user stories are, what a design doc and requirements sheet are, then it's unlikely that they'll grasp what to do with flexible tools like BearClaude where you're the one writing the specs (with AI assist) rather than the other way around.

Kiro pretty much locks you in to the Requirements -> Design -> Tasks -> Testing flow. There's no way around it.

Every feature it writes is automatically paired with a unit test.

It's a rigid, standardized inflexible pipeline that steers the model carefully via AI-generated guard rails. That's what I find cool about it.

Though if an Open Source version of Kiro (like a GUI wrapper for CC) does come out then that will be awesome. Especially since Claude Code is still superior in its agentic capabilities and the MAX plans are unbeatable in value.

Amazon is one of Anthropic's primary investors so they're probably getting Sonnet access at dirt price as well.



Upvote
26

Downvote

Reply
reply

Award

Share
Share

Coldaine
•
1d ago
Analyze Icon
Eh, see that's my main complaint about claude code for example, it's too flexible.

I will check out kiro, (and bear claude) because you need a very rigid, purposeful workflow to get the best results. Honestly, my dream IDE would have a graphical representation of where you are in the plan - execute - test - commit - replan cycle. I have legimitately awful ADD, and that is my number one pain point in my workflow.

LLMs have all the same strengths and weaknesses as I do, we write and execute really good stuff, but easily lose context, and constantly overplan and overprovision.

Where's the apps that structure both my workflow and claude's? That force both of us to take the right steps?

Eh, it'll probably come out and be called "Your LLM and you, fusing a more perfect union" or something dumb and attractive to VC money



Upvote
14

Downvote

Reply
reply

Award

Share
Share

u/IversusAI avatar
IversusAI
•
1d ago
Analyze Icon
LLMs have all the same strengths and weaknesses as I do, we write and execute really good stuff, but easily lose context, and constantly overplan and overprovision.

This is why I have always felt that LLMs are neurodivergent. It is why I intuitively "get" them.



Upvote
5

Downvote

Reply
reply

Award

Share
Share

u/AbsurdWallaby avatar
AbsurdWallaby
•
23h ago
Analyze Icon
For us, by us.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/arbornomad avatar
arbornomad
•
1d ago
Analyze Icon
We're working on a Planner mode right now for BearClaude that's more opinionated. It'll put up guide rails for Brainstorming, User focus, Needs analysis, Application readiness (definition of done), Core features, Cloud services, and Key packages.

It'll keep a strong separation between overarching Plan, Tasks, and Code.

And it'll let you take full advantage of Claude Code, including subscriptions.

Still a week or two away from Beta, but would love to know what you think when it comes out.



Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/forestcall avatar
forestcall
•
14h ago
Analyze Icon
I like the direction. But something really bothers me is I can see a list view of the files in the project. I can't figure out how to show a list instead of these giant rows. O had to go back to my Neovim because I thought I would go nutz! I did like the Tree it made in a project file.md. Another weird thing is none of the icons have tool-tips or pop-overs to explain what the buttons do. When I clicked the Tree maker button, there was no satisfying click or any indication I did something. What did happen is the wheel was spinning for 30+ seconds like the app was going to freeze.

With that said I like the direction of the project. I personally need some basic QOL features.


Upvote
1

Downvote

Reply
reply

Award

Share
Share


1 more reply
u/Plinth_Debris avatar
Plinth_Debris
•
1d ago
Analyze Icon
Unit tests are definitely not remotely useful for a lot of web development and tend to slow it down dramatically when they are enforced in TDD there

Hope you can turn them off if they are enforced by default in Kiro



Upvote
0

Downvote

Reply
reply

Award

Share
Share

partnerinflight
•
1d ago
Analyze Icon
Of course UTs would slow the development process down. That’s the cost of UTs. But without them how do you know that that next feature or refactor CC did didn’t break something?

The argument for UTs in vibe coding is exactly the same as the general UT argument, except you should actually review the UTs generated to make sure they’re testing the desired behavior and not just simply passing. (That’s where a TDD comes in.)

You want to run fast and get features out? Sure. But expect to deal with constant bugs and customer complaints if your code isn’t properly tested.


Upvote
5

Downvote

Reply
reply

Award

Share
Share

u/HumanityFirstTheory avatar
HumanityFirstTheory
OP
•
1d ago
Analyze Icon
Yeah I’m running into that issue lol. Way too many unit tests. Haven’t found a way to tune it down but it definitely slows the process down considerably.



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/BryantWilliam avatar
BryantWilliam
•
1d ago
Analyze Icon
Can’t forget that investing in many unit tests will help you a lot in the future and prevent regression though.


Upvote
3

Downvote

Reply
reply

Award

Share
Share


7 more replies

3wteasz
•
1d ago
Analyze Icon
c0unt_zero
•
1d ago
Analyze Icon
Hey u/infinitejester7 , I've looked up BearClaude when I saw you mention it here, but all I'm finding is a repo on github that's basically just a docker image with claude code preinstalled?

Could you post the link to the IDE you're mentioning in your comment please?



Upvote
2

Downvote

Reply
reply

Award

Share
Share

c0unt_zero
•
1d ago
Analyze Icon
Nevermind, found it.

For anyone else wondering: https://bearclaude.specstory.com/


Upvote
5

Downvote

Reply
reply

Award

Share
Share

u/Frequent_Beat4527 avatar
Frequent_Beat4527
•
1d ago
Analyze Icon
What is BearClaude? I searched for "BearClaude" and couldn't find relevant answers



Upvote
1

Downvote

Reply
reply

Award

Share
Share

gregce_
•
1d ago
Analyze Icon
https://bearclaude.com


Upvote
3

Downvote

Reply
reply

Award

Share
Share


1 more reply
ClubAquaBackDeck
•
49m ago
Analyze Icon
I'll tell you that Kiro will succeed over BearClaude because it's ultimately easier and amazon has a much larger reach.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

choronz
•
1d ago
Analyze Icon
damned, more vendors leverage on open source VS code to build IDE like windsurf, and slap it with agentic vibe coding lol



Upvote
10

Downvote

Reply
reply

Award

Share
Share

u/960be6dde311 avatar
960be6dde311
•
22h ago
Analyze Icon
Yeah it's getting really annoying how many different tools there are. Everyone wants to try to control the market with "their" tool. I'm sticking with VSCode personally ... I can't find any reason to switch off of it.



Upvote
5

Downvote

Reply
reply

Award

Share
Share

IllegalThings
•
13h ago
Analyze Icon
As annoying as it is, it’s because things are evolving rapidly. Companies are realizing how important tooling is. This is a good thing.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/nick-baumann avatar
nick-baumann
•
20h ago
Analyze Icon
Seems like closed-source Cline with only Anthropic models.



Upvote
27

Downvote

Reply
reply

Award

Share
Share

u/Realistic-Zebra-5659 avatar
Realistic-Zebra-5659
•
8h ago
Analyze Icon
I used it heavily for a day (coming from roo). Not a big fan.

Kiro has two modes - over engineer and yolo. 

In over engineering mode every feature has a requirements, design doc, and tasks to review before it can start. For the scope of feature AI can successfully do today it’s super slow to get it going. 

In yolo mode it immediately codes whatever it thinks (which is almost always wrong) and you have to then have the model revert its code and redo it another way. 

Roo/cline is the sweet spot, review what it’s going to do concisely and then let it go do it


Upvote
2

Downvote

Reply
reply

Award

Share
Share

TheMellowArms
•
1h ago
Analyze Icon
Ding ding ding


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Meshyai avatar
Meshyai
•
Promoted

At this point I’ve accepted that I’m not gonna hand-model anything. Meshy does it for me in like 2 minutes. Text in, model out. It’s like AI gacha for 3D devs. Code MESHYHALF if you’re also done pretending you’ll “learn it properly someday.”
Sign Up
meshy.ai
Thumbnail image: At this point I’ve accepted that I’m not gonna hand-model anything. Meshy does it for me in like 2 minutes. Text in, model out. It’s like AI gacha for 3D devs. Code MESHYHALF if you’re also done pretending you’ll “learn it properly someday.”
IANAL_but_AMA
•
1d ago
Analyze Icon
During free preview I totally understand the need to learn and gather feedback including prompts / code.

Just be mindful of what you paste in…

“For the Kiro Free tier and during preview, your content, including code snippets, conversations, and file contents open in the IDE, unless explicitly opted out, may be used to enhance and improve the quality of FMs. Your content will not be used if you use the opt-out mechanism described in the documentation.”



Upvote
19

Downvote

Reply
reply

Award

Share
Share

u/HumanityFirstTheory avatar
HumanityFirstTheory
OP
•
1d ago
Analyze Icon
Honestly whenever I use these tools I operate under the impression that all my code is being harvested, regardless of what their terms of service say.

There have been countless times of well-established companies having one thing in their ToS and then doing the other...

I would heavily advise that anyone who doesn't want to risk their code being harvested should stick to local on-device models.

Luckily for me I'm building NextJS project managers so I don't care about privacy in this case lol.



Upvote
24

Downvote

Reply
reply

Award

Share
Share

Isssk
•
1d ago
Analyze Icon
Bold of you to think someone else actually wants my code 😂



Upvote
11

Downvote

Reply
reply

Award

Share
Share

u/2roK avatar
2roK
•
16h ago
Analyze Icon
All my code is written by their shitty AI so they can have it, sure...


Upvote
5

Downvote

Reply
reply

Award

Share
Share

raycuppin
•
23h ago
Analyze Icon
One hundred percent yes.


Upvote
-1

Downvote

Reply
reply

Award

Share
Share

u/Impressive_Beat4857 avatar
Impressive_Beat4857
•
19h ago
Analyze Icon
Thanks for pointing it out.
Gotta be careful about them private keys and personal details.
I care less about it being used for model learning, more about the human access to the data.
I hope in the big models it's less of a risk, since people do share personal information on a daily basis.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

No_Accident8684
•
1d ago
Analyze Icon
that might explain the recent stupidity of cc.. they need more resources for amazon



Upvote
15

Downvote

Reply
reply

Award

Share
Share

u/2roK avatar
2roK
•
15h ago
Analyze Icon
I was here to read this message before mods delete and ban it to the megathread.


Upvote
3

Downvote

Reply
reply

Award

Share
Share

trysidersern
•
1d ago
Analyze Icon
anything that works well to generate and keep documentation up to date with a human in the loop? spec driven development has been our default for a while but keeping the docs up do date and actually representative for very large repos is hard.

we can do human curation but feels like there should be a better way



Upvote
13

Downvote

Reply
reply

Award

Share
Share

u/aspittel avatar
aspittel
•
22h ago
Analyze Icon
Not sure if this is what you're referring to, but Kiro has agentic hooks as a feature, which allows you to run an action on each save or feature - for ex. update the docs!


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/LambdaAPI avatar
LambdaAPI
•
Promoted

You can now run DeepSeek-R1-0528 on Lambda’s Inference API. It’s a beast.
Appropriate_Car_5599
•
1d ago
Analyze Icon
thank you a lot for sharing this info! I just tried it, and honestly, I was really impressed. Last time I felt this way was when I tried Claude Code for the first time. In my case this tool generated three stages of documentation for me: a Requirements doc with five user stories, a Design document with two valid Mermaid charts (Claude usually struggles to generate correct Mermaid charts with first shot), and a detailed task implementation plan with references to the previously created documents.

Another thing that impressed me was how it crafted tests during implementation. The tests followed Go’s table-driven design, not just basic test functions

Also UI of their editor looks much better for me than vscode/cursor or windsurf

I'm not sure if it runs pure Claude or some pre-trained Claude models, but it works perfectly. I’m not sure I’ll be able to switch from Claude to this tool, but instead, I’m thinking about making Claude Code work in a similar way. Thanks to the raw performance and prompts, I believe we can turn this small CC tool into a complete framework like Kiro


Upvote
12

Downvote

Reply
reply

Award

Share
Share

u/IversusAI avatar
IversusAI
•
1d ago
•
Edited 1d ago
Analyze Icon
If anyone is reading along and wants the link:

https://kiro.dev/downloads

https://kiro.dev/blog/introducing-kiro

Devs just did a livestream: https://www.youtube.com/live/sXbIw1_Rvo4

edit: There's a windows version out of the box, yeah!


Upvote
12

Downvote

Reply
reply

Award

Share
Share

u/Kai_ThoughtArchitect avatar
Kai_ThoughtArchitect
•
1d ago
Analyze Icon
Amazon jumping into spec-driven AI development is huge validation. As someone who's been building in this space for a while, it's wild seeing them announce features I've already built and improved on.

Their requirements, design, and task flow is solid (been doing that for months), but tying systematic development to a specific IDE/vendor at premium pricing seems backwards. Some of us have already built these systems to work with any AI, anywhere.

The real innovation isn't locking developers into another $39/month ecosystem - it's giving them the methodology and freedom to use it with the tools they already have.

Still, respect to Amazon for validating what the future looks like. Those of us already there are excited to see the space grow.


Upvote
6

Downvote

Reply
reply

Award

Share
Share

Coldaine
•
1d ago
Analyze Icon
i've used kiro now for a couple of hours and have one enormous critique, and It's the same one I give to people who think they can put everything in just one claude.md

It's making these absolutely enormous spec and a spec and design documents, As giant enormous entities. And it doesn't have any tools that it provides to Sonnet to edit these in a manner that makes sense at all. So it's absolutely chewing through the LLM, use to just make even basic edits to any of the plan.

Plus performance has degraded so much that it takes two to three minutes to even add or delete a line on these big documents so as the for the moment as configured it's a complete fail.

Sonnet just does not have the context window size to to work that way. you need a bunch of small reasonably sized documents that refer to each other for it to efficiently move through and understand your documentation or you need a RAG MCP to give it the information in bite size pieces. it's not Gemini Pro where you can just dump the entire spec into the LLM and expect it to make edits quickly and efficiently.



Upvote
6

Downvote

Reply
reply

Award

Share
Share

twolf1973
•
21h ago
Analyze Icon
Add steering that tells it to separate the specs out logically, so it's not all one big file.



Upvote
5

Downvote

Reply
reply

Award

Share
Share

Coldaine
•
14h ago
Analyze Icon
Sure, but this is supposed to be the solution for “vibe coders”

It needs more intrinsic guard rails. It’s a source of free sonnet access for now at least, I’ve used it for probably 12 straight hours. I’ll soften my critique a bit, right now it’s as good as windsurf or cursor, if not quite the godsend it claims to be. Top feature: built with MCP in mind. You don’t have to restart anything if you change the MCP config, just pops into existence.


Upvote
1

Downvote

Reply
reply

Award

Share
Share


3 more replies
DrMistyDNP
•
1d ago
Analyze Icon
I WANT to justify Cursor, Kiro etc but I just can't wrap my head around paying a monthly fee for an IDE wrapper's Agent, when Claude Code CLI can do so much more - and I'm already paying $200 for it! No chance I'd give up CC for an IDE, no IDE as of now that can do what CC does.

I just refuse to pay to use a suboptimal agent. If the agent is literally Sonnet, then I already have certainty that I'm not going to get more out of it than what I already have access to. I can use VS Code with CC for free. I think they are going to have to figure out the balance, it's nonsense to pay for an LLM subscription, and then to pay for separate agents. Not sure what the solution is, but we will find out! I love the concept of a fully integrated & light weight IDE, I just don't think that they are worth Monthly subscriptions just to use the AI component.

I'm open to feedback/suggestions from anyone. Would love to hear if you have a solution.



Upvote
10

Downvote

Reply
reply

Award

Share
Share

Appropriate_Car_5599
•
1d ago
Analyze Icon
exactly, this is why I liked Kiro approach and want to try implement this into Claude Code instead

Another thing which is cool in their IDE I just discovered - hooks. Not sure if I can do this in CC, but theoretically it sounds pretty cool. Like trigger some logic once some file is changed



Upvote
6

Downvote

Reply
reply

Award

Share
Share

DrMistyDNP
•
1d ago
Analyze Icon
Oh yes, CC has easy to setup hooks. You can have CC write them for you. I'm still waiting on the settings to import. I use hooks for agent sign-in/sign-out (to review & update Project.md/Claude.md/Logs/Domain Specific MD files (Frontend/Backend/Reviewer). The hooks work perfectly! I also use them to assure CC only uses UV, Bun, Bunx etc. As well as to use a sound to notify my when a task is complete, or CC needs permissions.

https://docs.anthropic.com/en/docs/claude-code/hooks

Have Claude Code review the documentation above, setup a "Hooks" folder (to store hooks), and reference where the hooks should be stored in your Global MD file. Then just tell CC exactly what you want to happen and it will write the hooks for you!



Upvote
8

Downvote

Reply
reply

Award

Share
Share

Appropriate_Car_5599
•
1d ago
Analyze Icon
omg, thank you so much!!! I haven't heard of this before, thank you!


Upvote
3

Downvote

Reply
reply

Award

Share
Share

_50Hertz
•
1d ago
Analyze Icon
Can you explain how you use hooks to update Domain Specific MD Files?



Upvote
2

Downvote

Reply
reply

Award

Share
Share

DrMistyDNP
•
1d ago
Analyze Icon
I wrote a huge response explaining my setup, but Reddit isn't having it! I saved it to notes and will try to figure out why later! So frustrating!


Upvote
3

Downvote

Reply
reply

Award

Share
Share


1 more reply

1 more reply
u/Kai_ThoughtArchitect avatar
Kai_ThoughtArchitect
•
1d ago
Analyze Icon
Funny you mention that, I've been building exactly this for Claude Code (and any AI) for the last 6 months! It's called Noderr and it's completely platform agnostic.

Launching next week actually. Seeing Kiro drop with similar concepts right before launch is wild validation. The systematic approach is definitely the future.



Upvote
0

Downvote

Reply
reply

Award

Share
Share

DrMistyDNP
•
1d ago
Analyze Icon
Definitely needed!


Upvote
2

Downvote

Reply
reply

Award

Share
Share

Coldaine
•
22h ago
Analyze Icon
Is it out or available in preview? I am basically cheating this same workflow with Claude hooks and Serena MCP


Upvote
1

Downvote

Reply
reply

Award

Share
Share

DrMistyDNP
•
1d ago
Analyze Icon
TBF: I am downloading it rn - will post if I feel any differently after actually using it! But it would be really hard to convince me to tack on another subscription. I would be totally fine with paying for a license, but not to have me on the hook every month. 👎


Upvote
0

Downvote

Reply
reply

Award

Share
Share

FarVision5
•
1d ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
Everyone likes to pitch in their two cents about Grok and xAI, so let me chime in about AWS. I've been burned quite a few times by their ridiculous naming conventions and billing. I trust Google more than AWS and Anthropic more than Google.

There's a 0% chance this product will give me Sonnet or Opus less expensively or better performing than anthropic - therefore 0% interest.

At least Gemini CLI could work at some point with something different.



Upvote
12

Downvote

Reply
reply

Award

Share
Share

Icy-Marzipan-2605
•
1d ago
Analyze Icon
afaik, AWS runs Claude models on their hardware, I guess they just have an agreement with Anthropic on that one, so they might have less costs on running Claude models than the Anthropic


Upvote
5

Downvote

Reply
reply

Award

Share
Share

DrMistyDNP
•
1d ago
Analyze Icon
exactly! I actually let CC use Gemeni as a Subagent for Token Heavy Tasks! Some day it may be the other way around. For now Gemeni is CC's assistant.


Upvote
3

Downvote

Reply
reply

Award

Share
Share

u/960be6dde311 avatar
960be6dde311
•
22h ago
Analyze Icon
If you're using Gemini, why not check out the Roo Code extension for VSCode? It works with Gemini and a host of other LLM providers. I switch between different ones regularly. You can control which models you're using and how much you spend. I haven't found anything better than it so far.



Upvote
1

Downvote

Reply
reply

Award

Share
Share

FarVision5
•
9h ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
I'll try it again! I was going the Augment thing for a while before I discovered CC. I see the Roo people are going nuts with new updates. I'm concerned about bad processing. Just because CC is currently taking a shit, I don't want to break stuff by going cheap, then coming back later today to fix more tech debt then simply doing nothing!


Upvote
2

Downvote

Reply
reply

Award

Share
Share


1 more reply
External_Spread_8010
•
1d ago
Analyze Icon
Honestly, this looks like a legit leap forward. Most tools focus on vibe-coding and leave structure as an afterthought, but Kiro flipping that with spec-first flow is huge. Having requirements, design docs, and task lists auto-generated from the start? That’s real developer workflow stuff not just AI hype. Definitely keeping an eye on how it handles real-world complexity, but first impressions are 🔥.



Upvote
13

Downvote

Reply
reply

Award

Share
Share

u/HumanityFirstTheory avatar
HumanityFirstTheory
OP
•
1d ago
Analyze Icon
Yeah, also the fact that it generates tests for every single feature and auto-tests them is great. Again, without prompting.

The agentic stuff is a bit of a hit-or-miss. I've been using it for an hour or so and its run into issues editing files, but it is in public preview so I'll cut them some slack.


Upvote
7

Downvote

Reply
reply

Award

Share
Share

u/Zamaamiro avatar
Zamaamiro
•
19h ago
Analyze Icon
Why do you sound AI-generated?


Upvote
3

Downvote

Reply
reply

Award

Share
Share

raycuppin
•
23h ago
Analyze Icon
The idea of “spec-driven development” does seem to be a good one, and dovetails with a ton of agentic best-practices for sure. Interesting.


Upvote
3

Downvote

Reply
reply

Award

Share
Share

rusteh
•
18h ago
Analyze Icon
$39 for 3000 interactions a month isn't going to cut it for someone using this full-ish time. Spec driven deployment is cool, but it's a chatty process going back and forth. You are going to burn the 3000 interactions quickly. The overage model of $0.04 will then get expensive quickly. I think for most developers a Claude max plan with a bit of discipline is a better approach. 


Upvote
3

Downvote

Reply
reply

Award

Share
Share

bhc317
•
1d ago
•
Edited 1d ago
Analyze Icon
Just tried it, it's pretty great. Love how it revolves around requirements/design/tasks. Feels like a more fully fleshed out Claude Code.

Two issues:

Can't use my Claude Max subscription to use Claude Opus for coding. Dealbreaker.

It's slow as hell. Very, very slow. Pauses, waits, thinks A LOT. One of the best things about Claude Code is how snappy and fast it feels.

Thanks for the heads up on this - I love the design of the IDE and the way they're adding best practices around structure to the Claude Code experience.

Now I just need Anthropic to come out with their own version of this!



Upvote
5

Downvote

Reply
reply

Award

Share
Share

u/HumanityFirstTheory avatar
HumanityFirstTheory
OP
•
1d ago
Analyze Icon
Absolutely, very well said. It’s SO slow. I’ve been waiting 2 hours for a result that Claude code could do in 20min (if even that).

The constant pausing and slow testing is definitely something they should optimize.

But the overall structure and workflow they have going is amazing. Definitely hope Anthropic and others do the same! This is something cursor should add.



Upvote
3

Downvote

Reply
reply

Award

Share
Share

bhc317
•
1d ago
Analyze Icon
Absolutely. Great design overall, especially for something brand new.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/joninco avatar
joninco
•
1d ago
Analyze Icon
What you need is non-nerfed claude.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

Ok_Rough_7066
•
1d ago
Analyze Icon
How can I download the docs easily? They don't offer an offline option for docs


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/audiodolphile avatar
audiodolphile
•
1d ago
Analyze Icon
Interesting that they make another Code clone but not an extension like Kilo code? Builtin features are just system prompts


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/AtlantaSkyline avatar
AtlantaSkyline
•
1d ago
Analyze Icon
Are there any IDEs that support OAuth login to subscriptions rather than API integration?


Upvote
2

Downvote

Reply
reply

Award

Share
Share

daft020
•
23h ago
Analyze Icon
What counts as “1 interaction” though?


Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/960be6dde311 avatar
960be6dde311
•
22h ago
Analyze Icon
I want to use VSCode, not some other tool. There's a reason that VSCode is as popular as it is. It just does a lot of things that developers need, and it's extensible by anyone.

The Roo Code extension for VSCode is the best solution I've found for code generation. It works extremely well with Amazon Bedrock, Gemini, Open Router, and probably others. I still get all the benefits of working in VSCode, plus the added benefits of Roo Code.

The AI industry is getting too fragmented with everyone wanting to try to control the market.



Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/stormlrd avatar
stormlrd
•
15h ago
Analyze Icon
Install Amazon q extension into vs code


Upvote
1

Downvote

Reply
reply

Award

Share
Share

oh_jaimito
•
1d ago
Analyze Icon
game changer

If I had a nickel ...


Upvote
3

Downvote

Reply
reply

Award

Share
Share

ganderofvenice
•
1d ago
Analyze Icon
I'm trying it right now. Early impressions but I'm impressed. I like its unique approach to "vibe" coding where it uses a lot of context and documentation (and creates it!) based on your request to carefully perform tasks.

Huh, I'll test more but, this looks legit.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

Longjumpingfish0403
•
1d ago
Analyze Icon
Interesting to see Kiro's approach in structuring app dev through spec-first tooling. Reminds me of how GenAI is evolving UX design, shifting from clicks to conversational interfaces. This could tie-in with Kiro's aim to simplify dev processes by reducing friction. The focus there is more on understanding user intent and effortless experiences. Could be a similar mindset in action here!


Upvote
2

Downvote

Reply
reply

Award

Share
Share


[deleted]
•
1d ago
Analyze Icon
utkohoc
•
22h ago
Analyze Icon
How does it feel to be communicating with yourself using a multitude of bots while everyone looks on knowing this and cringing? Seriously. If you want to make marketing posts. Just make them. This whole guise of communication using bots is so obvious and Boring. Idk what the world can do as a collective to move on from this deranged type of marketing but pretending to be real people to shill your products is not it.



Upvote
-1

Downvote

Reply
reply

Award

Share
Share

u/HumanityFirstTheory avatar
HumanityFirstTheory
OP
•
22h ago
Analyze Icon
Yup.

Another genius appeared.

You’re right buddy.

You cracked the code.

Amazon wired me $200 million USD to write this post.

Because clearly Amazon can’t afford ads so instead they rely on obscure posters like me to astroturf niche subreddits.

Do you people have any common sense or any understanding of how the real world works?

Are you being serious when you claim we’re all marketers?

Because if so, I have a bridge to sell to you.

Kiro is developed by one of the largest tech companies in the world.

To assume that Amazon relies on astroturfing for marketing is so absolutely laughable that it’s absurd.

You people need to go back to school…



Upvote
5

Downvote

Reply
reply

Award

Share
Share

utkohoc
•
22h ago
Analyze Icon
You people?



Upvote
0

Downvote

Reply
reply

Award

Share
Share

u/HumanityFirstTheory avatar
HumanityFirstTheory
OP
•
22h ago
Analyze Icon
Yup. You’re not the only one accusing me of astroturfing for Amazon lmaoo.


Upvote
2

Downvote

Reply
reply

Award

Share
Share


[deleted]
•
1d ago
Analyze Icon
healthnuttier
•
1d ago
Analyze Icon
This sounds like the AI version of Amplify. If so run.



Upvote
1

Downvote

Reply
reply

Award

Share
Share

thisis-clemfandango
•
16h ago
Analyze Icon
😂


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/emptyharddrive avatar
emptyharddrive
•
1d ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
I think for anyone who already drafts a clear vision, writes up a concise PRD with use cases and acceptance criteria, sketches out architecture or API contracts, breaks things into backlog tasks, and stubs out tests before touching code (which now you can just ask AI to do for you and you can review it and tweak), you’re basically getting the same benefits, so I'm not sure if this is for me - but for any who like being locked into it, ok.

What Kiro adds is frictionless automation and built-in SWE guardrails: your docs live right alongside your code, stay in sync as you refactor, and CI can even validate against your spec. That’s awesome if you’ve struggled with stale Markdown files or missing test coverage creeping in.

But if you already treat specs the standard and your tests up to date (which you can AI do for you as well), Kiro’s mostly a convenience layer. That's nice, but not mission critical IMHO.

I think for solo projects or small squads with decent discipline, a well-organised repo, a few Markdown files, and a Jira board still do the job just fine.

But then again, that's why they have menus in restaurants.



Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/AbsurdWallaby avatar
AbsurdWallaby
•
23h ago
Analyze Icon
Yeah honestly at this point if you're going through all this you should be making your workflow AI agnostic so you aren't locked in.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/idkyesthat avatar
idkyesthat
•
22h ago
Analyze Icon
I literally just setup Claude code + Gemini Clinton try it out after moving on from cursor and chatgpt.

I’m gonna have to replace my free time with AI hobby alike time, lol


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Personal-Reality9045 avatar
Personal-Reality9045
•
21h ago
Analyze Icon
Uh that looks awesome. I'm wondering if it can do parallel tool calling and parallel agents.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

MuscleLazy
•
20h ago
•
Edited 20h ago
Analyze Icon
Claude told me:

During preview it’s free, with planned pricing tiers: free (50 agent interactions/month), Pro ($19/month for 1,000 interactions), and Pro+ ($39/month for 3,000 interactions).

I’m not inclined to pay for an IDE, when I can work with Claude Code and Desktop perfectly fine. Plus, I’m using it combined with my collab platform, which makes Claude a super developer. https://github.com/axivo/claude


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Impressive_Beat4857 avatar
Impressive_Beat4857
•
19h ago
Analyze Icon
I'm new to the "vibe coding" game and liked the approach - when starting a project, it makes sense to start with a design outline.

I believe a basic set of prompts according to a well established order of things would do the work as well -requirements -> specs/SRS -> high level design -> modules structure -> apis/persistence -> tasks list.

Also had to make quite significant changes to the proposed structure, especially on the task order stage. The tool wanted to do waterfall and not agile, which is for small project does not make sense.

But it was nice to have the steps automated, and use some free tokens while it lasts.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

d33mx
•
17h ago
Analyze Icon
Not really thinking IDE is the way.

Claude code sets a norm. Behaviours leads to terminal.

Btw; why a funny freaking purple ghost ? like jules.google.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

glidaa
•
16h ago
Analyze Icon
How are you meant to set up a testing environment? I have like puppeteer and play write running but mostly claude is just blindly ruining my code and cant test its on slop. Its just slop coding.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

bitdoze
•
13h ago
Analyze Icon
Looks ok even if is at beginning took it for a test: https://www.bitdoze.com/kiro-ai-ide/


Upvote
1

Downvote

Reply
reply

Award

Share
Share

DigitaICriminal
•
5h ago
Analyze Icon
How this compares to Gemini CLI?


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Dreamer_can avatar
Dreamer_can
•
3h ago
Analyze Icon
Why it's telling me: I'm built on Anthropic's Claude 3.5 Sonnet model???


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Community Info Section
r/ClaudeAI
hp
Join
ClaudeAI
This is a Claude-information subreddit which aims to help everyone make a fully informed decision about how to use Claude to best effect for their individual purposes. ¹⌉ This subreddit is not controlled, operated or sanctioned by Anthropic. ²⌉ If your problem requires Anthropic's help, visit https://support.anthropic.com/ This subreddit is not the right place to fix your account issues. ³⌉ For more help, check the resources below. ⁴⌉ Please read the rules before posting.

Show more
Created Jan 23, 2023
Public
273K
Members
293
 Online
Top 1%
Rank by size 
Anthropic Resources
Discord Community
Discord Community
How to Get Support
How to Get Support
Community Resources
ClaudeLog.com
ClaudeLog.com
r/ClaudeAI Rules
1
Be respectful
Diversity of opinion is welcome. Controversial opinions are welcome. Personal attacks and harassment are not. Ask Claude for a definition of "good faith discussion for a subreddit" if you're unsure what's acceptable.

2
Be relevant
Stay relevant to the Claude technology. We don't accept posts of general AI interest here. Also if you are discussing competitor technology, you must include detailed comparisons with Claude. "I used X and it was much better than Claude" is not sufficient.

3
Be constructive. Don't come here to agitate others.
Is your post/comment likely to add positively to the knowledge or experience of other readers here? Has it already been shared recently? Is it just designed to agitate others?

4
Be Reddit-compliant
This subreddit uses Reddit's default harassment and abuse filters. In addition, you may find yourself or your content removed by Reddit if you don't follow their policies. These can be found below.

Reddit content policy: https://www.redditinc.com/policies/content-policy Those discussing the use of Claude for creative writing should pay particular attention to Rules 6, 7 and 4.

Reddit user agreement: https://www.redditinc.com/policies/user-agreement-september-25-2023

5
Use relevant post flair
Claude has vast amounts of diverse use cases. As a result, often the problems/questions/praise you have for Claude are not shared by others. Help others filter posts by their area of interest by choosing the flair most related to its usage group. If none fit, or you feel it is of more general interest, choose the flair most relevant.

6
Don't be spammy
Promoting your project or paid service is possible here but if your site looks spammy/sketchy to us, we will ban it. Fully disclosing what the user is getting, how and who it helps, and what your association is with the project will lower (but not eliminate) the likelihood of banning. Your posting privileges vary with your helpful participation on the sub.

7
Don't manipulate upvotes
Undermining the Reddit voting system is an immediate permanent ban offence. This subreddit has bots in place looking for suspicious activity.

8
Use the Megathread for your recent Claude performance reports/complaints
Help us keep track of Claude system performance by keeping your experiences and reports on the Claude Performance Megathread sticked at the top of the subreddit page. This also frees the feed from performance incident flooding. We may allow the occasional performance post through but this is not typical. Check first if your issue has been discussed recently.

9
Do not come here to fix your Anthropic account problem
We have no way of fixing the problem with your account and Anthropic does not respond to account help requests on this subreddit. Try their normal support channels. If you believe you were incorrectly charged, talk to your bank about a chargeback.

RELATED COMMUNITIES
r/artificial icon
r/artificial
1,116,231 members
r/MachineLearning icon
r/MachineLearning
2,983,276 members
Moderators
Message Mods
u/sixbillionthsheep avatar
u/sixbillionthsheep 
Mod
u/Kris_AntAmbassador 
Mod
Kris - Anthropic Ambassador
u/David_AntAmbassador 
Mod
u/inventor_black avatar
u/inventor_black 
Mod 
emoji:cl_divider:
emoji:cl_logo: ClaudeLog.com
InventorBlack
u/AutoModerator avatar
u/AutoModerator
u/manipulation-pi avatar
u/manipulation-pi
u/bot-bouncer avatar
u/bot-bouncer
u/evasion-guard avatar
u/evasion-guard
u/ai-moderator avatar
u/ai-moderator
u/automod-toggle avatar
u/automod-toggle
View all moderators
Installed Apps
Modmail Automator
Modmail Quick User Summary
Evasion Guard
Manipulation Detector
AutoModerator Toggle
Flooding Assistant
Admin Tattler
Modqueue Tools
Bot Bouncer
Subreddit Statistics
Comment Mop
AI Moderator
Reddit Rules
Privacy Policy
User Agreement
Accessibility
Reddit, Inc. © 2025. All rights reserved.

Collapse Navigation
解释

Skip to main content
Amazon's Cursor Alternative Kiro - this space is getting way more competitive than anticipated : r/singularity


r/singularity
Current search is within r/singularity

Remove r/singularity filter and expand search to all of Reddit
Search in r/singularity
Advertise on Reddit

Open chat
Create
Create post
Open inbox
2

User Avatar
Expand user menu
Skip to NavigationSkip to Right Sidebar

Back
r/singularity icon
Go to singularity
r/singularity
•
12 hr. ago
[deleted]
Analyze Icon

Amazon's Cursor Alternative Kiro - this space is getting way more competitive than anticipated
Sorry, this post was deleted by the person who originally posted it.

Upvote
97

Downvote

15
Go to comments

Share
Share
Join the conversation
Sort by:

Best

Search Comments
Expand comment search
Comments Section
Living-Medium8662
•
11h ago
Analyze Icon
I tried it. Very useful for senior devs. It's much more than vibe coding.



Upvote
21

Downvote

Reply
reply

Share
Share

u/poopertay avatar
poopertay
•
11h ago
Analyze Icon
It’s so slow that you end up having to code it yourself :P



Upvote
10

Downvote

Reply
reply

Share
Share

Living-Medium8662
•
11h ago
Analyze Icon
I noticed.. it’s still in preview. Loading and start times too


Upvote
2

Downvote

Reply
reply

Share
Share

crizzy_mcawesome
•
11h ago
Analyze Icon
I bet cursor will add that soon



Upvote
2

Downvote

Reply
reply

Share
Share

Living-Medium8662
•
11h ago
Analyze Icon
Everyone copy pastes eventually


Upvote
5

Downvote

Reply
reply

Share
Share

FarrisAT
•
11h ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
Anthropic screeching



Upvote
3

Downvote

Reply
reply

Share
Share

u/Additional_Bowl_7695 avatar
Additional_Bowl_7695
•
11h ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
Doesn’t Kiro use Anthropic’s API?

They’re making money with Cursor and these type of IDEs



Upvote
19

Downvote

Reply
reply

Share
Share

FarrisAT
•
10h ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
It’s circular shit eating

Anthropic sells below cost AWS cloud to Amazon who invests below cost AWS cloud credits into Anthropic



Upvote
6

Downvote

Reply
reply

Share
Share

u/garden_speech avatar
garden_speech
•
7h ago
AGI some time between 2025 and 2100
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
The prices will increase when enough of the user base has been captured I'm guessing. I'll admit I'd already pay way more than I do for GitHub Copilot. I didn't really care about the $10/mo when I first signed up when it was basically fancy autocomplete years ago, but now I pay $25/mo (I think) and would pay $100/mo easily.


Upvote
1

Downvote

Reply
reply

Share
Share

manubfr
•
9h ago
AGI 2028
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
It's basically Cline with far fewer features. Sticking with Cline for now.



Upvote
1

Downvote

Reply
reply

Share
Share

Alyax_
•
4h ago
Analyze Icon
Far fewer? Could you explain?


Upvote
1

Downvote

Reply
reply

Share
Share

Artistic_Load909
•
3h ago
Analyze Icon
Have you used it? Seems like it has way more features…


Upvote
1

Downvote

Reply
reply

Share
Share

ProposalOrganic1043
•
10h ago
Analyze Icon
I would like to see V0 for aws


Upvote
1

Downvote

Reply
reply

Share
Share

Community Info Section
r/singularity
Join
Singularity
Everything pertaining to the technological singularity and related topics, e.g. AI, human enhancement, etc.
Created Jan 28, 2008
Public
3.7M
Members
452
 Online
Top 1%
Rank by size 
User flair
u/Charlie0Simmon avatar
Charlie0Simmon
r/singularity Rules
1
Off-Topic Posts
2
Self-Promotion/Advertising Spam
3
Low-quality/Wildly Speculative Posts
4
No Flamebaiting or Hate
Sidebar
Official r/Singularity Discord
https://discord.gg/UYXce9r8mD

Links
Artificial Intelligence
Space Settlement
Space Flight
Cosmology
Space Videos
Cyborgs
Cyberpunk
All the Sciences

Futurism

FuturePorn

Imaginary Technology

Retro Futurism

The Control Problem

Singularity
Singularity
* Robotics
A subreddit committed to intelligent understanding of the hypothetical moment in time when artificial intelligence progresses to the point of greater-than-human intelligence, radically changing civilization. This community studies the creation of superintelligence— and predict it will happen in the near future, and that ultimately, deliberate action ought to be taken to ensure that the Singularity benefits humanity.

On the Technological Singularity
The technological singularity, or simply the singularity, is a hypothetical moment in time when artificial intelligence will have progressed to the point of a greater-than-human intelligence. Because the capabilities of such an intelligence may be difficult for a human to comprehend, the technological singularity is often seen as an occurrence (akin to a gravitational singularity) beyond which the future course of human history is unpredictable or even unfathomable.

The first use of the term "singularity" in this context was by mathematician John von Neumann. The term was popularized by science fiction writer Vernor Vinge, who argues that artificial intelligence, human biological enhancement, or brain-computer interfaces could be possible causes of the singularity. Futurist Ray Kurzweil predicts the singularity to occur around 2045 whereas Vinge predicts some time before 2030.

Proponents of the singularity typically postulate an "intelligence explosion", where superintelligences design successive generations of increasingly powerful minds, that might occur very quickly and might not stop until the agent's cognitive abilities greatly surpass that of any human.

Resources
Machine Intelligence Research Institute
LessWrong
Check out the Technological Singularity FAQ
Moderators
Message Mods
u/Anenome5 
Decentralist
Anenome
u/Anen-o-me avatar
u/Anen-o-me 
▪️It's here!
u/DnDNecromantic avatar
u/DnDNecromantic 
▪️Friendly Shoggoth
u/Apollo24_ 
2024
Apollo24
u/abrownn avatar
u/abrownn 
2026
(Not actually) Alton Brown
u/Vailhem avatar
u/Vailhem
u/Xenophon1
View all moderators
Reddit Rules
Privacy Policy
User Agreement
Accessibility
Reddit, Inc. © 2025. All rights reserved.

Collapse Navigation
解释Skip to main content
I tried Kiro the code assistant from Amazon with my svelte project, you won't believe how good it is : r/cursor


r/cursor
Current search is within r/cursor

Remove r/cursor filter and expand search to all of Reddit
Search in r/cursor
Advertise on Reddit

Open chat
Create
Create post
Open inbox

User Avatar
Expand user menu
Skip to NavigationSkip to Right Sidebar

Back
r/cursor icon
Go to cursor
r/cursor
•
5 hr. ago
zhamdi
Analyze Icon

I tried Kiro the code assistant from Amazon with my svelte project, you won't believe how good it is
Resources & Tips
r/sveltejs
•
5 hr. ago
I tried Kiro the coffee assistant from Amazon with my svelte project, you won't believe it
I have a complex project I'm working on for almost 8 months, I already have my internal architectural patterns and some opinionated ways to addressing problems, with a strongly dense core where 80% of the things are happening. I must admit I don't have previous experience with cursor or any other ide-integrated solution. I got helped by AI, using deepseek's huge conversation window, to share with it single problems, one at a time.

I was amazed by what Kiro managed to do! In one day: things I planned to do the next month are all almost done! And it's free until they release the production version.

I simply downloaded their ide, opened my project, asked it to read all my .MD files, once I verified it understood the overall architecture, I asked it to take a look at my mongoose model, then to my parent service class, it automatically navigated by curiosity to the individual implementation classes.

Then I asked it to fix a bug I was always delaying because the simple idea of solving it was making me tired: I have 500+ unit tests, and a few of them were connecting to the production database and deleting my users :-o, I couldn't go to production with that.

It found the tests causing that, did that with techniques I didn't know about, a complete three layer fixing. Then I told it, that to be really sure, I wanted to add a line in my host file to intercept connections to the production database and make them fail. To my surprise, it write a bag script that changes my host file, runs the tests, then puts my host file back to it's original state.

Then I have it a screen where a user can view data but cannot edit it, and told it: "I want you to use the same logic as I have in /profile/+page. svelte where the user has a draft of his modifications to his profile, and changes are auto saved, but as long as he didn't publish, the official profile page doesn't change.

He created a server layout file, a layout file, a +page.server.ts file, a page and a component, it almost all worked at first try.

One drawback is that it is a bit slow to process, so I found my self waiting for it to execute the tasks, and there I thought I could launch two or three ides on different machines to be able to do stuff while it is thinking.

One hack I advice you to do, because conversations end up consuming all available tokens, and he then forgets it all. I explained it the project architecture, then asked it to write an AI-readme.md file where it documents all relevant information, it's links to. MD files or to source files, and when starting a new discussion, all it to read that file that he write himself. When you think he learned something new, ask it to update that file.

That's all that comes to my mind, but I can tell you, I never thought it would be so advanced. Of I forgot to mention something, tell me in the comments.

Yeah, and if you ask it to write in svelte 5, it knows how to do that correctly

2 comments

Upvote
0

Downvote

1
Go to comments


Share
Share
u/monday_com avatar
monday_com
•
Promoted

That moment when work just... works. It’s time to give your team a platform they’ll actually love—intuitive, easy to use, built to streamline work and achieve goals faster.
Sign Up
monday.com
Thumbnail image: That moment when work just... works. It’s time to give your team a platform they’ll actually love—intuitive, easy to use, built to streamline work and achieve goals faster.
Join the conversation
Sort by:

Best

Search Comments
Expand comment search
Comments Section
u/steve31266 avatar
steve31266
•
1h ago
Analyze Icon
Gonna have to try Kiro after reading this, especially considering their $19.00 a month service sounds better than Cursor, add to that tool calling and multiple attempts do not count towards your limit.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Community Info Section
r/cursor
Join
Cursor
The AI Code Editor - cursor.com
Created Feb 21, 2024
Public

Community Guide
82K
Members
54
 Online
Top 2%
Rank by size 
Community Bookmarks
Forum
Docs
Status Page
r/cursor Rules
1
Keep it relevant
2
Be civil
3
No rants
4
No misinformation
5
Provide context
6
Limit self-promotion
7
No paid content
8
No spam
9
Write quality titles
10
Use flairs
11
No slop
Moderators
Message Mods
u/IveWastedMyLifeAgain avatar
u/IveWastedMyLifeAgain 
Mod
u/IndraVahan avatar
u/IndraVahan 
Founding Mod
Indra
u/dev-andrew-healey 
Mod
dev-capybara
u/shaoruu avatar
u/shaoruu 
Dev
u/cursor_dan 
Mod
Dan
u/freshkoala 
Mod
u/ydaars 
Dev
u/mntruell 
Dev
u/eric-cursor avatar
u/eric-cursor
u/NickCursor avatar
u/NickCursor 
Mod
Nick Miller
View all moderators
Reddit Rules
Privacy Policy
User Agreement
Accessibility
Reddit, Inc. © 2025. All rights reserved.

Collapse Navigation
解释Skip to main content
AWS launches Kiro, an agentic IDE : r/ChatGPTCoding

r/ChatGPTCoding
Current search is within r/ChatGPTCoding

Remove r/ChatGPTCoding filter and expand search to all of Reddit
Search in r/ChatGPTCoding
Advertise on Reddit

Open chat
Create
Create post
Open inbox

User Avatar
Expand user menu
Skip to NavigationSkip to Right Sidebar

Back
Go to ChatGPTCoding
r/ChatGPTCoding
•
1 day ago
thejoyofcraig
Analyze Icon

AWS launches Kiro, an agentic IDE
Discussion
r/ChatGPTCoding - AWS launches Kiro, an agentic IDE
kiro.dev

Open

Upvote
43

Downvote

21
Go to comments


Share
Share
u/monday_com avatar
monday_com
•
Promoted

The feeling of not having enough time to finish all your tasks is real! Well, with monday.com’s work management platform, get more done in less time with automations, real-time communication, and notifications. Smash that done button! Try now.
The feeling of not having enough time to finish all your tasks is real! Well, with monday.com’s work management platform, get more done in less time with automations, real-time communication, and notifications. Smash that done button! Try now.
The feeling of not having enough time to finish all your tasks is real! Well, with monday.com’s work management platform, get more done in less time with automations, real-time communication, and notifications. Smash that done button! Try now.
The feeling of not having enough time to finish all your tasks is real! Well, with monday.com’s work management platform, get more done in less time with automations, real-time communication, and notifications. Smash that done button! Try now.
monday.com
Sign Up
Join the conversation
Sort by:

Best

Search Comments
Expand comment search
Comments Section
u/thejoyofcraig avatar
thejoyofcraig
OP
•
1d ago
Analyze Icon
Interesting analysis, someone just posted. https://ghuntley.com/amazon-kiro-source-code/ to this subreddit.


Upvote
7

Downvote

Reply
reply

Award

Share
Share

u/nilerafter avatar
nilerafter
•
1d ago
Analyze Icon
Another product that will die after they realize they cannot compete in this space in a meaningful way (e.g. CodeCommit)

AWS should really focus on what it's good at - which is infrastructure services. AWS Cognito is an important but languishing service because AWS, like many others, are hyper-focused on a market that is a bubble and WILL pop. Stop wasting talented engineers on unnecessary products (unless they plan to build Kiro with AI)



Upvote
11

Downvote

Reply
reply

Award

Share
Share

u/IcyDragonFire avatar
IcyDragonFire
•
23h ago
•
Edited 9h ago
Analyze Icon
Imagine an ide that understands aws deployments in and out, so that you prompt your app and deploy it instantly. That brings tremendous value.  

Google is doing the same with firebase studio, and Microsoft will probably try something similar on azure.


Upvote
7

Downvote

Reply
reply

Award

Share
Share

Trotskyist
•
1d ago
Analyze Icon
I'm not so sure. I think Amazon is being pretty forward thinking here, actually - I think the angle they're taking here is absolutely the future of IDEs. That is: more of a platform for planning, orchestrating, and reviewing swarms of agents than actually coding.



Upvote
11

Downvote

Reply
reply

Award

Share
Share

u/nilerafter avatar
nilerafter
•
1d ago
Analyze Icon
Sure. But what stops Cursor from literally implementing the same features next month? Again, CodeCommit is a great example. Nothing really differentiated it from Github and Gitlab and as such it died a slow death.

Kiro is another VSCode clone that may pack some unique features initially (specing, tasking) but that's just one PR for Cursor or VSCode and Kiro's lunch is eaten. AWS will not dedicate the same kind of resources that Cursor or Microsoft are throwing at their IDEs.

Meanwhile, the services that actually make AWS money like compute, auth, storage are dying for engineering to move their development faster. I truly think this is a case of chasing shiny new thing and hoping for the best rather than a focused product strategy.

But hey, maybe I'll be proven wrong. I'll check back in a year from now.



Upvote
0

Downvote

Reply
reply

Award

Share
Share

Trotskyist
•
23h ago
Analyze Icon
Nothing, but amazon has a first-mover advantage here, and furthermore if it's Amazon vs. Cursor I'm absolutely betting on Amazon.

Enterprise buy-in is ultimately what will decide the "winner" here, and Amazon has an ENORMOUS advantage in that half of the world's tech companies already are in the AWS ecosystem. That means this can be just another line-item on an invoice, rather than a whole new contract.



Upvote
8

Downvote

Reply
reply

Award

Share
Share

u/Tendoris avatar
Tendoris
•
16h ago
Analyze Icon
Amazon is also the primary investor in Anthropic and its GPU provider. If they truly want it, they will outcompete Cursor in the long run.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Jealous_Change4392
•
10h ago
Analyze Icon
Microsoft has first mover advantage with GitHub Copilot - along with enterprise penetration


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/OilofOregano avatar
OilofOregano
•
14h ago
Analyze Icon
Kind of an unusual mindset - amazon would still just be selling books if they never continued to branch out. Why stamp an arbitrary point in time where all the new trials have to cease? Any of the biggest and best products of a given time where always once dwarved by more successful alternatives.


Upvote
3

Downvote

Reply
reply

Award

Share
Share

u/FosterKittenPurrs avatar
FosterKittenPurrs
•
10h ago
Analyze Icon
Infrastructure and funding.

Cursor just had to revamp its pricing because it was losing too much money.

Amazon's main business model has always been to basically make stuff so cheap that other companies can't compete. And here, they have AWS that hosts Claude, so they will have availability and the pricing model is already better than Cursor's ever was.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/Illustrious-Film4018 avatar
Illustrious-Film4018
•
17h ago
Analyze Icon
No thanks, that's not a real job.



Upvote
-1

Downvote

Reply
reply

Award

Share
Share

Trotskyist
•
16h ago
Analyze Icon
It absolutely will be


Upvote
3

Downvote

Reply
reply

Award

Share
Share

SatoshiReport
•
1d ago
Analyze Icon
I wonder how this compares to Roo code...



Upvote
2

Downvote

Reply
reply

Award

Share
Share

u/thejoyofcraig avatar
thejoyofcraig
OP
•
1d ago
Analyze Icon
I tested it briefly, it's basically a more opinionated type of Roo. Focused on TDD development. Kiro seems all right based on my ten minute tinkering. I like Roo a lot, especially considering you can use your own API connections and your own VS Code.


Upvote
5

Downvote

Reply
reply

Award

Share
Share

u/OpenAI avatar
OpenAI
• Official
•
Promoted

Turn ideas into images with ChatGPT. Describe anything - like “a wizard reading in a moonlit forest” - and watch it appear. Try it out now ⬇️
Start creating today.
Start creating today.
Start creating today.
chatgpt.com
Sign Up
carterpape
•
10h ago
Analyze Icon
These companies trying to keep their IDEs and VSCode extensions etc. closed source is weird to me. There is so much good open source competition in this space (Cline being best).

Microsoft figured out they might as well just open source GitHub Copilot. Why didn’t Amazon?


Upvote
1

Downvote

Reply
reply

Award

Share
Share


bitdoze
•
13h ago
Analyze Icon
u/OscarHL avatar
OscarHL
•
1d ago
Analyze Icon
Another folk of vsc?


Upvote
-1

Downvote

Reply
reply

Award

Share
Share

u/StupidIncarnate avatar
StupidIncarnate
•
19h ago
Analyze Icon
Ughhhh charge for ide bullshit. No thank you 


Upvote
-1

Downvote

Reply
reply

Award

Share
Share

Whyme-__-
•
11h ago
Professional Nerd
Analyze Icon
Only if Amazon could create an ai product that could simplify deployment to their cloud platform but instead building yet another coding tool


Upvote
-1

Downvote

Reply
reply

Award

Share
Share


[deleted]
•
1d ago
Analyze Icon
Community Info Section
r/ChatGPTCoding
Join
For The Coding Side of ChatGPT
Welcome to our community! This subreddit focuses on the coding side of ChatGPT - from interactions you've had with it, to tips on using it, to posting full blown creations! Make sure to read our rules before posting!

Show more
Created Dec 6, 2022
Public
296K
Members
94
 Online
Top 1%
Rank by size 
User flair
u/Charlie0Simmon avatar
Charlie0Simmon
r/ChatGPTCoding Rules
1
Only Links to ChatGPT (and related websites) are allowed.
2
Be Civil
3
Flairs are required for every post
4
Discussions must be on-topic
5
Whenever possible, include the prompt the used to generate the code
6
Self Promotion and Sponsorships
7
No selling access to models
Moderators
Message Mods
u/PromptCoding avatar
u/PromptCoding 
FOUNDER
u/brianberns avatar
u/brianberns
u/JuliusCeaserBoneHead avatar
u/JuliusCeaserBoneHead
Julius
u/BaCaDaEa avatar
u/BaCaDaEa
u/AutoModerator avatar
u/AutoModerator
View all moderators
Reddit Rules
Privacy Policy
User Agreement
Accessibility
Reddit, Inc. © 2025. All rights reserved.

Collapse Navigation
解释Skip to main content
Is Kiro IDE the next Cursor? : r/webdev


r/webdev
Current search is within r/webdev

Remove r/webdev filter and expand search to all of Reddit
Search in r/webdev
Advertise on Reddit

Open chat
Create
Create post
Open inbox
2

User Avatar
Expand user menu
Skip to NavigationSkip to Right Sidebar

Back
r/webdev icon
Go to webdev
r/webdev
•
2 hr. ago
_cofo_
Analyze Icon

Is Kiro IDE the next Cursor?
It seems there’s a market for IDEs.


Upvote
0

Downvote

10
Go to comments


Share
Share
u/MongoDB_ avatar
MongoDB_
•
Promoted

You don't need a separate database to start building gen AI-powered apps. All you need is MongoDB Atlas.
Learn More
mongodb.com
Thumbnail image: You don't need a separate database to start building gen AI-powered apps. All you need is MongoDB Atlas.
Join the conversation
Sort by:

Best

Search Comments
Expand comment search
Comments Section
ChatWindow
•
2h ago
Analyze Icon
Typically am a bit bearish when big tech makes a product like this tbh. Usually is mostly hype, with meh quality



Upvote
8

Downvote

Reply
reply

Award

Share
Share

_cofo_
OP
•
2h ago
Analyze Icon
It seems it will be a FireTv-like product. It will just, be there.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

jcl274
•
2h ago
Analyze Icon
bruh cursor 1.0 launched literally a month ago (June 2025). how has it been out long enough for there to be a “next” of it



Upvote
4

Downvote

Reply
reply

Award

Share
Share

EliSka93
•
2h ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
Hype cycles have to move fast.


Upvote
2

Downvote

Reply
reply

Award

Share
Share

_cofo_
OP
•
1h ago
Analyze Icon
In this AI war-race, 1 month is 1 year in normal launches.


Upvote
0

Downvote

Reply
reply

Award

Share
Share

ZGeekie
•
2h ago
Profile Badge for the Achievement Top 1% Poster Top 1% Poster
Analyze Icon
I don't know. The rule of thumb amid the AI race is: launch first, ask questions later!


Upvote
0

Downvote

Reply
reply

Award

Share
Share

AY-VE-PEA
•
2h ago
I coded this one time
Analyze Icon
Maybe, it’s slow to implement so far



Upvote
1

Downvote

Reply
reply

Award

Share
Share

_cofo_
OP
•
2h ago
Analyze Icon
They’re implementing it in-house. Hopefully it will be no aws db affected haha.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

u/pambolisal avatar
pambolisal
•
55m ago
Profile Badge for the Achievement Top 1% Commenter Top 1% Commenter
Analyze Icon
I've never heard of it.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

hikip-saas
•
47m ago
Analyze Icon
It’s great to have options. Trying it out is the best way to compare. If you need help with software or AWS for a project, feel free to send a DM.


Upvote
1

Downvote

Reply
reply

Award

Share
Share

Community Info Section
r/webdev
Join
webdev: reddit for web developers
A community dedicated to all things web development: both front-end and back-end. For more design-related questions, try /r/web_design.

Show more
Created Jan 25, 2009
Public
3.1M
Members
198
 Online
Top 1%
Rank by size 
User flair
u/Charlie0Simmon avatar
Charlie0Simmon
Community Bookmarks
Discord
Twitter
YouTube
FAQs
r/webdev Rules
1
No vague support questions about WYSIWYG editors or other software.
2
No memes, screenshots, and jokes
3
No self-promotion
4
No commercial promotions/solicitations
5
No soliciting feedback not on Saturday
6
Assistance Questions Guidelines
7
Career/Getting Started Questions
Showoff Saturdays
Work on something and want to share it? Showoff Saturdays are for you! Make a new post on Saturday and tag it [Showoff Saturday] and watch the views rise.

Sharing your project, portfolio, or any other content that you want to either show off or request feedback on is limited to Showoff Saturday. If you post such content on any other day, it will be removed.

Links
Discord server
Discord server
Twitter account
Twitter account
YouTube channel
YouTube channel
Related Communites
r/web_design icon
r/web_design
925,520 members
r/SaaS icon
r/SaaS
341,497 members
Moderators
Message Mods
u/snissn 
expert
u/julian88888888 
emoji:snoo_dealwithit: Moderator
Julian
u/aflashyrhetoric avatar
u/aflashyrhetoric 
front-end
u/so_much_reddit_T-T avatar
u/so_much_reddit_T-T 
emoji:snoo_dealwithit: Moderator
u/AutoModerator avatar
u/AutoModerator
u/CherryJimbo
James Ross
u/notcaffeinefree avatar
u/notcaffeinefree
u/duckballista
u/Gurgen 
emoji:snoo_dealwithit: Moderator
View all moderators
Reddit Rules
Privacy Policy
User Agreement
Accessibility
Reddit, Inc. © 2025. All rights reserved.

Collapse Navigation
解释