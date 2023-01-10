---
layout: posts
title: "Operationalizing Business Process Management"
number: 113
permalink: EDT113
has_children: false
parent: Episodes
nav_order: 113
tags:
    - EDT113
    - EmbracingDigital
    - Business Process Management
    - Automation
    - Camunda
    - CapitalBPM
    - BPM

date: 
guests:
    - Darren W Pulsipher
    - Max Young

img: TBD
summary: "In this episode, Darren discusses business process management and automation with Max Young, CEO of Capital BPM"
---

{% include soundcloud.html id="edt113" title="#113 Operationalizing Business Process Management" %}

{% include youtube.html id="bIJRyJxSGvE" %}

---

In this episode, Darren discusses business process management and automation with Max Young, CEO of Capital BPM.

Max calls himself a “failed academic” because he left his Ph.D. in mathematics, specializing in topology, to study computer science. He earned an undergraduate and a master’s degree, specializing in AI. He then worked in business process management (BPM), starting at Lombardi, which was sold to IBM, and a few other vendors in the BPM space. Ten years ago, he took a plunge with friends and founded Capital BPM.

Max chose to focus on BPM for two reasons. First, he has always liked algorithms because it provides a systematic approach to solving complex problems. Algorithms give him a sense of security during crazy situations.

Second, he likes what is called transformations in mathematics. For example, if you have an ugly shape with many corners that is hard to measure, you would transform it into, say, a rectangle and then apply all the theories around rectangle measurement, measure it, and translate the answer back to the original shape. In the same way, in BPM, you can take a problem to a domain where it can be easily solved. Rather than making an issue a micro problem with complicated nested F statements that are difficult to maintain, you can transform it into a flattened-out problem that you can see and attack in stages.

This process is like zooming in on Google maps to see where you need concentrated focus and then zooming back out to see how that fits into the big picture. The heart of enterprise architecture is the ability to zoom in and out to ensure that line you’re drawing is still valid.

Max likens his fondness for BPM within the computer science world to martial arts, which he has studied since he was six. He says there are practical martial arts, such as judo and muay Thai, and more esoteric ones, such as tai chi. He likes pragmatic martial arts because they solve real-world problems. He doesn’t get into fistfights anymore, but, for example, his judo skills help him when he slips and falls. BPM is pragmatic in that it is the key to solving a business problem. He believes there is actual value in using all the theories he learned in school and making them subservient in creating a business platform that allows people to more efficiently and consistently solve everyday problems, thereby giving people and the community more opportunities.

This is one area of computer science that can be attached to how people work. Things can be automated to reduce the amount of repeatable and mundane tasks so they can focus on more important things. People worry that automation will swallow up everyday jobs, but instead, it removes drudgery and frees up time for more critical work. It can also create jobs. These same fears existed when Ford automated computers were introduced, but they ultimately made new industries. BPM should be fully embraced rather than feared.

The best way to start operationalizing processes is to use the scientific method of articulating the problem. In business process management, you draw pictures via a business process modeler. Max likes Camunda Business Process Modeler, which is downloadable for free with just a little notation to learn. In the modeling program, you draw steps that articulate the different systems and how they work.

In a hiring process, for instance, you start with a pool that defines interested parties, such as the candidate, the IT manager, and HR. Inside the pool are “swim lanes,” each containing one player who can do things. You can think of these as LDAP groups. Then you start laying out your business process: first, a candidate applies for the job, then HR might do a review, then an IT manager will review. Approved decisions are noted along the way. After the top-level, significant steps are in the model, you can get down into more detail regarding more articulate and nuanced processes, like a split interview, one for technical and one for management.

![bmp image](./bpm.png)

The modeling program generates XML behind the scenes as you draw all of these diagrams. This XML is run time interpretable by BPM machines; as you are drawing the diagram, it can become an executable process.

The human element is still in this loop but using a BPM system like this makes it clear where processes can be automated, such as checking job history or running a criminal background check. The model also allows flexibility and experimentation. For example, suppose the subject matter expert says that they don’t want to run a job check and criminal record check simultaneously because the criminal record check is expensive, and the job check is cheap. In that case, it’s easy to change to move the job check first and require a decision before the criminal record check. As changes are made, you build consensus and a true story that becomes progressively truer the more you experiment.

While the tool looks like a drawing tool, it is a modeling tool that lets you draw pictures and simulates them on the back end. So you can run this process and see all the different decision points and where they lead. The model will also tell you that you can’t deploy if you haven’t done something correctly.



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
<p>On today's episode, Operationalizing</p>
<p>Business Process Automation</p>
<p>with CEO of Capital BPM, Max Young.</p>
<p>Max, welcome to the show.</p>
<p>Thank you, Darren.</p>
<p>Good. Good to be talking to you again.</p>
<p>So, Max, this is like the third or fourth</p>
<p>time we've talked.</p>
<p>I was really impressed</p>
<p>with some of the things that you showed me</p>
<p>on business process management</p>
<p>and business process automation.</p>
<p>I really like the approach</p>
<p>that you guys took.</p>
<p>But before we dove into that, Max,</p>
<p>let's hear your background a little bit.</p>
<p>Where do you come from?</p>
<p>What led you to where you're at today?</p>
<p>Sure. Sure.</p>
<p>So I am a failed academic.</p>
<p>I was studying for my Ph.D.</p>
<p>in mathematics, specializing</p>
<p>in topology in the mid-nineties,</p>
<p>and I looked at my</p>
<p>talents, which were meager,</p>
<p>and I looked at the job.</p>
<p>Pull for mathematicians</p>
<p>versus computer sciences.</p>
<p>And I walked across the street at Ohio</p>
<p>State, and I got into computer science</p>
<p>specifically and finishing</p>
<p>an undergraduate</p>
<p>and a masters specializing in AI.</p>
<p>And then I just started</p>
<p>working in the computer field.</p>
<p>I got the bug early on.</p>
<p>I published a couple of books</p>
<p>I actually helped with.</p>
<p>Part of the Java line was the digital 1.4</p>
<p>Value Expressions Engine.</p>
<p>I had a small, small part to do with that.</p>
<p>And then, you know, I found myself</p>
<p>a small company called Lombardi,</p>
<p>which was run business process management</p>
<p>that was sold to IBM.</p>
<p>I bumped around to a couple</p>
<p>of other vendors that work</p>
<p>in the same</p>
<p>BPM process orchestration space.</p>
<p>About ten years ago I took the plunge and</p>
<p>with some friends we formed Capital IPA.</p>
<p>Oh, that's awesome.</p>
<p>I what what a great story.</p>
<p>Right.</p>
<p>Mathematician found your way</p>
<p>to the computer science realm like myself.</p>
<p>I started in E, actually. Okay.</p>
<p>And I said, wow,</p>
<p>I'm really good at this programing stuff.</p>
<p>Let me go learn how to do it right.</p>
<p>And I had some great teachers</p>
<p>in computer science</p>
<p>and I ended up switching</p>
<p>literally the last year of college.</p>
<p>I switched from double lead to see us</p>
<p>and finished my senior degree.</p>
<p>And yeah, that was crazy that I did that.</p>
<p>What was I thinking?</p>
<p>You know, you double</p>
<p>guys were the only ones</p>
<p>that I was intimidated by academically.</p>
<p>Like, I always felt like, you know,</p>
<p>like a chief nerd being a mathematician.</p>
<p>And then, you know,</p>
<p>you guys walked in the room,</p>
<p>and you guys could do all the math.</p>
<p>We could do,</p>
<p>but you could also do the engineering.</p>
<p>And it was very intimate. Well.</p>
<p>I have to tell you, I come from a company.</p>
<p>Intel has a lot of doubles.</p>
<p>They're not the best they're not the best</p>
<p>software engineers in the world.</p>
<p>Right.</p>
<p>Because and I learned that I'm</p>
<p>a total software guy.</p>
<p>I'm not in fact, even in double E, I said</p>
<p>I don't want to be like everyone else.</p>
<p>So I took the power option.</p>
<p>What was he thinking?</p>
<p>Because I'm not a great mathematician.</p>
<p>I'm horrible at math.</p>
<p>But I there was something</p>
<p>I could really architect software.</p>
<p>Really? Well, yeah.</p>
<p>And, and look at it tops down</p>
<p>and it got me through</p>
<p>some of my classes, my programing skills</p>
<p>because the teacher was like,</p>
<p>you really are horrible</p>
<p>at the test and things,</p>
<p>but this program you wrote that explains,</p>
<p>you know, a field theory on on power</p>
<p>lines, that's incredible.</p>
<p>I'm like, oh, thanks.</p>
<p>Yeah.</p>
<p>So we'll let you pass this class.</p>
<p>That's kind of</p>
<p>what my my college career was like.</p>
<p>So very nice.</p>
<p>I know exactly what you're talking about,</p>
<p>but that's let's let's talk about why</p>
<p>business process management.</p>
<p>I mean, this is</p>
<p>this is kind of in that real weird</p>
<p>realm of computer science</p>
<p>where, oh, it's not algorithms, it's,</p>
<p>you know,</p>
<p>but it's so important and so useful.</p>
<p>But why did you choose that route?</p>
<p>So there are two reasons.</p>
<p>One is I've always liked algorithms.</p>
<p>I've always liked systematic approaches</p>
<p>to solving complex problems.</p>
<p>It's the same reason I got into</p>
<p>martial arts.</p>
<p>You know, there is a way to do this thing.</p>
<p>There's a way to throw a good punch.</p>
<p>There's a</p>
<p>there's a way to protect your ribs</p>
<p>when you're,</p>
<p>you know, when you're boxing, whatever.</p>
<p>I like algorithms.</p>
<p>They give me a sense of security and also,</p>
<p>frankly, a sense of daring.</p>
<p>I can get into crazy situations</p>
<p>and trust the algorithm.</p>
<p>The other thing I really like about</p>
<p>business process management in particular</p>
<p>is that it reminds me a lot</p>
<p>of what we call</p>
<p>transformations in mathematics.</p>
<p>So let's say you have this shape</p>
<p>that's like really ugly, right?</p>
<p>And you're trying to measure it and you</p>
<p>can't because it's got all these corners.</p>
<p>What you would do in mathematics</p>
<p>and mathematics is you would</p>
<p>transform this to a different space</p>
<p>where it's like a beautiful rectangle.</p>
<p>And then you apply</p>
<p>all the theories around measurements</p>
<p>of rectangles, and you measure that.</p>
<p>You take the answer and then you translate</p>
<p>the answer back right?</p>
<p>So you take your problem to a domain</p>
<p>where it can be solved easily.</p>
<p>You get the value out of that</p>
<p>and you bring it back.</p>
<p>And that's what I really like</p>
<p>about business process management.</p>
<p>I can take all these things around.</p>
<p>Well, this system has got to talk</p>
<p>to this other system,</p>
<p>except when this event goes off.</p>
<p>And here's the escalation that we do,</p>
<p>unless there's an eruption.</p>
<p>And then sometimes</p>
<p>we have a business rule</p>
<p>that we have to apply,</p>
<p>and this is how we talk</p>
<p>to this other thing.</p>
<p>And rather than making that</p>
<p>like a micro problem, super</p>
<p>complicated, nested, if statements</p>
<p>that are difficult to maintain,</p>
<p>it becomes this</p>
<p>beautiful, sort of flattened out problem.</p>
<p>The you can see and attack in stages</p>
<p>you know like zooming in on Google Maps</p>
<p>like here's</p>
<p>where we need concentrated focus</p>
<p>and then you zoom back out and see how</p>
<p>that fits into the big picture.</p>
<p>I really like what you said there</p>
<p>because I found that myself.</p>
<p>You do need a top level picture</p>
<p>of everything so you can see how things</p>
<p>relate to each other in proximity,</p>
<p>just like in the map, right?</p>
<p>You can see a map of the United States</p>
<p>to really understand</p>
<p>where the California where I live</p>
<p>is it with relationship to other things?</p>
<p>I need to blow it out</p>
<p>in order to get a feel for, hey,</p>
<p>how long is it</p>
<p>going to take me to drive to Oregon?</p>
<p>Exactly right.</p>
<p>I can see that</p>
<p>same thing with business process.</p>
<p>I love</p>
<p>I love that analogy. That's a great one.</p>
<p>Yeah. That ability.</p>
<p>I think that's something</p>
<p>that you and I have in common.</p>
<p>You know, as soon as we started talking,</p>
<p>I felt like we were from the same tribe</p>
<p>because that ability to be able</p>
<p>to zoom out and zoom in</p>
<p>and make sure that the line</p>
<p>you're drawing is still true.</p>
<p>That's the</p>
<p>heart of, I think, enterprise</p>
<p>architecture,</p>
<p>right?</p>
<p>I think that's really critical.</p>
<p>And finally, I will say this.</p>
<p>The thing that I really like about</p>
<p>okay, so minor tangent here,</p>
<p>I'm really in a martial arts.</p>
<p>I've been doing it.</p>
<p>I'm 51 now. I've been doing martial arts.</p>
<p>I was like six.</p>
<p>Oh, wow.</p>
<p>And within the realm of martial arts</p>
<p>and I've got multiple ones.</p>
<p>I've been beat up by a lot of people.</p>
<p>But within the realm of martial arts,</p>
<p>they're like these martial arts that</p>
<p>are considered practical, like your judo,</p>
<p>your boxing, your Muay Thai.</p>
<p>And then you've got ones</p>
<p>that are a little bit more esoteric,</p>
<p>like your Thai cheese</p>
<p>and your Aquino's and whatnot.</p>
<p>Now, the thing that I like</p>
<p>about the pragmatic martial arts</p>
<p>is that they solve real world</p>
<p>problems, right?</p>
<p>They they have an effectiveness</p>
<p>that is germane to the art itself.</p>
<p>So, you know, I'm at my fifties</p>
<p>and I don't get into fistfights anymore,</p>
<p>but I slip and fall</p>
<p>all the time and my judo saves me.</p>
<p>Right.</p>
<p>There's a pragmatic</p>
<p>there's a pragmatic aspect to it.</p>
<p>In the same way I</p>
<p>like business process management</p>
<p>because it is fun.</p>
<p>It is key to solving a business problem.</p>
<p>We're taking all these theories</p>
<p>and all these things that you and</p>
<p>I learned through school and grad school</p>
<p>and on the job.</p>
<p>But we're making them subservient</p>
<p>to creating a business platform.</p>
<p>That means that people</p>
<p>get to keep their jobs and get bonuses</p>
<p>and buy Christmas kids for their kids.</p>
<p>And I love being a part of that.</p>
<p>Without without, you know,</p>
<p>writing a love letter to capitalism.</p>
<p>I feel that there is a true value</p>
<p>that I provide to my community</p>
<p>by making it easier and more consistent</p>
<p>for people to solve common problems.</p>
<p>Therefore, giving them the opportunity</p>
<p>to go solve uncommon</p>
<p>and interesting and exciting problems.</p>
<p>So this is I like how you said that,</p>
<p>because</p>
<p>it's not always the case</p>
<p>with computer science</p>
<p>that we can really attach</p>
<p>to the way people work.</p>
<p>Right. Right.</p>
<p>And this is kind of that human computer</p>
<p>interaction part.</p>
<p>A lot of times we're actually creating</p>
<p>more work for for people with this.</p>
<p>You're kind of turning it around.</p>
<p>How do people work? Yeah.</p>
<p>And how can we automate</p>
<p>the things that they do</p>
<p>that are</p>
<p>that are repeatable and mundane, right?</p>
<p>So that we can make their</p>
<p>their work easier</p>
<p>and so they can focus more</p>
<p>on more important things.</p>
<p>I really like that.</p>
<p>And that's another thing</p>
<p>that I am really excited about.</p>
<p>People talk about the threat of automation</p>
<p>to mundane jobs,</p>
<p>and that is a valid that is a valid</p>
<p>critique.</p>
<p>Automation is going to swallow up</p>
<p>a lot of mundane jobs.</p>
<p>Yeah, but look what the. Jobs</p>
<p>it creates. Though.</p>
<p>That's yeah, you're you read my mind</p>
<p>because what it really does</p>
<p>is it removes drudgery of open email,</p>
<p>you know, copy,</p>
<p>I don't know this field number 27</p>
<p>from Excel put it into the services,</p>
<p>then push the button</p>
<p>and wait 3 minutes to removes that</p>
<p>and it allows people</p>
<p>to step back and solve next generation</p>
<p>problems, real problems that were hiding</p>
<p>behind the money problems.</p>
<p>But you never got to them because you were</p>
<p>opening Excel and waiting 3 minutes.</p>
<p>Right, exactly.</p>
<p>And it I mean, this revolution</p>
<p>that we're seeing on</p>
<p>on information automation and things, it's</p>
<p>the same thing</p>
<p>that went through with Ford</p>
<p>when he automated automaking.</p>
<p>Right.</p>
<p>It's the same thing that we saw</p>
<p>when computers were first introduced</p>
<p>in the sixties and seventies.</p>
<p>Yeah, right.</p>
<p>Oh, no.</p>
<p>What are all those people going to do?</p>
<p>It is true</p>
<p>we don't have typing pools anymore,</p>
<p>right?</p>
<p>Yeah.</p>
<p>I can't even imagine because I grew up on</p>
<p>I grew up with email and.</p>
<p>Oh, yes, this world I can't even imagine.</p>
<p>How would you communicate</p>
<p>before you'd call on the phone?</p>
<p>You'd some memos</p>
<p>so someone would take something up.</p>
<p>So, so much wasted time.</p>
<p>But there were a lot of people</p>
<p>supporting that.</p>
<p>But if you look,</p>
<p>those people are now in powered in more</p>
<p>powerful and more</p>
<p>contributing positions</p>
<p>than they were before.</p>
<p>Yeah. So yeah.</p>
<p>And it's created</p>
<p>whole new whole new industries around it.</p>
<p>So I think we have to embrace it.</p>
<p>Absolutely.</p>
<p>So let's let's talk about embracing</p>
<p>how do I operationalize this?</p>
<p>Because there are so many tools out there</p>
<p>on business process automation</p>
<p>or robot process or robotic process</p>
<p>automation.</p>
<p>RPA Yeah.</p>
<p>Yeah.</p>
<p>How, how do I really make this happen</p>
<p>now where</p>
<p>I can actually use it</p>
<p>effectively and repeatedly?</p>
<p>So what was the first step?</p>
<p>So great that man, I, I really,</p>
<p>I love the way</p>
<p>you approach things because your first</p>
<p>questions are pragmatic. So</p>
<p>what I would say is that</p>
<p>the best way,</p>
<p>so it comes back to the scientific method.</p>
<p>The best thing to do</p>
<p>is to articulate out your problem</p>
<p>and the way that we do that.</p>
<p>In my world, in the business process</p>
<p>management world,</p>
<p>is we draw little pictures.</p>
<p>So can I share my screen</p>
<p>and show you something?</p>
<p>Absolutely.</p>
<p>So there is a free tool like this</p>
<p>called it's called the Commander</p>
<p>BPM and Modeler.</p>
<p>You can download it for free.</p>
<p>There's a company out there</p>
<p>called Commander.</p>
<p>They, you know, they make this modeler.</p>
<p>There are other companies</p>
<p>that do this as well.</p>
<p>I like is</p>
<p>I think it's a pretty good one. It's</p>
<p>it's pretty clear.</p>
<p>And there's just a little bit of notation</p>
<p>that you have to learn.</p>
<p>And it is this you're basically</p>
<p>going to be drawing steps</p>
<p>that articulate out</p>
<p>what the different systems are</p>
<p>and how they work.</p>
<p>So just a little bit of vocabulary.</p>
<p>This will literally this one part of it,</p>
<p>it'll be over in about 2 seconds.</p>
<p>So we have this concept of a pool</p>
<p>and a pool kind of defines</p>
<p>all of the interested parties</p>
<p>in a process.</p>
<p>So if this was like a hiring process,</p>
<p>we would have like a candidate</p>
<p>and we'd have the i.t manager</p>
<p>and we have h.r.</p>
<p>So the larger thing that you see</p>
<p>and hear outside is called the pool.</p>
<p>The inner ones are called swim</p>
<p>lanes. Right?</p>
<p>So let's say</p>
<p>we're doing like a hiring process.</p>
<p>We have a candidate in the swim line</p>
<p>and then we have like h.r.</p>
<p>And you can think of these</p>
<p>as sort of elderly groups, right?</p>
<p>People who are in a role</p>
<p>that are allowed to do something</p>
<p>and then you might have like 90 manager.</p>
<p>So now you</p>
<p>start laying out your business process.</p>
<p>What's the first thing that happens?</p>
<p>Well and candidate might apply</p>
<p>and you have excuse me.</p>
<p>My my spelling is atrocious.</p>
<p>Apply for a job.</p>
<p>And then, you know, from there</p>
<p>it goes to a next step, which is H.R..</p>
<p>H.R. might do a review.</p>
<p>There's a there's a name</p>
<p>you can register how you do this stuff.</p>
<p>You know, you have like a active verb</p>
<p>and a noun, but you might say something</p>
<p>like review application</p>
<p>and then you might have like a decision.</p>
<p>These little diamonds represent decision.</p>
<p>So if you know, if it's approved,</p>
<p>it goes back up.</p>
<p>You go to say the i.t.</p>
<p>Manager who might do an interview</p>
<p>and if it's not approved,</p>
<p>it goes back to the job applicants</p>
<p>to answer more questions.</p>
<p>Right.</p>
<p>So here's like the first generation</p>
<p>of this question.</p>
<p>How do we hire</p>
<p>people? Well, it's like this.</p>
<p>Okay, now</p>
<p>how do we make this more nuanced,</p>
<p>more articulate?</p>
<p>Well, maybe the interview process has,</p>
<p>you know, like a split, and it's and,</p>
<p>you know, this interview is actually like</p>
<p>a technical interview.</p>
<p>And then there's like a management</p>
<p>interview, and each one of those</p>
<p>has an opportunity to be approved.</p>
<p>And then if it is approved, we go on.</p>
<p>And if it's not approved, we progress</p>
<p>and we push it.</p>
<p>And I like what you said here.</p>
<p>You start with the very top level. Yeah.</p>
<p>And say what are the major steps</p>
<p>into hiring person.</p>
<p>That's right.</p>
<p>Right.</p>
<p>And start there and then you can start</p>
<p>getting down into more detail</p>
<p>after you do that.</p>
<p>And a tool like this lets</p>
<p>you do this pretty quick, it looks like.</p>
<p>That's right.</p>
<p>So you start sort of articulating</p>
<p>what this is and this is not new</p>
<p>to anyone like you and me,</p>
<p>any any architect, any business analyst.</p>
<p>What's interesting about this</p>
<p>is that when you draw these diagrams,</p>
<p>it actually</p>
<p>behind the scenes is generated X amount</p>
<p>and this example is runtime</p>
<p>interpretable by BPM engines.</p>
<p>So what that means is that as I'm drawing</p>
<p>this diagram,</p>
<p>this can actually become</p>
<p>an executable process</p>
<p>right?</p>
<p>So as I'm writing this down, I'm saying,</p>
<p>oh, wow, this is a special kind of task.</p>
<p>It's a human task.</p>
<p>So you can see it's</p>
<p>got a human component here.</p>
<p>And, you know, maybe this one is as well.</p>
<p>And then when we do a review, applicants,</p>
<p>maybe now we start to say,</p>
<p>well, you know, we review the applicant</p>
<p>and maybe we have an h.r.</p>
<p>Person that does the review,</p>
<p>but they talk</p>
<p>to, you know, like a background check</p>
<p>system, right?</p>
<p>So check for job history, right?</p>
<p>Or a criminal record.</p>
<p>Right? Right. Yeah.</p>
<p>So that's a that's a great one.</p>
<p>So you would say and that's part</p>
<p>of the natural evolution of these things,</p>
<p>you would say, well, yeah, let's</p>
<p>check for job history and also let's check</p>
<p>for like criminal record, right?</p>
<p>So so far you haven't taken</p>
<p>even if this is automated,</p>
<p>you still haven't taken human</p>
<p>out of the loop yet, which is good.</p>
<p>Right? Right.</p>
<p>So this is this is augmenting the work</p>
<p>that a human is doing is what I'm seeing.</p>
<p>Right.</p>
<p>But even as I'm doing this,</p>
<p>what's interesting is you could say, boy,</p>
<p>you know, the time of people is expensive</p>
<p>and the time of machines is cheap.</p>
<p>Why don't we do this</p>
<p>criminal background check first, right?</p>
<p>And then if that passes,</p>
<p>then we bring it to the person and review.</p>
<p>Because if you don't pass the criminal</p>
<p>background check, maybe we don't let you.</p>
<p>You didn't get time from our guy, right?</p>
<p>Right.</p>
<p>So what you're really doing here is</p>
<p>you are using this mechanism</p>
<p>to describe your problem.</p>
<p>And in the definite,</p>
<p>like most things in life,</p>
<p>when you start thinking about it out</p>
<p>loud, you end up discovering solutions,</p>
<p>right?</p>
<p>Yeah.</p>
<p>And that's where things start</p>
<p>to get kind of interesting.</p>
<p>You're like, okay,</p>
<p>well now I understand that</p>
<p>I'm probably going to need an integration</p>
<p>with, you know, some back</p>
<p>end system that's</p>
<p>going to check for their job history</p>
<p>and check for their criminal history.</p>
<p>So you as, say, the business</p>
<p>analyst or the, you know,</p>
<p>the enterprise architect will say,</p>
<p>you know, call up one of your solution</p>
<p>architect friends and you'll say, hey,</p>
<p>how long would it take</p>
<p>us to figure this out?</p>
<p>You know, finding a system</p>
<p>that we can afford that can do this</p>
<p>sort of background check right?</p>
<p>So I'm starting to hack</p>
<p>this problem together</p>
<p>and and I get a little obsessive</p>
<p>with my lines crossing.</p>
<p>So I'm trying to make sure</p>
<p>that doesn't happen.</p>
<p>This is almost like a fidget</p>
<p>toy for me at this point,</p>
<p>but you can see how I am looking</p>
<p>for opportunities to do automation, right?</p>
<p>So here I am.</p>
<p>And I can easily see this in this diagram,</p>
<p>you know, using a BPM tool like this,</p>
<p>it will, it will</p>
<p>screen, hey, this is an automated check</p>
<p>that I could do.</p>
<p>There's a service</p>
<p>that lets you do this sort of thing.</p>
<p>Exactly.</p>
<p>And this is actually the other part of it</p>
<p>that's really powerful for, again,</p>
<p>people like you and I,</p>
<p>because we need to be subservient</p>
<p>to the needs of the business.</p>
<p>So the first thing that I'll do with</p>
<p>this is I will run this by my semi</p>
<p>and my subject matter expert and I'll say,</p>
<p>Hey, am I hearing this right?</p>
<p>Is this what we do?</p>
<p>And you know, he'll say, Well, you know,</p>
<p>it's kind of what we do,</p>
<p>but it turns out that we don't want</p>
<p>to do these things in parallel</p>
<p>because, say, a criminal background</p>
<p>check is really expensive,</p>
<p>but a job history search is really cheap.</p>
<p>So what we really want to do is we want to</p>
<p>do these maybe sequentially, right?</p>
<p>So we do the first one and if it passes,</p>
<p>then we do the second one.</p>
<p>And I'm not saying</p>
<p>that's necessarily the case, but what I.</p>
<p>Say, it's easy</p>
<p>for you to make that change.</p>
<p>That's right.</p>
<p>And in making that change,</p>
<p>I am building consensus.</p>
<p>I am building rapport.</p>
<p>I am building a true story</p>
<p>about what's happening.</p>
<p>Right. Like again,</p>
<p>like the scientific process.</p>
<p>It becomes progressively more true</p>
<p>the more the you experiment with it.</p>
<p>Yeah.</p>
<p>So now I start to tell this story</p>
<p>and as I'm telling this story,</p>
<p>like, okay, well this, you know,</p>
<p>this makes a little bit of sense</p>
<p>so I can come in here and, you know,</p>
<p>I can put like</p>
<p>logic into this, like this</p>
<p>and say for the sake of argument</p>
<p>that I want to build this and deploy it</p>
<p>so I can actually take this thing</p>
<p>and say, well, you know, here's a process</p>
<p>and here's like another one.</p>
<p>And literally, within a matter of minutes,</p>
<p>I can have this deployed and working.</p>
<p>So we can see what happens when you go</p>
<p>one way or you go the other way.</p>
<p>So you're telling you with</p>
<p>if I use a modeling tool</p>
<p>and it's not a drawing tool,</p>
<p>I want to make sure people understand</p>
<p>that.</p>
<p>That's right.</p>
<p>This is a modeling tool.</p>
<p>So it does let you draw pretty pictures,</p>
<p>but it also simulates on the back end.</p>
<p>So I can actually run this workflow</p>
<p>or this process and see</p>
<p>all of the different decision points</p>
<p>and where they lead to.</p>
<p>So I can check my.</p>
<p>That's exactly. Right. My model.</p>
<p>That's exactly right.</p>
<p>And this is where this becomes</p>
<p>really sort of powerful</p>
<p>because I can build this.</p>
<p>I think I screwed up</p>
<p>some of my logic here,</p>
<p>but I can build this, I can deploy it,</p>
<p>I can see it,</p>
<p>execute.</p>
<p>And it's actually what it's actually doing</p>
<p>is it's yelling at me and it's saying,</p>
<p>hey, I can't actually deploy this</p>
<p>because you didn't do it.</p>
<p>The right way.</p>
<p>And what?</p>
<p>It's yelling at me, right?</p>
<p>So yeah, it's helping you, right?</p>
<p>It's yeah, it's actually catching me.</p>
<p>So it's saying, hey,</p>
<p>you told me you were going to do</p>
<p>some kind of integration here,</p>
<p>but you didn't.</p>
<p>So I'm not going to let you</p>
<p>deploy this, right?</p>
<p>So now I can build this.</p>
<p>And that was a successful deployment.</p>
<p>That's cool.</p>
<p>Max To finish listening to my interview</p>
<p>with Max Young.</p>
<p>On Business Process Automation,</p>
<p>check out our next episode.</p>
<p>Thank you for listening</p>
<p>to Embracing Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcasting site or YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>and embracingdigital.org until next time.</p>
<p>Go out and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
