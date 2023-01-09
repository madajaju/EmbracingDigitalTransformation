---
layout: posts
title: Put the Title Right Here
number: 101
permalink: EDT101
has_children: false
parent: Episodes
nav_order: 101
tags:
     - EDT111
    - EmbracingDigital
date: 
guests:
    - Darren W Pulsipher
img: TBD
summary: Summary
---

{% include soundcloud.html id="edt101" title="#101 Put the Title Right Here" %}

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
<p>is Darren Pulsipher chief solution</p>
<p>architect of public sector at Intel.</p>
<p>And welcome to Embracing</p>
<p>Digital Transformation,</p>
<p>where we investigate effective change,</p>
<p>leveraging</p>
<p>people, process and technology.</p>
<p>On today's episode, Network</p>
<p>Controller Security with Dana Yanch</p>
<p>and Dan Demers from Elisity.</p>
<p>Dan, Dana, welcome to the show.</p>
<p>Thanks.</p>
<p>Thanks.</p>
<p>Hey, Dana,</p>
<p>tell us a little bit about your background</p>
<p>and why we're talking today</p>
<p>and then we'll head over to Dan.</p>
<p>Yeah, absolutely. Thanks, Darren.</p>
<p>So I'm Dana Yanch, director of technical</p>
<p>marketing at Elisity.</p>
<p>My background as well has been hard</p>
<p>core networking for the last 15 years.</p>
<p>A lot of software</p>
<p>defined networking, wide area networking,</p>
<p>the SDWAN world, which is something</p>
<p>I was focused on for a long time.</p>
<p>And then the cloud world,</p>
<p>I went to work for a company</p>
<p>called Aviatrix for a period of time</p>
<p>and it's been great.</p>
<p>But I came back to my roots</p>
<p>here on network security at Elisity</p>
<p>Great.</p>
<p>Thanks.</p>
<p>Dana, what about you?</p>
<p>Dan, your background</p>
<p>is different than Dana's.</p>
<p>I know that it's as we've talked</p>
<p>quite a few times.</p>
<p>Yeah, I started</p>
<p>I've been the networking most of the time,</p>
<p>but I started out in the services area</p>
<p>with advanced services at Cisco</p>
<p>for a few years down oil did some oil</p>
<p>and gas work down in Houston.</p>
<p>And then I moved over into kind of SASE</p>
<p>amd SDWAN space</p>
<p>after that for several years and then</p>
<p>worked with Dana in the past.</p>
<p>And then we jumped over here to Elisity</p>
<p>and now more focused on</p>
<p>network security,</p>
<p>but also software defined security.</p>
<p>It's kind of a an elusive term</p>
<p>here in the sense of we're quite lans,</p>
<p>but from a micro segmentation to identity.</p>
<p>Yeah, this</p>
<p>is something really unique about what</p>
<p>your guys's approach to securing networks</p>
<p>and things like that.</p>
<p>Very different</p>
<p>than what I've seen traditionally</p>
<p>and what I learned right</p>
<p>when I started doing networking.</p>
<p>It's very different, very unique.</p>
<p>So I was very fascinated.</p>
<p>So let's start off</p>
<p>with the first question why?</p>
<p>Why not just use </p>
<p>VLANs and firewalls</p>
<p>just to protect my network?</p>
<p>Isn't that good enough</p>
<p>to create micro segmentation?</p>
<p>Because that's what I was told.</p>
<p>So yeah. Why</p>
<p>why do any different than that?</p>
<p>Okay. Yeah,</p>
<p>it's it's it's a pretty common question.</p>
<p>We've been doing one way,</p>
<p>one thing for a long time.</p>
<p>And and why?</p>
<p>Why fix what's potentially not broken?</p>
<p>But actually it is</p>
<p>it's quite broken in this day and age.</p>
<p>So I mean, for me to talk about that</p>
<p>in the preface to it a little bit</p>
<p>about what we've</p>
<p>been focused on for the last 15 years</p>
<p>or more in network security,</p>
<p>and that's been hardening</p>
<p>the perimeter of the network.</p>
<p>I'm sure you've heard that</p>
<p>that terminology</p>
<p>before, the perimeter of the network.</p>
<p>And that's things</p>
<p>like when as the Internet, as DMS,</p>
<p>these remote access edge.</p>
<p>And so what we've spent a lot of time</p>
<p>and energy spent there making this</p>
<p>impenetrable wall around our enterprises,</p>
<p>and that's still important.</p>
<p>But the problem, that</p>
<p>problem's been solved for a long time.</p>
<p>Firewall firewalls doing an incredible job</p>
<p>keeping people out of the network.</p>
<p>But for the most part,</p>
<p>we neglected the inside of the network</p>
<p>where there's been this explosion</p>
<p>of new connectivity requirements</p>
<p>because of all this Iot and IMT and OT</p>
<p>and Iot, that's just being connected</p>
<p>internally to absolutely everything,</p>
<p>to the Internet too, to resources. And</p>
<p>so, you.</p>
<p>Know, it reminds me we did</p>
<p>we did a podcast on Zero</p>
<p>Trust Architectures</p>
<p>and we compared it to a castle.</p>
<p>So what you're telling me</p>
<p>is you built a really strong moat.</p>
<p>You built really strong walls</p>
<p>around your castle,</p>
<p>and we've done a great job at that.</p>
<p>But what you're saying</p>
<p>is inside the castle, once I'm inside,</p>
<p>it's like a free for all.</p>
<p>Yeah. A pretty safe to say. Exactly.</p>
<p>For the most part, that's. That's</p>
<p>pretty much what we've seen.</p>
<p>We've been looking at a lot of networks</p>
<p>with our customers and finding out that</p>
<p>the inside of the network</p>
<p>has been implicitly permitted</p>
<p>because, you know,</p>
<p>if you've made it past this robust</p>
<p>outer wall and into the network,</p>
<p>you must be a legitimate.</p>
<p>You must be.</p>
<p>Yeah, exactly.</p>
<p>But that's really not the case.</p>
<p>It's not the case this day.</p>
<p>And so,</p>
<p>I mean, as you're</p>
<p>well aware, the majority of the attacks</p>
<p>that are happening</p>
<p>these days are happening</p>
<p>from the inside of network, namely</p>
<p>from exploited trusted users, devices</p>
<p>and applications.</p>
<p>It's almost like the Trojan horse.</p>
<p>Well, that's</p>
<p>where Trojan Horse came from. Right.</p>
<p>The whole concept. Yeah. Right.</p>
<p>They brought the Trojan horse</p>
<p>inside the security walls of Troy.</p>
<p>Right.</p>
<p>That's what happened.</p>
<p>That's right.</p>
<p>I mean, then they came out</p>
<p>and killed everyone, right? Yeah.</p>
<p>I mean, what that means</p>
<p>is that these threat actors, they're</p>
<p>crawling around the network that's that's</p>
<p>got all these channels that are fully open</p>
<p>that we've never sat down and analyzed.</p>
<p>And it's shut down, you know, made it</p>
<p>so that only what you need to access to do</p>
<p>your job is open</p>
<p>and everything else is closed off</p>
<p>or that's something</p>
<p>we totally just ignored.</p>
<p>And now it's time to go back and fix this,</p>
<p>because all sorts of organizations</p>
<p>are being,</p>
<p>you know, brought to their knees because</p>
<p>of all the threats that are happening now.</p>
<p>All right.</p>
<p>So but the term I've heard on</p>
<p>this is just Microsoft mentation.</p>
<p>Yeah.</p>
<p>So why not just create a bunch of VLANs</p>
<p>with firewalls around each Phelan and say,</p>
<p>hey, only these applications</p>
<p>can talk to each other and why not?</p>
<p>Why not just go that route? That's right.</p>
<p>Yeah, it's a good question.</p>
<p>And that's the we need to answer here.</p>
<p>That's what</p>
<p>we've been focused on solving for adults.</p>
<p>See the problem with traditional</p>
<p>mechanisms of segmentation</p>
<p>and I say that lightly</p>
<p>when we talk about VLANs,</p>
<p>but things like leveraging VLANs</p>
<p>or IP, ACLs</p>
<p>or firewalls with access control entries</p>
<p>in them, there's all sorts of reasons</p>
<p>why they don't work today</p>
<p>for lateral movement security.</p>
<p>They worked</p>
<p>great for the edge of the network</p>
<p>and they were great for very specific</p>
<p>maybe bottlenecks or aggregation points.</p>
<p>I'll talk about three common ones. Okay.</p>
<p>And that should frame the conversation</p>
<p>pretty, pretty, pretty.</p>
<p>Well.</p>
<p>So number one, VLANs, ACLs,</p>
<p>firewalls, their scalability</p>
<p>and operational efficiency</p>
<p>is questionable, right?</p>
<p>Managing VLANs,</p>
<p>IP, ACLs and firewalls across</p>
<p>large enterprises is done quite manually.</p>
<p>Right.</p>
<p>It's not a scalable mechanism.</p>
<p>It's not a distributed</p>
<p>software-defined architecture.</p>
<p>It requires a box by box</p>
<p>configuration, line by line.</p>
<p>They're not dynamic in any way</p>
<p>and they don't respond to anything</p>
<p>happening on the network.</p>
<p>They're just not intelligent</p>
<p>enough. Right.</p>
<p>These are kind of dumb mechanisms that</p>
<p>kind of work for certain environments.</p>
<p>But in the grand scheme of things,</p>
<p>for large enterprises,</p>
<p>lateral movement</p>
<p>is not a efficient way to do this.</p>
<p>What happens also that we've seen</p>
<p>is that you might try to use</p>
<p>these features, these functionalities,</p>
<p>and you'll come back and realize that</p>
<p>there's a network full of random holes.</p>
<p>It's like a Swiss cheese network</p>
<p>because people have put little access</p>
<p>control entries that allow this and that.</p>
<p>And out of nowhere you now have.</p>
<p>Well, that would be me.</p>
<p>Yeah, yeah.</p>
<p>Just yeah, that's that's your,</p>
<p>that's your software developers, right.</p>
<p>They do that all over the place. Yeah.</p>
<p>Because we just want the thing to</p>
<p>work, right.</p>
<p>So we're like, okay, we're under pressure.</p>
<p>Let's just make it work</p>
<p>and nobody comes back. Results for</p>
<p>I'm your</p>
<p>worst user as far as security goes,</p>
<p>because if I need to download something</p>
<p>or if I need a port open</p>
<p>so I can attach to an external service,</p>
<p>I open the port.</p>
<p>Yeah, right. Right.</p>
<p>I don't ask permission.</p>
<p>So Dan, you were going to say</p>
<p>something about this.</p>
<p>How do you manage?</p>
<p>ALL Yeah, one of the,</p>
<p>one of the things that always hit me</p>
<p>was that your users are your greatest</p>
<p>asset, but also your biggest risk in</p>
<p>the sense of users are especially</p>
<p>the operators of networks in the sense of,</p>
<p>hey, I'm going to open up that VLAN</p>
<p>or change this one piece</p>
<p>just to do a quick test.</p>
<p>But then don't undo the change.</p>
<p>Or well, because something else happened.</p>
<p>Or VLANs started,</p>
<p>especially the VLAN example.</p>
<p>We've actually seen this in the real world</p>
<p>numerous times where a VLAN</p>
<p>or some kind of verve or a construct</p>
<p>will start with a use case</p>
<p>and then it will slowly creep</p>
<p>to other use cases.</p>
<p>And all of a sudden what was a ten device?</p>
<p>VLAN is now having 40, 50, 60 devices</p>
<p>and in the OTTI world</p>
<p>it might have six or seven</p>
<p>different processes running inside of it</p>
<p>because that's the that was the trusted</p>
<p>this, you know, the safety lan</p>
<p>that wasn't the dirty one.</p>
<p>But then it kind of blew up over ten years</p>
<p>because these environments often</p>
<p>they're static a</p>
<p>lot of the time, but they kind of go slow</p>
<p>and are documented.</p>
<p>Yeah. Okay.</p>
<p>So this brings up something interesting</p>
<p>what you're saying is</p>
<p>VLANs and firewalls do work</p>
<p>in very static environments</p>
<p>where I can where I know everything</p>
<p>that's going to happen on there and</p>
<p>and in small scale.</p>
<p>Well, one thing.</p>
<p>That that's what I just heard, right.</p>
<p>Yeah. That's that brings me to the</p>
<p>that's fine.</p>
<p>That brings me excited</p>
<p>because that brings me to the other</p>
<p>two points</p>
<p>around the efficacy of these mechanisms.</p>
<p>Right.</p>
<p>The fact that VLANs and firewalls</p>
<p>are inherently</p>
<p>in the wrong place in the network</p>
<p>to provide lateral movement.</p>
<p>Security is the big problem.</p>
<p>I mean, if you're in the same VLAN</p>
<p>as another device that community</p>
<p>or user</p>
<p>or application, that communication channel</p>
<p>is completely open and available</p>
<p>even though it may not have to be.</p>
<p>And firewalls are typically</p>
<p>not even deployed</p>
<p>in a strategic place where it can handle</p>
<p>that access level of lateral movement.</p>
<p>You have to funnel traffic</p>
<p>up to a firewall, get it back down.</p>
<p>It's just it's not the most efficient.</p>
<p>Then you have a bottleneck.</p>
<p>Yeah, yeah.</p>
<p>So just</p>
<p>they're not even seeing the traffic</p>
<p>that we're trying to secure</p>
<p>most of the time.</p>
<p>Interesting. Very interesting. Yeah.</p>
<p>So that goes into that scalability</p>
<p>issue as well then.</p>
<p>Yeah, right.</p>
<p>The first off,</p>
<p>they're not catching the right traffic.</p>
<p>Doesn't really prevent lateral movement</p>
<p>inside the same network, right.</p>
<p>Yeah.</p>
<p>And not to me,</p>
<p>if I'm a VLAN and I have a process running</p>
<p>inside, that's some kind of use case.</p>
<p>What's to stop me from going from port</p>
<p>three to port 32 in the same VLAN?</p>
<p>Now if there's nothing,</p>
<p>there is nothing to do and it comes down</p>
<p>to what was the intended,</p>
<p>what's the intended function</p>
<p>that should be occurring versus</p>
<p>what could occur.</p>
<p>And that's too often people will design</p>
<p>security around what they they'll put</p>
<p>security up into a point of, all right,</p>
<p>this is what I'm going to allow.</p>
<p>I'm thinking it's a white list,</p>
<p>but it's not.</p>
<p>They don't actually think of</p>
<p>how could this be turned around and used</p>
<p>differently because when when bad actors</p>
<p>are looking at networks</p>
<p>and not looking of how</p>
<p>they should be functioning,</p>
<p>they're looking at how they can take</p>
<p>what is functioning and twisted</p>
<p>to get some type of outcome</p>
<p>they're looking to do.</p>
<p>And they're not using your tools.</p>
<p>They're using their tools.</p>
<p>Well,</p>
<p>isn't that a developer as well as a saw?</p>
<p>I'm a software developer. Right.</p>
<p>And and I'm trying to find ways</p>
<p>to get my work done most effectively.</p>
<p>And I will jump ports.</p>
<p>I do that. Right, which is awful.</p>
<p>I know I'm but I do jump ports,</p>
<p>especially</p>
<p>if for some reason a port goes down, I'm</p>
<p>going to jump ports onto something else</p>
<p>and try other through a range of ports.</p>
<p>I mean, that's</p>
<p>just something that I've done.</p>
<p>Yeah, but what you're saying is</p>
<p>that's kind of dangerous is in,</p>
<p>in the current VLAN environment. Right.</p>
<p>Because I, I'm kind of open.</p>
<p>Yeah, you're absolutely right.</p>
<p>In firewalls, nobody is placing</p>
<p>far hundreds or thousands of firewalls</p>
<p>across the entire access edge</p>
<p>to get that type of visibility.</p>
<p>If be impossible to manage</p>
<p>and it be fiscally restrictive.</p>
<p>There's no way</p>
<p>a lot of organizations can handle</p>
<p>putting these firewalls everywhere.</p>
<p>So so isn't that isn't that the balance</p>
<p>the balance between flexibility</p>
<p>that I need to actually deliver my</p>
<p>application or my data and also security?</p>
<p>Aren't they at odds with each other? Yeah.</p>
<p>Yeah, to an extent.</p>
<p>They are at odds</p>
<p>and it be based on current technologies</p>
<p>because for the last 15, 20 years,</p>
<p>ever since the firewall, you know,</p>
<p>in the nineties</p>
<p>really kind of became a thing.</p>
<p>The it's been the go to tool, hey,</p>
<p>I need security.</p>
<p>I'll throw a firewall and hey,</p>
<p>I've got to separate two things.</p>
<p>I'll throw a firewall.</p>
<p>And it's always been this L-3 two or three</p>
<p>hops up in the network kind of thinking</p>
<p>and the whole market,</p>
<p>all the vendors, including have,</p>
<p>you know, the major vendors have kind of</p>
<p>gone down that path in the sense of, hey,</p>
<p>you know,</p>
<p>we're going to invest there because it</p>
<p>may not be the best possible way to do it,</p>
<p>but it's a way that that is rinse</p>
<p>and repeatable and that.</p>
<p>Oh I see.</p>
<p>Yeah.</p>
<p>So they first did it</p>
<p>because it was exactly.</p>
<p>What it was.</p>
<p>It was probably, you know, day 1/1</p>
<p>firewall, iteration, eighties, nineties</p>
<p>ish, true kind of modern firewall</p>
<p>thinking it was a wild success day one.</p>
<p>It's more like day 20,000, you know, some,</p>
<p>you know, many years later,</p>
<p>the success calculation is,</p>
<p>is it much different?</p>
<p>Well, and I think a lot of that</p>
<p>has to do with the scalability,</p>
<p>the sophistication of cyber attacks now.</p>
<p>Yeah, totally. So.</p>
<p>All right.</p>
<p>So what you're telling me is</p>
<p>we've got an internal combustion</p>
<p>engine, the firewall,</p>
<p>and it's time to replace it with electric.</p>
<p>I love that.</p>
<p>I'm a massive Tesla fan, so.</p>
<p>Yeah, absolutely.</p>
<p>Right.</p>
<p>So, so</p>
<p>so you have a third one that you gave me.</p>
<p>Yeah, the third one to me is probably</p>
<p>the most interesting out of them all.</p>
<p>And it's the fact</p>
<p>that these legacy solutions, these legacy</p>
<p>security slash segmentation solutions,</p>
<p>don't take into consideration identity</p>
<p>or the context or the behavior of</p>
<p>the asset that's connected to the network.</p>
<p>So it means it's really unintelligent.</p>
<p>It's a really network</p>
<p>centric topology, dependent and rigid</p>
<p>way to provide</p>
<p>some measure of basic security.</p>
<p>I mean, an IP address tells me</p>
<p>nothing about the legitimacy of the asset</p>
<p>and the network that it's attached to.</p>
<p>Right. It doesn't tell you anything.</p>
<p>So how can you secure this network</p>
<p>and dynamic fashion</p>
<p>when you don't even really know what's</p>
<p>out there connecting to the network?</p>
<p>How can you make a policy</p>
<p>in the first place without any</p>
<p>with any type of granularity?</p>
<p>If all your match yarn or five tuple</p>
<p>network constructs, that's your policy</p>
<p>match criteria.</p>
<p>It doesn't work in this day and age,</p>
<p>I think.</p>
<p>Yeah, that's really fascinating</p>
<p>because what you're saying is</p>
<p>every day, every device securing</p>
<p>the network, every device is equal.</p>
<p>That's right. Yeah.</p>
<p>They're all the same. Right.</p>
<p>How are you supposed to get graphs?</p>
<p>They all look the same,</p>
<p>right?</p>
<p>But I can't.</p>
<p>I analyze traffic and then,</p>
<p>you know, based off the type of traffic,</p>
<p>I can do different things with work.</p>
<p>But that's not how. This is happening.</p>
<p>It's going to be happening.</p>
<p>How many hands and.</p>
<p>Several hops he essentially.</p>
<p>Gets, right?</p>
<p>Yeah.</p>
<p>Which means I have exposure now.</p>
<p>And let's say let's say we</p>
<p>we tapped everything</p>
<p>and we saw everything.</p>
<p>The analysis is going to still happen</p>
<p>in the traditional thinking,</p>
<p>multiple hops away firewall thinking</p>
<p>and or some kind of appliance.</p>
<p>And then any type of enforcement</p>
<p>it may or may not be able to do</p>
<p>is going to be up there.</p>
<p>It's not going to be down here.</p>
<p>And so I might know something</p>
<p>that's very valuable</p>
<p>that's not to take away from the value.</p>
<p>It's the whole concept of,</p>
<p>you know,</p>
<p>protect, detect</p>
<p>and then kind of some kind of response.</p>
<p>That's very oversimplify it.</p>
<p>But we still need that.</p>
<p>The detection, we still need to know</p>
<p>something bad happened</p>
<p>even if we didn't protect ourselves.</p>
<p>That's incredibly and that's actually</p>
<p>an underused part of cybersecurity</p>
<p>in the sense of now</p>
<p>there's more value to be put in there.</p>
<p>But the ability</p>
<p>to stop something from happening</p>
<p>and then detect</p>
<p>something could have happened</p>
<p>and I killed it before it happened.</p>
<p>That's something that can happen</p>
<p>and should be happening at the very edge</p>
<p>of the network, as close to the asset</p>
<p>as possible, whatever that asset may be.</p>
<p>That's really interesting.</p>
<p>Let's go back to my castle.</p>
<p>I got my castle.</p>
<p>So you guys are telling me</p>
<p>as people are coming through my castle,</p>
<p>I'm sending</p>
<p>my report on who's come through</p>
<p>and what they're carrying with them off</p>
<p>to another city to go tell.</p>
<p>And they're going to analyze it.</p>
<p>And then they'll get back to me</p>
<p>on who's in my castle.</p>
<p>That's what today happens. Yeah.</p>
<p>And then they'll make a need</p>
<p>to keep the analogy going.</p>
<p>They'll make a rule somewhere in the road</p>
<p>outside the city of.</p>
<p>Hey, if anyone comes,</p>
<p>it goes from the city.</p>
<p>We're going to kill that,</p>
<p>you know, that behavior.</p>
<p>But the what if and it's not even a</p>
<p>what if the</p>
<p>what happens often</p>
<p>is it all stays within that little realm.</p>
<p>It doesn't actually leave</p>
<p>and go to the other city</p>
<p>or hit the highway and so forth.</p>
<p>You know, great analogy.</p>
<p>Oh, very, very fascinating.</p>
<p>Okay, guys.</p>
<p>So we've scared everyone.</p>
<p>Oh, there's a. Solution. Don't worry.</p>
<p>To find out about a solution</p>
<p>to solve the network</p>
<p>controller security problems,</p>
<p>listen to Dana and Dan explain.</p>
<p>Identity based micro segmentation</p>
<p>in the second part</p>
<p>of this interview.</p>
<p>Thank you for listening</p>
<p>to Embracing Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcasting site or YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>and embracingdigital.org</p>
<p>until next time, go out</p>
<p>and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
