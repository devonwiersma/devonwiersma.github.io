---
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true

title:  "Arc Raider's AI Voices Are Just Bad Design"
---

### So recently I've been playing Arc Raiders.

All things considered, it's a pretty well-made video game that I think I enjoy - and that's saying something considering I **hate** PvP games.

I'm simultaneously too competitive for my own good, don't perform well under pressure, and hate gambling on things, which makes me a pretty bad combination of player to really enjoy a PvPvE extraction shooter where you basically bet your loadout on loot.

However, I enjoy the atmosphere and worldbuilding in the game and the emgernt social interactions of the gameplay. Given how anyone you meet in that game can freely turn around and shoot you in the back of the head when you're not looking, I've been pleasantly surprised at how kind and wholesome people have been while I wander around shooting robots and looking for scarce resources.

Sure a few people have murdered me in *cold blood*, but by and large everyone I've met on there have been pretty chill people who just want to have a fun time.

### But this isn't about that.

I actually held off on playing it for about a month or so because I heard there was some controversy about them using AI in the game. It doesn't help that [in an interview](https://automaton-media.com/en/news/its-important-to-assume-every-game-company-is-now-using-ai-nexon-ceo-comments-on-role-of-human-creativity-as-ai-tools-become-the-norm/) their C.E.O. reinforced their use of AI, claiming:

<blockquote>First of all, I think it’s important to assume that every game company is now using AI. But if everyone is working with the same or similar technologies, the real question becomes: how do you survive? I believe it’s important to choose a strategy that increases your competitiveness.</blockquote>

It is, of course, perhaps the most "C.E.O. of a game development studio" thing one can say given the current economic climate where investors are all looking at AI as being the money-maker.

But having now played a bit of the game I think it's terribly interesting just how **little** of the game screams "we needed AI to make this".

### I should preface this with a disclaimer

I am really not much of an Anti-AI Hardliner. I actually think there are many applicable uses of AI, and it's quite easy to come up with use cases for them that make workers more productive and don't run people out of jobs, destory their workflows, nor overwrite their creative intentions with absolute crap.

That said, I also believe in most every cases with how AI has forced its way into the forefront via giant datacenters destroying the environment, the enshittification of the internet, the undermining of people jobs...I think it all has less to do with AI as a tool, and has everything to do with how capitalism has chosen to wield it as an agent of maximizing profit at any cost.

I think the tool is probably useful in specific niches, but also completely destructive in the hands of people who want to wring profit out of the world by any means necessary.

With that being said...

### The AI use in Arc Raiders

is actually very subtle at times, and frankly can be easy to miss if you're not paying attention.

Nexon has claimed it's largely used in animation, which I think is pretty fair given how common techniques like procedural models are used for things like in-betweening in those types of pipelines.

However, I think the most obvious area they used voice acting was [apparently](https://www.pcgamesn.com/arc-raiders/generative-ai-use) in the generation of voices:

<blockquote>"As [you] stated, [it's] the same as The Finals, we use that text-to-speech model. That is, we hire and contract voice actors for it - it's part of their contract that we use it [AI] for this purpose, and that allows us to do things like our ping system, where it's capable of saying every single item name, every single location name, and compass directions. That's how we can get that without needing to have someone come in every time we create a new item for the game."</blockquote>

(Now, I will say that I suspect they generated voices for more than just these lines as a **lot** of the dialog in the game's cutscenes and interstitial moments feel incredibly robotic and lifeless, but I'm going to focus primarily on the pinging system here.)

At a glance I thought the explanation made sense - at least at first. If you can just generate the audio for an item in the game it certainly makes it easier and more agile to be able to implement new ones. Rather than requiring voice actors to record a line for each object, you can get those lines faster and, to that end, get them in the game with less work. Ostensibly, this was in the contract the voice actors signed, so they did so knowing their voices would be used to this end.

However, what I soon realized is that the workflow they're describing - from a design standpoint - hardly feels like a mark of *efficiency*, but rather one of *inefficency*.

### It all falls apart

when you look at how this feature actually plays out in the game:
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/OXt1JTGTUA4?si=YVuDZHUziQWzGW4d&amp;start=203" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

It's undeniably a silly novelty to hear your character say goofy things like "I have a *prickly pear*" or "I have a *comfy pillow*".

But...on a design level, AI use here is solving a scalability problem that most games of like genre *don't* have, because they simply **design solutions for it**. In fact, the way Arc Raiders uses AI is in some ways creating *more* work that other studios don't even have to do in the first place!

When I think of a ping system from other online games, it's bog standard to have a character simply say something to the effect of "*Look at this*!" with some text of the object on screen, or even have item text just pop up in the world chat if you really need to call an object out in your inventory.

MMOs have solved this problem years ago by simply having a text pop-up to display the item (and frankly there's no reason to believe Arc Raiders doesn't have a console of some kind built into its engine):

<img src="/assets/images/GuildWars2ItemLink_01.jpg" alt="An image from Guild Wars 2 in chat, showing items and locations being displayed in text" style="width:700px;height:300px; border: 5px solid #ffffff; float:center; margin: 25px">

Even a similar Game as a Service title Fortnite designed around this issue by just...making an icon representing the object pop-up in the world!
<img src="/assets/images/FortnitePing.jpg" alt="An image from fortnite showing an item being pinged" style="width:500px;height:300px; border: 5px solid #ffffff; float:center; margin: 25px">

After all, the point of a ping system is typically to simply make point a user aware of something for a brief moment - it doesn't need to 100% inform them of the name of the name of the subject in question via in-world dialog; they player will see what it is on their own while playing intuitively.

So in this case, Arc Raiders seems to have overcomplicated their design around item pinging by having the item be read aloud, and then used AI to solve the problem they had engineered themselves.

### This begs the question...

does this really *feel* easier to design it this way?

This sort of system in any other production would be "let's keep these voice actors around for callbacks", which is...so, so far from being a monumental task. It's literally "oh we need to make callouts for the new enemy/item we added. Let's call Susan and get her in here next week to say 'I have a prickly pear'". It's not *really* that big an issue if you already have voice actors and an audio team on your payroll.

Which they certainly must have, because even with an AI voice someone still hase to generate it, implement it, QC it, and so on. It's all work someone has to do and get paid for anyway (work which is also error prone as you're left re-generating files to get better takes). You're saving what is almost imperceptible levels of time and effort just to avoid paying a voice actor.

I've seen all sorts of arguments - unsurprisingly from fans of the game - saying various things like "well Embark is a small studio!" or "it's a cost-saving measure!".

I think it's also fair to say that voice actors really **aren't** that expensive to work with. In fact, most of the effort is getting them on the project in the first place - but generally things like pickups and the like are trivial once you have them integrated into the pipeline (which, again, they had to do in order to create models from their voices in the first place).

And according to [Wikipedia](https://en.wikipedia.org/wiki/Embark_Studios), Embark Studios has approximately 350 employees. That's *not* a small studio by any stretch of the imagination! Nor do I think it's reasonable to claim that a studio which already hired a suite of voice actors to record voices for their game doesn't have the money to continue paying them, especially after releasing **two** Live Service online multiplayer titles in the span of just a year (the other being [The Finals](https://en.wikipedia.org/wiki/The_Finals)).

And - again to emphasize - they *already did the work of seeking, signing and paying voice actors to get into the booths and create voice models out of them*! If they wanted to save money, I imagine they would have instead simply designed a system in a way that was more accomodating for scale.

These scalability issues are not problems that are unique to a game like Arc Raiders, nor are they problems that remain unsolved by the wider industry at large.

### So what I'm feeling here
is that I think this is - unsurprisingly - a whole lot of excuses to find use of AI in a place it *really doesn't* need to be. It feels like a case of someone up top saying "we should put AI in this", and the designers enacting that demand.

And we're seeing a lot of weird, useless direct integrations of AI in games these days - probably as a result of the market bubble being built as companies buy into the hype and fight to find exuses to adopt it into their workflow. I'm sure by simply saying "*we've integrated AI in our game :]*" serves Nexon a useful talking point to investors seeking to capitalize on the AI trend while it's still hot.

While I think this is far from the most egregious use of AI, it just feels so obvious to me that a decision like this speaks largely to a design failure that also undercut voice actors, rather than any kind of innovative application of a tech already desperately struggling to find a useful place in games. 🤷

<br>

<br>





