---
layout: posts
title: "Myths of Lift and Shift Cloud Migration #112"
number: 112
permalink: EDT112
has_children: false
parent: Episodes
nav_order: 112
tags:
    - EDT112
    - EmbracingDigital
    - Multi-Cloud
    - Cloud Migration
    - Cloud

date: 
guests:
    - Darren W Pulsipher
    - John Evans

img: TBD
summary: "Darren Pulsipher, Chief Solutions Architect, Public Sector, Intel, and John Evans, Chief Technology Advisor, WWT, discuss five lift and shift cloud migration myths."
---

{% include soundcloud.html id="edt112" title="#112 Myths of Lift and Shift Cloud Migration #112" %}

{% include youtube.html id="7pQKyV45ay4" %}

---

John started his career in technology at the help desk at a principal defense contractor 20 years ago. As his career progressed, he got into cybersecurity and enterprise architecture. He worked as a contractor for the Defense Information Systems Agency (DISA), where he was the lead architect for the Department of Defense DISA cloud. Eventually, the state of Maryland brought him in to lead the digital transformation efforts for the state, including cloud migration. That migration was the largest ever done across state and local education.

After that, he transitioned to the state Chief Information Security Officer (CISO) position, overseeing high-level operations, security, and governance. He left government service and joined WWT about three years ago. He works primarily in state and local education, although he helps in other public sector areas.

## Myth One - Cloud is Cheaper

The cloud is not necessarily cheaper than an on-premise environment. Legacy applications were built for the on-prem environment, so there is no issue with auto-scaling. It is a  consumption-based model, and there are already sunk costs, such as the servers. Most products meant to help organizations move applications to the cloud don’t support auto-scaling, so when they are forced to the cloud, they now have to be max provisioned at all times, which doesn’t often translate into cost savings. Customers are likely paying more than they were for the same capabilities on-prem.

When Darren worked with the Canadian government, they moved an SAP instance into the cloud. It was max provisioned, running 24/7, and they blew through their budget in just six months. When they discovered this problem, they turned it on and off every day since the instance didn’t need to run 24/7. They saved a lot of money by reducing it to 14-16 hours a day.

Access must be available at all times in a department such as Health and Human Services, which is typically the largest in a state IT budget, but it is possible to bring it down to a minor instance during off hours to save money.

The Cloud Service Providers (CSP) now offer cloud-native services that are being fulfilled by a third-party application or OEM product that can provide a similar capability with cost savings.  This won’t work with everything, as some legacy applications are not developed to leverage some of the cloud-native applications. It would be best to be careful about getting locked into a specific cloud. If, for example, you use proprietary AWS services, it could be challenging to extricate an application and move to Azure and vice versa.

John advises organizations to ask if it makes sense to move into the cloud. It’s not a good reason to move to the cloud because you think you should. You might end up with elevated expenses and frustrating superiors and workers because the strategy was not thoroughly thought through.

## Myth Two - Cloud Erases Technical Debt

Moving into the cloud does not eliminate technical debt in almost any case. It exposes and accelerates the debt. You will find exposure points if you take something running for 30 years and move it into a new environment. The acceleration part is that you have a more technical debt to worry about now that it's exposed.

Technical debt means you have systems falling behind what they should be. For example, when John first went to work for Maryland, some systems were still running on green screens. It was easy for current employees to navigate but had a steep learning curve for new users. Although the system had been working for many years, the downside of this technical debt is the amount of training necessary and retaining employees. More recent generations coming into the workforce who are knowledgeable on the latest trends and developments don’t want to deal with legacy applications.

Technical debt also means security issues. If a legacy application has not been updated, you may not be able to apply patches for fear of breaking it. This creates security vulnerabilities you must accept until you get out of the technical debt cycle.

A common reaction in an organization is to bolt on a bit of extra code when necessary to accommodate, for example, a rule change from a state legislature. This does not fix a problem; instead, the system ends up with a lot of spaghetti code, making it impossible to recreate the system for an update. One of the concepts in the cloud is breaking up your system into modules or microservices, but the spaghetti code does not allow for this since you can’t just pull out a piece of it.

This makes organizations even more hesitant to modernize because they’ve been doing things the wrong way for all these years. When something does break and becomes the impetus for this change, it’s even more challenging.

Sometimes it might make sense to scrap the old system and start fresh. This is costly, and you must have the new system before you toss the old system. For some organizations, however,  such as states, which can get federal funding for departments such as Health and Human Services, it might be the best choice. In a situation like this, you can also figure out the benefit of reusability, such as templates and governance structures for other departments.

## Myth Three - Cloud is Secure

Moving into the cloud does not necessarily make securing applications easier, although you don’t have to worry about physical security or hypervisors, for example. Cloud providers have a shared responsibility model in various forms. You have to understand what you are responsible for with each provider and what they are responsible for. It doesn’t just change with the provider but also with what services you consume. This can make security more complex for your security teams because they must stay on top of all the different variations across providers and services.

## Myth Four - Cloud is Easy

Migration to the cloud is complex. It is, in fact, easier to run everything in your own data center, not connected to the internet. Security is easy this way, and cost models are simple. However, you can’t grow. You can’t provide services to your constituents or customers, and you can’t satisfy mission needs, among other issues. The world is complex, and migration to the cloud is complicated.

## Myth Five - A New Skillset is not Necessary.

A knowledge gap can also add to the pain points around that complexity. Software developers and other IT specialists must change how they think about computing in the cloud, especially surrounding security. For example, software developers shouldn’t be spinning up instances in the cloud wherever they want or downloading things from GitHub or other repositories, grabbing libraries to make things work. This opens up all the firewall rules because they may not pick correctly. Guardrails must be implemented when moving to the cloud, which requires change. Working in the cloud requires a different skill set and mindset. Most importantly, you must figure out better ways to manage security with sophisticated ransomware and cyber attacks.


<details>
<summary> Podcast Transcript </summary>

<p>﻿1</p>
<p>Hello, this is Darren</p>
<p>Pulsipher, chief solution</p>
<p>architect of public sector at Intel.</p>
<p>And welcome to Embracing</p>
<p>Digital Transformation,</p>
<p>where we investigate effective change,</p>
<p>leveraging</p>
<p>people, process and technology.</p>
<p>On today's episode, the Myths of Lift</p>
<p>and Shift to the Cloud with special guest</p>
<p>John Evans, Chief Technology Advisor</p>
<p>at WWT John, welcome to the show.</p>
<p>And thank you for for for having me.</p>
<p>It's my pleasure.</p>
<p>You come highly regarded</p>
<p>from someone that left</p>
<p>WWT and came to Intel and that's Hannah.</p>
<p>I know you know who Hannah is,</p>
<p>and we're glad we have her.</p>
<p>Sorry we stole her from you.</p>
<p>But we're happy</p>
<p>to have Hannah on our team.</p>
<p>So a shout out to Hannah on that one?</p>
<p>Absolutely. She definitely deserves it.</p>
<p>I'm still a little bitter.</p>
<p>I'm totally kidding. But no.</p>
<p>And it is is is awesome.</p>
<p>I totally concur. They're</p>
<p>great.</p>
<p>So, John, tell us a little bit</p>
<p>about your background and your history,</p>
<p>how you got involved in technology</p>
<p>and all that.</p>
<p>Okay.</p>
<p>So been involved in technology</p>
<p>for about 20 years now,</p>
<p>started actually during college</p>
<p>in a in a helpdesk.</p>
<p>So I think that's not an uncommon start</p>
<p>for a lot of technologists</p>
<p>starting off and helped us.</p>
<p>But I started off doing Tier</p>
<p>one support in a</p>
<p>major defense contractor, helped us</p>
<p>their internal help helpdesk and then</p>
<p>just started moving on from from there</p>
<p>move that into a NOC</p>
<p>as a service type of position</p>
<p>started getting more</p>
<p>into the cybersecurity side the enterprise</p>
<p>architecture side worked for DISA</p>
<p>for a few years as a contractor</p>
<p>helping to architect the DOD,</p>
<p>the DISA Cloud.</p>
<p>I was one of the lead architects for that</p>
<p>and then</p>
<p>eventually came to the state of Maryland</p>
<p>where I was brought in to lead</p>
<p>the cloud migration, digital</p>
<p>transformation efforts for the state.</p>
<p>They became aware of the work</p>
<p>I'd done on the cloud, so they brought me</p>
<p>in to help out with their cloud</p>
<p>and after a few years</p>
<p>of doing that,</p>
<p>I transitioned to the State CSO position.</p>
<p>So got to see</p>
<p>at a at a high level,</p>
<p>got to do the operations</p>
<p>side as well as the security</p>
<p>and governance side.</p>
<p>And then about three years ago</p>
<p>I left government service</p>
<p>and came over to WWT</p>
<p>and it's been awesome here since.</p>
<p>So are you still doing a lot</p>
<p>in the public sector with WWT?</p>
<p>I mean, because your whole career</p>
<p>has been in the public sector.</p>
<p>Yeah, no doubt. Yeah, absolutely.</p>
<p>I work primarily in state,</p>
<p>local and education.</p>
<p>Help out a little bit</p>
<p>in some other public sector.</p>
<p>But I've really kind of focused</p>
<p>more on the state</p>
<p>local in education</p>
<p>over the last year or so.</p>
<p>I guess there's still help out</p>
<p>in some other areas, things like,</p>
<p>you know, zero</p>
<p>trust road maps coming up with the</p>
<p>WWT sort of way of doing things and cyber</p>
<p>cyber consulting.</p>
<p>So those types of of initiatives that are</p>
<p>kind of crossing the different verticals</p>
<p>within public sector.</p>
<p>I still help out with,</p>
<p>with, with those as as well.</p>
<p>You know what</p>
<p>we're going to have to are non-retail.</p>
<p>You have to come back on the show</p>
<p>and talk about security</p>
<p>since you were a see.</p>
<p>So we're going to have to do that</p>
<p>but not today.</p>
<p>Today, today we're doing lift and shift</p>
<p>the myth of lift and shift.</p>
<p>You've done several cloud migrations.</p>
<p>It sounds like.</p>
<p>I've I've been</p>
<p>very involved in two very large ones.</p>
<p>So if you think of</p>
<p>the Department of Defense, that's yeah.</p>
<p>Yeah. That's a huge. One.</p>
<p>And then State of Maryland is a</p>
<p>I just learned this actually</p>
<p>about a couple of months ago</p>
<p>talking to one of the major cloud service</p>
<p>providers that the program I let it</p>
<p>Maryland is still the largest</p>
<p>cloud migration ever to be done</p>
<p>across state local education.</p>
<p>So wow that's amazing. Yeah.</p>
<p>So 2 to 2 pretty big ones.</p>
<p>All right.</p>
<p>So a lot of we we all want to hear</p>
<p>we all want to hear how that went.</p>
<p>Right.</p>
<p>And we and we name the episode today</p>
<p>the the myths of lift and shift.</p>
<p>I've I've seen this myself</p>
<p>I've helped some organizations</p>
<p>go through this migration</p>
<p>and the way that cloud is sold</p>
<p>initially was just move your workloads</p>
<p>just move everything right.</p>
<p>And so what have you found?</p>
<p>Well, I mean, let's start off at right</p>
<p>at the beginning with that first</p>
<p>what's the first myth?</p>
<p>So I think that there's kind of four major</p>
<p>lifts, I guess.</p>
<p>But let's start with the.</p>
<p>First one being</p>
<p>clouds cheaper.</p>
<p>And it's not not necessarily,</p>
<p>you know, when you lift and shift,</p>
<p>a lot of the times</p>
<p>your applications were built</p>
<p>for an on premise environment.</p>
<p>So there was no issue with things</p>
<p>like auto scaling.</p>
<p>They didn't have to be</p>
<p>developed</p>
<p>with some of these cloud concepts in mind.</p>
<p>Some of these</p>
<p>more of consumption based</p>
<p>concepts in mind.</p>
<p>So when you think about auto scaling,</p>
<p>that wasn't something</p>
<p>that was built into a lot of your legacy</p>
<p>applications.</p>
<p>So and, and a lot of the</p>
<p>I don't want to mention</p>
<p>any names of, of products,</p>
<p>but there's products out there</p>
<p>that will help customers</p>
<p>or help organizations</p>
<p>move an application into the cloud</p>
<p>majority of those products</p>
<p>don't support auto scaling either.</p>
<p>So what you've got is when you move</p>
<p>your application to the cloud, you</p>
<p>now have to be max provisioned at all</p>
<p>times.</p>
<p>Being max provisioning all at all times</p>
<p>means a lot more money,</p>
<p>which</p>
<p>doesn't often translate into cost savings,</p>
<p>especially if you've already paid</p>
<p>for a server, you already paid for</p>
<p>whatever environment you're</p>
<p>you're hosting the application</p>
<p>and now you move it in the cloud,</p>
<p>you're having to max provision at at all</p>
<p>times.</p>
<p>You're not able to automate scale.</p>
<p>So you're not really making</p>
<p>use of a consumption based model which is</p>
<p>the main cost</p>
<p>savings mechanism in the cloud.</p>
<p>And now customers are actually paying more</p>
<p>than they were</p>
<p>for the same capability on premise.</p>
<p>You know, I have a great example that I</p>
<p>was doing work in the Canadian government</p>
<p>and this was at the early days of them</p>
<p>using the cloud</p>
<p>and they moved in SFP instance</p>
<p>into the cloud and SAP.</p>
<p>And since that they ran</p>
<p>and they moved it in the cloud.</p>
<p>Same thing, Max provisioned running</p>
<p>and they blew through their budget</p>
<p>just blew through it</p>
<p>right in like six months,</p>
<p>the year budget completely blew fluid in</p>
<p>and they were complaining</p>
<p>back to the cloud</p>
<p>service provider,</p>
<p>what in the world is going on here?</p>
<p>And they quickly learned that well,</p>
<p>that instance</p>
<p>did not need to be running 24 seven.</p>
<p>They only really needed it</p>
<p>I think they finally got it down</p>
<p>to 14 five.</p>
<p>So they actually turned it on and off</p>
<p>every day.</p>
<p>Yeah.</p>
<p>Which it sounds silly, but.</p>
<p>But it saved them gobs of money.</p>
<p>So you're right,</p>
<p>it's a different mentality</p>
<p>because the cost is consumption based,</p>
<p>which is</p>
<p>a completely different model than what</p>
<p>we're used to in in our data center.</p>
<p>It's sunk costs in our data center. Right.</p>
<p>Yeah.</p>
<p>Well, and you know, if you think about</p>
<p>Health and Human Services,</p>
<p>which is typically the largest,</p>
<p>I would say it budget</p>
<p>within state government,</p>
<p>if you just think about that,</p>
<p>we can't turn off a lot of the access</p>
<p>to these services, you know, applications</p>
<p>for eligibility services</p>
<p>as a for instance, you can't turn them off</p>
<p>a certain times of day.</p>
<p>They have to be available all the time.</p>
<p>But if you're able to auto scale,</p>
<p>I mean, you could</p>
<p>you could bring that down</p>
<p>to the smallest instance,</p>
<p>probably that, you know, a cloud service</p>
<p>provider or CSP offers,</p>
<p>you know, in those off hours.</p>
<p>So it's still running,</p>
<p>is still there, still available.</p>
<p>Somebody needs it, but you're hardly</p>
<p>running through any money at all.</p>
<p>Whereas if you're not able to auto scale,</p>
<p>you're not coming down to a small instance</p>
<p>and you're having to run at that</p>
<p>large size,</p>
<p>even in those hours where nobody's used.</p>
<p>So it is is that the main saver</p>
<p>or is that the main thing</p>
<p>that helps realize that cloud is cheaper,</p>
<p>is understanding the consumption model</p>
<p>and in changing the your operations</p>
<p>and or your application</p>
<p>to fit that model better?</p>
<p>Or are there other factors that are in</p>
<p>that are contributing to your your bill?</p>
<p>So there's others, but that one's</p>
<p>probably the easiest to to talk through.</p>
<p>And it's got it's</p>
<p>arguably the largest cost savings</p>
<p>mechanism is that that auto scaling</p>
<p>the consumption base based model</p>
<p>other things that you can consider</p>
<p>that I would say</p>
<p>you could put into that same bucket</p>
<p>are some of the cloud native services.</p>
<p>So each of the cloud providers,</p>
<p>each of the CSP offers</p>
<p>services that</p>
<p>now in</p>
<p>most organizations are being fulfilled</p>
<p>by some third party applications</p>
<p>on some OEM product.</p>
<p>Now, if you move into the cloud,</p>
<p>you'll typically get</p>
<p>a cost savings</p>
<p>for a similar type of capability.</p>
<p>They typically most of the CCP's offer</p>
<p>some of those capabilities</p>
<p>at a price</p>
<p>that would be less than if you were to go</p>
<p>to a third party vendor, an OEM,</p>
<p>whatever you were in.</p>
<p>Running yourself</p>
<p>in. Your on premise environment.</p>
<p>And a lot of times</p>
<p>it'll be managed or in some</p>
<p>at some level managed by by the CSP.</p>
<p>So there's, you know, the potential there</p>
<p>to take some work off of your workforce.</p>
<p>Also.</p>
<p>So there's a lot of attractive pieces</p>
<p>to doing that.</p>
<p>Part of the problem,</p>
<p>there's a couple of problems with that.</p>
<p>One is, again, a lot of these legacy</p>
<p>applications, they're not developed</p>
<p>to be able to leverage</p>
<p>some of the cloud native applications.</p>
<p>So you won't be able to do every</p>
<p>everything that, you know,</p>
<p>you read a white paper maybe, and says</p>
<p>how great the CSP offering is.</p>
<p>Your application</p>
<p>may not be able to consume that.</p>
<p>The other issue there is lock in.</p>
<p>So if you use those services quite a bit,</p>
<p>it's very easy</p>
<p>to get locked in to that specific cloud</p>
<p>if you need to for some reason,</p>
<p>whether it's cost, whether it's licensing,</p>
<p>you need to move your application</p>
<p>now to another cloud environment.</p>
<p>But you know, just say in</p>
<p>not trying to say</p>
<p>one is better than the other by any means,</p>
<p>let's say you need to move from the U.S.</p>
<p>to to to Azure.</p>
<p>If you've used a whole bunch of services,</p>
<p>it could be very difficult for you</p>
<p>to extricate your application,</p>
<p>you know, break all the ties</p>
<p>with the services, move to Azure.</p>
<p>But the same is exactly true.</p>
<p>Moving from Azure table use.</p>
<p>I'm not I was just using the right.</p>
<p>Now it's that typical vendor</p>
<p>lockdown thing that people worry about.</p>
<p>Right and it's real in the cloud for sure.</p>
<p>It's probably more so</p>
<p>it's it's more of a concern, I would say,</p>
<p>in the cloud than I've seen it</p>
<p>be in the past, because you can</p>
<p>leverage so many services across</p>
<p>so many different areas</p>
<p>of of your stack.</p>
<p>You know what it kind of reminds me of?</p>
<p>It reminds me of the server wars</p>
<p>in the nineties and early 2000.</p>
<p>Do you remember that</p>
<p>you had to compile your code</p>
<p>for Solaris or Ajax or HP Unix?</p>
<p>And then Linux came along</p>
<p>and rattled everyone's cages.</p>
<p>And now we don't worry about stuff</p>
<p>like that.</p>
<p>Yeah. At all in the data center.</p>
<p>So I'm wondering,</p>
<p>do you think we'll ever get to the point</p>
<p>where the cloud service providers</p>
<p>are relying on proprietary</p>
<p>SAS offerings that lock people in?</p>
<p>Do you think the people will get</p>
<p>frustrated enough where they move to like</p>
<p>what happened with Linux?</p>
<p>I Linux was just earth shattering</p>
<p>to all these big companies that had</p>
<p>these proprietary operating systems.</p>
<p>I don't know that the CCP's</p>
<p>will want to do that only because it.</p>
<p>Well, yeah, I</p>
<p>if I'm locked into your environment,</p>
<p>I'm going to keep paying you</p>
<p>my consumption costs.</p>
<p>So there's is sort of that's why</p>
<p>they offer it at a lower</p>
<p>cost is to get you locked in is.</p>
<p>That is to get you. Locked. Yeah.</p>
<p>So that you're</p>
<p>you're then going to continue</p>
<p>paying consumption cost to them</p>
<p>and not move off to another</p>
<p>class. So they all sort of</p>
<p>I would guess.</p>
<p>Like a drug dealer,</p>
<p>let's just say what it is.</p>
<p>Okay. Well.</p>
<p>They probably</p>
<p>they want to get you hooked now.</p>
<p>Of course they do.</p>
<p>I mean, this is</p>
<p>this is a normal business model, right?</p>
<p>I'm going to entice you</p>
<p>with better services at a lower price</p>
<p>to get you locked in so that you can</p>
<p>consume additional services.</p>
<p>Yeah. Yeah.</p>
<p>I but you still bring back the point</p>
<p>that sometimes your legacy applications</p>
<p>that maybe you can't afford to</p>
<p>date, you can't afford to.</p>
<p>What's the right</p>
<p>where you can't afford to replace</p>
<p>that may prevent you</p>
<p>from actually moving to the cloud</p>
<p>and or using some of these services</p>
<p>because of the cost.</p>
<p>I would say good I Mike,</p>
<p>I would say don't move into the cloud</p>
<p>unless you can do it the right way.</p>
<p>And I think that's part of why, you know,</p>
<p>we want to call it that's part of why</p>
<p>this is</p>
<p>maybe called the myth of lift and shift.</p>
<p>If you're</p>
<p>if you're not able to move into the cloud</p>
<p>for whatever reason,</p>
<p>if you're not able to do it the right way,</p>
<p>take a good, hard look in the mirror</p>
<p>and say, why am I moving into the cloud?</p>
<p>Why am I, you know,</p>
<p>what is my reason for doing this?</p>
<p>Maybe you have</p>
<p>you know, legislation</p>
<p>that says that you have to</p>
<p>move into the cloud</p>
<p>or we have to be out of a data center.</p>
<p>Okay. Well,</p>
<p>that that that's a good reason.</p>
<p>That's a pretty big motivator right there.</p>
<p>That's a great reason.</p>
<p>But if it's just to say</p>
<p>that you're in the cloud,</p>
<p>you know. Not a good.</p>
<p>Not not a good reason, you're probably</p>
<p>going end up costing yourself more.</p>
<p>You're probably going to end up</p>
<p>frustrating both your superiors</p>
<p>and your workers because the strategy</p>
<p>hasn't been fully thought</p>
<p>through.</p>
<p>Let's talk about technical here.</p>
<p>This is a good one. Okay.</p>
<p>Yeah. Yeah.</p>
<p>Because I'm seeing this in in huge droves.</p>
<p>Right.</p>
<p>It's a big.</p>
<p>Problem. Absolutely.</p>
<p>And people think a lot of times</p>
<p>that by moving into the cloud that they're</p>
<p>going to fix their technical debt</p>
<p>or eliminate their</p>
<p>some portion of their technical debt.</p>
<p>Doing the lift and shift doesn't</p>
<p>eliminate your technical debt.</p>
<p>In almost any case.</p>
<p>That doesn't</p>
<p>it actually expose it more 100%.</p>
<p>That was going to be the next point.</p>
<p>It can expose it</p>
<p>more and accelerate it even</p>
<p>away. Explain it.</p>
<p>I understand the expose</p>
<p>because I'm now taking something</p>
<p>that's been running for 30 years</p>
<p>and moving it into a new environment.</p>
<p>I am going to find exposure points.</p>
<p>But what's what's the acceleration part?</p>
<p>I don't know.</p>
<p>I think it's kind of the same concept is</p>
<p>when I think</p>
<p>we're kind of saying the same thing,</p>
<p>you know, by, okay, you're exposing it.</p>
<p>But I guess what I was,</p>
<p>you know, the other by saying</p>
<p>that it's accelerating it's</p>
<p>you know, you've</p>
<p>now you have more technical debt</p>
<p>to sort of worry about.</p>
<p>So whether you look at that</p>
<p>as more technical debt being exposed</p>
<p>or whether it happening,</p>
<p>accelerate your technical debt.</p>
<p>Either way, you have more technical debt</p>
<p>to kind of worry about in some of</p>
<p>those cases.</p>
<p>All right.</p>
<p>Let's walk through an example,</p>
<p>because I think some of the people hear</p>
<p>that word, technical debt.</p>
<p>I think they think they know what it is.</p>
<p>But let's walk</p>
<p>let's walk through an example.</p>
<p>What would be a good</p>
<p>a good, easy case to understand.</p>
<p>So I can I can look and see</p>
<p>if I'm having the same issues.</p>
<p>So you move into that well.</p>
<p>So first of all, technical debt is</p>
<p>often sort of the,</p>
<p>I guess, colloquial kind of term</p>
<p>for systems that are kind of falling</p>
<p>behind what they should be.</p>
<p>So when you're not making updates</p>
<p>to your system, when those systems I mean,</p>
<p>when I came in to the state of Maryland</p>
<p>as a for instance, we had systems</p>
<p>that were still running on green screens</p>
<p>where the, you know, the.</p>
<p>The 81 VTI 100 terminals.</p>
<p>Yeah.</p>
<p>The operators were, you know, they would</p>
<p>they would hit, you know,</p>
<p>whatever code five or something</p>
<p>and it would bring up a new screen</p>
<p>and like there was no navigation</p>
<p>that was happening there</p>
<p>for people who had been using that system</p>
<p>for ten years.</p>
<p>It was super easy for</p>
<p>for for them to navigate</p>
<p>for someone just coming into the system.</p>
<p>I sat down at a terminal one day.</p>
<p>I couldn't figure out</p>
<p>how to make anything work on this thing.</p>
<p>Like, and then and the and,</p>
<p>and the book is this thick, you know,</p>
<p>to to learn all the commands</p>
<p>and everything. So</p>
<p>not a super great user experience there</p>
<p>and a super steep learning curve there.</p>
<p>So that was well,</p>
<p>I want to stop you for a second there,</p>
<p>but it's working.</p>
<p>That's well, it's working for those people</p>
<p>who have been there ten years.</p>
<p>Oh, gotcha.</p>
<p>But but what's the what's the</p>
<p>what's the danger in</p>
<p>carrying technical debt like that?</p>
<p>I mean, it works</p>
<p>well, but I mean,</p>
<p>what's the downside of that?</p>
<p>Well, so anytime I have to bring in</p>
<p>somebody new when it's a lot of training</p>
<p>to get them brought up and brought up to</p>
<p>speed, there's a lot of doubt downsides.</p>
<p>You know, one of the downsides</p>
<p>that people don't often think about,</p>
<p>especially when you're talking about in</p>
<p>a government space, is employee retention.</p>
<p>So, you know, millennials,</p>
<p>any of the newer generations, I guess,</p>
<p>that are coming into the workforce,</p>
<p>which is, you know, you want to have</p>
<p>someone who is knowledgeable on the latest</p>
<p>trends and developments around casework</p>
<p>as a as a for instance.</p>
<p>So if you're trying to attract</p>
<p>those top caseworker talents out of school</p>
<p>who are up on the newest, not knowledge,</p>
<p>they're not going to want to come in</p>
<p>and learn a green screen.</p>
<p>They're not going to want to come in and</p>
<p>and deal with these legacy applications.</p>
<p>So we were seeing a high amount</p>
<p>of turnover</p>
<p>of very qualified people</p>
<p>coming in after a couple of months.</p>
<p>They're like,</p>
<p>you know, I've had enough of this.</p>
<p>I'm washing my hands of this place.</p>
<p>I'm out of here. That is fast.</p>
<p>I never would have</p>
<p>thought I never would have thought</p>
<p>of employee retention with technical debt.</p>
<p>Yeah,</p>
<p>but that's an interesting correlation.</p>
<p>Yeah, that's cool.</p>
<p>I mean, it was one of our biggest issues</p>
<p>in in one of the agencies</p>
<p>was the amount of people</p>
<p>who were turning over and</p>
<p>we think it was directly attributable</p>
<p>to some of the technical debt</p>
<p>that we had in some of our systems.</p>
<p>You know,</p>
<p>when you have technical debt also,</p>
<p>there's there's security issues.</p>
<p>If I.</p>
<p>Think.</p>
<p>If I have an old legacy application</p>
<p>that hasn't been updated, I mean, I saw</p>
<p>this firsthand more times than than</p>
<p>I would like to have to think about, but</p>
<p>I may not be able to apply patches</p>
<p>to that to that system.</p>
<p>There may be a fear</p>
<p>that I'm going to break it.</p>
<p>This is an outdated operating system</p>
<p>that it's that it's running on.</p>
<p>I may not be able to apply</p>
<p>patches, therefore,</p>
<p>I've got six security vulnerabilities that</p>
<p>I just have to accept until we can get out</p>
<p>of that technical debt cycle.</p>
<p>As a C.</p>
<p>So that must have driven you crazy it.</p>
<p>Now when I say I had to actually accept</p>
<p>we had a risk acceptance process</p>
<p>where the head of the agency</p>
<p>actually had to accept them,</p>
<p>but it was still not a not</p>
<p>a pleasant process for for years.</p>
<p>I bet not now.</p>
<p>Did you did you see a lot of that</p>
<p>in the space in operational technology</p>
<p>or was this in your i.t</p>
<p>environment as well?</p>
<p>Oh, this was in the I.T. environment</p>
<p>I'm talking about. Oh, yeah.</p>
<p>And I'm talking because I can</p>
<p>I've seen that a lot in the OT space.</p>
<p>It's been doing that same job.</p>
<p>That pump has been pumping water</p>
<p>for the last 30 years on Windows 95 box.</p>
<p>I'm not touching it. Never, ever. Right.</p>
<p>I'll just keep it connect</p>
<p>disconnected from the internet.</p>
<p>That's kind of mentality, the Iot guys.</p>
<p>But in the IT space, that's</p>
<p>I mean, that's a whole different beast.</p>
<p>Oh yeah. No, it was a real thing.</p>
<p>We had applications that were running</p>
<p>outdated operating systems, couldn't</p>
<p>apply patches to them because they would</p>
<p>it would break the system essentially.</p>
<p>So they just had to accept</p>
<p>the agency had to accept the risk that</p>
<p>something real bad may happen</p>
<p>here.</p>
<p>What about cost.</p>
<p>To maintain these legacy,</p>
<p>this technical debt?</p>
<p>The first thing that comes to my mind</p>
<p>is COBOL systems, how much you have to pay</p>
<p>a COBOL programmer</p>
<p>to come and fix problems.</p>
<p>Oh yeah.</p>
<p>And I mean, we laugh about it, but there's</p>
<p>a lot of COBOL out there still running.</p>
<p>The IRS uses</p>
<p>some and I know a lot of other states</p>
<p>are still using mainframes</p>
<p>that run COBOL on them.</p>
<p>Yeah.</p>
<p>So COBOL in itself,</p>
<p>I mean, there are some things</p>
<p>COBOL is really good at and so it's not</p>
<p>necessarily a bad language on its own.</p>
<p>The problem is two things.</p>
<p>One is the lack of talent out there around</p>
<p>COBOL still.</p>
<p>So now you're having to pay</p>
<p>exorbitant prices</p>
<p>to get someone in who understands it.</p>
<p>But another big problem</p>
<p>that relates back to</p>
<p>the technical debt</p>
<p>is a lot of these systems.</p>
<p>So again, I'm not talking the health</p>
<p>and in the services space,</p>
<p>that's an easy example for for</p>
<p>for for me to give.</p>
<p>But it happens across motor vehicle</p>
<p>departments, happens in other places.</p>
<p>Also, there's rule changes</p>
<p>that that come down either</p>
<p>from the state legislature,</p>
<p>maybe from the feds, from CMS,</p>
<p>and they they make tweaks</p>
<p>to your eligibility programs.</p>
<p>Very a</p>
<p>very common reaction to</p>
<p>that is for someone to sort of</p>
<p>or for an agency,</p>
<p>I guess, to kind of bolt on,</p>
<p>I'll say a little bit extra code</p>
<p>to account for these these these tweaks.</p>
<p>Right.</p>
<p>So they're not actually</p>
<p>really going in and and fixing the system.</p>
<p>They're essentially kind of, you know,</p>
<p>adding on something a little bit extra</p>
<p>that will that that</p>
<p>that will achieve the required result.</p>
<p>The problem with</p>
<p>this is in this release back</p>
<p>to the concept of technical debt,</p>
<p>you end up with a ton of spaghetti code.</p>
<p>And then so now when you do want to update</p>
<p>your, your,</p>
<p>your systems, there's no way to recreate</p>
<p>these systems, essentially.</p>
<p>So it becomes this very daunting</p>
<p>task to the point where it makes</p>
<p>people almost want to continue</p>
<p>in the technical debt cycle</p>
<p>because they're like, well,</p>
<p>I can't just like, I can't break this up.</p>
<p>You know, one of the common concepts</p>
<p>now in around cloud is</p>
<p>breaking up your system into modules</p>
<p>containerized, right?</p>
<p>Yeah.</p>
<p>I've heard I've heard that first approach.</p>
<p>The way the spaghetti code is written now,</p>
<p>I have no way typically</p>
<p>of breaking these up into modules,</p>
<p>breaking these up into microservices.</p>
<p>So now it's I have to do all of it.</p>
<p>I can't just pull out</p>
<p>a little piece of it.</p>
<p>So that makes people even more hesitant</p>
<p>to move towards this modernization effort</p>
<p>because they've been doing things wrong</p>
<p>for all these years now.</p>
<p>It's like when something does break,</p>
<p>when, when,</p>
<p>when they're when there is the impetus</p>
<p>for this change, it's it's even harder.</p>
<p>So that tells me</p>
<p>I need to tell my kids to learn COBOL.</p>
<p>They will have a job forever.</p>
<p>Well, I think the other option there is we</p>
<p>I mean, one of the other options there</p>
<p>and this is what we had to largely do</p>
<p>in Maryland, you just essentially scrapped</p>
<p>the old program. You.</p>
<p>Yeah, but aren't won't services go down</p>
<p>for your constituents and you don't.</p>
<p>Scrap it until you have a new program</p>
<p>built to replace it.</p>
<p>Right.</p>
<p>But but basically you have to rebuild.</p>
<p>You have to go back, look at.</p>
<p>Go go from scratch, look at the old.</p>
<p>Graduated from scratch,</p>
<p>rebuild something new.</p>
<p>And then you can scrap the old one.</p>
<p>That's costs</p>
<p>that cost a lot of money. It does.</p>
<p>There's some</p>
<p>so like</p>
<p>when we got our cod migration of Maryland,</p>
<p>one of the reasons we started</p>
<p>with Health and Human Services</p>
<p>is because there's a lot of federal</p>
<p>funding dollars</p>
<p>out there to help with these migrations.</p>
<p>So what we were able to do,</p>
<p>I mean, the program at Maryland ended up</p>
<p>being about a $500 million program over</p>
<p>the life of it, and it's not done yet.</p>
<p>Goodness.</p>
<p>But it was paid for by about 70%</p>
<p>or more, probably more than that, 70</p>
<p>something percent</p>
<p>by the federal government.</p>
<p>So the state didn't have to put up nearly</p>
<p>as much money</p>
<p>for a lot of these activities.</p>
<p>When you're updating a medicaid system</p>
<p>as a for instance,</p>
<p>when you're developing the Medicaid</p>
<p>system, moving the Medicaid system</p>
<p>into the cloud, the federal government</p>
<p>typically pays for 90% of all the costs.</p>
<p>So the states were responsible for 10%.</p>
<p>So if a state is doing this, you know,</p>
<p>if they're really thinking about costs</p>
<p>and how to optimize their money,</p>
<p>if you start in the health</p>
<p>and human services space,</p>
<p>you can get up to 90%</p>
<p>or a lot of these activities</p>
<p>paid for by the federal government.</p>
<p>You can keep things like your your cloud</p>
<p>formation template, some of your turf.</p>
<p>So, you know, the the templates for</p>
<p>for saying these things up the governance</p>
<p>structures, all those things are reusable</p>
<p>across the entire enterprise later.</p>
<p>So yeah,</p>
<p>so you have reusability that you built.</p>
<p>In, you have reusable,</p>
<p>you're paying for a fraction of what</p>
<p>you would have to pay</p>
<p>if, say, central I.T</p>
<p>or maybe Department of motor vehicles</p>
<p>or someone i don't know</p>
<p>what the matches on divvy, but</p>
<p>if you started another agency,</p>
<p>you may have to pay significantly more</p>
<p>out of your state funds than if you start</p>
<p>on the health human services on health.</p>
<p>And this totally makes a lot of sense,</p>
<p>right, because you also build up your</p>
<p>your muscle memory on</p>
<p>how to do this sort of stuff.</p>
<p>Right. Which can be daunting.</p>
<p>It sounds like a.</p>
<p>Lot of people think that by moving</p>
<p>into the cloud, well, the cloud is secure.</p>
<p>I can move into the cloud,</p>
<p>and that's going to make securing</p>
<p>my applications easier.</p>
<p>But that's not always the case either.</p>
<p>It's very important.</p>
<p>So it'll be us and all the all the CCP's</p>
<p>have some version of it.</p>
<p>I'm most versed in the WCF</p>
<p>where I have something</p>
<p>on my cert, so it's easiest</p>
<p>for me to talk about that in some cases.</p>
<p>But they have what's called</p>
<p>the shared responsibility model.</p>
<p>Yeah, they all have it.</p>
<p>They all have the the model,</p>
<p>but they differ.</p>
<p>This is one thing that got me tricky.</p>
<p>You know, they differ</p>
<p>just a little bit in each one.</p>
<p>So there's this weird overlap,</p>
<p>right, where, you know, things are secure,</p>
<p>but then there's this gap.</p>
<p>Yeah, you have to be real careful.</p>
<p>That was kind of the point</p>
<p>I'm making is you have to be real careful</p>
<p>of understanding in each CSP Exactly.</p>
<p>To your point,</p>
<p>it's a little bit different.</p>
<p>So you have to understand</p>
<p>exactly what you're responsible</p>
<p>for in each of the CCP's</p>
<p>and exactly what they're responsible for.</p>
<p>And it doesn't just change by, say, a CSP,</p>
<p>it changes by which services</p>
<p>you're consuming in that system and CSP.</p>
<p>So it's very important</p>
<p>that your security teams, it's</p>
<p>it's almost more complex in some cases</p>
<p>to figure out</p>
<p>exactly what I'm responsible for,</p>
<p>make sure that I'm staying on top of that</p>
<p>versus what they're responsible for.</p>
<p>You know, it's almost like like</p>
<p>a racing matrix across the different CSPs</p>
<p>and across the different products</p>
<p>that you have.</p>
<p>But if you don't keep up on that,</p>
<p>you could have vulnerabilities out there</p>
<p>where CSP knows that</p>
<p>they're not responsible for it,</p>
<p>but your team may not.</p>
<p>So security in the cloud</p>
<p>if it's not necessary.</p>
<p>There's a couple of things</p>
<p>you don't really have to worry about.</p>
<p>You worry about things like hypervisors</p>
<p>and stuff, stuff, stuff like that.</p>
<p>Or even physical security.</p>
<p>Physical security, yeah.</p>
<p>But it doesn't necessarily make it easier.</p>
<p>It's it's still complex.</p>
<p>You still have to be on the stuff</p>
<p>that you're responsible for.</p>
<p>And it can be difficult to know</p>
<p>what you're responsible for at times</p>
<p>unless you're well, well versed in cloud.</p>
<p>Have have you ever taken an approach?</p>
<p>Well, the security is ultimately</p>
<p>your responsibility anyway.</p>
<p>Have you ever run into the</p>
<p>in the in the case where you are</p>
<p>stepping on the security measures</p>
<p>of the cloud service provider?</p>
<p>Are they ever in conflict?</p>
<p>Have you have you run into that case?</p>
<p>I don't.</p>
<p>I'm trying to think if I ran into that,</p>
<p>I can't think of where I ran into that.</p>
<p>I have run into the reverse</p>
<p>of that, though,</p>
<p>where someone thought</p>
<p>the CSP was responsible for something</p>
<p>and it's like,</p>
<p>no, you're responsible for for for that.</p>
<p>If you give me enough time, I maybe</p>
<p>I'll come up with an answer on that one.</p>
<p>I just I haven't heard of one ear.</p>
<p>I so in my gut</p>
<p>I'm constantly thinking, well,</p>
<p>ultimately I'm responsible</p>
<p>anyway for, for security of my stuff.</p>
<p>It's my stuff, right?</p>
<p>So maybe if I am a little overzealous</p>
<p>and step on the cloud service providers</p>
<p>a little bit, I think that might be okay</p>
<p>because it's it's better to be</p>
<p>a little over cautious than have a gap.</p>
<p>So I think I don't know I this is well.</p>
<p>So that makes a lot of sense.</p>
<p>And if you have</p>
<p>I'm going to be a little bit specious here</p>
<p>in interpreting what I'm saying.</p>
<p>But if you have unlimited funds,</p>
<p>then that's a great approach.</p>
<p>Oh yeah, you can.</p>
<p>If if you have.</p>
<p>Yeah. I don't have unlimited funds.</p>
<p>So if you have to make tradeoffs</p>
<p>and you have to prioritize.</p>
<p>You know, there's.</p>
<p>Even cases that I could point to,</p>
<p>I don't want to</p>
<p>maybe reference anything directly</p>
<p>because I don't know</p>
<p>if that would be politically proper.</p>
<p>But cases where if the risk of an incident</p>
<p>was less costly</p>
<p>than the risk</p>
<p>of fixing that vulnerability,</p>
<p>just let that. Take that risk.</p>
<p>Just let it roll.</p>
<p>You know what? That's a normal.</p>
<p>That should be in your risk</p>
<p>assessment plans that you do.</p>
<p>That's part of a life of a CSO.</p>
<p>So that tells me</p>
<p>when you're moving to the cloud,</p>
<p>it adds to your risk profile.</p>
<p>Most definitely.</p>
<p>Right.</p>
<p>And you said it's more complex.</p>
<p>I totally agree with you there.</p>
<p>And in fact, people said, oh,</p>
<p>the cloud is easy,</p>
<p>not easier</p>
<p>than just running</p>
<p>because it's so much easier if I just run</p>
<p>everything in my own little data center</p>
<p>and I'm not connected to the Internet.</p>
<p>Right.</p>
<p>I mean, security's easy,</p>
<p>my cost models simple.</p>
<p>But I can't grow. I can't grow.</p>
<p>I can't provide services</p>
<p>to, you know, my constituents.</p>
<p>I can't satisfy mission needs,</p>
<p>all those sorts of things.</p>
<p>So we're living in this complex world.</p>
<p>We have to understand that</p>
<p>migration to the cloud is complex.</p>
<p>Absolutely.</p>
<p>And I mean,</p>
<p>when we were first moving into the cloud,</p>
<p>both on the DOD side and in Maryland,</p>
<p>I've got very specific examples</p>
<p>where the security team would say,</p>
<p>no, you can't do that.</p>
<p>You can't set the firewall rules to that.</p>
<p>And it's like, well,</p>
<p>you just don't understand the way that</p>
<p>the way that these concepts</p>
<p>work in the cloud, it's not the same. So</p>
<p>it's complex.</p>
<p>And, you know, there's a knowledge</p>
<p>gap a lot of times when you're first</p>
<p>starting off moving it to the cloud also.</p>
<p>So that adds to some of the pain points</p>
<p>also around that complexity.</p>
<p>So I think he's just found a fifth math.</p>
<p>It's and it is you need to scale up.</p>
<p>Yeah you can't</p>
<p>I mean you need to learn about it, right.</p>
<p>That's something that you</p>
<p>you can't just I think and I will</p>
<p>blame software developers.</p>
<p>I am a software developer.</p>
<p>I caused this problem in inside Intel.</p>
<p>I causes problem to a lot.</p>
<p>Right. Oh,</p>
<p>I can just spin up instances in the cloud.</p>
<p>I can do whatever I want.</p>
<p>Oh and oh I need to download</p>
<p>things out of GitHub</p>
<p>and you know, out of all these other</p>
<p>repositories where I'm just grabbing</p>
<p>libraries to make things work.</p>
<p>So I open up all the firewall rules because I'm too lazy to pick the right ports,</p>
<p>right?</p>
<p>So yeah, so I'm skilled enough</p>
<p>to spin up an instance, but that's not,</p>
<p>that's not the same.</p>
<p>I'm right.</p>
<p>I'm. I'm glad you didn't work in.</p>
<p>I'm just kidding.</p>
<p>Oh, believe me. Believe me.</p>
<p>I've interviewed our cloud.</p>
<p>Our cloud broker team, and they go, Yeah,</p>
<p>we know who you are, Darren.</p>
<p>Yeah, we know exactly who you are.</p>
<p>And they did, they did wonderful things by</p>
<p>putting security underneath me without me</p>
<p>knowing.</p>
<p>Yeah.</p>
<p>And that's a great.</p>
<p>In my own instances and, and there's so,</p>
<p>so it's a different skill set.</p>
<p>It's a different way</p>
<p>of thinking of compute.</p>
<p>And I think that's our number five is</p>
<p>you have to change your mindset,</p>
<p>you have to scale up</p>
<p>on because these are different ways of</p>
<p>doing compute than we've done in the past.</p>
<p>And that's a great you know,</p>
<p>what you were talking about there.</p>
<p>It's a great example of how</p>
<p>we need some different types of guardrails</p>
<p>when you're moving into the cloud,</p>
<p>there has to be</p>
<p>you know,</p>
<p>somebody shouldn't be able to from a</p>
<p>from an</p>
<p>enterprise managed cloud environment.</p>
<p>They should not be allowed to go out and</p>
<p>pull from whatever library they want to.</p>
<p>They should be limited to be able</p>
<p>to pull from from certain environments.</p>
<p>John,</p>
<p>you just scared every software developer.</p>
<p>If you need to have something,</p>
<p>tell me and we'll approve it</p>
<p>and we'll get it into the library and</p>
<p>then you can pull from so from that also.</p>
<p>But you're slowing me down.</p>
<p>Just slow me down and you.</p>
<p>Got to have security too, so.</p>
<p>Oh, I know, I know.</p>
<p>I, I totally, I totally agree</p>
<p>with you there, but I can tell you</p>
<p>from my perspective, I'm like,</p>
<p>Then forget it, I'll just write it.</p>
<p>I'll just go outside of the corporate,</p>
<p>because that's where Shadow it came from.</p>
<p>That's why people do it. People</p>
<p>that's why people do it.</p>
<p>Yeah. Yeah.</p>
<p>So we've got to figure out better ways</p>
<p>to manage, especially in today's world.</p>
<p>Holy cow.</p>
<p>Yeah.</p>
<p>The ransomware attacks.</p>
<p>The cyber attacks, though,</p>
<p>the sophistication of the attacks</p>
<p>are outrageous.</p>
<p>Yeah, I mean, we had bots crawling the web</p>
<p>looking for any sort of data</p>
<p>that could be Maryland</p>
<p>type of data looking for.</p>
<p>And we found a development environment</p>
<p>in another country</p>
<p>with an unlocked S3 bucket.</p>
<p>That was some of some of our code.</p>
<p>There wasn't</p>
<p>any of our sensitive information in there.</p>
<p>It was open source code,</p>
<p>but it was code that</p>
<p>we had adapted a little bit.</p>
<p>So it wasn't it wasn't this bad. For a</p>
<p>funny enough, though,</p>
<p>there actually was another state data</p>
<p>in that bucket</p>
<p>that they were using for test purposes.</p>
<p>So some of our code base was was in there.</p>
<p>It was open source, like I said.</p>
<p>So it wasn't, wasn't hugely concerning</p>
<p>from our perspective,</p>
<p>but I had to call that other state system</p>
<p>since becoming a good friend of mine</p>
<p>and explained to him, Hey, I think I found</p>
<p>PII information of your citizens</p>
<p>that they're running against</p>
<p>in order to validate.</p>
<p>How did that conversation go?</p>
<p>I got a colorful call on a Saturday</p>
<p>morning as I was heading to breakfast.</p>
<p>So this is John.</p>
<p>This has been wonderful,</p>
<p>great, great information.</p>
<p>Things we need to think about.</p>
<p>So thank</p>
<p>you so much for coming on the show.</p>
<p>It's my pleasure.</p>
<p>I enjoyed talking with you</p>
<p>and looking forward to doing this again</p>
<p>sometime soon.</p>
<p>Thank you for listening</p>
<p>to Embracing Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcasting site or YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>and embracingdigital.org until next</p>
<p>time, go out and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
