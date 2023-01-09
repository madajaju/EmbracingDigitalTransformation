---
layout: posts
title: Automating Business Process Management
number: 114
permalink: EDT114
has_children: false
parent: Episodes
nav_order: 114
tags:
     - EDT114
    - EmbracingDigital
    - Business Process Management
    - CapitalBPM
    - BPM
    - Automation
    - Camunda
date: 
guests:
    - Darren W Pulsipher
    - Max Young
img: TBD
summary: Darren Pulsipher, Chief Solutions Architect, Public Sector, Intel, and Max Young, CEO of Capital BPM, discuss operationalizing business process management with modeling programs.
---

{% include soundcloud.html id="edt114" title="#114 Automating Business Process Management" %}

{% include youtube.html id="ysjoqIqvOGw" %}

---

BMP modeling reminds Darren of when he took drafting in high school, and AutoCAD's introduction of computer-aided drafting systems changed the game.  Before, they would have pages and pages of complex systems and diagrams so people could build, but they couldn’t test the model to ensure it was right. Using computer modeling, they could run simulations to ensure there weren’t problems such as electrical and plumbing running through the same hole.

This is analogous to architects using PowerPoint to show business processes instead of using a modeling tool that can find conflicts and issues in what you thought the business process was.

Using a business modeling tool also solves a practical problem by eliminating the wasted time of getting all the interested parties together for meetings that may need to be more productive. Instead, you can put a deployed model into the hands of the business customer and work through the steps with them.

After articulating and modeling the processes, you can choose integration points that might attach to restful interfaces that get information and pump it back in. This is how business processes can integrate with microservices in the cloud. In the example of the hiring process, these points might be where you need an API to invoke checks for job history or criminal record. The inputs will be items such as social security numbers and dates of birth, and the outputs will be a Boolean - does the information match or not? This is where. You can start having that iterative conversation.

![bpm image](./bpm.png)

There are quite a few manual steps in this process, and you can choose which ones to automate. For example, if you decide that an interview didn’t go well, you can default to HR. After you deploy that new process, you can go back and look at the previous version if you want to, so you have two concurrent versions of the software working and deployed at the prototype.

The Camunda modeler is a native modeler, but Capital BPM has built its own applications that help streamline some of the work and support different user roles.

This system is different from RPA because instead of capturing what a user does with keystrokes, a business analyst looks at the processes and steps across multiple departments. The analyst is looking top-down at the whole process. An RPA can be plugged into some steps for efficiency. A simple example is if a job applicant passes the job history check and criminal record check, it can go to a senior HR person; if not, it’s rejected. Choosing specific steps, or sets of steps, to automate is an iterative approach that has been used successfully in software development for some time.

RPAs can be game changers, but they are tactical and short-term. While these short-term gains may be profitable, you need to look at the entire business process to find optimization and steps you can eliminate. The story of the woman who always cut the roast before baking it because that’s how her mother did it is analogous to some company processes. The woman finally asked her mother why she cut the roast, and her mother replied, “So it would fit in my pan.” Many company processes are only there because they’ve always been done that way, and no one has thought to question why.

Testing, simulation, moving things around, and running processes repeatedly in the modeler, in other words, empirically testing, can help eliminate this process bloat and add significant value. Visualization and experimentation are vital parts of the whole process.

Max points out that there is fidelity between the diagram and the actual execution. Developers often draw diagrams as a starting point. Still, the charts disappear as development moves through the different parties, so what the business thinks is happening and what is happening are different. The diagram and reality are separate.  In this type of modeling, the picture is always an accurate representation of what is happening. In addition, it’s easy to see and make changes for improvement. 


<details>
<summary> Podcast Transcript </summary>

<p>﻿1</p>
<p>Hello, this is Darren</p>
<p>Pulsipher, chief solution</p>
<p>architect of public sector at Intel.</p>
<p>And welcome to Embracing</p>
<p>Digital Transformation,</p>
<p>where we investigate effective change,</p>
<p>leveraging people, process and technology.</p>
<p>On today's episode, Optimizing.</p>
<p>Processes with Business Process Modeling.</p>
<p>Part two of my interview with Max Young,</p>
<p>CEO of Capital BPM.</p>
<p>Just so you know what this reminds me of</p>
<p>when I was in was I was in high school,</p>
<p>I took drafting.</p>
<p>Yeah.</p>
<p>So I was in three years</p>
<p>of drafting in high school</p>
<p>and my junior year</p>
<p>they introduced CAD systems</p>
<p>for the first time,</p>
<p>computer aided drafting systems, AutoCAD</p>
<p>and it was a huge shift</p>
<p>from drawing out</p>
<p>because we had the big drafting boards,</p>
<p>the whole thing,</p>
<p>and you would have to draw pages and pages</p>
<p>for complex systems, pages of diagrams</p>
<p>so people could build them.</p>
<p>But you couldn't really test how could you</p>
<p>test that your model was right.</p>
<p>You, you did a lot of work</p>
<p>and there was a lot of back and forth</p>
<p>between the drafters, the architects</p>
<p>and the guys that had to build the things</p>
<p>right.</p>
<p>All of a sudden, computer aided drafting</p>
<p>came along and they really used a model</p>
<p>instead of.</p>
<p>That.</p>
<p>By using a model technique,</p>
<p>now we could actually run simulations</p>
<p>of those models</p>
<p>and see if there were any issues like,</p>
<p>Hey, did I have electrical and plumbing</p>
<p>going through the same holes in a wall?</p>
<p>Well, that's a problem.</p>
<p>You don't want electrical</p>
<p>and plumbing together, right.</p>
<p>And small things like that.</p>
<p>So what you're saying with this,</p>
<p>this is very analogous</p>
<p>to a lot of architects</p>
<p>are using PowerPoint presentations</p>
<p>to architect</p>
<p>or to show these business processes.</p>
<p>But if you use a modeling tool, it</p>
<p>ups the game so it it can find conflicts.</p>
<p>It can find issues in what you captured</p>
<p>or what you thought the business.</p>
<p>Process was not.</p>
<p>All right. So what</p>
<p>you can actually see here, for example,</p>
<p>that this thing has been deployed.</p>
<p>You know, it's at this particular step.</p>
<p>I can submit it, I can have logic,</p>
<p>and it allows it to go one way or another.</p>
<p>And what I like about this</p>
<p>is that it solves</p>
<p>a really important problem for me.</p>
<p>And it's, again, a deeply pragmatic</p>
<p>problem, you know as well as I do.</p>
<p>What happens</p>
<p>when you want to start a new project?</p>
<p>You sit down, you get, you</p>
<p>know, ten, 20 people into a room.</p>
<p>You guys shoot the breeze for about ten</p>
<p>or 15 minutes about the kids in the snow.</p>
<p>You know, you talk about stuff</p>
<p>somebody might draw on a whiteboard,</p>
<p>somebody takes notes, takes pictures.</p>
<p>There is an analyst in the room.</p>
<p>They go away and, you know,</p>
<p>if you're lucky, you know,</p>
<p>by the end of the week, they've typed out</p>
<p>the notes as senator everyone.</p>
<p>And then after you're done with that,</p>
<p>you find a time when everybody else</p>
<p>can get in the room again and again.</p>
<p>If you're lucky, somewhere in the next 2</p>
<p>to 4 weeks, you have like a second meeting</p>
<p>about this, and you spend most of that</p>
<p>meeting reviewing what you did previously.</p>
<p>And then you might be able</p>
<p>to move the ball forward in nature to.</p>
<p>Right.</p>
<p>I don't think I'm spelling</p>
<p>any corporate secrets.</p>
<p>That's a no, no, no.</p>
<p>This is no, this is corporate. Right.</p>
<p>By here's what I just did.</p>
<p>I just went out and I built</p>
<p>and I deployed this.</p>
<p>I can put it into the hands</p>
<p>of my customer, my business customers.</p>
<p>They can actually come in here</p>
<p>and they can say, well,</p>
<p>I'm going to actually drive this task.</p>
<p>Right? I'm I'm going to actually.</p>
<p>I want to step through it.</p>
<p>So you have. To push this. Wow.</p>
<p>Now I come over here and we see that</p>
<p>the diagram is at this step,</p>
<p>like it</p>
<p>really went through these processes.</p>
<p>And if I had told you to do like a check</p>
<p>for a restful</p>
<p>call here or here,</p>
<p>you would have done those things.</p>
<p>So that's that's the next</p>
<p>that's kind of the third part here is</p>
<p>I can take it from modeling</p>
<p>to integration.</p>
<p>That's it.</p>
<p>So if I, if I, if I look at the</p>
<p>the steps here, we had to articulate.</p>
<p>Right, or capture the business process</p>
<p>and articulate it, model it.</p>
<p>And now I can choose</p>
<p>integration points in these steps.</p>
<p>I can say, hey, at this step</p>
<p>I'm attaching to a rest will interface</p>
<p>that's out there that gets</p>
<p>that information for me and pumps back in.</p>
<p>So this is how I can integrate</p>
<p>business process</p>
<p>with microservices or services</p>
<p>that are out there in the cloud, whatever.</p>
<p>Exactly.</p>
<p>So, so for example, you could say,</p>
<p>hey, if we're going to do this project,</p>
<p>the orange spots are the places</p>
<p>where we're going to need,</p>
<p>you know, someone to come in and create</p>
<p>an API for us that we can invoke</p>
<p>the checks for job history</p>
<p>and checks for criminal review</p>
<p>and what are going to be</p>
<p>the inputs and outputs of this?</p>
<p>Oh, well, you know, the inputs are going</p>
<p>to be the Social Security number</p>
<p>of the date of birth and the state</p>
<p>and and the outputs going to be a boolean.</p>
<p>You know, did you know</p>
<p>does the information match or does it</p>
<p>not match? Right.</p>
<p>So you can start having</p>
<p>that iterative conversation</p>
<p>and that becomes.</p>
<p>Yeah, so so this,</p>
<p>yeah, this, this sounds a lot</p>
<p>like what we do in software development.</p>
<p>It is.</p>
<p>Right.</p>
<p>Which has been kind of missing</p>
<p>in the business process or systems</p>
<p>analyst space where this is mostly sits.</p>
<p>Right.</p>
<p>This mostly says, oh,</p>
<p>I've got a business analyst that's come</p>
<p>in, help me do process improvement stuff.</p>
<p>But they're they're not modeling.</p>
<p>They're using, you know, Visio.</p>
<p>Visio is not a model. Right.</p>
<p>This is a drawing tool.</p>
<p>So I really like this.</p>
<p>And then you can drill down</p>
<p>on, hey, here's some steps.</p>
<p>You could deploy this as a process today.</p>
<p>No, I just did. Right.</p>
<p>So this diagram,</p>
<p>this is a deployed process.</p>
<p>Okay. So sweet.</p>
<p>There's a lot of manual steps</p>
<p>in this process.</p>
<p>No big deal. Yeah.</p>
<p>And that's why you actually.</p>
<p>Now I can choose which ones to automate.</p>
<p>I see what you're saying. Right.</p>
<p>And I can actually, like,</p>
<p>do this really fast.</p>
<p>Like, let's say, for the sake of argument,</p>
<p>I want to put</p>
<p>a decision on this interview</p>
<p>staff and go, hey,</p>
<p>if the interview didn't go well,</p>
<p>maybe we push back to h.r.</p>
<p>And we say, you know,</p>
<p>we push it back to the candidate</p>
<p>who said we have questions for you right?</p>
<p>So i can actually come</p>
<p>in, i can evolve this, i can say, hey,</p>
<p>you know, this is going to be</p>
<p>my default path here.</p>
<p>This is going to be,</p>
<p>you know, an expression.</p>
<p>And that would be you know, I've</p>
<p>yeah, we've got to</p>
<p>to put a lot of work in here,</p>
<p>but we could be examining like a checkbox</p>
<p>or whatever to indicate</p>
<p>whether we want</p>
<p>to move forward or not. Right.</p>
<p>And then we build this.</p>
<p>We say that we deploy it.</p>
<p>And now the thing that's actually deployed</p>
<p>is this newer process</p>
<p>with the you know, with a gateway here.</p>
<p>And if I wanted to, I could go back</p>
<p>and look at the previous version.</p>
<p>So I've got two concurrent versions</p>
<p>of the software</p>
<p>working and deployed right</p>
<p>now, right at prototype.</p>
<p>That's bad and good.</p>
<p>And going at the same time. Right.</p>
<p>So you can actually see in here.</p>
<p>Yeah, like the data</p>
<p>that's going through the system.</p>
<p>So all right.</p>
<p>So I like, I like where we're headed here</p>
<p>if we so we've got our three selves.</p>
<p>What's the next step after</p>
<p>I've integrated.</p>
<p>Right. Because you show me some of that,</p>
<p>some of the stuff</p>
<p>before I can actually run.</p>
<p>You guys have a tool lint</p>
<p>for business process you.</p>
<p>So my thing is without being too braggy</p>
<p>of our own stuff, we've actually built,</p>
<p>you know, a couple of applications</p>
<p>that make this a, a more,</p>
<p>a more</p>
<p>easy thing to do.</p>
<p>So what I was showing</p>
<p>was the native okay on the modeler, but</p>
<p>we've built our own system</p>
<p>where you can kind of go on.</p>
<p>To help streamline.</p>
<p>Is it is it targeted primarily for is</p>
<p>it targeted</p>
<p>primarily for business analyst?</p>
<p>It is men.</p>
<p>That are doing capture</p>
<p>or is it for the developer</p>
<p>that's writing rest interfaces</p>
<p>and things like that?</p>
<p>Who what?</p>
<p>So it's a</p>
<p>it has support, different roles, right?</p>
<p>So initially you would have a business</p>
<p>analyst or an SMB come in and sort of</p>
<p>define out, well, you know, here's</p>
<p>the data model that we're working with.</p>
<p>Here is the workflow that we have</p>
<p>and the different rules that are involved.</p>
<p>You can actually have them come in</p>
<p>as in this case</p>
<p>and go, Well, here's</p>
<p>a restful API that we're going to call.</p>
<p>Let's</p>
<p>say this gets a list of all the customers.</p>
<p>And then,</p>
<p>you know, we're going to have like a form</p>
<p>and the form is going to say,</p>
<p>display the customer</p>
<p>or display all the different users and</p>
<p>and we have like a one way, okay.</p>
<p>So you actually can take it</p>
<p>to the next level, what I would call</p>
<p>the next level below test</p>
<p>that model where now</p>
<p>you're actually creating the application.</p>
<p>Yeah, that's right.</p>
<p>On top of that model.</p>
<p>On top of that business process</p>
<p>so that I can watch it go through,</p>
<p>I can drive it through, I can ask</p>
<p>users for information, all that.</p>
<p>Yeah.</p>
<p>So for example, I could create a table</p>
<p>and I can say this table</p>
<p>when it loads, you know, it's</p>
<p>going to make a restful call</p>
<p>and the restful call</p>
<p>is going to be to say,</p>
<p>I don't know, load</p>
<p>all the customer is right.</p>
<p>So right.</p>
<p>So I want to kind</p>
<p>of tease out a little bit on</p>
<p>this.</p>
<p>This is different than RPA. Yeah. Yeah.</p>
<p>Because RPA is I'm capturing</p>
<p>what a user does with keystrokes, right.</p>
<p>It's doing that.</p>
<p>You guys are saying</p>
<p>I have a business analyst that comes in,</p>
<p>really looks at the process and the steps.</p>
<p>Right.</p>
<p>Across multiple depart in in.</p>
<p>My opinion and.</p>
<p>Then. RPA.</p>
<p>Yeah. Would be a step in here. Right.</p>
<p>So you might have like.</p>
<p>Yeah I can see.</p>
<p>How we you know,</p>
<p>when we review an application</p>
<p>and the first thing we do is</p>
<p>we look at the boxes</p>
<p>that come in from criminal background</p>
<p>check and job history check.</p>
<p>And if that's true, then, you know,</p>
<p>we pass it on to a senior h.r.</p>
<p>Person, otherwise we reject it, right?</p>
<p>So at that point, I might plug in</p>
<p>like an RPA step and here I go.</p>
<p>This is just going to invoke RPA, right?</p>
<p>Gotcha.</p>
<p>Okay, so that's that's the main</p>
<p>that's the main difference.</p>
<p>You're looking top down the whole process.</p>
<p>Yeah, that's exactly right.</p>
<p>Across departments and an RPA is</p>
<p>really how a individual</p>
<p>might be doing a step</p>
<p>in that process or even a couple steps</p>
<p>in that process, whatever the case.</p>
<p>Absolutely right.</p>
<p>You know, RPA,</p>
<p>you can get a really fast win</p>
<p>like, you know, creating a true</p>
<p>integration that talks to the back end and</p>
<p>and you put the security certificates</p>
<p>in place and all the right environments</p>
<p>that can take months.</p>
<p>Right.</p>
<p>Just from the bureaucratic architecture.</p>
<p>But you put an RPA bot in there</p>
<p>that just opens the email,</p>
<p>it takes the two fields out and puts them</p>
<p>into the system and pushes the button</p>
<p>and you just immediately</p>
<p>solve the problem.</p>
<p>And in a couple of days or</p>
<p>a couple of weeks, that might have taken</p>
<p>a really long time</p>
<p>to do in a quote unquote correct way.</p>
<p>And you always have the latitude</p>
<p>to come in and change this</p>
<p>and make it a true</p>
<p>integration down the road.</p>
<p>Right.</p>
<p>And I like that approach</p>
<p>because there's there's always a point</p>
<p>when you're designing a system like this</p>
<p>where you have to make a decision on</p>
<p>how how</p>
<p>what is my return on the investment</p>
<p>I'm going to spend right now</p>
<p>by automating something</p>
<p>and this I love this</p>
<p>because this gives you that opportunity</p>
<p>to say, well,</p>
<p>I'm going to automate this step.</p>
<p>And that's</p>
<p>how everything else is going to be manual.</p>
<p>But this one step I'm going to automate</p>
<p>or the set of steps I'm going to automate</p>
<p>and I'm good. I'm in good shape.</p>
<p>So I really like this iterative</p>
<p>approach that we've been doing in software</p>
<p>development for some time.</p>
<p>And it sounds like</p>
<p>you're doing a great job at bringing</p>
<p>the things that we learned in software</p>
<p>development over the last 30 years</p>
<p>into business process</p>
<p>management and business process.</p>
<p>So, you know, I think I saw a little bit</p>
<p>about some of the things</p>
<p>that you had built there, and I think you</p>
<p>had sort of done the same sort of thing.</p>
<p>Like you have a system</p>
<p>where you can visualize</p>
<p>how things interact</p>
<p>and actually drive that.</p>
<p>And I think that's just what happens</p>
<p>when you take smart people</p>
<p>that have to solve big problems.</p>
<p>We recognize the value of clarity.</p>
<p>Yeah, I like what you said there.</p>
<p>The visualization is key,</p>
<p>right?</p>
<p>Because that's how you're communicating.</p>
<p>What's going on know</p>
<p>so and that gives you clarity.</p>
<p>I really like how you brought that out.</p>
<p>So that visualization really helps</p>
<p>other people understand what's going.</p>
<p>Yeah, we,</p>
<p>you know, going back to like the,</p>
<p>the martial arts metaphor and some ways</p>
<p>I think of the injection of RPA</p>
<p>as sort of fighting dirty like,</p>
<p>you know, you've got to do an integration.</p>
<p>Oh, all all my RPA buddies out there,</p>
<p>forgive me.</p>
<p>Oh, I love it because I.</p>
<p>Know it. Is.</p>
<p>Yeah, it does work like that.</p>
<p>You get quick wins. Absolutely.</p>
<p>And I think that that's</p>
<p>the highest compliment.</p>
<p>It's pragmatic.</p>
<p>You can solve a problem today, say that</p>
<p>if you took another path, you wouldn't</p>
<p>be done talking about for two months.</p>
<p>I love that.</p>
<p>It is</p>
<p>without putting too fine a point on</p>
<p>it is a game changer,</p>
<p>but it is, in my opinion, a tactical.</p>
<p>But it's a short term gain.</p>
<p>But it's enough, right?</p>
<p>You you could in a corporation</p>
<p>the size of intel</p>
<p>or some of the ones that you know</p>
<p>that we work with</p>
<p>short term gain by three months,</p>
<p>millions of dollars.</p>
<p>But but you don't you don't want to rest</p>
<p>your laurels on that short term gain.</p>
<p>Right. That's the problem. Right.</p>
<p>Right.</p>
<p>You need to see how that little process</p>
<p>fits into this bigger process.</p>
<p>And you need to look at your full business</p>
<p>processes</p>
<p>to to find optimizations,</p>
<p>to find steps that I can get rid of.</p>
<p>I mean, we've had this</p>
<p>there's this old story.</p>
<p>It's a funny story where this lady</p>
<p>is teaching her daughter</p>
<p>how to cook a Thanksgiving roast.</p>
<p>And she goes and she cuts the</p>
<p>roast in half and</p>
<p>and puts it in in the pan and cooks it.</p>
<p>And her daughter says, well,</p>
<p>why do you cut the roast in half?</p>
<p>And she goes, Well, because my mom</p>
<p>taught me to cut the roast in half.</p>
<p>So they asked Grandma, right, hey, why?</p>
<p>Why are you cutting roast?</p>
<p>You know, why did you do that?</p>
<p>And says,</p>
<p>because the pan I used wasn't big enough.</p>
<p>But this process</p>
<p>of cutting the roast</p>
<p>passed down from generation to generation.</p>
<p>We have stuff like that in our companies</p>
<p>all over the place.</p>
<p>Why are you doing it that way?</p>
<p>Well,</p>
<p>because it's always been done that way</p>
<p>without anyone sitting</p>
<p>and really analyzing why?</p>
<p>What is the purpose of doing it?</p>
<p>So we end up with process bloat</p>
<p>all over the place.</p>
<p>Yeah, yeah.</p>
<p>And and bureaucracies that fit in.</p>
<p>And I think that's</p>
<p>where our training as engineers comes in</p>
<p>because we have to be clear eyed</p>
<p>and look at why are we doing it this way.</p>
<p>What is the benefits doesn't have one</p>
<p>that I'm that's a variable</p>
<p>that I failed to capture in this equation</p>
<p>right and</p>
<p>and testing simulation</p>
<p>running things again and again</p>
<p>like one of the things that I love</p>
<p>to do as,</p>
<p>as a stress relieving mechanism is once</p>
<p>I deploy a process,</p>
<p>I will pull it up</p>
<p>and I'll start moving activities around.</p>
<p>I'll do this this thing before that thing,</p>
<p>and I'll see if I can do</p>
<p>parallel processing.</p>
<p>I'm, I'm playing with it.</p>
<p>I'm empirically testing it</p>
<p>and that adds a value to it.</p>
<p>That does add a lot of value. Absolutely.</p>
<p>And it's something</p>
<p>that we need to be able to do more of.</p>
<p>And that is I don't know what</p>
<p>you would call that permutations</p>
<p>just test the model by pulling it apart</p>
<p>a little bit or the process</p>
<p>by rearranging things.</p>
<p>I call it experimentation again.</p>
<p>I like.</p>
<p>There you go.</p>
<p>That's the word</p>
<p>I was looking for experimentation.</p>
<p>We did something like this.</p>
<p>I was on a big project</p>
<p>at a former company, Cadence</p>
<p>Design Systems, where we were doing</p>
<p>a running test of our software</p>
<p>every night and our software runs</p>
<p>would take 24 hours</p>
<p>to test our software and we had to run it.</p>
<p>This is back in the good old days</p>
<p>where you had to run on HP X</p>
<p>Air x Solaris, all the flavors of Linux.</p>
<p>So we had these massive, massive grids</p>
<p>of compute, all compute resources</p>
<p>that we ran these tests on</p>
<p>and we would run them one test on CPU,</p>
<p>we would run front ways and the other one</p>
<p>on air X would run backwards.</p>
<p>So halfway through the night</p>
<p>we would know like 12 hours</p>
<p>and we would know how the test</p>
<p>generally did of crazy that we did that.</p>
<p>So we started looking at optimizing,</p>
<p>how could we make this faster?</p>
<p>And we took the same approach.</p>
<p>What if I pulled things apart</p>
<p>a little bit,</p>
<p>move things around, group tests together?</p>
<p>If they failed, they failed early</p>
<p>and I didn't run more tests.</p>
<p>We were able to get that cycle</p>
<p>talent to about four or five.</p>
<p>So all of a sudden I</p>
<p>could run tests in the middle of the day,</p>
<p>I could run them at night, I could run.</p>
<p>So this whole idea of experimentation</p>
<p>and the only reason we were able to do</p>
<p>that is because we could visualize</p>
<p>and we could see the steps</p>
<p>and how they interrelated.</p>
<p>And I love how this all fits together,</p>
<p>right?</p>
<p>Yeah.</p>
<p>And and this should really empower</p>
<p>business analyst and process engineers</p>
<p>how to really do this right</p>
<p>instead of I'm just going to copy</p>
<p>exactly what we've always done</p>
<p>in the same order we've always done that.</p>
<p>That's not the real benefit</p>
<p>from absolutely right.</p>
<p>Absolutely right.</p>
<p>You literally couldn't have said that</p>
<p>any better.</p>
<p>I think that the</p>
<p>the thing that I really like about this</p>
<p>approach is what and I'm not saying</p>
<p>it's the best approach in the world.</p>
<p>I know that there are software</p>
<p>engineers just as good</p>
<p>or better than me</p>
<p>who take a completely different approach.</p>
<p>And I am sure they're.</p>
<p>Very they're just not as enlightened</p>
<p>as we are.</p>
<p>But I'm sure there are valid</p>
<p>counterarguments.</p>
<p>But what I really like about this</p>
<p>is that it feeds the business.</p>
<p>And here's what I mean by that.</p>
<p>There is fidelity between the diagram</p>
<p>and the actual execution.</p>
<p>A lot of times</p>
<p>in the business that you and I are,</p>
<p>and we'll draw the diagrams</p>
<p>and that will be the starting point.</p>
<p>But and then from there.</p>
<p>On, right, people,</p>
<p>the developers make a compromise,</p>
<p>they do something or another</p>
<p>and it doesn't reflect back.</p>
<p>So what the business thinks is happening</p>
<p>and what it is really doing.</p>
<p>And what's.</p>
<p>Happened, they've separated</p>
<p>where with this the picture is the code</p>
<p>is always an accurate representation</p>
<p>of what you're really doing.</p>
<p>And the business can come and look at you</p>
<p>and go, No, dummy, you're doing it wrong.</p>
<p>Do step two before you do</p>
<p>step one, it'll save you a lot of trouble.</p>
<p>You know, we we had</p>
<p>we had a system where we were</p>
<p>checking to see</p>
<p>what country somebody was in.</p>
<p>And then based on that, we were giving</p>
<p>you were looking at what rewards</p>
<p>they were entitled to</p>
<p>and then giving them discounts.</p>
<p>We know we did this for a long time.</p>
<p>We model that</p>
<p>because the way I was showing you</p>
<p>as a has a rule engine embedded into it.</p>
<p>And then one day</p>
<p>we showed it to the business</p>
<p>and they're like, Well, that's stupid.</p>
<p>is in the United States.</p>
<p>Why don't you check for that first?</p>
<p>Why is it down at the bottom</p>
<p>after all these other kind of bottom?</p>
<p>Yeah.</p>
<p>Right.</p>
<p>Drastic improvements</p>
<p>because.</p>
<p>It's so I love</p>
<p>I love that the model it's not a diagram.</p>
<p>Right. That's what we want to get across.</p>
<p>It's a model and it drives</p>
<p>the simulation,</p>
<p>it drives the application itself.</p>
<p>It represents</p>
<p>so I love how that's all tied together.</p>
<p>Max, this has been wonderful.</p>
<p>Yeah, Wichita. Wichita, 4 hours.</p>
<p>I already know.</p>
<p>That's about eight.</p>
<p>Our listeners will get tired.</p>
<p>So Max,</p>
<p>thank you so much for coming on the show.</p>
<p>We most certainly will set it</p>
<p>some time again.</p>
<p>I really enjoyed this time</p>
<p>and thanks for having me on.</p>
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
