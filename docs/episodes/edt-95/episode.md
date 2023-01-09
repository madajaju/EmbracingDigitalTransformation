---
layout: posts
title: Put the Title Right Here
number: 95
permalink: EDT95
has_children: false
parent: Episodes
nav_order: 95
tags:
     - EDT111
    - EmbracingDigital
date: 
guests:
    - Darren W Pulsipher
img: TBD
summary: Summary
---

{% include soundcloud.html id="edt95" title="#95 Put the Title Right Here" %}

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
<p>On today's</p>
<p>episode, Essential Requirements for Edge</p>
<p>the Cloud Service Architectures with Dr.</p>
<p>Anna Scott.</p>
<p>Anna welcome to the show.</p>
<p>Hey, thank you.</p>
<p>I was just going to say</p>
<p>I'm really excited to be here.</p>
<p>Thank you for giving me a chance</p>
<p>to come in and talk with</p>
<p>you about edge cloud.</p>
<p>So in if no one's heard Anna</p>
<p>speak before, which she has,</p>
<p>this is her third time guaranteed.</p>
<p>We just talked about that. Dr.</p>
<p>Scott is our chief edge architect</p>
<p>at Intel Public Sector and an incredible</p>
<p>background in industrial in the industrial</p>
<p>space, oil and gas and other things.</p>
<p>And Anna is is our go to</p>
<p>when it comes to edge architectures</p>
<p>so welcome again Anna to the show.</p>
<p>Thank you. So thank you so much, Dan.</p>
<p>It's really a pleasure.</p>
<p>So recently you headed up an effort</p>
<p>to write a white paper on edge,</p>
<p>the cloud service architectures</p>
<p>and tell tell the audience</p>
<p>a little bit about the experience.</p>
<p>Was it like herding herding cats? Right.</p>
<p>Yeah, it's really it's really interesting.</p>
<p>Like, obviously edge to cloud encompasses</p>
<p>a whole lot.</p>
<p>Right.</p>
<p>So we're in it's a beautiful match</p>
<p>for Intel because it hits</p>
<p>all of the high points of the technology</p>
<p>that we care about right now.</p>
<p>So you've got, you know,</p>
<p>artificial intelligence is critical.</p>
<p>You have edge is a major component.</p>
<p>Obviously,</p>
<p>you have cloud as a major component,</p>
<p>but then your network connectivity</p>
<p>is really, really important, too.</p>
<p>And so to really kind of tackle this paper</p>
<p>and just how Intel is approaching</p>
<p>cloud architectures,</p>
<p>you know, we got folks</p>
<p>from all of those different areas together</p>
<p>with some pretty impressive expertize</p>
<p>and really wanted to talk through</p>
<p>how do we just start saying, here's</p>
<p>a great edge architecture</p>
<p>with no discussion about how does that</p>
<p>then connect back into the cloud</p>
<p>and take advantage of that?</p>
<p>And, you know, again,</p>
<p>we have great cloud architectures as well.</p>
<p>So so this whole effort of how do you pull</p>
<p>everybody together was a lot of fun.</p>
<p>And also, you know, what's super true</p>
<p>is we all speak very different languages.</p>
<p>We have different taxonomies.</p>
<p>We say words</p>
<p>and they mean something to one group</p>
<p>and something</p>
<p>totally different to another group.</p>
<p>And so it's got it's</p>
<p>got some really interesting challenges</p>
<p>for us just to have the discussions</p>
<p>to really kind of pull</p>
<p>these architectures together.</p>
<p>We've had to ask people to</p>
<p>learn a whole lot of things, right?</p>
<p>Because you can't you can't talk about</p>
<p>how how you can really make a solid cloud</p>
<p>architecture without your cloud folks</p>
<p>knowing more about the edge and the edge.</p>
<p>Well.</p>
<p>To me, I thought that was the most</p>
<p>interesting thing</p>
<p>in being involved in in the discussion</p>
<p>is the OT guys and the IT guys.</p>
<p>I'm i t euro ti.</p>
<p>We were not speaking</p>
<p>the same at all, right?</p>
<p>When I would say something, you were like,</p>
<p>no, they're not.</p>
<p>Doesn't make sense in the space.</p>
<p>So I thought it was really interesting</p>
<p>because you're right,</p>
<p>we both learned a lot from each other</p>
<p>in, in addressing</p>
<p>these new architectures</p>
<p>that are spanning everything.</p>
<p>Yeah.</p>
<p>And then you like throw in network</p>
<p>and network.</p>
<p>Their language doesn't match</p>
<p>either of those, either of.</p>
<p>The network guys. I'm sorry</p>
<p>the network guys,</p>
<p>they can sit on the side network.</p>
<p>Come on. That's just plumbing, right.</p>
<p>Not for the.</p>
<p>It's just plumbing.</p>
<p>Not for this. No, not. So. Well, yeah.</p>
<p>And I know you know, Darren,</p>
<p>I mean, like one of the really cool</p>
<p>things about this was</p>
<p>what we what we really learned</p>
<p>with these discussions,</p>
<p>especially when you get out to the edge,</p>
<p>the communications is just hypercritical.</p>
<p>Like you're not going to design your edge</p>
<p>architecture without a really solid</p>
<p>knowledge of what your comms are,</p>
<p>because that's going to dictate</p>
<p>how much compute you need to be local,</p>
<p>how much you can really rely on the cloud,</p>
<p>how often you can rely on the cloud.</p>
<p>And since we're both in public sector,</p>
<p>we've got the added complexity of</p>
<p>of having use cases</p>
<p>that are really highly centered on</p>
<p>still needing to keep the functionality</p>
<p>when you've got the conditions right</p>
<p>or the delayed, disrupted</p>
<p>and intermittent communications.</p>
<p>So it becomes really, really important.</p>
<p>And that's where I have to say, I think so</p>
<p>many of the interesting conversations</p>
<p>and so many of the new</p>
<p>the new key points that are relevant</p>
<p>really came from is just comms</p>
<p>is no longer something that you can say</p>
<p>is going to be there and that it's</p>
<p>got the latencies that you need and</p>
<p>that it's got the bandwidth that you need.</p>
<p>You really have to rethink</p>
<p>these these architectures</p>
<p>in the cloud connectivity based on those.</p>
<p>So I thought that that's interesting.</p>
<p>So the first major difference</p>
<p>that we saw between a cloud</p>
<p>architected service infrastructure</p>
<p>and the edge was the comms part, right?</p>
<p>I think there's this huge assumption</p>
<p>and I know I make it, I made it.</p>
<p>I don't do it anymore</p>
<p>because you schooled me very well,</p>
<p>which is I'm not always connected.</p>
<p>All right.</p>
<p>Because a lot of the tools out there</p>
<p>assume connectivity.</p>
<p>And if you're not connected,</p>
<p>that means you're dead.</p>
<p>And I'm not going to deal with you</p>
<p>anymore.</p>
<p>Right. That's what it typically meant.</p>
<p>But that's not the case in edge, right?</p>
<p>Yeah, definitely not.</p>
<p>And it's it's also true.</p>
<p>I mean, I brought up the public sector</p>
<p>example because obviously for</p>
<p>for military applications,</p>
<p>that's that's really true.</p>
<p>But, you know,</p>
<p>one of the things</p>
<p>we were able to do with this</p>
<p>group is bring in a lot of experts</p>
<p>from other verticals.</p>
<p>So like Karen Perry really helped us</p>
<p>with the health care side of the world.</p>
<p>And turns out health care</p>
<p>totally has to assume</p>
<p>that you don't have good connectivity,</p>
<p>because if they want to do patient</p>
<p>edge cases</p>
<p>where like one of the ones</p>
<p>I know a little bit about that</p>
<p>that Karen had shared with me</p>
<p>is that if you</p>
<p>if you want to work in somebody's home</p>
<p>because they've got long, long term care,</p>
<p>you most people</p>
<p>are not necessarily</p>
<p>sophisticated users of technology,</p>
<p>especially if they're have a very serious,</p>
<p>serious health condition.</p>
<p>And so how do you really set something up</p>
<p>where you can do</p>
<p>continuous patient monitoring, do proper</p>
<p>alarming and alerting</p>
<p>and do all the things that you need to do</p>
<p>when, hey, that person's internet or their</p>
<p>WI fi could could go out.</p>
<p>So how do you how do you design around?</p>
<p>Well, you know,</p>
<p>you're dealing with people's lives, right?</p>
<p>So, yeah, it's not like,</p>
<p>oh, I couldn't stream</p>
<p>my Netflix video for,</p>
<p>you know, 30 minutes.</p>
<p>Now you're dealing with 15 minutes.</p>
<p>This is. Yeah, yeah.</p>
<p>And then it turns out</p>
<p>industrial has really similar</p>
<p>similar requirements as well.</p>
<p>You you can't be offline</p>
<p>because the control for certain</p>
<p>machinery, for certain processes</p>
<p>is just way too critical.</p>
<p>And so this whole idea of</p>
<p>how do you have this</p>
<p>very edge centric compute</p>
<p>that maintains all critical functionality</p>
<p>but then can have connectivity back</p>
<p>into the cloud and do that in</p>
<p>essentially an intermittent fashion?</p>
<p>Right.</p>
<p>So we can absolutely architect for that.</p>
<p>But that's something that there's</p>
<p>there's obviously been work</p>
<p>from the edge perspective,</p>
<p>but there's still a lot more</p>
<p>that can be done, especially if you want</p>
<p>a nice seamless set of operation of a</p>
<p>you do have cloud connectivity.</p>
<p>Now here's what you can do</p>
<p>and you've lost introduced.</p>
<p>You can</p>
<p>now what does it mean</p>
<p>when everything is restored</p>
<p>and what's your version of the truth?</p>
<p>Right,</p>
<p>because you're going to have a disconnect</p>
<p>between</p>
<p>what's been happening with your data.</p>
<p>And in some cases,</p>
<p>that can be very, very, very important.</p>
<p>And then when it got really cool, right</p>
<p>when we were talking to this is,</p>
<p>you know, when you really do this at scale</p>
<p>and you've got hundreds or thousands</p>
<p>of edge devices that whole idea of</p>
<p>how do you synchronize all of that data</p>
<p>if you're</p>
<p>trying to really understand</p>
<p>what's happening across</p>
<p>a large area and across a large time</p>
<p>frame, you get into some complexity</p>
<p>that is really.</p>
<p>Yeah, yeah.</p>
<p>In fact,</p>
<p>one one of the more interesting ones is</p>
<p>let's say your cloud goes down,</p>
<p>you have a thousand nodes connected</p>
<p>and then you reconnect.</p>
<p>You can get a Akamai swarm</p>
<p>where everything is trying to communicate</p>
<p>all at once and send all the data</p>
<p>they had all at once</p>
<p>and you'll overwhelm your cloud instances.</p>
<p>So yeah, and I wanted to highlight</p>
<p>like we didn't really do this</p>
<p>in the white paper when we,</p>
<p>when we wrote that up, we tried to keep it</p>
<p>focused on here</p>
<p>are the things that matter as opposed</p>
<p>to here's the technology that we have</p>
<p>that can help address these problems.</p>
<p>Right.</p>
<p>With the idea that what we wanted to do</p>
<p>is start the dialog</p>
<p>and help provide a framework</p>
<p>for how to think about things and where</p>
<p>where to look for some of the disconnects</p>
<p>that we've we've identified.</p>
<p>But like if you're up for it, Darren,</p>
<p>I think talking about the work</p>
<p>that you've done with Edge</p>
<p>Mirror is really fascinating, right?</p>
<p>Because because Edge Mirror</p>
<p>is really designed in a way that allows</p>
<p>everything to work well,</p>
<p>even when you've got that</p>
<p>sort of a complex situation</p>
<p>where tons of edge nodes,</p>
<p>you've just come back on to the cloud,</p>
<p>how do you make sure your comms are?</p>
<p>You know, how do you make sure that your</p>
<p>your system isn't overwhelmed</p>
<p>because everybody is talking it?</p>
<p>Yeah, well, and we</p>
<p>I have a couple podcasts on edge mural</p>
<p>I'll point people to on this</p>
<p>but edge mirrors this like you mentioned</p>
<p>it's a conceptual architecture</p>
<p>on how clouds work, cloud to edge work</p>
<p>and the things you have to watch out for.</p>
<p>But I want to go back to kind of these</p>
<p>requirements that were flushed out, right?</p>
<p>Because we talked about comms,</p>
<p>which is probably the biggest one.</p>
<p>Let's talk about some of the other ones</p>
<p>like security.</p>
<p>Right. Why?</p>
<p>What's different in security on the edge</p>
<p>than like in the cloud?</p>
<p>What would you say? The number one thing.</p>
<p>Probably the</p>
<p>number one thing is your edge</p>
<p>devices could be picked up.</p>
<p>Picked up and carry out.</p>
<p>Yeah, someone could steal it. So.</p>
<p>So physical security is a different thing</p>
<p>at the edge.</p>
<p>And depending on how critical</p>
<p>your functionality is</p>
<p>and what's actually on that device,</p>
<p>there could very easily be information</p>
<p>that you don't want to be retrievable.</p>
<p>You also want to make sure that</p>
<p>if somebody takes an edge device, that</p>
<p>that doesn't give them essentially an</p>
<p>entry point into your into your network.</p>
<p>So there's a whole new set of requirements</p>
<p>that that</p>
<p>that really can come to place.</p>
<p>A lot of the a lot of the traditional</p>
<p>security stuff is still super important.</p>
<p>Right. You still want to do</p>
<p>all of your authentication.</p>
<p>You still want to be able to</p>
<p>to know that the devices,</p>
<p>the device that you think it is.</p>
<p>But we have to.</p>
<p>Yeah, I thought it was interesting</p>
<p>when we went over the security ones.</p>
<p>There's new cases where I can put it</p>
<p>in, I can put an edge device out there and</p>
<p>and proxy or spoof your cloud instance</p>
<p>and say, hey, I'm one of your edge devices</p>
<p>and all of a sudden I'm sucking down</p>
<p>all the information,</p>
<p>all of your critical information,</p>
<p>or I'm just feeding it garbage,</p>
<p>which could,</p>
<p>you know, cause major problems.</p>
<p>You just.</p>
<p>Yeah. So, yeah, security on the edge.</p>
<p>It's a little scary to me, frankly.</p>
<p>Yeah.</p>
<p>And I would say it's also where</p>
<p>where we need</p>
<p>to like we as an industry</p>
<p>need to be devoting more time.</p>
<p>Right.</p>
<p>Because</p>
<p>there, there are very good solutions</p>
<p>that are out that are out there.</p>
<p>But but it is just a more complex world.</p>
<p>And, you know, as we talk</p>
<p>zero trust architectures, which again</p>
<p>for public sector are super important,</p>
<p>you know, edge devices are just this huge</p>
<p>attack surface now.</p>
<p>Right.</p>
<p>And in some ways it's not so different</p>
<p>from, hey, everybody's working on.</p>
<p>Yeah. That's an interesting point.</p>
<p>Yeah.</p>
<p>COVID kind of pushed us a little bit</p>
<p>to secure our or come up</p>
<p>with better edge security solutions.</p>
<p>Yeah, and there's there's a lot there.</p>
<p>But one of the things that we realized</p>
<p>that we really want to be working on is</p>
<p>we have great laptop security and we have</p>
<p>all sorts of ways to protect around that.</p>
<p>Those aren't nascent.</p>
<p>Those types of capabilities</p>
<p>aren't necessarily applied to</p>
<p>to edge devices that are not laptops</p>
<p>that are for more</p>
<p>industrial functionality</p>
<p>or are being used.</p>
<p>So for machine vision</p>
<p>or computer vision type of application.</p>
<p>And so there's a</p>
<p>there's a pretty solid dividing line.</p>
<p>And and we really do</p>
<p>at Intel want to work this idea of</p>
<p>how much</p>
<p>of what we've learned with our PC security</p>
<p>can we extract and really start applying</p>
<p>into what used to be called gateways.</p>
<p>Because it's an old term, right?</p>
<p>You know, it's now it's you know, it's</p>
<p>your your it's your edge device, right.</p>
<p>And say, what can we leverage there?</p>
<p>And are there some some rapid iterations</p>
<p>that we can do that, you know, that help?</p>
<p>And often</p>
<p>there's a big divide on operating systems</p>
<p>right between those two because, you know,</p>
<p>Linux is still the winner</p>
<p>when you're when you're doing anything,</p>
<p>you know, with a more functional and more,</p>
<p>you know, more application</p>
<p>focus as opposed to like a</p>
<p>traditional type of work</p>
<p>that you do with PCs. So</p>
<p>yeah, so it's a fascinating world.</p>
<p>I wanted to mention one thing</p>
<p>before we move on.</p>
<p>The other thing that is new that hasn't</p>
<p>we haven't really seen, adopted</p>
<p>or used yet, but is absolutely within</p>
<p>your line of vision is this idea that</p>
<p>for your edge</p>
<p>devices, we now know enough about what</p>
<p>the edge device is supposed to do,</p>
<p>where it's supposed to be,</p>
<p>how to confirm that it's in the place</p>
<p>that it's supposed to be.</p>
<p>There are some new things that could</p>
<p>really be brought into security to say,</p>
<p>don't just stop at, Hey,</p>
<p>I recognize this idea, right?</p>
<p>Or I recognize the device.</p>
<p>Can we confirm that?</p>
<p>But the other edge information that we're</p>
<p>collecting as a result of the application</p>
<p>that is. In the right location.</p>
<p>Is probably its primary function.</p>
<p>Right.</p>
<p>And in being able to do that gives us</p>
<p>a whole new horizon of of just</p>
<p>what we can really monitor</p>
<p>and what we can flag as a novel behavior.</p>
<p>And that's where I, from application</p>
<p>standpoint, is beautiful.</p>
<p>But if you just say, let's start talking</p>
<p>about how you can use AI for</p>
<p>anomaly detection to say, one of my 10,000</p>
<p>devices is really out there with respect</p>
<p>to what we would anticipate, given how</p>
<p>what its design functionality is, right?</p>
<p>So there's, there's some really, I think</p>
<p>amazing stuff that's going to be coming in</p>
<p>the near future because</p>
<p>because</p>
<p>we just have some some really good.</p>
<p>All right.</p>
<p>Let's talk a little bit about application,</p>
<p>because you mentioned a little bit</p>
<p>I can use it to help anomaly detection</p>
<p>of whether an application is running</p>
<p>appropriately</p>
<p>on an edge device or the edge device</p>
<p>is doing what it's supposed to.</p>
<p>How are applications different in edge</p>
<p>than they are in the cloud?</p>
<p>So yeah, so so obviously</p>
<p>there's a strong push</p>
<p>to have this be containerized, right?</p>
<p>Because</p>
<p>one of the things that you really want is</p>
<p>you want portability</p>
<p>of those applications.</p>
<p>And so without having to say, I know</p>
<p>exactly what this piece of hardware is</p>
<p>and I know it's operating system</p>
<p>and I know everything about it.</p>
<p>You don't want a custom design in that.</p>
<p>You want to say, hey,</p>
<p>that that architecture</p>
<p>is set up for a container</p>
<p>and now I'm going to just pop this new.</p>
<p>That's a major shift, right?</p>
<p>Because in the past, edge</p>
<p>it's all custom stuff, right?</p>
<p>Yeah.</p>
<p>Yeah, yeah.</p>
<p>And there's obviously been use of use</p>
<p>of containers and use of virtual machines.</p>
<p>But when you really want to scale this</p>
<p>and especially like the thing</p>
<p>we spent a lot of time</p>
<p>exploring, right, is where it becomes</p>
<p>the most relevant is</p>
<p>we're still going to develop</p>
<p>most of our applications on the cloud</p>
<p>or in a developer environment, right?</p>
<p>And so where they're all going to be</p>
<p>tested and use is going to be there first.</p>
<p>But if we can have a good understanding</p>
<p>of what those applications</p>
<p>really need to run at the edge and again</p>
<p>do that in a compute limitation</p>
<p>with compute limitations,</p>
<p>with power limitations,</p>
<p>with the connectivity limitations, right?</p>
<p>And say understand those up front</p>
<p>so that when those applications are</p>
<p>developed,</p>
<p>there's actually a very clear way for,</p>
<p>hey, here's how you can drop this</p>
<p>drop this down into this new location</p>
<p>without having to take an additional step</p>
<p>to be able to reprogram, you know,</p>
<p>without having to</p>
<p>bring in new middleware because, hey,</p>
<p>you've got this great application,</p>
<p>but to be able to understand your data,</p>
<p>you still have to do a whole</p>
<p>nother set of, of, of software development</p>
<p>so that it can get its raw data feeds to</p>
<p>the application, has something to work on.</p>
<p>So again, lots of things</p>
<p>have been done in that space.</p>
<p>But but again, just this whole idea</p>
<p>of begin with the end of mind,</p>
<p>appreciate that the edge environment</p>
<p>is very different and before you start</p>
<p>building those applications,</p>
<p>you know, take advantage of the fact that,</p>
<p>you know what</p>
<p>your limitations are on the edge.</p>
<p>We haven't talked about this yet,</p>
<p>but let's do a quick diversion</p>
<p>and say let's talk about how diverse</p>
<p>the edge can be, how much it can be</p>
<p>a new distributed compute setup,</p>
<p>because where we also see</p>
<p>some really remarkable things, right, is</p>
<p>most designs right</p>
<p>now as you have a single piece of compute</p>
<p>or maybe like a a few small servers and</p>
<p>you can run your applications right there.</p>
<p>We are already able to say,</p>
<p>can you design that application</p>
<p>so that it could actually run off</p>
<p>of a mesh network with highly distributed</p>
<p>compute where now that is</p>
<p>just if you've got ten nodes out there</p>
<p>and all ten, ten nodes of</p>
<p>those are in place now as well.</p>
<p>So that lends itself really</p>
<p>well then to containerization</p>
<p>and decoupling the application</p>
<p>from the hardware.</p>
<p>And that's a major shift, right?</p>
<p>Yes. Well, yeah.</p>
<p>And oh, well.</p>
<p>And then just getting getting more generic</p>
<p>and less purpose built.</p>
<p>Right.</p>
<p>You know, Iot and edge is</p>
<p>we still very much like here</p>
<p>is the single application</p>
<p>that you're going after, here's</p>
<p>your data feeds, here's</p>
<p>you know, and here is your one set of code</p>
<p>that's going to use those data feeds</p>
<p>to give you one answer.</p>
<p>Right.</p>
<p>And that is great for, for situations</p>
<p>where.</p>
<p>Yeah,</p>
<p>well which doesn't happen anymore. Right.</p>
<p>I mean those development cycles</p>
<p>are years long and now we need to get into</p>
<p>developing new, new applications</p>
<p>in, in months</p>
<p>instead of years. Yeah.</p>
<p>And they're constrained</p>
<p>and they tend to be very proprietary</p>
<p>and you have one company</p>
<p>that can actually keep them going.</p>
<p>And so this whole idea</p>
<p>of like changing the whole,</p>
<p>the whole dialog to say, hey,</p>
<p>now what we really want is</p>
<p>we want data from anywhere we can get it</p>
<p>and then we want to plop down whatever.</p>
<p>Oh, that's a good word.</p>
<p>It's just working for me.</p>
<p>We want to use whatever application,</p>
<p>you know,</p>
<p>whatever application is the cutting edge</p>
<p>application that we care about, right?</p>
<p>So we want the software part of that</p>
<p>to stay extremely current and robust,</p>
<p>to be able to take advantage of all of the</p>
<p>all of the advances that are being made.</p>
<p>And then just really marry up very quickly</p>
<p>and effectively to</p>
<p>to the data that's available.</p>
<p>And then if we can make</p>
<p>that even more robust by, say, you,</p>
<p>you can use</p>
<p>whatever compute you have at the edge.</p>
<p>And if your application</p>
<p>is too big to run on</p>
<p>a very constrained piece of hardware</p>
<p>that you've got,</p>
<p>if there's others in the area</p>
<p>and you can mesh that out now,</p>
<p>you can really still support</p>
<p>that application at the edge.</p>
<p>So you mentioned something</p>
<p>which is which is the next major</p>
<p>requirements, data management?</p>
<p>Yes. Right.</p>
<p>This is a major shift. Right.</p>
<p>This is probably right up there</p>
<p>with comms.</p>
<p>How do I manage data on the edge?</p>
<p>I remember</p>
<p>when I first saw Edge architectures,</p>
<p>everyone said, oh, 5G is going to fix us</p>
<p>because I'll just connect right to 5G.</p>
<p>Will, will connect it all up</p>
<p>and there's more bandwidth in 5G</p>
<p>than I could ever fill</p>
<p>and that's completely shot to smithereens.</p>
<p>I think.</p>
<p>So. I mean, it's still can work, right?</p>
<p>It's just it depends on when do you</p>
<p>actually have that network available?</p>
<p>And then can your applications</p>
<p>have that be,</p>
<p>you know, are your applications</p>
<p>such that you can support it</p>
<p>with a centralized model</p>
<p>where your maybe your data is collected</p>
<p>at a local, you know, at an edge location,</p>
<p>but then everything happens in the</p>
<p>in the cloud and then do you want a.</p>
<p>Is for. It.</p>
<p>Yeah. Yeah. It's the volume of data too.</p>
<p>There's so much data being collected</p>
<p>at the edge or generated at the edge.</p>
<p>I don't know this.</p>
<p>I don't think I want to send all that</p>
<p>raw data to a data center to be processed.</p>
<p>I just don't. Yeah.</p>
<p>And in most places, the cost is too high.</p>
<p>I mean, that's one of the nice things.</p>
<p>I will give a bit of a plug</p>
<p>for private 5G.</p>
<p>Part of the reason</p>
<p>that private 5G and again this is very US</p>
<p>centric is the spectrum applications</p>
<p>and things are different</p>
<p>than other parts of the world.</p>
<p>But for the U.S., like when they opened up</p>
<p>CVR, a spectrum and allowed,</p>
<p>you know,</p>
<p>essentially the individual users</p>
<p>or private users to take advantage</p>
<p>of that spectrum so that now, instead</p>
<p>of always being beholden to a carrier,</p>
<p>you could stand up your own 5G network</p>
<p>on that available spectrum.</p>
<p>And now you care a whole lot</p>
<p>less about those data costs,</p>
<p>because what you're already paying for</p>
<p>is your infrastructure</p>
<p>and keeping your network going,</p>
<p>as opposed to doing a,</p>
<p>you know, a normal cost structure.</p>
<p>If you're</p>
<p>if you're working with a carrier.</p>
<p>So there are some things that can happen</p>
<p>that can make it very cost effective</p>
<p>to still just move</p>
<p>a ton of data over your over your network.</p>
<p>Obviously some stuff to fly six to.</p>
<p>But but again, like most people</p>
<p>and for most organizations,</p>
<p>you're not standing up a private 5G</p>
<p>network, two or 40 4G LTE network</p>
<p>to do your work,</p>
<p>which means you got massive</p>
<p>data, data rates</p>
<p>and high data rates that you have to pay.</p>
<p>So there's a good incentive to.</p>
<p>Buy also to store all that</p>
<p>and this world data, right?</p>
<p>I mean, we're talking exabytes of data.</p>
<p>Yeah, petabytes</p>
<p>exabytes of data being generated</p>
<p>for camera is outrageous, right.</p>
<p>Well and most of the data</p>
<p>is of no use, right.</p>
<p>Because luckily when we're trying</p>
<p>to like monitor something</p>
<p>or we're trying to understand something</p>
<p>as a rule, you know,</p>
<p>most of the data that's coming</p>
<p>across is telling you that everything's</p>
<p>okay and all you really care about</p>
<p>is when things aren't okay.</p>
<p>Right.</p>
<p>And that's where the the value</p>
<p>of the computer vision of the edge</p>
<p>edge capabilities and really applying</p>
<p>AI algorithms gets really exciting</p>
<p>because because you can do that</p>
<p>and do that very effectively.</p>
<p>But if we go back to data management</p>
<p>a little bit, you know, Darren,</p>
<p>you're you're really much more</p>
<p>the data management expert than I am.</p>
<p>I did hope that we could talk a little bit</p>
<p>about some of the work</p>
<p>that Stan Mau has done with with Sandy.</p>
<p>With Sandy Vale.</p>
<p>And how that kind of makes sense and works</p>
<p>with the edge of your architecture</p>
<p>that you also have.</p>
<p>But maybe as opposed to talking</p>
<p>to architectures, we can say, here's</p>
<p>the cool stuff that those those types.</p>
<p>Yeah. So let's.</p>
<p>Help with the problem. Right. Yeah.</p>
<p>You turned it around.</p>
<p>Now you're interviewing me.</p>
<p>Way to go around it.</p>
<p>Yeah. No, that's good.</p>
<p>No, you know what?</p>
<p>What we found was there's different modes</p>
<p>of operation for data management,</p>
<p>or we call data ops.</p>
<p>The traditional one is copy everything</p>
<p>to the data center run analytics.</p>
<p>There.</p>
<p>And everyone's</p>
<p>been doing that for decades.</p>
<p>And they're finding,</p>
<p>oh, that doesn't quite work for Edge.</p>
<p>So we're just going to push</p>
<p>applications out to the edge</p>
<p>and that doesn't always work.</p>
<p>So we've identified a couple other data</p>
<p>architectures or data ops.</p>
<p>One is called a data exchange, where it's</p>
<p>a combination of moving data</p>
<p>in secure enclaves,</p>
<p>or only after</p>
<p>it's been analyzed on the edge.</p>
<p>And, and,</p>
<p>and that's in like batch type processing.</p>
<p>Another a fourth one</p>
<p>is what we call intelligent data streams.</p>
<p>And this is where Sadia and Saber</p>
<p>really come into play,</p>
<p>where I'm only moving data</p>
<p>based off of rules and it's being streamed</p>
<p>and it works in these digital environments</p>
<p>that you talked about.</p>
<p>So it's not just, hey,</p>
<p>this application always does</p>
<p>analytics and sends it, it's</p>
<p>what's the current operating environment?</p>
<p>Is it a full, full bandwidth?</p>
<p>I'm going to send everything</p>
<p>I possibly can.</p>
<p>Or am I only getting kill a bit right now</p>
<p>or do I have no comms?</p>
<p>I need to cache</p>
<p>and do some massaging there</p>
<p>and then only send what</p>
<p>really matters later when I reconnect.</p>
<p>So there's lots of really cool things</p>
<p>around the data management side.</p>
<p>We should probably have Stan</p>
<p>come on on the show and and talk about it</p>
<p>because we can go for another hour or two</p>
<p>just talking about data. So.</p>
<p>All right.</p>
<p>We're going to move, though,</p>
<p>because we'll never finish.</p>
<p>Let's let's talk about manageability</p>
<p>and what does</p>
<p>what does manageability really mean?</p>
<p>Well, you kind of touched on</p>
<p>a little bit earlier, but</p>
<p>give give me why</p>
<p>this is such a requirement.</p>
<p>Yeah.</p>
<p>So this is</p>
<p>this is the the classic edge problem for</p>
<p>for industrial</p>
<p>but also for for other verticals,</p>
<p>which is,</p>
<p>you know, the real promise of Iot</p>
<p>has always been this whole idea of there's</p>
<p>millions</p>
<p>of millions of devices and now you've</p>
<p>just got this massive amount of data.</p>
<p>But there's the very real problem</p>
<p>that's like, hey,</p>
<p>let's just talk a hundred devices</p>
<p>and how are those hundred devices</p>
<p>really going to be monitored,</p>
<p>updated, authenticated,</p>
<p>you? How are you going to make sure</p>
<p>that you yeah,</p>
<p>you're pushing your updates</p>
<p>and the updates are actually loading</p>
<p>in that everything's healthy</p>
<p>and and you're responding as as expected.</p>
<p>And then</p>
<p>that whole whole set of problems</p>
<p>is something that everybody's known</p>
<p>about it for a long time.</p>
<p>And in some ways, is it terribly,</p>
<p>terribly different from, hey, your entire</p>
<p>workforce just had to stay home</p>
<p>for, you know, for years?</p>
<p>And now you've got, you know,</p>
<p>a 10,000 person organization and hey,</p>
<p>how is that working, right?</p>
<p>I mean, so same same sort of problems.</p>
<p>But now you just don't have a person</p>
<p>at the other end</p>
<p>that can pay attention to the updates</p>
<p>and can do the oh,</p>
<p>what's our, what's our term</p>
<p>for the Wednesday the Wednesday reboots.</p>
<p>Yeah.</p>
<p>So but that all still has to happen,</p>
<p>right.</p>
<p>And especially if you've got network</p>
<p>connectivity,</p>
<p>you know, you can't, you know,</p>
<p>like the current industrial thing, right.</p>
<p>Is like you may have some connectivity,</p>
<p>but essentially you'll</p>
<p>put something in the field</p>
<p>that has a dedicated capability</p>
<p>and you leave it there for ten years</p>
<p>and, and.</p>
<p>Don't touch it.</p>
<p>And you just don't touch it.</p>
<p>And maybe you do the firmware</p>
<p>once every ten years and then you do it</p>
<p>by sending a guy with thumb drive right</p>
<p>in modern systems, especially</p>
<p>when you want to do them at scale</p>
<p>and especially when you want to get it,</p>
<p>you know,</p>
<p>get a lot more devices out there.</p>
<p>None of that stuff makes any sense.</p>
<p>And so you need to really well,</p>
<p>these systems</p>
<p>just absolutely have to be architected</p>
<p>in a way that they can be maintained</p>
<p>because you can't say deploy, you know,</p>
<p>a thousand devices to a remote location</p>
<p>and then have a small army of people</p>
<p>that are going to be</p>
<p>going there on a regular basis</p>
<p>to make sure that everything's working.</p>
<p>There's no economics in that. So.</p>
<p>But it doesn't isn't that.</p>
<p>Yeah, isn't that kind of I know the i.t</p>
<p>guys are very cautious around this space.</p>
<p>Yeah.</p>
<p>Because and they don't upgrade things</p>
<p>because don't touch</p>
<p>what's working mentality</p>
<p>but there's, there's</p>
<p>a lot of fear around</p>
<p>ransomware attacks on OT networks now.</p>
<p>Absolutely.</p>
<p>And, and that's why</p>
<p>you can't leave it alone. Right.</p>
<p>It's like there's almost nothing worse</p>
<p>than you can do to say,</p>
<p>hey, we're not going to fix it</p>
<p>because it's not broken.</p>
<p>But that's not true from a security</p>
<p>vulnerability perspective, right?</p>
<p>So if you're going to have this type</p>
<p>of connectivity, you have to have a way</p>
<p>of keeping everything updated</p>
<p>so that it's got the robustness that</p>
<p>you need to deal with the</p>
<p>you know, with the environment</p>
<p>that we live in with respect to security.</p>
<p>So so yeah.</p>
<p>And there's a lot of different points.</p>
<p>I mean, this is, again, like all of</p>
<p>the things that go into a cloud are,</p>
<p>you know, fields on their own</p>
<p>with experts and well-developed</p>
<p>industries and and lots of time spent.</p>
<p>It's so we were</p>
<p>we were did a very high level thing,</p>
<p>which is just don't neglect this</p>
<p>because don't just go out there</p>
<p>and start throwing out</p>
<p>some good architectures.</p>
<p>Because if that architecture hasn't been</p>
<p>crafted to be with manageability in mind,</p>
<p>you're probably going to find</p>
<p>that your management is going to say</p>
<p>thank you, but go away</p>
<p>because we're not ever going to apply it.</p>
<p>Yeah, no, I agree. Right.</p>
<p>There's there's one one major one left</p>
<p>and that's availability</p>
<p>which we've already kind of</p>
<p>touched on a little bit.</p>
<p>Yeah, availability.</p>
<p>Anytime I think of availability,</p>
<p>I remember when I was a CIO</p>
<p>and we talk about availability</p>
<p>as in three or four nines.</p>
<p>My data centers up for nines. Yeah.</p>
<p>Yeah, yeah.</p>
<p>But yeah, except for edge.</p>
<p>You don't talk even double nines, do you,</p>
<p>as far as availability goes.</p>
<p>So we would love to right the way,</p>
<p>the way that it works</p>
<p>is if we need that type of availability,</p>
<p>it's still all hardwired</p>
<p>and then typically</p>
<p>has the redundancy built in.</p>
<p>So that's one of the things like</p>
<p>if we go back to the health care model,</p>
<p>this is where</p>
<p>that part of it becomes really critical.</p>
<p>Or I don't even want double nines,</p>
<p>I want 100% uptime.</p>
<p>You know. Yeah, like nine nine.</p>
<p>They're like seven nine. Yeah, exactly.</p>
<p>It's almost impossible to meet,</p>
<p>but it's but it, it does become</p>
<p>like a whole new world of saying,</p>
<p>okay, it's not, again,</p>
<p>good enough to have an edge architecture</p>
<p>or have a manageable edge architecture</p>
<p>or even have an edge architecture</p>
<p>that can communicate with the cloud</p>
<p>and take advantage of that</p>
<p>with these nice seamless applications</p>
<p>flowing back and forth.</p>
<p>It is.</p>
<p>Can you design that with sufficient</p>
<p>redundancy based on what the applications.</p>
<p>Yeah, I like that approach</p>
<p>because it's more of a systems approach.</p>
<p>I don't care if one component fails</p>
<p>as long as the mission</p>
<p>senior you can tell I've been in the DOD</p>
<p>way too long.</p>
<p>Everything's in mission</p>
<p>as long as the application.</p>
<p>Like on a hospital bed, right?</p>
<p>As long as I keep that patient alive</p>
<p>and notify if there's issues.</p>
<p>I don't care if individual components fail</p>
<p>as long as I meet the end goal.</p>
<p>And that's very, very different</p>
<p>than what we do in the cloud.</p>
<p>It's all about</p>
<p>keeping the infrastructure up.</p>
<p>Yeah.</p>
<p>And like, oh,</p>
<p>I'll see if I can give an example because,</p>
<p>because I think at edge it's harder</p>
<p>because there's also a cost sensitivity</p>
<p>at the edge, because you want to</p>
<p>get the scale where you've got,</p>
<p>you know, lots and lots of devices</p>
<p>and lots of lots of capabilities.</p>
<p>Right.</p>
<p>And so so</p>
<p>one of the other things that Intel does is</p>
<p>we we have a Smart Edge platform.</p>
<p>I've worked the most with the commercial,</p>
<p>so I'll talk about that since,</p>
<p>since I just understand it better.</p>
<p>But like one of the examples is like</p>
<p>for some applications, you could say,</p>
<p>here's a Smart Edge Mac application</p>
<p>that has really good network connectivity.</p>
<p>You can use 4G, 5G, LTE, Wi-Fi, six,</p>
<p>whatever is available and it can work.</p>
<p>You know, has a Xeon class server</p>
<p>and it will work with like, you know,</p>
<p>say 10 to 100 different edge devices.</p>
<p>Right.</p>
<p>And that could be a really solid</p>
<p>architecture, but that almost undoubtedly</p>
<p>does not have a high enough availability</p>
<p>if it's single server</p>
<p>and if it's single network.</p>
<p>Right.</p>
<p>So if we're really talking availability,</p>
<p>there is extra cost</p>
<p>that you have to throw in</p>
<p>because at a minimum</p>
<p>you need redundancy of compute,</p>
<p>but then you need that software to</p>
<p>be designed so that if there is a channel,</p>
<p>you know, if something fails, you have</p>
<p>a seamless set of operation, right?</p>
<p>Ideally in this we're not there yet.</p>
<p>But is is on the on the radar</p>
<p>is this idea of,</p>
<p>hey, if you can get your hands</p>
<p>on multiple networks, then</p>
<p>you don't want a system</p>
<p>that's designed for a single network.</p>
<p>You really know this is especially true.</p>
<p>And the, you know, in the public sector</p>
<p>side of the world,</p>
<p>you want a system that can say,</p>
<p>hey, I've got WiFi 6</p>
<p>and I use that preferentially,</p>
<p>but if I lose my wife,</p>
<p>I don't have any 4G here</p>
<p>and can I keep the network moving</p>
<p>so that I still have good connectivity</p>
<p>and I can still do what I need to do?</p>
<p>So it's almost like</p>
<p>the availability is a bit too,</p>
<p>you know, twofold with respect</p>
<p>to making sure your computer's solid</p>
<p>and then making sure that your network</p>
<p>connection is solid.</p>
<p>And again, we can designed to be</p>
<p>standalone operations without the network</p>
<p>side.</p>
<p>But then does that mean you're hard</p>
<p>wired to all of your.</p>
<p>Yeah, yeah,</p>
<p>that means it's fragile, right?</p>
<p>It's right. Right.</p>
<p>And if you go hard wired costs get higher.</p>
<p>It's limitations.</p>
<p>You lose your mobile applications.</p>
<p>And so this whole idea of</p>
<p>how do you get your local network</p>
<p>to be highly, highly available as well?</p>
<p>And often what that means is</p>
<p>you've got to just go redundant, right?</p>
<p>So yeah, it's just it's fascinating.</p>
<p>So yeah, that's interesting</p>
<p>because you've tied cost.</p>
<p>Cost of course</p>
<p>is something in there and it's almost in</p>
<p>opposition to availability</p>
<p>and things like that.</p>
<p>So and this has been very insightful</p>
<p>if people want to find</p>
<p>out more,</p>
<p>you guys can go to embracingdigital.org.</p>
<p>There is a white paper there.</p>
<p>You can also find the white paper</p>
<p>on intel.com.</p>
<p>The white paper is called</p>
<p>Essential Requirements</p>
<p>for edge to Cloud Service Architectures.</p>
<p>Go out and look for Dr.</p>
<p>Anna Scott, thank you again, as always.</p>
<p>It's a pleasure.</p>
<p>Hey, Darren, great conversation.</p>
<p>I appreciate it.</p>
<p>Thank you for listening</p>
<p>to Embracing Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcasting site or YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>at embracingdigital.org</p>
<p>until next time, go out</p>
<p>and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
