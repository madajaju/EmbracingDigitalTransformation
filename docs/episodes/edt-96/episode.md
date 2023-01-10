---
layout: posts
title: "Put the Title Right Here"
number: 96
permalink: EDT96
has_children: false
parent: Episodes
nav_order: 96
tags:
    - EDT111
    - EmbracingDigital

date: 
guests:
    - Darren W Pulsipher

img: TBD
summary: "Summary"
---

{% include soundcloud.html id="edt96" title="#96 Put the Title Right Here" %}

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
<p>leveraging people, process</p>
<p>and technology.</p>
<p>Chris and Erin, welcome to the show.</p>
<p>Thanks, Darren.</p>
<p>We're excited to be here.</p>
<p>Hey, Erin, let's start with you first.</p>
<p>Tell my audience a little bit about</p>
<p>your background and why you're at Verge.io.</p>
<p>Yeah, so I've been in it for for 20</p>
<p>plus years.</p>
<p>I'm a pre-sales system</p>
<p>engineer here at Verge.io.</p>
<p>So that means when we go and engage</p>
<p>with customers, I'm one of the guys</p>
<p>who talks to customers about the technical</p>
<p>features and value of Bird's eye view</p>
<p>and helps them define the requirements</p>
<p>and how we can help them out.</p>
<p>So you're the you're</p>
<p>the point of the spear.</p>
<p>You're right at the beginning.</p>
<p>You're out there gathering, use cases,</p>
<p>finding out the pains that all the</p>
<p>professionals are having, right?</p>
<p>Yes, absolutely.</p>
<p>Part of the the tip, if you will.</p>
<p>That's great.</p>
<p>And Chris, a little bit about yourself</p>
<p>and your background and what your role is.</p>
<p>It varies.</p>
<p>So I had sales at AdWords</p>
<p>and that means hiring</p>
<p>teams like like Aaron</p>
<p>and his sales counterpart's</p>
<p>been in been doing tech</p>
<p>software companies for 25 years now and</p>
<p>we have a</p>
<p>we have a maniacal focus</p>
<p>on our customer satisfaction</p>
<p>and making them successful</p>
<p>with our software.</p>
<p>All right.</p>
<p>This is great.</p>
<p>Now, I've already for those of you</p>
<p>that are just tuning in to this episode,</p>
<p>go look at a previous episode</p>
<p>with your one of your founders, Greg,</p>
<p>who talked about we talked about</p>
<p>the rebirth of private cloud today.</p>
<p>We actually want to talk about</p>
<p>the use cases of virtual data centers</p>
<p>because there was something</p>
<p>that was really cool.</p>
<p>The Greg talked about was I'm no longer</p>
<p>just virtualizing machines,</p>
<p>I'm virtualizing data centers.</p>
<p>And I thought, man, that's super cool.</p>
<p>There's a whole bunch of use cases</p>
<p>I'm sure we can come up with.</p>
<p>And Aaron, since you talk to customers</p>
<p>every day, let's start with I mean, what</p>
<p>what does that unleash for customers</p>
<p>when they start thinking about,</p>
<p>oh, it's not VMs, it's</p>
<p>the disease,</p>
<p>I guess I virtual data centers now, right?</p>
<p>Yeah, it's a little different</p>
<p>than virtual data centers.</p>
<p>This is part of the terminology goes.</p>
<p>But basically what Verge.io has included</p>
<p>and built into it is multi tenancy</p>
<p>in those tenants stand standalone</p>
<p>as nested tenants</p>
<p>where you can provide all the resources</p>
<p>that you require inside of a data center</p>
<p>from CPU to memory</p>
<p>to storage to networking</p>
<p>and have it totally isolated, but build</p>
<p>those at the same time on demand, right?</p>
<p>So just like you go in</p>
<p>and you build a VM on demand,</p>
<p>you might have a template for that VM.</p>
<p>You can now do the same thing</p>
<p>with a tenant where it's encapsulates</p>
<p>everything that's included</p>
<p>in the virtual data center,</p>
<p>all those resources</p>
<p>that we just talked about.</p>
<p>But you can build those right on demand</p>
<p>and those can be a script</p>
<p>that you can build through</p>
<p>which we call our recipe engine,</p>
<p>where some of that's already predefined,</p>
<p>you can build it from scratch,</p>
<p>where you just, you know,</p>
<p>give it a name, give the resources,</p>
<p>everything that needs in.</p>
<p>Or you can take one of those tenants</p>
<p>and you can now clone those tenants.</p>
<p>So if you have a project where someone's</p>
<p>working on one of those tenants</p>
<p>or you have a customer</p>
<p>that's working in one of those tenants,</p>
<p>and you need to kind of copy paste</p>
<p>that same type of environment, it's very</p>
<p>easy to do.</p>
<p>Okay, so I can take</p>
<p>basically you just describe the snapshot,</p>
<p>I can take a snapshot of not just VMs, but</p>
<p>security profiles, network</p>
<p>storage memory and everything is</p>
<p>what you're talking about, not just what</p>
<p>we've seen traditionally, right?</p>
<p>Yeah, exactly.</p>
<p>Yeah.</p>
<p>So, for example,</p>
<p>if you have a test dust environment,</p>
<p>test environment,</p>
<p>and you're running workloads on there</p>
<p>and then all of a sudden</p>
<p>you want to move them into a production</p>
<p>in environment or AQR environment,</p>
<p>it's very easy to take that whole stack</p>
<p>could be an application stack.</p>
<p>It could be multiple application</p>
<p>stacks inside of a, you know, a network</p>
<p>framework.</p>
<p>And then just take that,</p>
<p>do a clone of that.</p>
<p>And now you have number</p>
<p>two running over here on the other side.</p>
<p>Okay.</p>
<p>Is there a limitation to how large</p>
<p>these snapshots go and you call them</p>
<p>tenants, not data centers?</p>
<p>Right. Well, we like to.</p>
<p>Get your term. Perspective.</p>
<p>We call it virtual data centers.</p>
<p>But really, what they are,</p>
<p>because we are a multi-tenant platform,</p>
<p>they are sub tenants of our.</p>
<p>So they can run multiple test. All right.</p>
<p>So let's just call them virtual</p>
<p>data centers because marketing, right.</p>
<p>Yeah, I gotcha there. I get that.</p>
<p>So how how big and complex</p>
<p>can these virtual data centers be</p>
<p>or is it like a limitation?</p>
<p>How many applications of this</p>
<p>could be massive and huge?</p>
<p>Yeah, they can be. They can be massive.</p>
<p>I think our largest customer today runs</p>
<p>over 60 plus nodes in their environment.</p>
<p>They have multiple tenants</p>
<p>that they run in their environment.</p>
<p>Really, the tenant,</p>
<p>the only restrictions around a tenant</p>
<p>or a virtual data center is what is the</p>
<p>what's defined or what's built in the back</p>
<p>end cluster, the virtual cluster.</p>
<p>So if I have a virtual</p>
<p>IO cluster, for example,</p>
<p>and I have four terabytes of memory</p>
<p>and I have 100 terabytes of storage</p>
<p>and I have, you know, 64 cores in my CPU,</p>
<p>I could assign all those resources</p>
<p>to that tenant by one or two</p>
<p>and or I could split in half, split</p>
<p>in thirds, however you want to split it up</p>
<p>and build them that way as well.</p>
<p>All right. So all right.</p>
<p>This is this is really interesting.</p>
<p>Let's see.</p>
<p>I have no tenants.</p>
<p>Ah, well, all right. No, no, no.</p>
<p>I think. I think this is interesting.</p>
<p>I can have maybe 128 nodes,</p>
<p>and I'm going to say I'm allocating</p>
<p>development,</p>
<p>Those would be different tenants. Yes.</p>
<p>Absolutely. Yep.</p>
<p>Right.</p>
<p>So I can snapshot between them</p>
<p>and then move into production.</p>
<p>Yeah.</p>
<p>I can even have multiple production</p>
<p>environments, red or blue.</p>
<p>Green updates in this case.</p>
<p>Yeah, you could</p>
<p>you could figure out a way either</p>
<p>with automation, with a recipe engine</p>
<p>and or if you're just switching between,</p>
<p>like you said, blue, green,</p>
<p>maybe my production, you know,</p>
<p>first quarter as my blue, then my green</p>
<p>and then my blue, etc.</p>
<p>flip back and forth.</p>
<p>Oh boy.</p>
<p>My, my head's starting to spin</p>
<p>just a little bit</p>
<p>on all the things I can do with this.</p>
<p>This could be pretty substantial.</p>
<p>Let's talk let's talk real quick about</p>
<p>some of the use</p>
<p>cases where you see people</p>
<p>using this ability.</p>
<p>What in</p>
<p>what areas</p>
<p>have you seen the most traction for this?</p>
<p>So for our multi tenancy,</p>
<p>we have a lot of our customer</p>
<p>base is MSPs.</p>
<p>So they'll actually use the multi</p>
<p>tenancy piece for their end user customers</p>
<p>and with that they can dedicate zero</p>
<p>trust secure environments</p>
<p>for those customers.</p>
<p>We can do things like BGP</p>
<p>routing to where those customers can use</p>
<p>our own public</p>
<p>IP addresses into those tenants.</p>
<p>And then we do oath authentication</p>
<p>to connect to their environments.</p>
<p>So at that point,</p>
<p>a customer can have their own</p>
<p>cloud environment</p>
<p>totally built out</p>
<p>with one of these virtual data centers</p>
<p>or slash tenant and log in</p>
<p>and they can, based on the resources</p>
<p>that the cluster owner</p>
<p>gave to them, the CPU, the memory,</p>
<p>the storage they can, provisioned</p>
<p>workloads, virtual workloads as needed.</p>
<p>Okay.</p>
<p>So you're your primary target right now</p>
<p>is your mid-tier cloud service provider</p>
<p>more right where I get that</p>
<p>what about what about</p>
<p>just your normal everyday i.t department?</p>
<p>Is there use case for them</p>
<p>or is this really geared just towards</p>
<p>those those mid-tier cloud service</p>
<p>providers?</p>
<p>No, there's great use cases</p>
<p>for the enterprise type I.T customers</p>
<p>where if you have test environments,</p>
<p>where you have environments</p>
<p>where you want to do like blue, green,</p>
<p>where you may have different environments</p>
<p>that have different security compliance</p>
<p>requirements.</p>
<p>Right?</p>
<p>Maybe it's a SOX requirement,</p>
<p>maybe it's a missed requirement, maybe</p>
<p>it's a HIPA or a C you a requirement.</p>
<p>We have some some higher education,</p>
<p>very large education, universities</p>
<p>that use us to create multiple tenants</p>
<p>because, one,</p>
<p>they may have their regulatory policies</p>
<p>that they have to fit under,</p>
<p>but then they want to do different types</p>
<p>of testing and to be able to do that,</p>
<p>they have to spin up basically the tenant</p>
<p>for the virtual data center</p>
<p>where they can get around those policies</p>
<p>but still have it secured</p>
<p>and in effect, you know, air gapped away</p>
<p>from the rest of their environment</p>
<p>like a sandbox,</p>
<p>if you will, or a cyber range.</p>
<p>So that's a very good use case there.</p>
<p>Another good use case, you know,</p>
<p>we can start with a minimum of two node</p>
<p>cluster and then, you know, go out as far</p>
<p>as you need to go out to build that out.</p>
<p>So depending on it may be an edge</p>
<p>use case or a robot remote office use case</p>
<p>where you need something on prem,</p>
<p>but then you want to take that</p>
<p>on prem workload</p>
<p>and you want to build to replicate that</p>
<p>data or replicate those VMs or tenants</p>
<p>to another site for data protection</p>
<p>and, you know, DRM backup and recovery.</p>
<p>Because oh,</p>
<p>boy, you just covered a whole</p>
<p>gamut of things.</p>
<p>Chris, you want to step in here and help</p>
<p>help out with, you know, use cases,</p>
<p>more areas that you think we can use us.</p>
<p>Yeah, sure.</p>
<p>So as Aaron said, we've got several</p>
<p>large EDA</p>
<p>use that are doing compliant research</p>
<p>and what we've enabled them</p>
<p>is they certify their their cluster</p>
<p>a single time.</p>
<p>We have a recipe engine or a template</p>
<p>engine that will create the same instance</p>
<p>with, you know, depending on on resources</p>
<p>like compute and storage and ram.</p>
<p>How much, how much of that they need.</p>
<p>They can they can deliver</p>
<p>a compliant research environment</p>
<p>to one of their research organizations</p>
<p>or researchers</p>
<p>in under an hour.</p>
<p>Okay. So let's delve into this.</p>
<p>One's really interesting to me</p>
<p>because there is a big uptick in</p>
<p>cyber</p>
<p>threats and and regulations</p>
<p>around all this.</p>
<p>Right.</p>
<p>So it's really hard</p>
<p>sometimes to get your environment</p>
<p>into a state that is compliant.</p>
<p>So what you're saying here is</p>
<p>I can build that environment once,</p>
<p>right.</p>
<p>With all the controls</p>
<p>and then just turn on those environments.</p>
<p>And then researchers can now research</p>
<p>in that environment without any concerns</p>
<p>of setting it up appropriately.</p>
<p>It's already. Done.</p>
<p>And and then legacy and legacy</p>
<p>environments.</p>
<p>The researchers</p>
<p>were doing a lot of their own work,</p>
<p>and it could take months to get, you know,</p>
<p>HIPA compliance and run through the EDI</p>
<p>this particular E to use</p>
<p>compliance process.</p>
<p>So we've we've,</p>
<p>you know, prospectively months</p>
<p>off off of,</p>
<p>you know, the beginning of the research.</p>
<p>This this is really this</p>
<p>because I'm in the middle of this</p>
<p>right now with a lot of customers</p>
<p>where we've got to get the patches</p>
<p>put up onto our OSes</p>
<p>or our VMs that are running,</p>
<p>you know, things.</p>
<p>But no one talks about updating</p>
<p>the datacenter with all the policies.</p>
<p>And if you look at the NYSC standards,</p>
<p>patching is is one of like 15 sections,</p>
<p>right?</p>
<p>So what was this? I could</p>
<p>I could patch a a virtual data center.</p>
<p>Correct.</p>
<p>With the things that it's needed</p>
<p>by bye bye bye.</p>
<p>Doing snapshots, is that a.</p>
<p>Snapshot or a clone?</p>
<p>But realistically, what you're doing is</p>
<p>you are copying that virtual data center</p>
<p>and you can take that data center,</p>
<p>update it with those type of regulations</p>
<p>you may have, or with our recipe engine,</p>
<p>you may have virtual data centers</p>
<p>that have different requirements or</p>
<p>regulations that are already set in there.</p>
<p>Right.</p>
<p>You might have different firewall rules.</p>
<p>You might have different network settings.</p>
<p>How to the trust and security set up.</p>
<p>And then it's very easy, just like you</p>
<p>said, snapshot or copy those off</p>
<p>to where, you know, we can do that</p>
<p>within minutes or hours versus</p>
<p>if you go into a traditional environment.</p>
<p>If, for example,</p>
<p>I'm building a virtualized cluster,</p>
<p>I have to build everything from the ground</p>
<p>up, bare metal networking, etc..</p>
<p>But once you put that virtual data center</p>
<p>on that, that multi-tenant, see,</p>
<p>it's very easy to copy create. Gotcha.</p>
<p>All right. So let's talk about updating,</p>
<p>though.</p>
<p>Let's say I have a recipe that's there</p>
<p>and and new HIPA regulations come out.</p>
<p>So I've got to make changes.</p>
<p>I've already deployed this</p>
<p>in several places.</p>
<p>So you guys have a mechanism</p>
<p>where I just update the recipe</p>
<p>and then I can go apply that recipe on</p>
<p>to currently running systems.</p>
<p>How would I do that?</p>
<p>Because</p>
<p>I, I, I don't I have applications running</p>
<p>in those that I've added on.</p>
<p>So how do I update an environment</p>
<p>like that then.</p>
<p>Does that?</p>
<p>Yes. So we don't necessarily</p>
<p>have an automation engine</p>
<p>or a recipe engine for your application</p>
<p>level or inside your VM workloads.</p>
<p>Typically that would be done with things</p>
<p>like infrastructure as a code or config</p>
<p>management like Ansible or TerraForm,</p>
<p>those types of tools, maybe puppet chef</p>
<p>or PowerShell Python</p>
<p>scripting tools, programing tools.</p>
<p>But for the environment, for our</p>
<p>our our tenant or virtual data center,</p>
<p>you could go back in with that recipe</p>
<p>and update that tenant with that recipe.</p>
<p>So maybe I need to change</p>
<p>some firewallrules maybe</p>
<p>I need to do some configuration settings</p>
<p>on the way my resources are mapped out to</p>
<p>my workloads.</p>
<p>Are mapped out. Right.</p>
<p>Okay.</p>
<p>Can I take a running VM?</p>
<p>Well, this is Darren's crazy thoughts.</p>
<p>I mean, these are crazy</p>
<p>where I've got a running environment,</p>
<p>everything's running.</p>
<p>I got my applications all running.</p>
<p>I have new hyper requirements</p>
<p>that came out.</p>
<p>Okay, gotcha.</p>
<p>I got I create a new environment.</p>
<p>Can I then take the VMs running in one</p>
<p>and migrate them over on</p>
<p>to the onto the new infrastructure?</p>
<p>You can.</p>
<p>And so what we do is we allow you to set</p>
<p>up the networking to be able to do that.</p>
<p>So you can take those VMs,</p>
<p>you can either snapshot them</p>
<p>or you can migrate them over</p>
<p>to that other tenant.</p>
<p>You will.</p>
<p>Okay, so there's a path</p>
<p>there's a path to upgrading</p>
<p>without having to reconstruct</p>
<p>because as you said before,</p>
<p>you guys don't handle the application</p>
<p>stacks per se.</p>
<p>But I can take a running environment,</p>
<p>the VMs in a running environment</p>
<p>and move them over</p>
<p>on onto a new</p>
<p>a new environment</p>
<p>that has the new compliance on it.</p>
<p>That's right. That would be okay.</p>
<p>Or you can even you could do it</p>
<p>even to a sense where you take that</p>
<p>that environment,</p>
<p>you do a clone of it, you test it</p>
<p>because you always want to test anything</p>
<p>before you upgraded or move it.</p>
<p>Right, of course.</p>
<p>And then do your adjustments</p>
<p>and then once it's</p>
<p>set and good clone it again or just,</p>
<p>you know, change over to that and.</p>
<p>Going to move it over. Yeah.</p>
<p>Yeah.</p>
<p>I'm glad you brought up test</p>
<p>because I used to be a CIO.</p>
<p>I've made some mistakes as a CIO.</p>
<p>I used to be a developer.</p>
<p>I've made some mistakes as a developer.</p>
<p>One of the biggest mistakes</p>
<p>is I think it's good enough.</p>
<p>I made that one small change.</p>
<p>It shouldn't really matter if I test it</p>
<p>and you push it into production,</p>
<p>everything falls apart.</p>
<p>So with that, with your guys's technology,</p>
<p>there's no excuses, really.</p>
<p>You got rid of my excuse.</p>
<p>Well, the other cool</p>
<p>thing about our technology, too, is we do</p>
<p>we have snapshots</p>
<p>built into the environment.</p>
<p>And the nice thing about our snapshots is</p>
<p>you can do VM level snapshots, you can do</p>
<p>virtual data center level snapshots</p>
<p>and you can do cluster level snapshots.</p>
<p>So you can have a snapshot</p>
<p>that protects you</p>
<p>from from those types of bugs</p>
<p>or stupid human tricks, if you will.</p>
<p>And I coined that phrase</p>
<p>from someone else, another CIO or CTO</p>
<p>that I had talked to in the past.</p>
<p>But, you know, you apply that update.</p>
<p>And if something does</p>
<p>go wrong with that update</p>
<p>and it's not something that you can easily</p>
<p>take out of the application, right?</p>
<p>The OS level</p>
<p>now you can easily rollback to a snapshot</p>
<p>before you apply that update.</p>
<p>And again, at that level,</p>
<p>a tenant level and the cluster level.</p>
<p>All right. Very, very cool. All right.</p>
<p>We cover like the update use case.</p>
<p>Let's talk about security.</p>
<p>Chris, will you lay tile?</p>
<p>Tell us a little bit about security.</p>
<p>How what use cases?</p>
<p>I can I can use this technology</p>
<p>in helping with security.</p>
<p>Yeah.</p>
<p>So it's very similar to the test dev</p>
<p>type of a type of a use case where,</p>
<p>you know, we deploy on x86 hardware.</p>
<p>Every, every test engineer or dev engineer</p>
<p>can can have their own environment</p>
<p>to do whatever they want with.</p>
<p>And when they're done, they blow it away.</p>
<p>And, you know, they've got</p>
<p>the original golden image back.</p>
<p>We have a very large</p>
<p>one of the largest quant firms</p>
<p>in in Europe that's a customer</p>
<p>and it's a security type use case.</p>
<p>So what they're doing is they're taking</p>
<p>a picture of their entire environment</p>
<p>and then they're running red</p>
<p>team, blue team drills against that.</p>
<p>It's a it's about an eight person</p>
<p>organization</p>
<p>and same thing, looking for security</p>
<p>vulnerabilities, checking patches,</p>
<p>that kind of thing.</p>
<p>Oh, so that's an interesting case.</p>
<p>I can take my production</p>
<p>system, environment, everything,</p>
<p>snapshot it and then release</p>
<p>my red team at it and say.</p>
<p>Break it.</p>
<p>Break it, you know, hack in</p>
<p>or my blue team sitting there going,</p>
<p>trying to defend it the whole time</p>
<p>without affecting production.</p>
<p>But I have a copy of the production</p>
<p>environment.</p>
<p>Yes, exactly.</p>
<p>That's pretty darn slick.</p>
<p>I like that use case.</p>
<p>Any other use cases around security.</p>
<p>That's that's</p>
<p>the one that we've actually tested out</p>
<p>and proved you know in the market</p>
<p>and it is akin to the</p>
<p>the test use case as well.</p>
<p>So that makes sense.</p>
<p>I my brain went to honeypots.</p>
<p>Yes. I you know,</p>
<p>I detect</p>
<p>I detect someone and I put I'd put them</p>
<p>in that pretend production environment</p>
<p>they don't even know.</p>
<p>Stay tuned on that one, Darren.</p>
<p>We've we are we agree with you.</p>
<p>We'll just leave it there.</p>
<p>We'll just we're not going to talk anymore</p>
<p>about that.</p>
<p>Well, no, Darren,</p>
<p>you hit it right on the head, too.</p>
<p>I mean, essentially, once you virtualize</p>
<p>the data center, you can pretty much apply</p>
<p>any type of use case to it, right?</p>
<p>Honeypot, cyber range, sandbox,</p>
<p>you know, arrogant environment.</p>
<p>It's,</p>
<p>you know, the whatever you want to do too.</p>
<p>It's very flexible.</p>
<p>Yeah, no, I'm in.</p>
<p>Well, sometimes we need to spell it out</p>
<p>because I don't think people</p>
<p>realize the flexibility that this gives.</p>
<p>This is</p>
<p>pretty cool.</p>
<p>All right, let's.</p>
<p>All right.</p>
<p>So we talked configuration, we talked</p>
<p>upgrades, security.</p>
<p>What's another major use case category?</p>
<p>Erin, what do you think?</p>
<p>Well.</p>
<p>So let's see here.</p>
<p>Let me just some of our use cases. So,</p>
<p>you know, we do partner with a company</p>
<p>for media support.</p>
<p>You can run BD in our environment.</p>
<p>The nice thing about that is</p>
<p>we can control the resources, the CPU,</p>
<p>the memory.</p>
<p>We also support</p>
<p>GPU, passthrough and virtual GPUs.</p>
<p>Today we support that with NVIDIA</p>
<p>for the virtual CPU</p>
<p>and GPU pass through and then for physical</p>
<p>just playing physical GPU.</p>
<p>Also, we also support</p>
<p>some other ones on there,</p>
<p>but for the most part,</p>
<p>that's a big use case for some customers,</p>
<p>especially if they're want to do things</p>
<p>like engineering, oil type,</p>
<p>you know, workloads, oil or oil and gas,</p>
<p>I should say.</p>
<p>But anything basically that requires</p>
<p>any type of GPU resource around that.</p>
<p>And then of course the vehicles as well.</p>
<p>Yeah, I really like</p>
<p>because normally when we think about it,</p>
<p>when we think about VDI,</p>
<p>we think, Oh, I have a virtual desktop.</p>
<p>That's what it is.</p>
<p>But for complex systems</p>
<p>like what I deal with, I'm programing.</p>
<p>For example, I have more than one VM,</p>
<p>I have a virtual desktop</p>
<p>and a bunch of VMs that I want to to use.</p>
<p>So this would be very cool for me where</p>
<p>I can have like a group of VMs that I'm</p>
<p>Snapchatting and doing my development on</p>
<p>and I can access them remotely.</p>
<p>And, and that that VDI session</p>
<p>can be bundled together</p>
<p>with my VMs into one virtual data center</p>
<p>for me or one virtual tenant for me.</p>
<p>Yeah, absolutely.</p>
<p>Pretty,</p>
<p>that's pretty cool that that unlocks</p>
<p>a lot of new programing use cases for me</p>
<p>as is what I see.</p>
<p>Yeah.</p>
<p>The the the virtual GPU also Darren</p>
<p>really,</p>
<p>really makes the economics favorable.</p>
<p>So, you know, that's not inexpensive</p>
<p>technology and a 1 to 1</p>
<p>can can get expensive.</p>
<p>So the ability to share</p>
<p>that out among several users</p>
<p>really really</p>
<p>really</p>
<p>delivers a favorable economic model.</p>
<p>My brain</p>
<p>also went to what I call micro cloud</p>
<p>because I know your guys's stuff</p>
<p>has a very small footprint.</p>
<p>I can run it on on very small machines.</p>
<p>And we're starting</p>
<p>to see more emergence of the edge.</p>
<p>And when people think edge,</p>
<p>they're thinking</p>
<p>smartwatches,</p>
<p>smartphones, sensors, cameras.</p>
<p>We're also seeing edge devices</p>
<p>that have three or four nodes.</p>
<p>And so I can really see your guys's</p>
<p>technology being used as a distribution</p>
<p>channel where I'm distributing</p>
<p>on to these micro data</p>
<p>centers, I'm distributing software stacks,</p>
<p>I'm distributing a full virtualized</p>
<p>data center tenant out there</p>
<p>that's self-contained,</p>
<p>managed, can, can run without issues.</p>
<p>Is that something</p>
<p>you guys have started to see yet or not?</p>
<p>Yeah, absolutely.</p>
<p>Yeah. I would say it's a use case</p>
<p>that we're going after.</p>
<p>It's actually a perfect fit for us.</p>
<p>If you look at an edge use case,</p>
<p>one example</p>
<p>that's common is a point of sale</p>
<p>use case, right?</p>
<p>Where I'm a retail customer</p>
<p>and I have 50 stores, 100 stores, and now</p>
<p>I need to have two or three applications</p>
<p>or VMs that are in that store.</p>
<p>And just like you said, we are our minimum</p>
<p>requirements are very small footprint.</p>
<p>We like to see at least two servers</p>
<p>for high availability.</p>
<p>But once you have that, you put that</p>
<p>in that edge use case data center</p>
<p>and you can build those VMs.</p>
<p>And then again with our snapshot</p>
<p>and replication</p>
<p>features,</p>
<p>you can take those configurations</p>
<p>and then just copy paste across</p>
<p>all those different environments.</p>
<p>Yeah, I see.</p>
<p>That's pretty cool because now,</p>
<p>now you're talking updates, right?</p>
<p>Yeah, I have 100</p>
<p>I have 100 stores out there.</p>
<p>I all want them to</p>
<p>have the latest and greatest</p>
<p>configurations, not</p>
<p>just OS patches, but also firewall rules.</p>
<p>The whole thing.</p>
<p>I can just peanut butter</p>
<p>that thing across.</p>
<p>Yeah, absolutely.</p>
<p>Now that's that's that's pretty slick.</p>
<p>And if you if you start to double</p>
<p>click on on the the edge use case.</p>
<p>And to your point, Darren, it's you know,</p>
<p>it means a lot of things.</p>
<p>It can be a smart refrigerator</p>
<p>or a gas meter.</p>
<p>It can be. Yeah, yeah, yeah. Cool.</p>
<p>We're looking hard right now</p>
<p>and speaking with people</p>
<p>in any eight hour space</p>
<p>because those cars generate so much data.</p>
<p>A lot of the vendors are testing them</p>
<p>in remote sites and they're</p>
<p>they're literally shipping</p>
<p>hard drives around.</p>
<p>I've been in that space.</p>
<p>Yeah, it's a nightmare.</p>
<p>And 80, 85% of that data ends up getting</p>
<p>thrown away once the processing is done.</p>
<p>So think about the ability now to be able</p>
<p>to process that on a remote site, fully</p>
<p>redundant with with the compelling cost</p>
<p>associated with it.</p>
<p>And then you can</p>
<p>then you can transport the data,</p>
<p>you know, via</p>
<p>a wide area versus a disk and a truck.</p>
<p>No, no, I really like that a lot.</p>
<p>And well, I'm actually Funyons.</p>
<p>They're not</p>
<p>they're not removing any of that data</p>
<p>they're collecting because they're afraid.</p>
<p>Oh, yeah, yeah.</p>
<p>Because I'm still training these cars.</p>
<p>There might be some data in there</p>
<p>so they don't get rid of anything.</p>
<p>They gather all the data,</p>
<p>but they ship that the,</p>
<p>you know, for the for the model data,</p>
<p>they'll ship that back overall.</p>
<p>Yeah. Yeah. That's versus a FedEx truck.</p>
<p>Well well and that's exactly</p>
<p>what they're using is FedEx trucks</p>
<p>full of drives</p>
<p>you know petabytes of storage,</p>
<p>being trans</p>
<p>transported via FedEx to the data center.</p>
<p>I've seen it myself. So I know.</p>
<p>I know so very, very cool.</p>
<p>Very cool.</p>
<p>Technology unleashing new ways</p>
<p>of thinking about things.</p>
<p>Very cool stuff, guys.</p>
<p>Any last words for our</p>
<p>our audience out there?</p>
<p>Chris Couple a couple things</p>
<p>we've mentioned the lightweight</p>
<p>hardware footprint a couple of times.</p>
<p>We can take two x86 based servers</p>
<p>and a crossover cable or a dumb layer</p>
<p>two switch and give it full</p>
<p>routing capability for redundancy. And</p>
<p>as many virtual data centers or tenancies</p>
<p>as you have resources to deliver.</p>
<p>We also</p>
<p>have to have a pretty robust</p>
<p>channel program as well</p>
<p>that that people should, should be,</p>
<p>should know about and be interested in.</p>
<p>Great.</p>
<p>All right, Aaron,</p>
<p>what about you, the boss, everything?</p>
<p>Yeah, I think Chris covered it</p>
<p>for the most part.</p>
<p>It is a great technology.</p>
<p>At the very beginning of the call,</p>
<p>you asked why, you know, why Verge.io</p>
<p>and one of the reasons coming over here</p>
<p>is when I saw the technology,</p>
<p>it looked like a disruptor to me.</p>
<p>And it's very solid.</p>
<p>We have a you know, our core team of</p>
<p>developers has been here the whole time.</p>
<p>So that means a lot to me.</p>
<p>It's coming in to a new company</p>
<p>because when when you need new features</p>
<p>or you have questions</p>
<p>about the technology,</p>
<p>we have the people there</p>
<p>to back it up and support it.</p>
<p>So it's really good.</p>
<p>Cool stuff.</p>
<p>Hey, guys, thank you very much.</p>
<p>Anyone can find out more information</p>
<p>about Verge.io.</p>
<p>Oh, there you go. Yeah.</p>
<p>All right. Hey, thanks a lot, guys.</p>
<p>Thank you. Thanks very</p>
<p>thank you for listening to Embracing</p>
<p>Digital Transformation today.</p>
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
