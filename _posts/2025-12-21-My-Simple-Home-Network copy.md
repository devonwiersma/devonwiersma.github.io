---
##################HIDDEN
hidden: true
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
      published: false
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true


title:  "My Simple Home Network"
---

### So it's no secret that
the internet (and the world at large) is becoming a pretty shit place, and arguably has been for a while.

Economies are slowly in a death knell as AI tries to invade every pocket of the world it doesn't need to be in, every subscription service on the planet has plateaued in profit and is [gradually decreasing its value](https://www.pcworld.com/article/2586837/amazon-prime-video-has-ads-now-heres-how-to-stop-them.html) while [increasing its prices](https://nerdist.com/article/every-streaming-cost-increase-in-2025/), and governments have started incorporating biometric data in security features - ostensibly as a means to 'protect children' - which actually endanger the privacy of basically everyone who is forced to use them.

I remember a few years ago I had a conversation with a friend who worked as a programmer on games in the mobile space for a long time. I asked him about what it was like making data-driven mobile games, and he told me the amount of data they collected on people - even just for playing a game on a phone - was insane.

Conversely I've also talked to people who work in games and tech - who should ostensibly know better than to trust tech - act surprised when I tell them I disable the collection of ad data on my mobile apps. What they've said stuck with me: "Well they're already collecting my data anyway, so **why bother**".

To be frank, I'm far from keen on the idea of just letting corporations do whatever they want with little parts of me - epecially not in an era where they're collecting your face data, photos, videos and the like to allow other people to generate content from. I also think "well they're doing it anyway why stop them" is perhaps the laziest and most defeatist approach to combatting capitalist overreach - if I can stop a multi-billion dollar corporation from knowing that I'm on the market for couch cushions then *I am going to*!

I'm now going to tell you about what I've learned you can do - and have done - to both protect your home network, as well as how you can improve your quality of life by re-using an old device.

Also note I just do this as a hobby and am bound to get small details wrong, so if you're a massive tech-head, sorry if this isn't 100% accurate. ;)

Also also note: this isn't me saying "go do illegal stuff online!!!", I'm simply outlining ways to make your business stay your business and keep it out of the hands of tech companies who don't need to be involved in your business. :)

I'll start with something that I think everyone - no matter what you do on the internet or how tech-savvy you are - should do.

### Turn Off Services You Don't Need
This one is easy - so much so that there's no point in not doing it.

Go to your device: phone, computer or whatever, and look in the options and account settings of apps you use. Anywhere you see it ask about data collection, or storing your information, or gathering your data or analytics info...just turn it off! Now do this on every device you own!

Location Services, for example, is my big one I always keep off. I don't need to allow my phone to collect location data from me all the time. There's...really no reason for this in a lot of cases, because unless you're doing something location-based, your phone doesn't need to know you're at home, or at work, or sitting in your backyard. THe only exception for me might be when I'm driving around or get lost somewhere, but generally I keep that off wherever possible.

And this is a great practice to keep going forward; whenever a device prompts you to allow it to access something, stop and ask yourself if it really **needs** it, or if you can just tell it no and be fine. It's understandable something like Google Maps would need to access location data, but does Instagram, Facebook or your phone's camera need that information? Not really!

They'll still find ways to gather info outside of this but in many cases this is a good, simple first line of defence you can do.

Coupled with the next step, it's very good too:

### USE A Virtual Private Network (VPN)
The first thing that felt like a no-brainer was setting our personal network up on a VPN.

A [VPN](https://en.wikipedia.org/wiki/Virtual_private_network) basically routes your internet traffic from a device through a privately-owned server and then to the provider. While it doesn't sound like much, this change can affect a lot of what you do online.

For example, you live in Calgary, Alberta and you click a link to enter a website. Google will use your internet's IP address and log that information. It might be used to send you targetted ads, or as demographic data for informing that site's owner where you live, or matching you with nearby services you don't want or aren't interested in. Ultimately Google (and the site owner) now know roughly where you live, and might choose to do something with that information.

It's not *necessarily* **implicitly** bad this is collected, but it can be used in malicious and annoying ways (and in the cases of tech companies, often is). For example, this is one of the first (and sometimes only) things that are checked when requiring you to Face ID to access a website - they will see if you're in a location that it's blocked in and will force you to ID to enter. In some countries, traffic to certain sites is even blocked completely, so you may not even be able to access certain websites you'd want to access. Even here in Canada, social media companies like Meta block news sites from being displayed to avoid having to pay as a result of the [Online News Act](https://en.wikipedia.org/wiki/Online_News_Act).

If your device is on a VPN - since you're routing through a different server in a different part of the world - you can functionally say "Actually no, I'm not a user in Calgary, I'm a user in Mexico City, Mexico". It will then process your traffic the same, but through a spoofed location that might afford regular privileges. In some cases it may even afford more protection, as some countries in places like Europe have even stronger protections for internet users.

VPNs can be installed on devices and turned on and off in an instant. Some have browser extensions that apply it only to your browser activity, while some apply to your entire computer. In the case of our own home VPN, I have it installed on our router so it actually applies by default to **every device that joins our home network**, which means visitors also have their data protected (at least for a time). It works on our phones, work PCs, laptops, and even our Internet of Things devices like our networked laundry machine, making it harder for our devices to leak our locations to the sites we use.

It's not foolproof however, and the added protection comes with a few potential risks:
- Some sites and services may still find ways around VPNs and use other methods of gathering data (such as your phone's location services) which is why it's important to turn them off too.
- Since VPN servers are shared, some servers may have been used by bad actors in the past, so some sites have blocked known VPN servers from accessing them. From my experience however, this is very infrequent (and honestly mostly applies to Reddit). It's easy to work around, as you just need to switch to a new VPN server (which takes like, ten seconds).
-  At the end of the day, a VPN company operating in a country may still need to answer to someone. There have been instances of VPN companies reporting use to local governments, though this is typically rare and depends a lot on an individual company's policies and processes, so researching a company helps mitigate this risk.

There are some public VPNs that allow you to use for free, however in my experience they're a little less reliable and may be likely to use your information themselves. Funny enough, one advantage to paying for a VPN service is that VPN companies generally have an interest in fighting to keep your information secure because *it's how they make money*!

A good place to start finding a VPN to sign up for yourself is looking into a VPN comparison chart to find a service you're comfortable with and in your price range. Something [like this](https://www.pcmag.com/picks/the-best-vpn-services) might help; I use [ProtonVPN](https://protonvpn.com), they have frequent deals and with pricing it comes out to just a few dollars a month. We've been on it for two years and haven't been disappointed with it yet.

### Anyway,




### Ok Bye!
<br>

<br>





