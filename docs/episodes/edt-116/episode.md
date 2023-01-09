---
layout: posts
title: An Argument for a Holistic approach to Critical Infrastructure Security
number: 116
permalink: EDT116
has_children: false
parent: Episodes
nav_order: 116
tags:
    - Cybersecurity
    - Critical Infrastructure
    - OT Security
date: 2022-12-15
guests:
    - Darren W Pulsipher
    - Steve Orrin
    - Anna Scott
img: thumbnail.png
summary: In this episode, Darren talks about the converance of OT and IT cybersecurity with Security expert Steve Orrin and Industrial OT expert Dr. Anna Scott
---

{% include soundcloud.html id="edt116" title="#116 An Argument for a Holistic approach to Critical Infrastructure Security" %}

{% include youtube.html id="DRGy_il_nUg" %}

---


## There is a real threat to Critical Infrastructure

According to Dr. Scott, OT organizations still use the traditional Purdue Model, which leverages air-gapped and firewalled-off networks. However, this model is starting to fall apart as IT and OT networks converge. Businesses are trying to get better insight into what is happening in their operational infrastructure. As a result, they punch holes in the previously well-isolated networks, exposing them to cyber threats. Additionally, cybercriminals are finding ways to circumvent air-gapped and firewalled networks. 

Steve argues that leveraging IT best practices can help, but OT professionals and IT professionals have different motivators and operating models. Continuing to isolate your network is still a good strategy but should be one of many tools used in critical infrastructure cybersecurity protection. OT security should look at IT cybersecurity best practices for ideas to improve their networks and infrastructure.

## IT and OT differences impeding Best Practices

IT systems are traditionally updated quickly or continuously based on security profiles. One of the primary tools to improve security is basic security hygiene through patching operating systems firmware and software in the IT infrastructure. However, as Dr. Scott enlightens us, OT systems managing critical infrastructure cannot have downtime, and the window to update these systems is measured in years, not days. It is not uncommon in OT infrastructure devices that machines run for 5 to 10 years with no downtime, meaning no patch updates. 

For example, in the oil and gas industry, refineries operate continuously for four to five years, have a one to three-week downtime for upgrades, and then operate again for four to five years. These operating models are not conducive to the traditional continuous security patching that IT organizations typically use. However, Steve elaborates on many other cybersecurity tools that should be leveraged when cybersecurity patches cannot be applied to existing devices due to their critical controlling infrastructure.

## Best Practice Risk Assessment
the primary cybersecurity best practice is risk assessment. Even though risk remediation may be different, the risk assessment process can be leveraged equally across OT and its environments. Steve argues that the first step of the risk assessment process is getting a complete inventory of hardware, firmware, and software assets in your OT environment. This first step is critical in evaluating your cyber threat position and assessing the risk your organization is willing to take. The next step is to evaluate CVEs against your known inventory. 

It is critical to recognize that this is a continuous process and not to be done just once or periodically. Some OT professionals have argued that their OT environments are static and do not require ongoing risk assessment evaluation. However, Steve points out that even though OT environments may be fixed, the threat environment constantly changes, and business factors can change the organization’s risk position. Therefore continuous risk assessment must be done to protect critical infrastructure from bad cybersecurity actors.

## Dealing with OT Vendors

Another interesting factor in OT infrastructure is the shared security model with device vendors. In many cases, these embedded devices controlling multimillion-dollar critical infrastructure are managed to buy the vendor, not the OT professional. The vendor can only make cyber security patches and updates to the devices. This can sometimes lead to vulnerabilities in your OT environment, increasing the risk of cyber infiltration. Steve brings additional cyber security tools to help protect assets that cannot be patched with critical cyber security patches, including increase isolation of affected devices, deploying watchdog devices, and canary design patterns into the OT infrastructure. These tools can help protect and isolate the device to prevent the spread and access to compromised assets.

## What to do when you are compromised

So what do you do when you have a critical infrastructure that has been compromised? Can the organization handle shutting down the infected infrastructure? What business continuity plans are in place when hazardous situations occur? Can this be used when a cyber security event happens as well? 

The key here is to isolate the infection as quickly as possible to minimize the impact on the critical infrastructure. I am decreasing the effect on the operating reliability of the necessary infrastructure. The goal is to reduce the impact and protect the safety of people and the infrastructure involved.

## Find out more 
Continue to look for more podcasts on OT cybersecurity. Additionally, a whitepaper describes the challenges of converging OT and IT cybersecurity environments.


<details>
<summary> Podcast Transcript </summary>

<p>﻿Hello, this is Darren</p>
<p>Pulsipher, chief solution,</p>
<p>architect of public sector at Intel.</p>
<p>And welcome to Embracing</p>
<p>Digital Transformation,</p>
<p>where we investigate effective change,</p>
<p>leveraging people process</p>
<p>and technology.</p>
<p>On today's episode,</p>
<p>an argument for a holistic approach</p>
<p>to critical infrastructure security</p>
<p>with our special guest, Dr.</p>
<p>Anna Scott and Steve Orrin.</p>
<p>Anna. Steve, welcome to the show.</p>
<p>Good to be here.</p>
<p>Thank you, Darren</p>
<p>I know it's hard to know who to go first</p>
<p>when I'm going to people.</p>
<p>To sort out at the same time say.</p>
<p>You guys have been on the show</p>
<p>several times, Steve,</p>
<p>I think I think you're my number one</p>
<p>interviewee.</p>
<p>I think. Anna, your second.</p>
<p>This is like your fifth time.</p>
<p>I think it's been a lot. Yeah. So.</p>
<p>And the reason I ask both of you</p>
<p>on today was I wanted to get</p>
<p>a different perspective</p>
<p>on critical infrastructure security.</p>
<p>First off, from a former CSO</p>
<p>and a security expert.</p>
<p>That's you, Steve, if you don't know.</p>
<p>And also from an industrial Iot</p>
<p>expert like you, Anna,</p>
<p>because you've been in the trenches</p>
<p>in industry trying to work through these</p>
<p>and critical infrastructure environments.</p>
<p>So both of you on together,</p>
<p>we should help figure out what's going on</p>
<p>as far as critical</p>
<p>infrastructure, cybersecurity.</p>
<p>So let's first get kicked off by</p>
<p>with you in a little bit.</p>
<p>Is is there a real threat to critical</p>
<p>infrastructure, cyber security,</p>
<p>or is that just a red herring or something</p>
<p>we're just hearing on the news</p>
<p>because there's nothing going on</p>
<p>in the news cycles to</p>
<p>know.</p>
<p>It's a huge it's a huge concern. Right.</p>
<p>And it's a it's a huge threat.</p>
<p>It it does depend a lot on</p>
<p>how the individual companies</p>
<p>are dealing with their systems.</p>
<p>Right.</p>
<p>There's still a predominance of the way</p>
<p>you protect</p>
<p>really critical systems is</p>
<p>you just don't let anything access them</p>
<p>through</p>
<p>through anything except</p>
<p>being in the same room with them.</p>
<p>So that that's a great way</p>
<p>if you can control around insider threats</p>
<p>because you have a very limited attack</p>
<p>surface</p>
<p>and you've got a great deal of control</p>
<p>in that space,</p>
<p>there's all sorts of reasons</p>
<p>why that just does not work</p>
<p>well in the modern world,</p>
<p>because that tends to prevent taking</p>
<p>advantage of a lot of modern technology,</p>
<p>especially when you get into</p>
<p>what you can do with analytics</p>
<p>and analytics across different data sets.</p>
<p>So so yes, you can continue</p>
<p>in that pattern, but you do that</p>
<p>at the expense</p>
<p>of not being able to take advantage</p>
<p>of those tools and bring that</p>
<p>competitive advantage into your space.</p>
<p>But as soon as you do that and you</p>
<p>connected to the Internet</p>
<p>or you can connect contributor systems,</p>
<p>now you've got a whole different set</p>
<p>of protections that you need.</p>
<p>And these tend to be things that are not</p>
<p>well understood and especially</p>
<p>where operational folks make the call,</p>
<p>which is what happens in the space,</p>
<p>then you have some real challenges</p>
<p>just in understanding</p>
<p>what are the real threats, what are the</p>
<p>real tools for to protect against them.</p>
<p>And the question that you addressed</p>
<p>with your paper, Darren, which is</p>
<p>can we really use I.T tools in this space</p>
<p>and use them to good advantage?</p>
<p>And I love that idea because I think</p>
<p>there's so much more that can be done</p>
<p>and much more that can be leveraged</p>
<p>to just deal with the,</p>
<p>the specific problems</p>
<p>that happened in the operations.</p>
<p>So, so what</p>
<p>what I heard a little bit there in is the</p>
<p>the Purdue model</p>
<p>that everyone's been using this isolation</p>
<p>either</p>
<p>firewalled off or completely air gapped.</p>
<p>That's a naive approach in today's</p>
<p>modern things because I need the data out.</p>
<p>Yeah, I hate to use my because I think</p>
<p>there's some really good reasons for it.</p>
<p>And I, I guess</p>
<p>having worked in situations</p>
<p>where where my life has depended</p>
<p>upon the systems working and not having it</p>
<p>having to be tampered with</p>
<p>and, you know, having malicious intent,</p>
<p>I, I'm pretty comfortable with that.</p>
<p>But I do think that there's a big cost</p>
<p>that goes that goes with that.</p>
<p>And so so it's really like getting</p>
<p>a good handle on your risk profile.</p>
<p>Like, I'm going to cite Steve here</p>
<p>because I love this so much.</p>
<p>Right?</p>
<p>It's like</p>
<p>if you try and figure out how to do</p>
<p>zero trust, what you have to start with is</p>
<p>what's your real risk profile</p>
<p>and what really matters, right?</p>
<p>Because if you take that type of approach,</p>
<p>then that helps balance off</p>
<p>what's really happening</p>
<p>when you do this connectivity</p>
<p>and you bring these assets</p>
<p>together. Right.</p>
<p>And so I think</p>
<p>you still have to do an assessment,</p>
<p>which is do those new capabilities</p>
<p>bring you enough value to overlay the risk</p>
<p>of the vulnerability of those systems,</p>
<p>especially when you know, one,</p>
<p>you're going to be constantly</p>
<p>trying to keep up with the hackers and all</p>
<p>of the new software and everything else.</p>
<p>And that is a pretty high request</p>
<p>and pretty difficult to do in some cases,</p>
<p>especially with organizations that don't</p>
<p>already have that type of capability.</p>
<p>And so really having a handle</p>
<p>on that relative to</p>
<p>what's the real benefit to your business.</p>
<p>Right.</p>
<p>So, Steve, she she quoted you,</p>
<p>you got to come in and cyber</p>
<p>and and also</p>
<p>I want you to address a little bit of</p>
<p>I call it naive and thank you, Anna, for</p>
<p>for correct me on it, but I still think</p>
<p>there's a little bit of false security</p>
<p>behind</p>
<p>a isolated network.</p>
<p>So, Steve.</p>
<p>So, Dan, I think Anna does hit it right.</p>
<p>It's understanding the risk profile.</p>
<p>I think one thing</p>
<p>and maybe naive is not the right term.</p>
<p>I think the cat is out of the bag.</p>
<p>Those systems,</p>
<p>that critical infrastructure is connected.</p>
<p>They're connected to IT systems.</p>
<p>They're being managed</p>
<p>in a distributed fashion.</p>
<p>They are getting tapped</p>
<p>into from the outside.</p>
<p>They're interconnected amongst themselves.</p>
<p>So the notion of a truly isolated</p>
<p>environment or a critical infrastructure</p>
<p>environment is actually a notion</p>
<p>that isn't true anymore.</p>
<p>In many cases, what's considered to be</p>
<p>an air gap of the old</p>
<p>or where you physically had space</p>
<p>is now more a virtual or logical air gap.</p>
<p>And then we're seeing attacks that can</p>
<p>jump that virtual or logical air gap.</p>
<p>And in many cases, the</p>
<p>what you thought was a logical or virtual</p>
<p>air gap is not an air gap at all.</p>
<p>And so</p>
<p>systems are much more connected</p>
<p>than they've ever been.</p>
<p>And so I wouldn't that's I call it naive.</p>
<p>I just say, like in some cases</p>
<p>it's already happened.</p>
<p>And so the question isn't, well,</p>
<p>should I open up my network,</p>
<p>your network,</p>
<p>because your systems are already open.</p>
<p>It's now how do I start to apply the right</p>
<p>controls and falling back on?</p>
<p>Well, I'm</p>
<p>just going to continually isolate</p>
<p>and that's been a major</p>
<p>approach is is a good one.</p>
<p>It's a tool.</p>
<p>It's not the only tool</p>
<p>and it's not the complete tool.</p>
<p>It's one of the tools.</p>
<p>So encrypting the network traffic</p>
<p>or providing logical firewalls to separate</p>
<p>networks that do network segmentation</p>
<p>is absolutely a great tool in the arsenal.</p>
<p>But it alone will not prevent</p>
<p>this kind of threats that these</p>
<p>OT and critical</p>
<p>infrastructure systems are seeing.</p>
<p>And so when you look at it</p>
<p>from that perspective, it's</p>
<p>okay, let's understand</p>
<p>the risks of the OT systems, understand</p>
<p>how they're different from the I.T systems</p>
<p>that many of these</p>
<p>security products and technologies</p>
<p>were originally designed for</p>
<p>and apply</p>
<p>those security controls in an old fashion.</p>
<p>I think that's one of the learnings both</p>
<p>from from the paper that you published</p>
<p>as well as what organisé tions</p>
<p>that are doing this right now are seeing</p>
<p>is leveraging its security capabilities</p>
<p>and controls</p>
<p>in an way.</p>
<p>So I think glad you said in an odd way,</p>
<p>because a lot of times I've seen the IT</p>
<p>professional, the CSO come in</p>
<p>with a hammer on the operational guys</p>
<p>and say you need to be secure,</p>
<p>update all your patches,</p>
<p>right?</p>
<p>Everything needs to be updated.</p>
<p>And Ana, is that doable?</p>
<p>Well, depends on</p>
<p>how old your equipment is, right?</p>
<p>Well, I mean, yeah,</p>
<p>some of this equipment is 50 years old.</p>
<p>Yeah.</p>
<p>And then there's a lot of diversity in it</p>
<p>as well. Right.</p>
<p>And so many of those systems were designed</p>
<p>so that maybe you update the firmware</p>
<p>once every ten years and you're going out</p>
<p>there with a USB stick to do that.</p>
<p>Right? Because it does.</p>
<p>Does that scare you, Steve,</p>
<p>when you hear that ten years</p>
<p>you haven't updated</p>
<p>your security patches in ten years?</p>
<p>And I wish it was something</p>
<p>that was novel, but we see this often</p>
<p>in OT edge environments, even in systems</p>
<p>that are supposed to be it</p>
<p>related, but are driving those.</p>
<p>So that's actually an interesting point</p>
<p>is when you go</p>
<p>look at an industrial manufacturing line</p>
<p>or you go look at a smart city</p>
<p>or any of these sort of operational</p>
<p>technology, critical infrastructure,</p>
<p>and you go look inside</p>
<p>the cabinets, you go look,</p>
<p>it looks like an I.T system.</p>
<p>There's a rack of servers in there</p>
<p>now that are driving those technologies,</p>
<p>monitoring them, doing the the</p>
<p>the operations that once was very analog.</p>
<p>And so that the scary part</p>
<p>is that those i.t systems</p>
<p>do need to be patched regularly.</p>
<p>They do have vulnerabilities.</p>
<p>But as I pointed out, there's a reason</p>
<p>why they don't get patched</p>
<p>the same cadence that standard i.t. Yeah.</p>
<p>And why is that a why?</p>
<p>So they really weren't designed,</p>
<p>they weren't designed with this whole idea</p>
<p>of you're connected</p>
<p>all of the time and you need to</p>
<p>be constantly updated. It's</p>
<p>what is</p>
<p>the difference between</p>
<p>streaming on your music, on your iPhone,</p>
<p>right,</p>
<p>where you're connected all of the time</p>
<p>and everything's completely up to date</p>
<p>and having an old iPod</p>
<p>where you can load it up once</p>
<p>and then run that sucker</p>
<p>until it died, right?</p>
<p>Or until it just really needed attention.</p>
<p>So and I shouldn't have you start because</p>
<p>that's not how you fix the old system,</p>
<p>but it's just kind of the idea.</p>
<p>It is</p>
<p>it is a just a completely different world.</p>
<p>If you are living in a space</p>
<p>where you're constantly connected</p>
<p>and so much of the legacy equipment,</p>
<p>it was never designed with that in mind.</p>
<p>It was it was hardened</p>
<p>in a way that once you install that,</p>
<p>you could really keep it going for a very,</p>
<p>very long period of time.</p>
<p>And so you have this much longer lifecycle</p>
<p>like so.</p>
<p>That the applications</p>
<p>that are being supported by the systems</p>
<p>are very different from it.</p>
<p>So if your email goes down</p>
<p>for a couple of hours, it's no.</p>
<p>Big deal.</p>
<p>Life goes on.</p>
<p>But many of these critical infrastructure</p>
<p>that are driving your power, water</p>
<p>treatment, you know, life</p>
<p>saving devices inside hospitals,</p>
<p>they're not meant to be taken down</p>
<p>by a patch that, you know, that didn't do.</p>
<p>It's quality assurance to the same level</p>
<p>and the regular cadence of being able</p>
<p>to do things and bring things offline</p>
<p>and bring them back in.</p>
<p>That's a modern i.t concept,</p>
<p>but these systems were meant to,</p>
<p>like I said, run for 15 years nonstop</p>
<p>and that's not something that is easily,</p>
<p>you know, deployed patches</p>
<p>or to be able to do, you know, inspections</p>
<p>and security tools that get in the way</p>
<p>of the operational technology.</p>
<p>And that's again</p>
<p>why I talked about it in an odd way.</p>
<p>So it sounds to me like there's</p>
<p>a total mismatch in motivation</p>
<p>and in in results in the space right?</p>
<p>High availability.</p>
<p>We're not talking</p>
<p>three nines, we're talking 12 nines.</p>
<p>Right.</p>
<p>I don't want I don't want a heart monitor</p>
<p>or a heart machine</p>
<p>to oh, I need to reboot</p>
<p>or I need to reboot every three days.</p>
<p>You don't want that.</p>
<p>Or even your power grid</p>
<p>you really don't want down.</p>
<p>So because the</p>
<p>because the motivation is so different,</p>
<p>can I really use</p>
<p>the same techniques in I.T in O.T.</p>
<p>or, or do I just go and I understand</p>
<p>the isolate myself</p>
<p>because I don't want any change.</p>
<p>Things are working.</p>
<p>Don't bother me. Right.</p>
<p>Isn't that how it's done In a.</p>
<p>Probably way too often.</p>
<p>Right.</p>
<p>And there's definitely a risk associated</p>
<p>with trying to fix your problems.</p>
<p>Right.</p>
<p>The same way there's risks</p>
<p>with just continuing to do nothing</p>
<p>and keeping your fingers crossed.</p>
<p>There's a lot of very clever people</p>
<p>that still want</p>
<p>to find ways to disrupt systems,</p>
<p>even the legacy systems.</p>
<p>Right.</p>
<p>And in some ways, many of the legacy</p>
<p>systems are more vulnerable</p>
<p>because they were designed before</p>
<p>modern hacking was really happening.</p>
<p>Right. So there's just some</p>
<p>some real concerns there.</p>
<p>But I do think that there's a real place</p>
<p>for having the i.t.</p>
<p>Tools, right?</p>
<p>Like, there's a lot of tools that can say</p>
<p>i'm going to look</p>
<p>at the network, I'm going to identify</p>
<p>everything that's on the network.</p>
<p>I'm going to identify</p>
<p>what is the current level of firmware.</p>
<p>And then if it's set up properly,</p>
<p>you can say what is,</p>
<p>what should be the current version</p>
<p>and where do you have gaps in</p>
<p>some of the tools where you're actually</p>
<p>sophisticated enough, where they can say,</p>
<p>What's your real risk associated</p>
<p>with not having those updates in place?</p>
<p>And when you get into that level</p>
<p>of sophistication and that becomes</p>
<p>very, very valuable, right?</p>
<p>Because now you have a clear picture</p>
<p>of what's going on</p>
<p>and then you have a way</p>
<p>to actually prioritize that risk.</p>
<p>Granted, I don't know that you ever want</p>
<p>to trust another company to do that.</p>
<p>You probably want to be</p>
<p>at least understand very clearly how</p>
<p>the software made the decisions</p>
<p>about where your risk really lies,</p>
<p>because there's no way a software</p>
<p>company knows what each of your individual</p>
<p>components are really controlling</p>
<p>and how how critical those can be.</p>
<p>So so you got to stay very involved.</p>
<p>Right?</p>
<p>But if you have that type of assessment,</p>
<p>at least you can start out and do that.</p>
<p>And my understanding is that's pretty</p>
<p>common on its systems, right?</p>
<p>There are tools that can do that, and</p>
<p>there's lots of tools that can do that.</p>
<p>So at least you're not just having</p>
<p>this big black box</p>
<p>and a bunch of question marks.</p>
<p>You can say,</p>
<p>let's start doing that assessment.</p>
<p>And if those types of tools</p>
<p>can find things on your network,</p>
<p>that means somebody who's coming into that</p>
<p>environment can also find things, right?</p>
<p>So you really do want to understand</p>
<p>what's discoverable</p>
<p>and what is its current status and</p>
<p>and then determine where you take this.</p>
<p>So that brings up</p>
<p>one of the best practices</p>
<p>that we know about in its cybersecurity,</p>
<p>which is risk assessment.</p>
<p>And Steve, can you talk a little bit</p>
<p>about risk assessment?</p>
<p>Because I know</p>
<p>if we ran a vulnerability scan,</p>
<p>there would be tens of thousands,</p>
<p>hundreds of thousands in any company.</p>
<p>You can't do them all.</p>
<p>So this is where</p>
<p>the risk assessment comes in.</p>
<p>So can you explain how I can leverage the</p>
<p>IT risk assessment?</p>
<p>Best practice in the OT space as well?</p>
<p>Absolutely.</p>
<p>And so it really starts</p>
<p>with what Hannah was talking about.</p>
<p>You can't secure what you don't know.</p>
<p>And so starting with the asset</p>
<p>inventory, the discovery</p>
<p>to understand what your assets are,</p>
<p>understand what's running inside the box,</p>
<p>what you know, what firmware,</p>
<p>what operating systems, what versions</p>
<p>you need to create that asset inventory</p>
<p>to be able to do the next phase.</p>
<p>And before you even get to your security</p>
<p>considerations, the next piece of this,</p>
<p>this is actually defined as part</p>
<p>of the next cybersecurity framework</p>
<p>is once you know what your environment is,</p>
<p>understanding what's what they're doing,</p>
<p>what is the purpose of those systems.</p>
<p>And this is important.</p>
<p>When you do your risk calculation,</p>
<p>you need to know what are your mission</p>
<p>critical, what are the necessary</p>
<p>support systems to keep those mission</p>
<p>critical systems operational</p>
<p>so that you can create that risk</p>
<p>profile and understand the prioritization</p>
<p>of applying the security.</p>
<p>So before you ever get to your first</p>
<p>encryption key or firewall, it's</p>
<p>knowing what you have in great detail,</p>
<p>understanding what those systems</p>
<p>and processes and technologies</p>
<p>do for your business,</p>
<p>for your mission systems.</p>
<p>And then from there</p>
<p>you can start to apply a risk calculus.</p>
<p>And that risk takes</p>
<p>from published vulnerability.</p>
<p>So databases,</p>
<p>there's new technology, new standards</p>
<p>and formats around softer built</p>
<p>materials and vulnerability.</p>
<p>And in our exchange called VEX, to be able</p>
<p>to give you information about</p>
<p>what's the vulnerable state</p>
<p>of the components, there's</p>
<p>a lot of great information out there</p>
<p>already in the might or frameworks</p>
<p>to let you do</p>
<p>the assessment of what you found.</p>
<p>So no, this version of Linux</p>
<p>has got this level of vulnerability</p>
<p>or this particular product over here</p>
<p>has these cves that I need</p>
<p>that haven't been patched in the version</p>
<p>I have.</p>
<p>So you get that information now</p>
<p>you have what you have, what's it called,</p>
<p>what's critical in your organization</p>
<p>and what the known vulnerability,</p>
<p>the other side of the risk assessment</p>
<p>besides the known form is understanding.</p>
<p>And this is where things like pen</p>
<p>tests, scanners and other kinds of tools</p>
<p>give you an idea of what</p>
<p>your overall threat landscape is.</p>
<p>Those come together</p>
<p>into understanding your risk profile.</p>
<p>So I understand what my current assets</p>
<p>are, what the known risk,</p>
<p>what the potential risk,</p>
<p>and then the what these things</p>
<p>are usually important for helps</p>
<p>guide the prioritization of, okay, now</p>
<p>I need to start planning security tools.</p>
<p>And it's only at this last phase</p>
<p>that you start applying</p>
<p>process, technology and procedures</p>
<p>to do the compensating controls to reduce</p>
<p>or mitigate</p>
<p>the risks that you've identified.</p>
<p>And that's your standard I.T flow</p>
<p>that I've been describing</p>
<p>can be absolutely applied</p>
<p>to the OT systems, understanding that the</p>
<p>what you actually implement the process,</p>
<p>the procedures have to be done</p>
<p>in that way.</p>
<p>So it's not going to be well,</p>
<p>I'm just gonna push a button</p>
<p>and patch everything or I can just put a,</p>
<p>you know, an encryption system onto</p>
<p>or an enterprise product</p>
<p>on to that, that PFC device.</p>
<p>You have to be able to apply</p>
<p>the right kind of controls,</p>
<p>but it's only at that last phase of the</p>
<p>process of assessing the risk environment,</p>
<p>your risk posture,</p>
<p>and then the prioritization</p>
<p>that your assets tell you about that,</p>
<p>then you can start to make the decisions</p>
<p>and applying budgets and actually building</p>
<p>your capacity and capability</p>
<p>to mitigate the controls.</p>
<p>And it's not a one and done this,</p>
<p>not like we're finished.</p>
<p>We did our assessment. Okay, we can go</p>
<p>back.</p>
<p>It's an ongoing, constant process because</p>
<p>even if you're in a nice, structured</p>
<p>environment, that never changes.</p>
<p>For 15 years,</p>
<p>the threat landscape is always changing.</p>
<p>Your app threat, your risk appetite</p>
<p>is actually always changing.</p>
<p>What's happening in the macroeconomic</p>
<p>world changes regularly.</p>
<p>And so reassessing and reevaluating.</p>
<p>Are your controls sufficient?</p>
<p>What's next on the list</p>
<p>Prioritization list to be addressed</p>
<p>and verifying that you're mitigating</p>
<p>controls are in fact doing what they said</p>
<p>they do are all part of the ongoing</p>
<p>process of securing your infrastructure.</p>
<p>Whether that's it or not.</p>
<p>I want to</p>
<p>I want to reemphasize what you said there.</p>
<p>Even if your own environment is static,</p>
<p>the threat environment changes</p>
<p>and your business motivators</p>
<p>can be changing too.</p>
<p>So you have to constantly evaluate</p>
<p>and nothing.</p>
<p>I like that you said to let's say</p>
<p>that I have a certain version of Linux</p>
<p>that has a security vulnerability</p>
<p>across it</p>
<p>and it doesn't mean</p>
<p>I'm patching everything on the outside.</p>
<p>It may be I can't patch that</p>
<p>because name the critical infrastructure,</p>
<p>so I have to come up</p>
<p>with a different remediation</p>
<p>for that device, a.k.a locking it down</p>
<p>completely as far as network and monitor</p>
<p>the firewall around that one device</p>
<p>more rigidly.</p>
<p>That might be a different remediation</p>
<p>than doing the patch for example.</p>
<p>So Darren, so two things we've seen</p>
<p>successful inside of environments.</p>
<p>These two terms</p>
<p>I'm going to use of that new kind</p>
<p>of mitigating control when you can't just</p>
<p>flip a switch and turn on encryption.</p>
<p>One is what I call watchdog approach,</p>
<p>where you take a modern system,</p>
<p>put it right up next to a legacy system</p>
<p>on the wire so that they can monitor</p>
<p>and have the advanced inspection</p>
<p>and detection in.</p>
<p>Particular, watching everybody.</p>
<p>On behalf of the device</p>
<p>that it's proxy in.</p>
<p>And the other approach that's often used</p>
<p>is what I call the canary approach,</p>
<p>where if you've got an environment</p>
<p>where you have a segmented network</p>
<p>of legacy systems that are hard to patch,</p>
<p>you can't get the right</p>
<p>the tight security controls.</p>
<p>You put a detector in there on the network</p>
<p>that has</p>
<p>those does advanced detection</p>
<p>and B, it becomes the canary for that.</p>
<p>That segment.</p>
<p>So it will alert, whereas legacy systems</p>
<p>don't have the capacity to alert</p>
<p>or to tell you that something is</p>
<p>being attacked or are being targeted.</p>
<p>And so that watchdog in Canary</p>
<p>combination is a different</p>
<p>kind of compensating control</p>
<p>that is very popular in O.T.</p>
<p>because it doesn't require going</p>
<p>and changing that policy itself.</p>
<p>It's about adding the right i.t</p>
<p>capabilities into that environment</p>
<p>to to proxy those systems</p>
<p>and to give them the capabilities</p>
<p>without impacting know mission</p>
<p>critical functions.</p>
<p>And there's also another thing I heard.</p>
<p>I was talking to our own</p>
<p>OT organization</p>
<p>and they were saying</p>
<p>we actually can't patch</p>
<p>some of the devices in our infrastructure</p>
<p>because we're not allowed to</p>
<p>because it's the vendor, right?</p>
<p>It's their machine, right.</p>
<p>If we touch it, then</p>
<p>our warranty on this multimillion dollar</p>
<p>particle accelerator</p>
<p>or whatever it is, right,</p>
<p>is is now null and void. Right.</p>
<p>We can't we can't enforce</p>
<p>some of our security things</p>
<p>on some of these embedded devices.</p>
<p>But we know that there's</p>
<p>a vulnerability in there.</p>
<p>Right.</p>
<p>Is that a common thing that you're</p>
<p>seeing as well, or is that just unique to</p>
<p>these really huge,</p>
<p>you know, manufacturing or fab</p>
<p>OT systems?</p>
<p>So I think it can definitely be</p>
<p>definitely be the case.</p>
<p>You know,</p>
<p>like a lot of on the industrial side,</p>
<p>what we really worry</p>
<p>about is the control systems</p>
<p>because because that's where</p>
<p>you can go in and mess with things, right?</p>
<p>Otherwise you have to.</p>
<p>Be that's where you're messing</p>
<p>with the physical world.</p>
<p>Right. Exactly.</p>
<p>I'm sorry.</p>
<p>I just got a call. So.</p>
<p>So updating those control systems, you're</p>
<p>not going to be doing that in isolation.</p>
<p>You're going to be doing that in close</p>
<p>coordination with who the vendors are</p>
<p>and make sure that you've got a plan</p>
<p>that you've executed with with them.</p>
<p>The other thing I wanted to mention,</p>
<p>because we haven't talked talked about it</p>
<p>yet, is often in the oh two systems,</p>
<p>your only window for really doing updates</p>
<p>is when you're shutting down</p>
<p>for planes, flat maintenance.</p>
<p>So that's another factor that comes into</p>
<p>it is you really do have to say,</p>
<p>well, when I worked in</p>
<p>refining, we did turnarounds</p>
<p>between three and</p>
<p>five years, depending on the type of unit.</p>
<p>Literally all of the updates</p>
<p>to major systems had to fall</p>
<p>within the three week period of turnaround</p>
<p>because that was the only time</p>
<p>it was really safe</p>
<p>to go in and change those systems.</p>
<p>And it was also the only time</p>
<p>we could actually test them to say,</p>
<p>Hey, we've just made this change.</p>
<p>Is it really ready to come back online?</p>
<p>And so those intervals around the planned</p>
<p>maintenance can also</p>
<p>be extremely important</p>
<p>as well as the point that you brought up,</p>
<p>which is then talk to your vendor, right,</p>
<p>when they're part of those</p>
<p>critical systems.</p>
<p>Because because they will</p>
<p>they will have strong opinions, Right?</p>
<p>I'm sure they will about. How to do that</p>
<p>properly.</p>
<p>Now, in a refinery where you work,</p>
<p>how how often are these turnarounds?</p>
<p>How often do you get to do that?</p>
<p>Once a year, six months, three years,</p>
<p>four years?</p>
<p>Well, typically, the</p>
<p>kind of</p>
<p>average cadence was about four years.</p>
<p>If you're really stretched on</p>
<p>profitability,</p>
<p>you try and push it to five</p>
<p>just because those are</p>
<p>extraordinarily expensive.</p>
<p>But yeah, so about a four,</p>
<p>four year time frame, right?</p>
<p>So if you can imagine,</p>
<p>you've got a control system</p>
<p>that's running everything</p>
<p>and you only get to touch it once</p>
<p>every four years, right?</p>
<p>That's that's. Crazy. You touch it.</p>
<p>Now you've got a window that's</p>
<p>maybe if you're lucky, it's three weeks.</p>
<p>And if it's somebody you can do the</p>
<p>maintenance maintenance on really quickly.</p>
<p>It's like one week, right?</p>
<p>So fit and everything.</p>
<p>You've got to change in a one week period</p>
<p>and you got to plan for that because you</p>
<p>know, your next opportunity for an update</p>
<p>is also going to be four years.</p>
<p>And it's a similar cadence</p>
<p>in a lot of military systems</p>
<p>as well with the tech refresh</p>
<p>as being once every three or more years.</p>
<p>One of the techniques</p>
<p>that we're seeing being adopted by</p>
<p>a lot of the more advanced organizations</p>
<p>and we're seeing vendors</p>
<p>actually supply this to their customers</p>
<p>of some of these</p>
<p>environments</p>
<p>is what's called a digital twin.</p>
<p>And the idea is that you have</p>
<p>a digital virtual version of that physical</p>
<p>asset of that policy or that controller</p>
<p>that you can apply changes,</p>
<p>you can do patches too,</p>
<p>and run simulations and basically run it</p>
<p>through its paces to see what impact</p>
<p>it may have on the digital twin version.</p>
<p>Now it's not you're still going</p>
<p>to want to do physical or testing,</p>
<p>but allows you to do a whole lot</p>
<p>of pre-loaded tests</p>
<p>before you ever get to touching that</p>
<p>that system</p>
<p>where you got that one week window</p>
<p>to do all of your testing</p>
<p>and all of your patching.</p>
<p>And so we're seeing digital twins come up.</p>
<p>I've seen them</p>
<p>in the construction industry.</p>
<p>I've seen, you know, in facts</p>
<p>where there's digital versions of those</p>
<p>that are supplied along with the product</p>
<p>for the contractor to basically run their</p>
<p>their simulations both from a patching,</p>
<p>but also test on load,</p>
<p>be able to look at the environmental</p>
<p>conditions and changes there</p>
<p>and be able to do those tests</p>
<p>in a virtual simulated environment.</p>
<p>That's one technique that can actually</p>
<p>be applied to security patches as well.</p>
<p>You know, we're also seeing</p>
<p>I've been approached by a couple of state</p>
<p>governments</p>
<p>to set up a site in cyber range</p>
<p>where in their</p>
<p>primary focus</p>
<p>has been on the electrical grid system,</p>
<p>which I found totally fascinating.</p>
<p>Right.</p>
<p>They want us to help them</p>
<p>establish a noticeable range</p>
<p>so they can test out</p>
<p>some of these new architectures</p>
<p>that we're talking about,</p>
<p>like the watchdog, the canary,</p>
<p>the the data diode and some new ones</p>
<p>that we're talking about around</p>
<p>one is called the</p>
<p>the patch here or the patch</p>
<p>airlock pattern,</p>
<p>which is an interesting pattern as well.</p>
<p>Do you even with these things,</p>
<p>we still have this long cycle time</p>
<p>between being able to to update</p>
<p>and A, do you ever see us</p>
<p>where we could do continuous</p>
<p>updates</p>
<p>on these critical infrastructure systems</p>
<p>or is there</p>
<p>just too much risk involved in updating,</p>
<p>you know, controllers</p>
<p>as there as they're operating?</p>
<p>Yeah, And I think, yes, with time and</p>
<p>a lot of it's redundancy of capabilities.</p>
<p>Okay. Right.</p>
<p>There's a</p>
<p>the there's been work going on for</p>
<p>it might even be seven years now</p>
<p>that is the Open process automation forum</p>
<p>and they have been leading</p>
<p>a consortium effort through the Open group</p>
<p>to really do a modernization</p>
<p>of control systems</p>
<p>for not just refining</p>
<p>but chemicals and pharmaceuticals</p>
<p>and kind of all the groups that use</p>
<p>those sophisticated control systems.</p>
<p>And there's specifically addressing this.</p>
<p>Right?</p>
<p>They've got a whole cybersecurity</p>
<p>subcommittee</p>
<p>that much of it is really coming down</p>
<p>to what's the design,</p>
<p>How do you have the redundancy set up</p>
<p>so that if you lose one</p>
<p>capability, do you have jail over</p>
<p>within the timeframe?</p>
<p>That's important.</p>
<p>So that does it kick out your equipment</p>
<p>because a lot of equipment,</p>
<p>if it loses a signal like a</p>
<p>to a power failure or even a power blink,</p>
<p>that'll just take it down.</p>
<p>So there's</p>
<p>there's some real hard and fast rules</p>
<p>there.</p>
<p>I think all of that is fantastic.</p>
<p>But I'll I'll kind of add on top of that,</p>
<p>the next thing that has to happen</p>
<p>is people have to trust those systems.</p>
<p>And so once they've got a good design</p>
<p>and they start doing those testbeds,</p>
<p>there's going to be a lot of rigorous</p>
<p>testing that goes on for years</p>
<p>and then deployments will be in very low</p>
<p>risk systems where</p>
<p>if you do have something, go on, go down</p>
<p>that it's know.</p>
<p>No one's going to get hurt.</p>
<p>No one's going to get hurt. Right.</p>
<p>So, yeah,</p>
<p>probably start out with wastewater</p>
<p>because wastewater is pretty</p>
<p>you know, it's you don't it's smelly.</p>
<p>That's about. It.</p>
<p>Well, you can kill your bugs,</p>
<p>but then it's easy to recover from,</p>
<p>or at least it's recoverable in ways</p>
<p>that other other technologies aren't.</p>
<p>So, yes, I think we will get there.</p>
<p>But it's it is a slow process.</p>
<p>You know, we.</p>
<p>Can't put too much reliance on</p>
<p>patching is the only compensating control.</p>
<p>I know that the security created</p>
<p>a lot of toxic patch.</p>
<p>Your system</p>
<p>and security hygiene is important.</p>
<p>Absolutely.</p>
<p>But as we're as end is indicating,</p>
<p>you don't you can't rely on that</p>
<p>as your only major compensating control</p>
<p>and that's why</p>
<p>when we look at an OT system security,</p>
<p>it's got to be an overall evaluation</p>
<p>from the security aspect,</p>
<p>not just can I patch the operating system,</p>
<p>the firmware.</p>
<p>Well, I think that's the number one tool</p>
<p>that it uses, right, for security?</p>
<p>It is. It's one of many categories.</p>
<p>And that's really the goal</p>
<p>here, is finding out the right security</p>
<p>control, the right security tool</p>
<p>to mitigate the risk.</p>
<p>It's not always going to be in the case</p>
<p>of what we're talking about,</p>
<p>it often can't be it can't go for years.</p>
<p>And that's four years of risk</p>
<p>that you should not be,</p>
<p>you know,</p>
<p>are accepting within your organization.</p>
<p>So that's where, you know, segmentation</p>
<p>encryption, strong</p>
<p>authentication inspection detects</p>
<p>and prevention, all these kind of things</p>
<p>come into play, providing the</p>
<p>surrounding controls to compensate</p>
<p>for the one that you can't use, which.</p>
<p>Is that you can't touch them. No, no, no.</p>
<p>I like to add another thing</p>
<p>in the OT space.</p>
<p>I know it's very different in i.t.</p>
<p>If we have an asset</p>
<p>that has been compromised,</p>
<p>we typically we isolate it.</p>
<p>After we've done some forensics on it,</p>
<p>we isolate it right?</p>
<p>Then we restart it,</p>
<p>we clean it and restart it.</p>
<p>That's a typical pattern.</p>
<p>I can't do that in the old space.</p>
<p>Right. I can not.</p>
<p>Easily not know</p>
<p>without a great deal of expense.</p>
<p>And we're taking other things</p>
<p>down with it. Right.</p>
<p>So unless you're super lucky.</p>
<p>Yeah.</p>
<p>So what approach</p>
<p>can I use in the Iot space if I know that</p>
<p>I have a device that's been compromised,</p>
<p>what do I do?</p>
<p>I if I can't take it down</p>
<p>because maybe I am</p>
<p>a policy controller in a refinery</p>
<p>and we know once you set a refinery down,</p>
<p>it takes a long time to bring it back up.</p>
<p>Right.</p>
<p>So what do I do and</p>
<p>what techniques do I have at my disposal?</p>
<p>Yeah,</p>
<p>and I'm trying to think through that.</p>
<p>And and I have to say,</p>
<p>that is a really good question</p>
<p>and what I've never asked myself.</p>
<p>And so I'm hoping Steve hasn't.</p>
<p>I'm up all night worrying about stuff.</p>
<p>Like this, about this,</p>
<p>because that's a that's a super tough one</p>
<p>because besides higher monitoring you</p>
<p>and then trying to add something else</p>
<p>into the chain that allows you to see</p>
<p>to see if that is really being exploited</p>
<p>or it's what the real status is.</p>
<p>I have no good answers for you.</p>
<p>So let's make a distinction</p>
<p>between something</p>
<p>that you find to be absolutely vulnerable</p>
<p>to an exploit</p>
<p>and something that has been</p>
<p>has been exploited.</p>
<p>Okay, that's fair enough.</p>
<p>So you've got a known vulnerability</p>
<p>that's active exploitation in the field.</p>
<p>There are controls</p>
<p>you can put in place to isolate</p>
<p>signals and inspect the traffic to</p>
<p>and from a device</p>
<p>to monitor it for aberrant behavior.</p>
<p>There are things you can do today</p>
<p>and you can do that.</p>
<p>The IT world.</p>
<p>You can do that. The world.</p>
<p>Oftentimes you have to do that</p>
<p>when you have a known vulnerability</p>
<p>that doesn't have a patch.</p>
<p>But it's active exploitation.</p>
<p>In the case of a zero day,</p>
<p>you don't have a patch, but you can turn</p>
<p>on, you know, turn the dial to 11</p>
<p>on the infrastructure of security.</p>
<p>Like long log log.</p>
<p>In the event that you have a OT system</p>
<p>that has been compromised.</p>
<p>So you're detected the aberrant behavior.</p>
<p>You've detected the signature</p>
<p>of a OT style attack</p>
<p>or you've noticed</p>
<p>the firmware has been swapped out.</p>
<p>That's where, you know, again,</p>
<p>in the good parts of systems that they're</p>
<p>highly redundant and often place.</p>
<p>So that's where you're going to kick in</p>
<p>your your process and procedures</p>
<p>that you have for</p>
<p>if it was a non cyber event, if it was a.</p>
<p>Physical,</p>
<p>if it is a physical event. Gotcha.</p>
<p>So it's the same way is</p>
<p>when if a power station goes down</p>
<p>because of a weather storm,</p>
<p>you have redundancy</p>
<p>built the system to help handle the load.</p>
<p>If you're under active, explain your bet.</p>
<p>You have been attacked.</p>
<p>You've identified a a power generator or</p>
<p>a transformer that has been compromised.</p>
<p>Kick in the process</p>
<p>you already have for dealing with the</p>
<p>every other kinds of outage</p>
<p>and take that thing offline</p>
<p>before it can infect the neck.</p>
<p>And we've seen</p>
<p>where cascading events can happen,</p>
<p>where you get one OT system, in fact,</p>
<p>because you don't have</p>
<p>often the inspection tools,</p>
<p>the lateral movement</p>
<p>can be a lot faster to the systems</p>
<p>that it's connected to because again,</p>
<p>there isn't the same level of controls</p>
<p>once it's into that, you know, it's</p>
<p>the old adage of the the egg,</p>
<p>you know, you've got a harder shell,</p>
<p>but once you get in, it's nice and soft.</p>
<p>OTI systems are often the same way</p>
<p>once you get past the door on one of those</p>
<p>key mission critical air</p>
<p>systems is compromised.</p>
<p>You may have to take a lot of it</p>
<p>offline, but</p>
<p>again, it's that's</p>
<p>where you kick in the existing processes.</p>
<p>And one advice that we give to CISOs</p>
<p>and organizations is game the system</p>
<p>before you ever get a vulnerability</p>
<p>or an exploit you have to deal with,</p>
<p>run the war gaming on your environment.</p>
<p>Actually, you know, identify a policy</p>
<p>and have it be quote unquote</p>
<p>taken out and run the course</p>
<p>and see what would be the problem.</p>
<p>Make sure you've covered all your bases</p>
<p>and you know what</p>
<p>the procedures and people</p>
<p>all the way at the tactical edge</p>
<p>and at the executive level</p>
<p>all know their role in the event</p>
<p>so will make</p>
<p>when it does that much smoother.</p>
<p>So what you're telling me is run</p>
<p>my own business continuity scenarios.</p>
<p>That's which makes.</p>
<p>Yeah. And I have to have them.</p>
<p>There's a really good context</p>
<p>for doing that.</p>
<p>Every manufacturing facility,</p>
<p>at least in the U.S., is required</p>
<p>to do what they call has ups,</p>
<p>and it's exactly what Steve described.</p>
<p>They don't tend to focus on cyber threats,</p>
<p>although I'm</p>
<p>sure that's that is definitely evolving</p>
<p>and that is happening now.</p>
<p>It tends to be more, hey, this pump fails</p>
<p>or we had a power failure or a.</p>
<p>Hurricane or tornado hit somewhere.</p>
<p>But it's very easy</p>
<p>to take that methodology and say,</p>
<p>now let's apply that to our system.</p>
<p>It's been hacked and it's been hacked</p>
<p>in these particular ways.</p>
<p>Now, what does that really mean?</p>
<p>And what is going to be our response and</p>
<p>how can we design in mitigations, Right?</p>
<p>And how can we change our system?</p>
<p>So so if it does happen,</p>
<p>there's much less vulnerability, right?</p>
<p>Or it's back to can we</p>
<p>can we live with that?</p>
<p>Because some things you can live</p>
<p>with. Right, right, right, right.</p>
<p>Guys, this</p>
<p>has been this has been very insightful.</p>
<p>As always. I love talking to you guys.</p>
<p>Any last words for our our listeners</p>
<p>today</p>
<p>on that are dealing with this opportunity</p>
<p>so things what would your advice</p>
<p>be to them that are that are dealing with</p>
<p>you know this convergence</p>
<p>that we're already starting to see.</p>
<p>We'll go with you first, Steve.</p>
<p>Okay.</p>
<p>So I think,</p>
<p>you know, just restating what we said</p>
<p>earlier is that it is already happening.</p>
<p>It's not a wait and see</p>
<p>when when this happens.</p>
<p>Your AT&T systems are blurring.</p>
<p>And so it's take to take</p>
<p>the measured approach</p>
<p>of understanding your assets, providing,</p>
<p>you know, doing the risk assessment</p>
<p>so that you can apply proper controls</p>
<p>and security</p>
<p>to the systems</p>
<p>you have and start planning for it.</p>
<p>And then the key is get out of analysis</p>
<p>phase, get into implementation.</p>
<p>So get, you know,</p>
<p>knowing that this is going to be ongoing.</p>
<p>If you spend all your time</p>
<p>analyzing your environment</p>
<p>and not only your time actually</p>
<p>implementing controls,</p>
<p>you're never going to get anywhere.</p>
<p>It's a feedback loop.</p>
<p>So you you analyze and you go deploy</p>
<p>feedback into the analysis and continue.</p>
<p>So it's going to constant processes</p>
<p>and continuous security assessment.</p>
<p>Is not a one and done.</p>
<p>It's not a one and done and the you know,</p>
<p>the key thing is to start deploying</p>
<p>the security now and getting that</p>
<p>visibility into your environment.</p>
<p>Is that the first step in being able</p>
<p>to understand what's going on</p>
<p>and what your risk posture is</p>
<p>and what your risk and be able to</p>
<p>then manage</p>
<p>that risk across your own enterprise.</p>
<p>Sounds good to Ana.</p>
<p>Yeah, and I would say on the O2 side,</p>
<p>you as an operational companies</p>
<p>start bringing in your I.T folks</p>
<p>and treating them like they're part</p>
<p>of your operations and make sure</p>
<p>that they understand the implications,</p>
<p>make sure they are equally involved</p>
<p>in all of these discussions</p>
<p>because the there is no longer,</p>
<p>as you know, a reasonable</p>
<p>that treats them in a</p>
<p>in isolation and just has them</p>
<p>worried about your pieces.</p>
<p>They they need to be integrally involved</p>
<p>in what's happening</p>
<p>and they need to help bridge the gap</p>
<p>between what we understand</p>
<p>of the operational systems</p>
<p>and all the electronics</p>
<p>and all of the compute</p>
<p>that's necessary to back that up.</p>
<p>Thanks, Santa.</p>
<p>I think that's that's absolutely critical,</p>
<p>I'd say on the CSO side as well.</p>
<p>Bring the OT guys to sit at the table</p>
<p>at the top of the table with you</p>
<p>because I've seen this before</p>
<p>where C so mandates down to the OT guys,</p>
<p>you will do this.</p>
<p>And they're like, No, we're not all right,</p>
<p>But if you're sitting at the table</p>
<p>with them at the front of the table,</p>
<p>then they have a say.</p>
<p>Then you can talk about the differences</p>
<p>and really take a look at the paper.</p>
<p>It is on on the website, we talk about</p>
<p>the differences between opportunity</p>
<p>and how we're going to get over this,</p>
<p>this division. So.</p>
<p>All right.</p>
<p>Thanks again,</p>
<p>guys, for coming on the show.</p>
<p>Thank you, Darren</p>
<p>Thank you, Darren Pleasure as always.</p>
<p>Thank you.</p>
<p>Anna for your insights.</p>
<p>Thank you for listening</p>
<p>to Embracing Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcasting site or YouTube channel,</p>
<p>you can find out more information</p>
<p>about embracing digital transformation</p>
<p>and embracingdigital.org</p>
<p>Until next time, go out</p>
<p>and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
