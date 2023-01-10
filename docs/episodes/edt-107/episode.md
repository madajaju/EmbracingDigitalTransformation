---
layout: posts
title: "Put the Title Right Here"
number: 107
permalink: EDT107
has_children: false
parent: Episodes
nav_order: 107
tags:
    - EDT111
    - EmbracingDigital

date: 
guests:
    - Darren W Pulsipher

img: TBD
summary: "Summary"
---

{% include soundcloud.html id="edt107" title="#107 Put the Title Right Here" %}

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
<p>And welcome to Embracing</p>
<p>Digital Transformation,</p>
<p>where we investigate effective change,</p>
<p>leveraging</p>
<p>people, process and technology.</p>
<p>On today's episode, the importance</p>
<p>of Security and Critical Infrastructure</p>
<p>with special guest</p>
<p>Carla Trevino from IRDeto.</p>
<p>Carla, welcome to the show.</p>
<p>Thank you very much, Darren,</p>
<p>and thank you for having me here.</p>
<p>Excited for our talks.</p>
<p>Yeah.</p>
<p>So Carla</p>
<p>and I've been working together on a joint</p>
<p>effort between Intel on your demo.</p>
<p>Carlos The solution architect.</p>
<p>I'm a solution architect.</p>
<p>So we got two real geeky people on</p>
<p>on today, on the episode,</p>
<p>which should be a lot of fun.</p>
<p>And we're working together on</p>
<p>security in the Iot space,</p>
<p>which is really fascinating stuff.</p>
<p>But first, Carla,</p>
<p>before we get into the geeky stuff,</p>
<p>tell us a little bit about yourself.</p>
<p>Yeah, thank you very much.</p>
<p>Yeah. So, Carla Trevino, my name.</p>
<p>I'm originally from Mexico.</p>
<p>I'm currently</p>
<p>living in Amsterdam in the Netherlands.</p>
<p>I've had interesting path on my career</p>
<p>international wise.</p>
<p>I've lived in several countries</p>
<p>the past four years.</p>
<p>I was living in Germany.</p>
<p>I know very much what it is</p>
<p>about working cross-cultural</p>
<p>and living cross-cultural.</p>
<p>I can say that</p>
<p>I'm an engineer from background,</p>
<p>so we are geeky.</p>
<p>Would be the nice term.</p>
<p>I studied industrial</p>
<p>engineering and mechatronics engineering</p>
<p>and after a couple of years of working,</p>
<p>I decided I wanted to study</p>
<p>more engineering.</p>
<p>So I did a master's in Science</p>
<p>in Mobility Systems Engineering,</p>
<p>and where I focused in autonomous driving</p>
<p>cars, vehicles and so on.</p>
<p>So yeah, I love technology engineering.</p>
<p>That's something</p>
<p>that I'm into pretty much.</p>
<p>All right.</p>
<p>Finally, a real engineer on the show.</p>
<p>I've had others, but it's great to have</p>
<p>someone that just you love learning.</p>
<p>I can tell Carla.</p>
<p>Yes, definitely. Yeah.</p>
<p>And then also a little bit going to</p>
<p>this is you don't know.</p>
<p>I'm going to ask this question.</p>
<p>What has been some of the hardest things</p>
<p>when you move to a new culture?</p>
<p>Because you said you've moved to</p>
<p>different cultures throughout the world.</p>
<p>It sounds like</p>
<p>you've been a lot of places.</p>
<p>What's one of the hardest things</p>
<p>to get used to when you first move?</p>
<p>I would say, first</p>
<p>of all, if you don't know the language,</p>
<p>that's a great barrier.</p>
<p>So when I moved to Germany,</p>
<p>I couldn't speak any German,</p>
<p>so that was hard part to start on.</p>
<p>It's been really hard. Yeah.</p>
<p>But getting used to people's</p>
<p>behavior,</p>
<p>like people acting on different way.</p>
<p>The typical things that you don't know,</p>
<p>as if you have to tip the servers</p>
<p>when you go to a restaurant.</p>
<p>What are the normal like?</p>
<p>How do people behave</p>
<p>in certain circumstances or things</p>
<p>like that, or critical conversations</p>
<p>like maybe politics?</p>
<p>How do people talk about those things?</p>
<p>That's hard.</p>
<p>And then I always miss Mexican food,</p>
<p>so that's.</p>
<p>All I was going to say.</p>
<p>I love Mexican food</p>
<p>because I live in California</p>
<p>and I'm a I'm</p>
<p>a fourth generation Californian.</p>
<p>So we have a lot of Mexican food</p>
<p>in California.</p>
<p>And I've been to Europe.</p>
<p>There is no good</p>
<p>Mexican food in Europe. Now,</p>
<p>I can only confirms.</p>
<p>You can you can confirm that.</p>
<p>That's good to know.</p>
<p>All right.</p>
<p>Let's let's dove right into this.</p>
<p>First off, what first off,</p>
<p>what is critical infrastructure?</p>
<p>When we say that term critical</p>
<p>infrastructure, what do we really mean?</p>
<p>Well, when we talk about</p>
<p>critical infrastructure,</p>
<p>it talks about any</p>
<p>open point that can lead.</p>
<p>Or let me see, how do I not get</p>
<p>so technical into answering this question?</p>
<p>You get technical.</p>
<p>Let's start being basic.</p>
<p>So critical infrastructure</p>
<p>comes from critical</p>
<p>right on what can bring chaos</p>
<p>if it's exposed, what can be.</p>
<p>When when some when you're</p>
<p>managing something, when you're managing</p>
<p>infrastructure, if something goes wrong</p>
<p>in certain points or in certain</p>
<p>parts, that is definitely something</p>
<p>that is critical to start with.</p>
<p>We can we can start with the definition</p>
<p>part of it.</p>
<p>So any point that can be</p>
<p>that can be a trigger</p>
<p>for chaos can be considered critical.</p>
<p>So in this case, when we</p>
<p>talk about it, we're talking about chaos</p>
<p>in the real world. Yes.</p>
<p>Audience, not in the virtual world. Right.</p>
<p>This is very different than I.T.</p>
<p>infrastructure.</p>
<p>There's very little critical</p>
<p>infrastructure in the IT world.</p>
<p>In the OT world, critical infrastructure.</p>
<p>I mean, people die right</p>
<p>if things go wrong.</p>
<p>Right. Exactly.</p>
<p>I mean, chaos on like our on a people</p>
<p>level, let's call it like that.</p>
<p>So I mean,</p>
<p>it's you world, but it's chaos</p>
<p>that you can solve by fixing some things.</p>
<p>When there is chaos</p>
<p>on critical infrastructure or when you're</p>
<p>talking about transportation,</p>
<p>when there's chaos, people can die.</p>
<p>Accidents can happen.</p>
<p>Yeah. Yeah.</p>
<p>So we've seen an uptick in the importance</p>
<p>of critical infrastructure</p>
<p>over the last probably five years</p>
<p>and a little bit pre-COVID,</p>
<p>but absolutely during peak during COVID,</p>
<p>we saw critical infrastructure</p>
<p>being attacked relentlessly.</p>
<p>In some cases.</p>
<p>Have you guys</p>
<p>have you noticed that, too,</p>
<p>in the transportation world as well?</p>
<p>Definitely. More attacks more?</p>
<p>Definitely.</p>
<p>I think it's a combination</p>
<p>of probably people where bored from</p>
<p>not being able to be able to fly</p>
<p>and started to get creative.</p>
<p>People got very I mean, creativity</p>
<p>moved into like fears for other people.</p>
<p>So probably that was something</p>
<p>that was generated for being locked</p>
<p>in the time that we were locked in COVID.</p>
<p>Definitely this had started before.</p>
<p>So we would like</p>
<p>you would see certain creativity</p>
<p>that would harm</p>
<p>or that would look into people</p>
<p>just testing out, Hey,</p>
<p>what happens if I do this?</p>
<p>And but this creativity,</p>
<p>I think went beyond what we had</p>
<p>seen on the COVID period.</p>
<p>It can be a combination of people</p>
<p>being bored, of people having more time</p>
<p>to get creative while being at home or</p>
<p>of yeah, of more fears coming out</p>
<p>from people's mind and people's mouth.</p>
<p>Yeah,</p>
<p>I think that had a lot to do with it.</p>
<p>The, you know, society</p>
<p>as a whole was kind of disrupted, right?</p>
<p>With COVID worldwide</p>
<p>and people started toying around.</p>
<p>I think boredom was part of it.</p>
<p>I also think with more people</p>
<p>working from home,</p>
<p>we also increased the attack surface.</p>
<p>So now there were more people working</p>
<p>remote, even people that were working</p>
<p>in managing critical</p>
<p>infrastructure were working remote now.</p>
<p>And I think that broke down some of the</p>
<p>security measures</p>
<p>that we used to keep in place.</p>
<p>Definitely. And I mean.</p>
<p>What are your thoughts on that?</p>
<p>I mean. I am I can only agree.</p>
<p>And I think the fact that the companies</p>
<p>had to adjust so quick</p>
<p>to everyone working from home,</p>
<p>they had to adjust their networks.</p>
<p>They had to adjust the workloads.</p>
<p>They had to adjust so many things.</p>
<p>And on a sure like we can say in a very,</p>
<p>very short period of time</p>
<p>and this opened the possibilities for</p>
<p>attacks</p>
<p>into different levels than before, because</p>
<p>then if you were living in a building</p>
<p>and you had</p>
<p>let's say in that building,</p>
<p>you could have access or you could have</p>
<p>a pretend like you knew everyone was there</p>
<p>and you knew everyone was working.</p>
<p>And you probably talk</p>
<p>to your neighbors before.</p>
<p>So it opened up the possibility</p>
<p>of getting into more layers</p>
<p>than it would have been before.</p>
<p>So let's talk specific.</p>
<p>Let's drill down a little bit</p>
<p>into transportation.</p>
<p>Um, specifically and how, how is that</p>
<p>changed over the last three or four years?</p>
<p>And, and what kind of threat vectors</p>
<p>and what kind of threats</p>
<p>are we seeing in that area?</p>
<p>Well, I would talk about maybe.</p>
<p>Yeah, what has happened is</p>
<p>transportation is becoming more connected.</p>
<p>You have more services</p>
<p>that are being offered.</p>
<p>You have more connectivity</p>
<p>in vehicles and infrastructure.</p>
<p>And with connectivity,</p>
<p>there always comes the potential.</p>
<p>I mean, there comes</p>
<p>all the beauties that there are with them.</p>
<p>You can control them,</p>
<p>but if you can control them,</p>
<p>you can control them for the good</p>
<p>or for the bad.</p>
<p>Right.</p>
<p>And and this comes I mean, this comes from</p>
<p>from the services that the providers</p>
<p>are giving to the final customers,</p>
<p>those that are being transported, that</p>
<p>they want to have more digital services.</p>
<p>But also the services</p>
<p>that are being offered to the transport</p>
<p>suppliers or providers</p>
<p>from their suppliers themselves.</p>
<p>Everyone wants to become more digital.</p>
<p>Everyone wants to have more connectivity,</p>
<p>more access to data, more access</p>
<p>to information.</p>
<p>And all of that comes</p>
<p>with opening your transport network,</p>
<p>which was formerly not open.</p>
<p>So what we know as air gap,</p>
<p>so it was not connected, it was safe</p>
<p>per definition, right.</p>
<p>So and I think this is interesting</p>
<p>because you said services</p>
<p>to the customers.</p>
<p>So services like wi fi on the train,</p>
<p>other digital services like</p>
<p>streaming video and entertainment,</p>
<p>all those sorts of things.</p>
<p>I think people don't understand</p>
<p>all those sorts of things provide.</p>
<p>You need connectivity to do that.</p>
<p>Right.</p>
<p>And what you're saying is</p>
<p>they've broken down that air gap that</p>
<p>originally the train was connected,</p>
<p>but that was control systems.</p>
<p>Those were critical systems. Right.</p>
<p>Controlling the train.</p>
<p>All of a sudden,</p>
<p>those those there's connectivity between</p>
<p>those critical infrastructure and also</p>
<p>all this other connectivity that I have.</p>
<p>Is that what I'm hearing?</p>
<p>Yeah, exactly.</p>
<p>Yeah, that's that's exactly the point.</p>
<p>So what's so</p>
<p>and so why not just use the IT</p>
<p>security stuff we've been doing for years</p>
<p>and just put that on the train?</p>
<p>Why why doesn't that work?</p>
<p>Well, there are several aspects to that.</p>
<p>First aspect is when you talk about it,</p>
<p>when we</p>
<p>when we talk about like the devices</p>
<p>that are using it and the world of it,</p>
<p>we can say it's a world</p>
<p>that it's pretty standardized.</p>
<p>That's not true for the old world.</p>
<p>We have a huge ecosystem</p>
<p>with huge differences</p>
<p>in devices, fielded devices and such</p>
<p>that are following different</p>
<p>protocols</p>
<p>that are implemented on different.</p>
<p>Even if you go like internationally,</p>
<p>every country has a different way</p>
<p>of implementing and so on.</p>
<p>So it's not standardized, it's</p>
<p>not a mobile device. And</p>
<p>and therefore</p>
<p>from that side, it's already</p>
<p>a very different level from that.</p>
<p>It second level is what we discussed</p>
<p>before the</p>
<p>the differences in critical</p>
<p>infrastructure in talking about, well,</p>
<p>if you're on the train</p>
<p>and you're a person</p>
<p>and something happens to the train, well,</p>
<p>there's a possibility of persons</p>
<p>getting injured or worse.</p>
<p>So you have to from one side</p>
<p>handle it on a different level</p>
<p>because we're talking</p>
<p>about different things completely.</p>
<p>And why are you talking about</p>
<p>different things</p>
<p>and the complexities that come with that</p>
<p>go with the standardize the different</p>
<p>devices,</p>
<p>the different everything that there is</p>
<p>now. I</p>
<p>love how you said it's not standardized,</p>
<p>so it's highly heterogeneous.</p>
<p>So I can't apply</p>
<p>just one security standard</p>
<p>and just go with every</p>
<p>everyone needs to just follow this.</p>
<p>So that's one aspect.</p>
<p>And then the other one I kind of</p>
<p>want to pick out a little bit, and that is</p>
<p>if there's a problem in your i.t.</p>
<p>Network, a security problem</p>
<p>isolated in a quarantine, it.</p>
<p>Right.</p>
<p>And then I shut it down.</p>
<p>I can't do that</p>
<p>in critical infrastructure, can I? No.</p>
<p>I mean, what are you going to do?</p>
<p>Are you gonna isolate, train</p>
<p>and shut it down?</p>
<p>And, I mean.</p>
<p>Yeah, that's a big problem, right?</p>
<p>Definitely.</p>
<p>You can't just shut it down in and move</p>
<p>the move the workload somewhere else.</p>
<p>It's on a physical. Device and you cannot</p>
<p>freeze it until we see what's going on.</p>
<p>So the approach,</p>
<p>it sounds like the approach in O.T.</p>
<p>and critical is very, very different.</p>
<p>It is. It is.</p>
<p>And I think this is one of the things that</p>
<p>the industry and everyone around</p>
<p>it has to first of all, understand</p>
<p>why it's different, but also understand</p>
<p>the differences between it not.</p>
<p>I think sometimes this is not so clear</p>
<p>for certain persons or.</p>
<p>Yeah.</p>
<p>So first.</p>
<p>Especially</p>
<p>if you're a cybersecurity expert, right?</p>
<p>If you're a cybersecurity expert,</p>
<p>you just come in and say,</p>
<p>oh, that's a cybersecurity problem.</p>
<p>This is what we do, right?</p>
<p>We identify, we detect, we quarantine,</p>
<p>we do forensics on it.</p>
<p>Then we you can't do that in O.T.</p>
<p>so it's a completely different space.</p>
<p>Exactly. Yeah.</p>
<p>So this sounds to me like a disaster</p>
<p>just waiting to happen.</p>
<p>Right.</p>
<p>We've collapsed the 90 networks together</p>
<p>in some aspects</p>
<p>because I want more connectivity.</p>
<p>I want more data coming out of those</p>
<p>trains to run analytics on.</p>
<p>And at the same time, we've seen an uptick</p>
<p>in cyber threats and cyber</p>
<p>malfeasance, if that's a word.</p>
<p>And so and people that don't have</p>
<p>a real good knowledge on</p>
<p>how to do ot security.</p>
<p>Sounds like a disaster waiting to happen.</p>
<p>Is that true?</p>
<p>Well, we hope we don't get to that point.</p>
<p>So this is exactly what</p>
<p>we're trying to do.</p>
<p>We're trying to work together</p>
<p>with the industry,</p>
<p>educate on the complexities, educate.</p>
<p>We don't want to bring fear.</p>
<p>It's not about bringing fear</p>
<p>to the industry.</p>
<p>It's about opening the eyes</p>
<p>before the disaster happens</p>
<p>and looking at cybersecurity.</p>
<p>I mean, you can we sometimes do</p>
<p>this comparison.</p>
<p>It's a sad comparison, but you can see</p>
<p>cybersecurity kind of like an insurance.</p>
<p>You don't want to have the insurance</p>
<p>after your house burnt down.</p>
<p>You want to have it before it burned down.</p>
<p>You want it not to burn down,</p>
<p>of course. Yes.</p>
<p>You don't want it to have her down. Yeah.</p>
<p>You don't want to get to the point</p>
<p>where your house is on fire.</p>
<p>But if your house is on fire,</p>
<p>you want to have an insurance.</p>
<p>And this is exactly what cybersecurity</p>
<p>is going to prevent.</p>
<p>The having the fire, let's say so.</p>
<p>I mean, it's</p>
<p>a different level of complexity.</p>
<p>But we we think there's a</p>
<p>there's a lot of education</p>
<p>that needs</p>
<p>or that is happening that at the moment.</p>
<p>And we're working together</p>
<p>with a lot of players.</p>
<p>And I think this is</p>
<p>I mean, the cybersecurity on the old side,</p>
<p>I think we are all on the same side.</p>
<p>We're all wanting to educate the industry</p>
<p>to help them be aware of what there is</p>
<p>so that they consciously decide</p>
<p>that they need something</p>
<p>and take preventive measures</p>
<p>before that something happens.</p>
<p>These attacks are getting more</p>
<p>and more complex.</p>
<p>Does that mean if I do have critical</p>
<p>infrastructure that I need to hire</p>
<p>a cybersecurity expert or</p>
<p>I need to hire a firm to help me do that?</p>
<p>Or can I do it on my own?</p>
<p>Is it is it can I educate myself to do it</p>
<p>on my own or not?</p>
<p>Well. What would you say?</p>
<p>I would say it's very hard to educate</p>
<p>yourself in topics that you don't know.</p>
<p>So from one side,</p>
<p>I mean, if you're confident</p>
<p>that you are an expert on the matter</p>
<p>and that you can do it on yourself</p>
<p>because you have the expertize,</p>
<p>then it can be that you build it.</p>
<p>But if you're trying to say, hey,</p>
<p>this is something that I mean,</p>
<p>you need experts and experts are only</p>
<p>going to</p>
<p>be experts if they've done it before,</p>
<p>if they know what they're talking about.</p>
<p>So there are, of course, standards,</p>
<p>which is I mean,</p>
<p>we all work on I mean, industry works on</p>
<p>standard basis, right?</p>
<p>Sadly, what we're seeing today</p>
<p>is that the standards</p>
<p>are running behind the development</p>
<p>that is coming with the industry.</p>
<p>So of course, you can follow</p>
<p>if you want to develop things in-house,</p>
<p>you say, well, I'm following the standards</p>
<p>that are mandated.</p>
<p>The question is, is that enough?</p>
<p>And if you're not able to answer that</p>
<p>by your own,</p>
<p>probably you don't have the expertize</p>
<p>to assess</p>
<p>whether</p>
<p>what kind of cybersecurity solutions</p>
<p>you need, what kind of protections</p>
<p>do you need where you're vulnerable,</p>
<p>what are your vulnerabilities</p>
<p>and things like that?</p>
<p>So this is where your data comes</p>
<p>in, right?</p>
<p>You guys have a long history</p>
<p>of securing critical infrastructure.</p>
<p>And so</p>
<p>I'm sure you guys have seen an uptick</p>
<p>in business in the last couple of years.</p>
<p>I would guess you have.</p>
<p>Is that true to say?</p>
<p>Yeah.</p>
<p>Well, your data, it's a company</p>
<p>that started doing cybersecurity</p>
<p>and that is five zero, not one five.</p>
<p>So we've built time.</p>
<p>You know.</p>
<p>It's more than I've been alive,</p>
<p>I can tell you that. So</p>
<p>with we have experts</p>
<p>and we have expertize</p>
<p>that has been evolving as industries</p>
<p>have been evolving as this</p>
<p>malicious attacks have been evolving.</p>
<p>And we're no there's no end point to this.</p>
<p>There's going to be new ways</p>
<p>people are going to get more creative.</p>
<p>Technology is advancing and there's</p>
<p>going to be new ways of attacking.</p>
<p>But companies like our company,</p>
<p>we are a company,</p>
<p>we have around about 1000 employees,</p>
<p>but 70% of them are in research</p>
<p>and development and they're looking into</p>
<p>what kind of attacks exist</p>
<p>today, but also what kind of attacks</p>
<p>can exist in the future.</p>
<p>And we're doing the research into that</p>
<p>and we're making sure</p>
<p>that we are future proof.</p>
<p>We want to be one step ahead.</p>
<p>We want to make sure that our customers</p>
<p>are going to be protected</p>
<p>not only the moment that they get a</p>
<p>secured system, but also ask the security.</p>
<p>As the system is evolving</p>
<p>and the new use cases are coming, that our</p>
<p>our services are also evolving with them</p>
<p>and that they're going to be secured</p>
<p>in the future as well.</p>
<p>So it's not something that you just buy</p>
<p>and you implement it today.</p>
<p>You can't just buy it and say,</p>
<p>oh, I'm secure right now.</p>
<p>That makes sense.</p>
<p>And I like how you said</p>
<p>I mean, everything's evolving, right?</p>
<p>The cybercriminals</p>
<p>are getting really sophisticated.</p>
<p>We saw that with the Centennial Pipeline</p>
<p>breach.</p>
<p>That was very interesting.</p>
<p>And there's been several others as well</p>
<p>that that</p>
<p>the people thought they were air gapped,</p>
<p>but they weren't</p>
<p>because cyber criminals</p>
<p>have figured out how to bridge air gaps.</p>
<p>Now in creative, very creative ways.</p>
<p>So tell me a little bit</p>
<p>about the types of you</p>
<p>mentioned tools that you guys have,</p>
<p>but what's your approach</p>
<p>when when you talk about securing</p>
<p>critical infrastructure, what are the key</p>
<p>tenants</p>
<p>that you guys have put into place, both</p>
<p>in in process and technology?</p>
<p>Because I know you guys do both. Right.</p>
<p>And so tell tell us a little bit</p>
<p>about your portfolio,</p>
<p>what you guys have available</p>
<p>to help people?</p>
<p>Well, there is let's say there are always</p>
<p>the two sides of the story, right?</p>
<p>When it comes to, hey, I'm a customer,</p>
<p>I need some support.</p>
<p>So there are and there are different</p>
<p>levels where the customers are.</p>
<p>There are customers that really know</p>
<p>what they want and what they need.</p>
<p>And you can talk very straightforward</p>
<p>into the solutions that they need.</p>
<p>And this is where we can talk</p>
<p>about portfolio, about specifics.</p>
<p>So what do you need?</p>
<p>Are you talking about you need PKI?</p>
<p>I do need some kind of keys</p>
<p>and credentials.</p>
<p>Life cycle management.</p>
<p>Do you need are you looking into</p>
<p>protecting your network?</p>
<p>Do you need an anomaly detection system?</p>
<p>These are all solutions that we offer.</p>
<p>We offer, for example,</p>
<p>software protection as well.</p>
<p>But there's also customers</p>
<p>that are kind of more into</p>
<p>I don't know what I need.</p>
<p>I don't know what else. Yeah.</p>
<p>You don't know what you don't know, right?</p>
<p>That's tough.</p>
<p>So, I mean, we have expertize</p>
<p>and we're more than happy</p>
<p>to walk with our customers,</p>
<p>to walk with the and</p>
<p>with what kind of solutions</p>
<p>are there in the industry?</p>
<p>There are several practices</p>
<p>that you can have that you can implement.</p>
<p>For example, when you're talking about,</p>
<p>I want to protect my asset,</p>
<p>we can make some kind of guidelines</p>
<p>like device hardening to</p>
<p>detect where the vulnerabilities are</p>
<p>and detect what kind of solutions</p>
<p>are needed to mitigate those people</p>
<p>in our abilities that the customers have.</p>
<p>So we can we mostly work on implementing</p>
<p>managed services</p>
<p>because we do believe</p>
<p>that the customer needs</p>
<p>us to work together with them</p>
<p>and give them a solution.</p>
<p>As I said before,</p>
<p>not that, hey, here's what you need.</p>
<p>Put it on your on your system.</p>
<p>And there you go.</p>
<p>You're good to go because the thing that</p>
<p>the threats are evolving,</p>
<p>the hackers are getting more creative</p>
<p>technologies evolving.</p>
<p>So we want that</p>
<p>our solutions evolve with them.</p>
<p>We want to make sure that our expertize</p>
<p>is being offered</p>
<p>throughout the lifespan of the</p>
<p>of the asset that we're protecting.</p>
<p>But we can also offer what there is</p>
<p>before some kind of professional services</p>
<p>that might be needed</p>
<p>so that they're aware</p>
<p>of what they need to implement beforehand.</p>
<p>Right.</p>
<p>And I love that you guys have that service</p>
<p>because you're right, a lot of people</p>
<p>don't know how to even secure</p>
<p>their critical infrastructure.</p>
<p>Right.</p>
<p>Maybe they just use the Perdue model,</p>
<p>which is just air gapped it</p>
<p>and then someone</p>
<p>walks in with a USB key</p>
<p>and sticks it into a device</p>
<p>and all of a sudden you've got malware</p>
<p>spread throughout the whole OT network.</p>
<p>We've seen that time and time again.</p>
<p>So you guys understand the crime,</p>
<p>the criminal element,</p>
<p>let's call them what they are</p>
<p>or the nation state that's trying</p>
<p>to disrupt your critical infrastructure.</p>
<p>So it's good to have you guys come in</p>
<p>and kind of do an assessment, right?</p>
<p>This is where you're at.</p>
<p>These are the tools that you need</p>
<p>and so on and so forth.</p>
<p>I love the approach.</p>
<p>I think it's it's very valuable</p>
<p>if people want to find out more</p>
<p>about this approach and what your data</p>
<p>can bring to the table, where do they go?</p>
<p>Because are going to our website</p>
<p>that your death toll</p>
<p>you spell it irtet0 dot</p>
<p>com slash connected dash transport.</p>
<p>There you can find some information</p>
<p>about our products. Definitely.</p>
<p>There's also an option</p>
<p>to contact us directly from there.</p>
<p>And then you can like</p>
<p>we can schedule the first call</p>
<p>to get to know</p>
<p>you, that you get to know us</p>
<p>and that we start understanding</p>
<p>what the requirements are.</p>
<p>So, I mean, you can get a good understanding of our products from the website, but</p>
<p>don't be shy to ask for</p>
<p>for getting in contact with us</p>
<p>and we will make sure to give</p>
<p>that information more in accordance</p>
<p>to what the customer</p>
<p>specifically is needing or the company.</p>
<p>Oh, that's great.</p>
<p>Also, you guys, we work together, Intel</p>
<p>and your dad, we're working together</p>
<p>so that you guys can even make your tools</p>
<p>even more secure by using Intel's</p>
<p>technology under the covers.</p>
<p>So a great partner here. Ditto.</p>
<p>And Carla, thank you.</p>
<p>It's been it's</p>
<p>been very enlightening today.</p>
<p>I learned a lot of things.</p>
<p>Yeah. Thank you very much for having me.</p>
<p>And yeah, I'm</p>
<p>looking forward into our collaboration.</p>
<p>I think Bringing</p>
<p>Security Foundation from hardware</p>
<p>plus adding extra layers of software</p>
<p>on the security in top of it,</p>
<p>what Intel has to bring, plus what</p>
<p>your data has to bring will definitely</p>
<p>help the industry get one step further</p>
<p>into being more secure.</p>
<p>Thank you for listening to Embracing</p>
<p>Digital Transformation today.</p>
<p>If you enjoyed our podcast, give it five</p>
<p>stars on your favorite podcast insider</p>
<p>or YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>and embracingdigital.org until next</p>
<p>time, go out and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
