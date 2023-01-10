---
layout: posts
title: "Put the Title Right Here"
number: 94
permalink: EDT94
has_children: false
parent: Episodes
nav_order: 94
tags:
    - EDT111
    - EmbracingDigital

date: 
guests:
    - Darren W Pulsipher

img: TBD
summary: "Summary"
---

{% include soundcloud.html id="edt94" title="#94 Put the Title Right Here" %}

{% include youtube.html id="url" %}

---

# Title

*Tagline*

Summary here

![episode image](./thumbnail.png)

Epsiode Body here.

## Media

<video src='url'></video>


<details>
<summary> Podcast Transcript </summary>

<p>﻿1</p>
<p>Hello, this</p>
<p>is Darren Pulsipher, chief solution</p>
<p>architect of public sector at Intel.</p>
<p>And welcome to Embracing.</p>
<p>Digital Transformation,</p>
<p>where we investigate effective</p>
<p>change, leveraging people.</p>
<p>Process and technology.</p>
<p>On today's episode, The Rebirth</p>
<p>of the Private Cloud with CTO of Verge.io.</p>
<p>Greg Campbell.</p>
<p>Craig, welcome to the show.</p>
<p>Thank you, Darren Good to be here.</p>
<p>We had an opportunity to talk</p>
<p>about a month ago is when we first talked.</p>
<p>I was enamored with with your team</p>
<p>and what you've done.</p>
<p>Greg tell my audience</p>
<p>a little bit about yourself</p>
<p>and why you are where you are.</p>
<p>Sure.</p>
<p>So I'm a I've been developing software</p>
<p>since I was a kid.</p>
<p>And the Commodore 64 days and.</p>
<p>Oh yeah, never stopped coding.</p>
<p>It was a daily thing. Since then</p>
<p>worked a lot of different</p>
<p>projects from, you know, 3D</p>
<p>gaming engines to communications database</p>
<p>engines and web servers and encryption</p>
<p>and all sorts of different things.</p>
<p>I was working in some write in public</p>
<p>safety software</p>
<p>and I rode one in computer,</p>
<p>aided dispatch,</p>
<p>then broke off and started my own company.</p>
<p>And it was I wrote some interoperable</p>
<p>communication software.</p>
<p>So can solving some of the problems</p>
<p>that were exposed during 911 where police</p>
<p>can't talk to fire, can't talk to you,</p>
<p>everyone is different radio</p>
<p>systems, different communication methods</p>
<p>and none of them can talk to each other.</p>
<p>So I came up with a software</p>
<p>and hardware solution to solve</p>
<p>that problem and built that company up</p>
<p>and the head of successful exit with that.</p>
<p>And after that, I worked for the company,</p>
<p>the Boss, for a couple of years</p>
<p>and did some other things with them,</p>
<p>parking systems and fire truck systems.</p>
<p>And, and then I started another company</p>
<p>after that</p>
<p>with the goal of building</p>
<p>a vertical search engine from scratch.</p>
<p>And so this was probably 2008 ish.</p>
<p>And when it started that one and</p>
<p>it was it was a really interesting project</p>
<p>because, you know,</p>
<p>I go into this thinking,</p>
<p>you know, the search engine</p>
<p>and the algorithms and the</p>
<p>and all that's going to be the hard part.</p>
<p>Right.</p>
<p>And it ended up 80%</p>
<p>of my time was spent with everything.</p>
<p>Other than that.</p>
<p>It was</p>
<p>it was really this infrastructure problem.</p>
<p>And, you know, it's you know,</p>
<p>you got billions and billions of records</p>
<p>that you need to search,</p>
<p>you know, to get millions of results,</p>
<p>thousands and simultaneously each</p>
<p>get coming back in a quarter millisecond.</p>
<p>And, you know, you can't buy a big enough</p>
<p>server to do that.</p>
<p>So you need lots of servers.</p>
<p>And I kind of found myself back</p>
<p>looking at, you know,</p>
<p>think of your PC days and and what</p>
<p>the hardware abstraction layer</p>
<p>did to development, you know,</p>
<p>and it was kind of like,</p>
<p>you know, we're missing that here.</p>
<p>I'm finding</p>
<p>too much of my code is very specific</p>
<p>to do the hardware together.</p>
<p>And and, you know, there really needs</p>
<p>to be some form of abstraction.</p>
<p>Right.</p>
<p>And so, again,</p>
<p>instead of giving some of the base ideas</p>
<p>and, you know, I spent so much time</p>
<p>building, stitching, storage together</p>
<p>and, you know, to</p>
<p>the traditional span and the</p>
<p>purchase at that time, just</p>
<p>it doesn't work well in this sort of,</p>
<p>you know, applications, large scale thing.</p>
<p>And and at the time and, you know, Google</p>
<p>or anybody else had been doing this,</p>
<p>a lot of that stuff is very proprietary.</p>
<p>There's just</p>
<p>there weren't a lot of good tools.</p>
<p>So they gave the idea for</p>
<p>at the time what became the right.</p>
<p>So started a company out of right</p>
<p>and really started off</p>
<p>focusing on the storage problem,</p>
<p>being able to just take a bunch of</p>
<p>inexpensive drives, throw them</p>
<p>in some chassis, stitching together bits,</p>
<p>but really with the goal</p>
<p>of presenting it all as one thing.</p>
<p>So I can,</p>
<p>I can write software to this one thing</p>
<p>and not worry about what was underneath</p>
<p>the hood.</p>
<p>And I had this vision of expanding</p>
<p>upon past that to include</p>
<p>computing, memory and networking</p>
<p>and kind of all of that.</p>
<p>And that kind of gave birth to the device,</p>
<p>which more recently became Virgil.</p>
<p>So it's really interesting</p>
<p>because I got a demo of</p>
<p>You Ought to Buy It back in 2009</p>
<p>I think at supercomputing.</p>
<p>Yeah.</p>
<p>And I was blown away</p>
<p>with your architecture and I thought,</p>
<p>hey, this is a company to, to, to look at,</p>
<p>especially in the high performance</p>
<p>computing realm</p>
<p>where data was just joint and everything.</p>
<p>And you guys had a,</p>
<p>a way of addressing a Yahoo!</p>
<p>Bite of data.</p>
<p>I mean, no one was doing that</p>
<p>at that time.</p>
<p>It was I was just like blown away.</p>
<p>And then, you know,</p>
<p>I find you guys as Virgil.</p>
<p>Oh, you're still around. It's awesome.</p>
<p>Yeah, yeah, yeah.</p>
<p>The company name was the Idevice.</p>
<p>So it, you know, when I was architecting</p>
<p>the design for, I'm like, well,</p>
<p>it has to be able to address</p>
<p>a array of storage, otherwise</p>
<p>we can't be called that. Yeah.</p>
<p>No. What I found</p>
<p>compelling with, with, with you guys is</p>
<p>you extended</p>
<p>beyond the software defined storage.</p>
<p>And you frankly,</p>
<p>you guys were one of the first ones</p>
<p>that did software defined storage.</p>
<p>No one was even talking about it</p>
<p>back in that time.</p>
<p>And you guys really kind</p>
<p>of blazed the way for that.</p>
<p>And you see other people</p>
<p>that have done software defined storage</p>
<p>now, but back in that day,</p>
<p>I mean, no one was talking about it.</p>
<p>But you found really quickly that you also</p>
<p>needed compute and network as well.</p>
<p>You couldn't just do one.</p>
<p>One of the pillars of software</p>
<p>defined infrastructure.</p>
<p>Right.</p>
<p>And really the key here is that,</p>
<p>you know, even even today,</p>
<p>when when people are solving</p>
<p>these problems, it's</p>
<p>they're still taking a bunch of things</p>
<p>and trying to stitch them together,</p>
<p>make them work together.</p>
<p>Right.</p>
<p>And so it's millions of lines of code</p>
<p>across all sorts of different</p>
<p>components that</p>
<p>that weren't necessarily designed</p>
<p>to do what they are now.</p>
<p>They're more general purpose components</p>
<p>that were, you know, like Lego boxes</p>
<p>and trying to figure it all together here.</p>
<p>And, you know, when I designed the storage</p>
<p>layer, it it was built</p>
<p>for this purpose.</p>
<p>I brought,</p>
<p>you know, file system from scratch.</p>
<p>We wrote,</p>
<p>I mean, to pull this off, we actually</p>
<p>we designed our own programing language.</p>
<p>We wrote our own database</p>
<p>engines from scratch.</p>
<p>We have our own web servers from scratch.</p>
<p>We have our own</p>
<p>mesh network networking fabric</p>
<p>to connect things together.</p>
<p>We went into the development of this</p>
<p>with the golden rule</p>
<p>that hardware is going to fail.</p>
<p>And, you know,</p>
<p>and we have to expect the worst of it.</p>
<p>And, you know, we're not tying it in</p>
<p>any specific piece of hardware</p>
<p>so that</p>
<p>the software needs to do everything.</p>
<p>And we've</p>
<p>we've you know, a lot of the development</p>
<p>was just going through all the different</p>
<p>spectacular ways that that hardware can</p>
<p>fail from, you know, bad firmware update.</p>
<p>Well, as a hardware vendor,</p>
<p>hardware never fails.</p>
<p>I don't know what you're talking about,</p>
<p>Greg.</p>
<p>Hardware spending drives,</p>
<p>they never go out.</p>
<p>So, you know,</p>
<p>so simplicity was really the key.</p>
<p>It was I. Like that.</p>
<p>Going down to the lowest level of building</p>
<p>just what we need just for this</p>
<p>purpose of good with, you know,</p>
<p>and our ultimate goal was to build virtual</p>
<p>virtualized the entire data center.</p>
<p>So it's not just a bunch of pieces</p>
<p>that stitch together</p>
<p>to make a singular private cloud.</p>
<p>It was you know, we were looking at</p>
<p>much the same way</p>
<p>you go into VMware and Head Start,</p>
<p>you run AVM.</p>
<p>We wanted to be able to go</p>
<p>in, assign resources, hit start</p>
<p>and a virtual data downstairs.</p>
<p>I was right there when OpenStack started,</p>
<p>which was a big group of private or</p>
<p>open source</p>
<p>projects, just crammed together</p>
<p>and said,</p>
<p>All right guys, make it all look like one.</p>
<p>And all I did was put lipstick on it.</p>
<p>Basically they just put a nice</p>
<p>UI on the front end, but on the back end</p>
<p>it was a bear to stand up.</p>
<p>It was.</p>
<p>And yeah.</p>
<p>And VMware is the same way, right?</p>
<p>It grew over time</p>
<p>where they were stitching</p>
<p>individual products together.</p>
<p>So your your approach was top down</p>
<p>virtualized full data center, not</p>
<p>just a hypervisor, not just</p>
<p>storage, not just network,</p>
<p>but the whole thing together.</p>
<p>Absolutely.</p>
<p>Yeah.</p>
<p>It's it's one thing to</p>
<p>to present a simplified user interface,</p>
<p>a simplified user experience,</p>
<p>which is what we see.</p>
<p>But if if everything underneath</p>
<p>that is not simple,</p>
<p>you're going to have a problem.</p>
<p>It might work when everything is perfect,</p>
<p>but as soon as</p>
<p>the world starts to fall apart,</p>
<p>it will power failure.</p>
<p>You've got a hardware failure.</p>
<p>You've got it.</p>
<p>You know, one key component got updated</p>
<p>when a different one didn't get updated.</p>
<p>I mean, there's all sorts of things</p>
<p>that that happened.</p>
<p>And even outside of the reliability</p>
<p>aspect, you</p>
<p>there's countless security issues</p>
<p>that can come into play</p>
<p>when you have all these different things</p>
<p>that weren't necessarily</p>
<p>designed to be together</p>
<p>and then you interface them together.</p>
<p>You know, I like to, you know,</p>
<p>look at it like like a house versus</p>
<p>a neighborhood or a city.</p>
<p>And it's, you know, if everything's</p>
<p>in the same house, I don't need</p>
<p>as many windows and doors and, you know,</p>
<p>entry points.</p>
<p>Right.</p>
<p>And this was all built from the ground up</p>
<p>for this purpose.</p>
<p>It's simple.</p>
<p>At the lowest level, you know,</p>
<p>which means, you know,</p>
<p>less security issues,</p>
<p>seamless updates and upgrades.</p>
<p>I mean, we would treat it like a firmware.</p>
<p>It's it's very, very lightweight,</p>
<p>you know, and</p>
<p>it's in it does a lot for,</p>
<p>you know, the reliability aspects,</p>
<p>especially, again, you know, with us,</p>
<p>you go on the road</p>
<p>assuming everything's going to fail</p>
<p>and the software</p>
<p>needs to take care of everything.</p>
<p>But it's it's a it's a huge difference,</p>
<p>you know, from</p>
<p>from a supporting aspect</p>
<p>and and even just the management aspect.</p>
<p>So our our goal has always been that,</p>
<p>you know, the target</p>
<p>users of this system are it generalist.</p>
<p>We don't need network experts,</p>
<p>we don't need sand experts.</p>
<p>We don't need programmers,</p>
<p>you know, to operate this.</p>
<p>It's an IP generalist.</p>
<p>And and we agreed we succeeded at that.</p>
<p>So I have a question around that.</p>
<p>I mean, most people listening to the show</p>
<p>are moving to public cloud.</p>
<p>So why why would I even do a private cloud</p>
<p>with you guys over public cloud?</p>
<p>What are the benefits that you guys see</p>
<p>with a private cloud over a public cloud?</p>
<p>Yeah,</p>
<p>there's there's a lot of lot of scenarios.</p>
<p>I'm not going to say</p>
<p>that you should never go to public cloud</p>
<p>is never a use case for that</p>
<p>they're actually is.</p>
<p>But I think what we've seen</p>
<p>is that a lot of</p>
<p>people moved to the public cloud,</p>
<p>maybe for the wrong reasons.</p>
<p>You know, it's they saw that simplicity.</p>
<p>And a lot of the moves happened</p>
<p>because of developers and developers,</p>
<p>you know, getting along with i.t and yeah.</p>
<p>Shadow i.t. Right.</p>
<p>Yeah.</p>
<p>You go through all the red tape</p>
<p>and hurdles and it's like, well,</p>
<p>wait a minute, I could just pop in a year</p>
<p>and I don't need a 90 staff</p>
<p>and it didn't just work</p>
<p>and I can manage it myself.</p>
<p>And that was kind of the wrong reason</p>
<p>to go to the public cloud.</p>
<p>And because at the time the management</p>
<p>and just the stitching together,</p>
<p>the complexity made it too big of a deal.</p>
<p>If I needed more resources, I go to I.T.</p>
<p>and it's like I</p>
<p>wait 16, 20 months for them to</p>
<p>come in</p>
<p>and I go, so, you know,</p>
<p>we are presenting it in such</p>
<p>we're giving you that same experience</p>
<p>that you might get from a public cloud.</p>
<p>In that simplicity, the self-service, the,</p>
<p>you know, the agility.</p>
<p>So I can now go to it and say, hey,</p>
<p>I need an environment.</p>
<p>And within seconds,</p>
<p>you know, here's your resources. Go.</p>
<p>And then either I can manage that</p>
<p>or they can hand me the keys and say, Here</p>
<p>you go, here's</p>
<p>your private, secure enclave.</p>
<p>Do whatever you want with it.</p>
<p>Self management you want to keep asking</p>
<p>to retain my new VM.</p>
<p>I restrain your resources,</p>
<p>do what you want</p>
<p>and and then I'm not paying</p>
<p>I'm not being nickel dimed on</p>
<p>every little piece of when I'm operating.</p>
<p>I'm not paying per eye app anymore.</p>
<p>I'm not paying for egress and</p>
<p>and everything else,</p>
<p>you know.</p>
<p>So there's a huge cost benefit there.</p>
<p>There's also,</p>
<p>you know, a data gravity problem as well.</p>
<p>You know, a lot of people,</p>
<p>if you move a lot to the cloud</p>
<p>and then you realize how much more</p>
<p>now you're relying on networks</p>
<p>and just where is my data stored versus</p>
<p>where I need it, you know?</p>
<p>So having a private cloud, you know,</p>
<p>it keeps things</p>
<p>closer to where</p>
<p>the data is being generated.</p>
<p>I think, you know, we throughout</p>
<p>computing time, if we see a lot of this</p>
<p>this ebb and flow from,</p>
<p>you know, client server models</p>
<p>to, you know,</p>
<p>back to sick and,</p>
<p>you know,</p>
<p>the pendulum has swung keeps swinging.</p>
<p>Right.</p>
<p>And I think, you know, we're generating</p>
<p>so much data</p>
<p>in general across the board at the edge</p>
<p>that we're going to start</p>
<p>to see a lot more.</p>
<p>That needs to be closer to where</p>
<p>where the data is being generated</p>
<p>in the cloud is not necessarily</p>
<p>the best place for that.</p>
<p>You know, there's only so fast we can go.</p>
<p>Physics can only allow things to go</p>
<p>so quick.</p>
<p>So if we can get that same agility,</p>
<p>security, everything,</p>
<p>all the benefits</p>
<p>that you see, all the public cloud,</p>
<p>but we can allow you to run that,</p>
<p>operate it at the edge and not have to</p>
<p>hire a team of fees to operate it.</p>
<p>You know,</p>
<p>we believe that that's a huge benefit.</p>
<p>All right.</p>
<p>So so the reason people moved</p>
<p>was ease of use, mostly developers.</p>
<p>I was I was totally guilty of that myself.</p>
<p>Right. Credit card.</p>
<p>I can spin up 10,000. Easy.</p>
<p>It's easy.</p>
<p>So what?</p>
<p>So you've you've tackled the easy part,</p>
<p>right?</p>
<p>I could do it on the other one</p>
<p>that you mentioned was cost.</p>
<p>Now a lot of people will say, well, look,</p>
<p>I am a no CapEx cost at the beginning</p>
<p>of when I use the cloud, right?</p>
<p>I can spin up a thousand instances</p>
<p>and it's only going to cost me</p>
<p>$10 for an hour.</p>
<p>I can't I can't have a thousand boxes</p>
<p>sitting in my datacenter</p>
<p>right at that cost.</p>
<p>But the cost is exorbitant over time.</p>
<p>And you mentioned egress.</p>
<p>This is a big, huge problem</p>
<p>that a lot of my customers run into.</p>
<p>They're like, I had no idea</p>
<p>egress costs was going to just kill me.</p>
<p>Right.</p>
<p>And it ingress is free,</p>
<p>right?</p>
<p>You bring your data to me, right?</p>
<p>Bring it on.</p>
<p>So you guys kind of you can handle that</p>
<p>because you can stitch together</p>
<p>lots of data sources together up to a Yoda</p>
<p>by the data.</p>
<p>I'm just mind blowing still. But</p>
<p>so yeah.</p>
<p>So the cost is, is,</p>
<p>is that why you're seeing people come back</p>
<p>from public cloud back to private?</p>
<p>The cost</p>
<p>the cost is absolutely a big component.</p>
<p>I think, you know, same same</p>
<p>your opening a credit card at 50</p>
<p>bucks a month,</p>
<p>you don't think too much of it.</p>
<p>And then all of a sudden,</p>
<p>you know, things start to scale out.</p>
<p>You go to production</p>
<p>and all those little costs that added up</p>
<p>to a little before are now,</p>
<p>you know, they're harder to predict.</p>
<p>And it's very, very easy for those costs</p>
<p>to get out of hand.</p>
<p>And at that point,</p>
<p>you're also kind of stuck.</p>
<p>I mean, the more you get pulled in</p>
<p>to an ecosystem, it's</p>
<p>that much harder to get out.</p>
<p>You kind of hold them at that point,</p>
<p>you know, and you're</p>
<p>giving up a lot of control as well.</p>
<p>I mean, you know,</p>
<p>unless you're a huge company, you know,</p>
<p>you have a problem or something,</p>
<p>something is going on in that environment.</p>
<p>I mean, you can call, but</p>
<p>you kind of just you got to wait.</p>
<p>You know, there's not too much you can do.</p>
<p>You have a lot of control over,</p>
<p>you know, issues that might pop up.</p>
<p>And there's there's</p>
<p>there's a lot more options.</p>
<p>Now, I think that people don't realize</p>
<p>it's not it's not just about,</p>
<p>you know, hey, I got to go buy,</p>
<p>you know, make it this large cap ex,</p>
<p>you know, it's expenditure</p>
<p>to build out a data center with AC units.</p>
<p>And yes, that's an option.</p>
<p>And for a lot of people, that makes sense</p>
<p>if you have enough volume.</p>
<p>But there is other alternatives as well.</p>
<p>I mean, you know, it's</p>
<p>you can go and get rents out bare</p>
<p>metal servers, for example, and still say,</p>
<p>I don't want to deal with hardware.</p>
<p>I don't want to swap drives,</p>
<p>I don't want to do any of that.</p>
<p>You go rent out bare</p>
<p>metal hardware for a fraction of the cost</p>
<p>of what a public cloud</p>
<p>might get to throw our software on it.</p>
<p>And now you have a</p>
<p>you have to have a build your own,</p>
<p>you know.</p>
<p>Right. And it's to whatever scale.</p>
<p>Ep and Flow Scale out, scale up, scale down.</p>
<p>And it works in</p>
<p>a, in a wide variety of commodity hardware.</p>
<p>So very, very important.</p>
<p>When you guys are out there</p>
<p>selling your solution,</p>
<p>what's the big hook? What are people like?</p>
<p>Hey, I need your stuff</p>
<p>because what's what's their concern?</p>
<p>What problem are you solving</p>
<p>that, that they migrate to you guys?</p>
<p>So there's yeah, there's a couple,</p>
<p>a couple of angles, you know, one,</p>
<p>we have a lot of service providers</p>
<p>that, you know, they're</p>
<p>they have a customer base that they need</p>
<p>to manage their workloads for them.</p>
<p>They traditional only</p>
<p>where they used to do it</p>
<p>the old way they would you know</p>
<p>get co-location space filled out you know,</p>
<p>sans and virtualization of the allows</p>
<p>i.t staff to manage them and run them.</p>
<p>Then they started to see the public cloud</p>
<p>erode some of that,</p>
<p>some of their customers moving</p>
<p>their others having to try to embrace it</p>
<p>and say, okay, we'll put you there too.</p>
<p>But then, you know, they give up a ton of</p>
<p>margin as well when they want to do that.</p>
<p>So we're able to go to them and say, hey,</p>
<p>now we can</p>
<p>we can give you the similar experience</p>
<p>that they were going to get.</p>
<p>You get the same ease of of what</p>
<p>it would have been managing in public.</p>
<p>I don't have to do a deal</p>
<p>with what you were doing before.</p>
<p>I imagine that it's just as easy,</p>
<p>it's more powerful,</p>
<p>and you get to make more money.</p>
<p>Right.</p>
<p>So that's that's one,</p>
<p>you know, subset of the people that that,</p>
<p>you know, deployed</p>
<p>as we're also seeing some use cases</p>
<p>that that are just very difficult</p>
<p>to even do with other software.</p>
<p>And so our our nested tenancy model</p>
<p>and what we do on the</p>
<p>storage for deduplication and</p>
<p>it's at the lowest levels of</p>
<p>a file system enables</p>
<p>you to do some really cool stuff.</p>
<p>So one of these cases,</p>
<p>for example, University of Michigan</p>
<p>is a very large customer of ours.</p>
<p>They have a very large on prem deployment,</p>
<p>you know, thousands</p>
<p>of cores, petabytes of data running.</p>
<p>And they do a lot of research</p>
<p>projects off of this.</p>
<p>So this was a scenario where, you know,</p>
<p>when we take this off,</p>
<p>they came to us, hey,</p>
<p>we got thousands of researchers.</p>
<p>They get a they get grant money.</p>
<p>They need an environment.</p>
<p>It needs to be, you know, hyper compliant</p>
<p>or full C UI compliant.</p>
<p>C every time they ask for</p>
<p>this, it's 6 to 9 months</p>
<p>to get hardware deployed, install it,</p>
<p>certify it, go through the whole process.</p>
<p>Right?</p>
<p>And what we were able to do is go in there</p>
<p>and build out this environment</p>
<p>and now anytime</p>
<p>somebody wants an environment,</p>
<p>they hit a button, it creates</p>
<p>a virtual enclave, they hand it to them.</p>
<p>It's already compliant,</p>
<p>full certification, ready to go.</p>
<p>And within minutes</p>
<p>they're they're up and running. Now,</p>
<p>these are all</p>
<p>completely encapsulated in isolated,</p>
<p>a very, very secure enclave.</p>
<p>And you can get this</p>
<p>this nested tenancy model.</p>
<p>So in a larger organization like that,</p>
<p>I can say,</p>
<p>all right, here's</p>
<p>what I'm going to carve out resources.</p>
<p>You're getting.</p>
<p>They allocate hardware to specific groups.</p>
<p>Yeah, I've seen that.</p>
<p>And then I. Yeah.</p>
<p>Headed to the hospital</p>
<p>now they could have their own i.t staff</p>
<p>managing that environment and carving up</p>
<p>and say, okay, here's this research</p>
<p>or here's test versus dev versus,</p>
<p>you know, production.</p>
<p>I could then say in with our snapshot.</p>
<p>And so we're not just looking at storage.</p>
<p>This isn't just snapshots of your VMs,</p>
<p>it's all of your networking,</p>
<p>all your user management here,</p>
<p>because we manage the entire stack,</p>
<p>you literally can take our software,</p>
<p>put it in bare metal, plug your carriers,</p>
<p>and we run everything</p>
<p>BGP, the 32 DNS,</p>
<p>all your firewall and rails you're.</p>
<p>So this is really interesting</p>
<p>because you mention I'm snapshot</p>
<p>in my data center</p>
<p>I'm a snapshot of a VM or set of VMs.</p>
<p>So this is really interesting</p>
<p>because what this</p>
<p>I my brain is like going, wait, I could do</p>
<p>a lot of really interesting things.</p>
<p>Like you mentioned, I have a, a snapshot,</p>
<p>a data center that's HIPA compliant. Wow.</p>
<p>Right.</p>
<p>Drop a new one in. I'm done. Right.</p>
<p>Or I need a snapshot</p>
<p>of my running environment.</p>
<p>I have a business continuity and disaster</p>
<p>recovery built in.</p>
<p>Is that right?</p>
<p>Absolutely. Absolutely.</p>
<p>And it's and it's this snapshot</p>
<p>of an encapsulated virtual representation,</p>
<p>meaning I can now pick this up,</p>
<p>move it over to a completely different</p>
<p>hardware architecture, different switches,</p>
<p>different every different.</p>
<p>Doesn't matter what the. Hardware.</p>
<p>And it's still going to work exactly</p>
<p>the way it did when it was over there,</p>
<p>which, you know, has been done.</p>
<p>It means,</p>
<p>hey, we got this issue in production,</p>
<p>okay, well, instead of having to try to</p>
<p>reproduce it, you know. Just snapshot.</p>
<p>In order.</p>
<p>Yeah, it's just boom, fired up now is the</p>
<p>exact isolated version of production.</p>
<p>Or, you know,</p>
<p>you get ransomware, it goes through it.</p>
<p>It's like</p>
<p>Yeah there</p>
<p>there's so many applications by.</p>
<p>Our, you know, snapshot someday.</p>
<p>Yeah, not now.</p>
<p>I mean, that's a that's a good question.</p>
<p>You said our by our snapshots,</p>
<p>I mean, how big are these snapshots?</p>
<p>How much</p>
<p>space are these taking up?</p>
<p>There's purely the differentials</p>
<p>the way our files.</p>
<p>Oh, so you're</p>
<p>you only snapshot in the differences.</p>
<p>Yeah. And there's more to it than that.</p>
<p>So the, the engine under the hood,</p>
<p>this is not deduplication</p>
<p>added on to an existing file system,</p>
<p>which is the kind of thing</p>
<p>you see out there or even snapshots</p>
<p>a lot of times are, you know,</p>
<p>there's some file systems that might have</p>
<p>some snapshots built into them.</p>
<p>But we are we're not only taking</p>
<p>a lot of snapshots, it's</p>
<p>you're you're looking up the</p>
<p>differentials in the data,</p>
<p>but there's still metadata.</p>
<p>And a lot of times, you know,</p>
<p>even if I want to take a snapshot</p>
<p>or take a clone</p>
<p>or a copy of an environment,</p>
<p>it's still tapping out the meta data</p>
<p>and meta tables that went with that.</p>
<p>So there's still a little bit of time</p>
<p>to restore or do whatever</p>
<p>and extra data that you're using.</p>
<p>Well, our deduplication is built</p>
<p>at such a low level that even the metadata</p>
<p>is duplicated, which means I can take</p>
<p>a snapshot of this entire environment.</p>
<p>I don't care if it's ten petabytes,</p>
<p>I can make a clone copy of it</p>
<p>in under 30 milliseconds.</p>
<p>That's how I. Have it done.</p>
<p>And the differentials for that now are</p>
<p>are truly only</p>
<p>what has actually changed between the two.</p>
<p>So I can</p>
<p>I could take this graininess or I want,</p>
<p>you know, it doesn't have to be hourly.</p>
<p>And not only are we doing that</p>
<p>at the local spec, local cluster level,</p>
<p>but we also have a global it's globally</p>
<p>if you do aware.</p>
<p>So if now if I'm taking it</p>
<p>and synchronizing it to another location,</p>
<p>it's utilizing that same engine</p>
<p>to get those differentials.</p>
<p>So even,</p>
<p>you know, a lot of even replication</p>
<p>services still have to walk the meter</p>
<p>to say what has changed</p>
<p>from from A to B and,</p>
<p>you know, for small files, not a big deal.</p>
<p>But when you're dealing</p>
<p>with hundreds of terabytes,</p>
<p>you know that the metadata alone</p>
<p>and still the expansive data</p>
<p>that have to go across just to do that,</p>
<p>whereas we could I could replicate</p>
<p>an entire environment in seconds</p>
<p>petabytes, you know.</p>
<p>So I changed.</p>
<p>That.</p>
<p>You guys created a virtual cloud.</p>
<p>Yeah, you have to, right?</p>
<p>I mean, when you think about it, right?</p>
<p>Because you're telling me</p>
<p>that my data center, my which it's,</p>
<p>you know, whatever you want to call it,</p>
<p>my data center now can migrate around.</p>
<p>They can go in a public cloud,</p>
<p>stay on a private cloud.</p>
<p>I can even drop it, you know,</p>
<p>into a co-located co-location center.</p>
<p>So this gives me as a as a business owner,</p>
<p>a lot more flexibility</p>
<p>in negotiating price</p>
<p>and performance of hardware.</p>
<p>I can upgrade hardware with with virtually</p>
<p>no downtime.</p>
<p>I mean.</p>
<p>Yeah, absolutely.</p>
<p>Yeah, it's meant.</p>
<p>To be because I can stand up a new rack.</p>
<p>I yeah.</p>
<p>Yeah I'll provide everything zip in line.</p>
<p>I mean, the system never shuts down.</p>
<p>I mean, you could even go through</p>
<p>your entire hardware refresh</p>
<p>cycles and never have downtime.</p>
<p>That's yeah.</p>
<p>Yeah, absolutely.</p>
<p>And, and</p>
<p>because the software is so lightweight,</p>
<p>it would just</p>
<p>it's scaled up and down equally.</p>
<p>So you could scale up</p>
<p>to, you know, these large environments,</p>
<p>but you could also scale down</p>
<p>and run this on a pair of,</p>
<p>you know, small, you know, atoms or,</p>
<p>you know, intel atoms or the Andes or</p>
<p>something, you know, put in two of them,</p>
<p>real lightweight, couple of grand apiece,</p>
<p>throw them in a, you know, in a</p>
<p>in a plant or a retail location</p>
<p>and have the entire virtual data</p>
<p>and experience at the edge as well.</p>
<p>Where I can</p>
<p>I could build out</p>
<p>these virtual data centers</p>
<p>and then just start</p>
<p>deploying them everywhere and manage them.</p>
<p>You know.</p>
<p>That's pretty cool. I love that you just.</p>
<p>You know, swap it out.</p>
<p>Yeah, that's happening. Micro cloud.</p>
<p>Micro Cloud Tech now.</p>
<p>I mean, this is something</p>
<p>a lot of my customers want.</p>
<p>They want a micro cloud.</p>
<p>You know, it's a maybe it's a11 unit,</p>
<p>a couple of islands or some nooks</p>
<p>sitting out there running some edge stuff.</p>
<p>But they still want the flexibility</p>
<p>of the private of a cloud like, hey,</p>
<p>I can deploy applications, I can do</p>
<p>whatever I want, right, and manage.</p>
<p>Which brings up another question</p>
<p>and we talked about before,</p>
<p>if I have</p>
<p>all these virtual clouds out there,</p>
<p>I'm assuming you have a way of managing</p>
<p>multiple clouds</p>
<p>then or multiple data centers, right?</p>
<p>Is that in your in your stack to where</p>
<p>hey, maybe I've got ten different data</p>
<p>center images</p>
<p>or data center,</p>
<p>I don't know, virtual data centers.</p>
<p>Right.</p>
<p>Can I now manage those as, as, you know,</p>
<p>a single pane of glass</p>
<p>or anything like that or how does that.</p>
<p>Yeah.</p>
<p>Yeah, you can.</p>
<p>And that's actually now now this now</p>
<p>we're getting into some road map stuff.</p>
<p>So that that is actually</p>
<p>one of the next things we are expanding on</p>
<p>is we're going to we are building out our,</p>
<p>you know, multi-cloud,</p>
<p>you know, aggregation software</p>
<p>to kind of take that to the next level.</p>
<p>We've got some stuff now</p>
<p>you're part of the issue is</p>
<p>you want a centralized single point.</p>
<p>You know, we're kind of building this</p>
<p>so that the management layer itself</p>
<p>can also you know, kind of exist in mobile</p>
<p>stuff and float around</p>
<p>so that you truly have never downtime,</p>
<p>even the super manager, you know.</p>
<p>So there's a lot of stuff</p>
<p>we're doing in there too.</p>
<p>Also, you know, sexy that up a little bit</p>
<p>and that is one of the next big ones</p>
<p>we're really</p>
<p>working on right now is the flesh</p>
<p>that we have some capabilities</p>
<p>now for for the multi asset management.</p>
<p>But there's a lot we want to add to</p>
<p>that as well.</p>
<p>This is really fascinating stuff</p>
<p>because to me</p>
<p>you're really you're making it much easier</p>
<p>to actually do private cloud</p>
<p>because I mean, today to deploy</p>
<p>a full stack of private cloud takes days.</p>
<p>Right.</p>
<p>Whether it's OpenStack and</p>
<p>or whether it's the VMware suite.</p>
<p>Well if I want a full of full thing,</p>
<p>it, it takes a couple of days</p>
<p>to get everything set up.</p>
<p>And with you guys</p>
<p>it sounds like it's much simpler.</p>
<p>I can type all your software inside.</p>
<p>Get it?</p>
<p>Yeah, the software. Yeah.</p>
<p>So the whole software is actually deployed</p>
<p>as a firmware.</p>
<p>So it's not it's not something that's</p>
<p>being installed, running through update</p>
<p>cycles and configuring files.</p>
<p>It's, it gets flashed as a firmware</p>
<p>and then you booted up</p>
<p>and then there</p>
<p>you have your user interface</p>
<p>and now you can, you know, in the UI</p>
<p>you can set up your networks</p>
<p>and do what you want.</p>
<p>And it really takes about 15 minutes</p>
<p>to get it up and running.</p>
<p>And then after that, as you're adding</p>
<p>additional nodes scaling out,</p>
<p>you can even have it</p>
<p>set up to execute them.</p>
<p>So you don't even have</p>
<p>to put any media. You just.</p>
<p>Execute on.</p>
<p>It. Auto configures itself. You know.</p>
<p>That's that's pretty cool.</p>
<p>Can can because of software or firmware</p>
<p>can it run</p>
<p>on other virtual infrastructure</p>
<p>like in like in the cloud,</p>
<p>like in the public cloud</p>
<p>or do I need bare metal?</p>
<p>That's going to be the you're going</p>
<p>to get the best bang for the buck</p>
<p>if you run it on bare metal.</p>
<p>Even if that's in a public cloud,</p>
<p>you know, you can go and get bare</p>
<p>metal server.</p>
<p>Yeah, yeah,</p>
<p>you can whoever and run it on there.</p>
<p>And that's where you can get the best bang</p>
<p>for your buck because we, we are,</p>
<p>we're, we're managing the hardware</p>
<p>at the lowest level for it.</p>
<p>So we're, we're talking</p>
<p>directly to the drives.</p>
<p>We're not,</p>
<p>you know, when you when you deploy us,</p>
<p>we don't we don't want raid cards.</p>
<p>We don't want,</p>
<p>you know, anything touching and managing,</p>
<p>you know, the storage or the hardware.</p>
<p>We want to talk directly to it</p>
<p>and control the whole experience.</p>
<p>So, you know, we're dealing with</p>
<p>the encryption.</p>
<p>We're dealing with, you know, all that raw</p>
<p>and silent corruption detection.</p>
<p>We're guaranteeing all that integrity</p>
<p>that it's going to happen.</p>
<p>Now, you could certainly layer something,</p>
<p>put something below it, but</p>
<p>then you're just doubling up on efforts</p>
<p>and kind of taking place, you know, right</p>
<p>there.</p>
<p>Very, very cool stuff, Greg.</p>
<p>And I'm glad to see</p>
<p>that your byte continues forward.</p>
<p>I, I, you know, I loved your architecture</p>
<p>and it's great to see that it's expanding</p>
<p>and a very, very well thought out.</p>
<p>So great.</p>
<p>Thanks for coming on the show today.</p>
<p>Oh, thanks.</p>
<p>Thanks for having me there.</p>
<p>Thank you for listening to.</p>
<p>Embracing Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcast insider YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>at embracingdigital.org.</p>
<p>Until next</p>
<p>time, go out and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
