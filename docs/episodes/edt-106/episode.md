---
layout: posts
title: Put the Title Right Here
number: 106
permalink: EDT106
has_children: false
parent: Episodes
nav_order: 106
tags:
     - EDT111
    - EmbracingDigital
date: 
guests:
    - Darren W Pulsipher
img: TBD
summary: Summary
---

{% include soundcloud.html id="edt106" title="#106 Put the Title Right Here" %}

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
<p>On today's episode,</p>
<p>the birth of Graph Intelligence Platforms</p>
<p>with Greg Steck</p>
<p>senior solution architect at Katana</p>
<p>Graph.</p>
<p>Welcome to the show.</p>
<p>Thanks, Darren.</p>
<p>Happy to be here.</p>
<p>Hey, Greg,</p>
<p>tell me a little bit about yourself.</p>
<p>We've already talked to Hadi</p>
<p>about the benefits of graph databases,</p>
<p>but tell me a little bit about yourself</p>
<p>and your background.</p>
<p>Sure.</p>
<p>Yeah.</p>
<p>So my background is in financial services.</p>
<p>So I started my career at an investment</p>
<p>bank in credit risk.</p>
<p>So it was right at the time</p>
<p>where they were starting to implement</p>
<p>a lot of the sector stress testing.</p>
<p>So we got heavily involved in that.</p>
<p>After doing that, for some time,</p>
<p>I went to did some consulting</p>
<p>and we did more kind of credit</p>
<p>risk modeling model validation,</p>
<p>and that's kind of where I was introduced</p>
<p>to graphs, right?</p>
<p>And really how they could be leveraged</p>
<p>for a lot of different kinds of analysis,</p>
<p>a lot of benefits on the data</p>
<p>management side, but then also on machine</p>
<p>learning and credit modeling side</p>
<p>specifically</p>
<p>so that I then I found my way to a ton of</p>
<p>that's how I ended up here.</p>
<p>All right.</p>
<p>So you're the one that, you know, made it</p>
<p>so I couldn't get a loan on my house?</p>
<p>Is that what I'm hearing?</p>
<p>You're the credit. Guy.</p>
<p>Pretty much said. Yeah, you got it.</p>
<p>Oh, great.</p>
<p>So you know how all those algorithms work.</p>
<p>So you know how to work.</p>
<p>You know how to work.</p>
<p>You know we're getting loans and things,</p>
<p>right?</p>
<p>Yep. Yeah, that's what we did.</p>
<p>A lot of it. Yeah.</p>
<p>Consulting a job at the investment bank.</p>
<p>It was more kind of on the derivatives</p>
<p>and OTC side,</p>
<p>so more counterparty risk,</p>
<p>but yeah, consulting.</p>
<p>We did a lot of the consumer lending.</p>
<p>Wow. That's that's incredible.</p>
<p>All right.</p>
<p>So what takes you from financial</p>
<p>into something high tech kind of bleeding</p>
<p>edge like a tanning graph?</p>
<p>What?</p>
<p>I mean, what made you move over there?</p>
<p>Yeah.</p>
<p>So when we were working with this data,</p>
<p>you know, as a data analyst</p>
<p>and as the data scientist,</p>
<p>we're constantly struggling trying to</p>
<p>integrate all these different data</p>
<p>sets. Right.</p>
<p>And so what I was introduced to graph</p>
<p>and I was actually introduced</p>
<p>through RDF, right?</p>
<p>So that's like a very semantic</p>
<p>kind of knowledge graph format.</p>
<p>It made a lot of intuitive sense</p>
<p>on how this data could be combined.</p>
<p>Right?</p>
<p>So I was very familiar with the data,</p>
<p>so it just made a lot of sense</p>
<p>to structure it as a graph.</p>
<p>So that's really kind of</p>
<p>what drew me into to start using graphs.</p>
<p>Well, that's that's incredible.</p>
<p>And then, I mean, you must have liked it</p>
<p>so much that you jumped ship onto creating</p>
<p>I mean, container graph.</p>
<p>That's what they do, right?</p>
<p>Yeah, exactly.</p>
<p>Yeah.</p>
<p>So with chaotic graph,</p>
<p>it was really seeing this</p>
<p>and we were experiencing</p>
<p>this scalability problem throughout.</p>
<p>We were trying to use</p>
<p>existing graph solutions.</p>
<p>We were having</p>
<p>a lot of our data was very big.</p>
<p>We were having a hard time scaling</p>
<p>our solutions with the existing databases.</p>
<p>And so that's really</p>
<p>what was very compelling with the town of</p>
<p>Graph was their ability to scale,</p>
<p>but then also the focus on machine</p>
<p>learning.</p>
<p>Okay. So tell me a little bit.</p>
<p>I mean,</p>
<p>we mentioned at the top of the show</p>
<p>this is the birth of graph</p>
<p>intelligence platforms.</p>
<p>What in the world is I mean,</p>
<p>because we heard about graph databases.</p>
<p>All right.</p>
<p>They're super cool.</p>
<p>I like using them for for my work.</p>
<p>But I mean, I can only carry those so far.</p>
<p>So what's this next phase?</p>
<p>I mean, what would you call us?</p>
<p>Yeah, exactly.</p>
<p>So, yeah, we've seen kind of the graph</p>
<p>databases evolve over time, right?</p>
<p>So kind of at the beginning,</p>
<p>kind of the 1.0 was,</p>
<p>you know, how you have the large companies</p>
<p>like Facebook</p>
<p>and Amazon building basically in-house</p>
<p>their own graph databases.</p>
<p>Right.</p>
<p>And they're doing a lot of the,</p>
<p>you know, the modeling</p>
<p>and then the machine learning around it.</p>
<p>And then you had some platforms like Neo</p>
<p>for Jay</p>
<p>Tiger Graph introduce, you know,</p>
<p>kind of a consumer version, right?</p>
<p>The ability to use those for,</p>
<p>you know, just general use cases.</p>
<p>But the challenge was</p>
<p>they really were centered</p>
<p>around the database</p>
<p>and not as much around analytics</p>
<p>and the machine learning, the processing,</p>
<p>the actual, the graph compute so that.</p>
<p>They were pretty</p>
<p>they were pretty limited then because</p>
<p>I mean they're they're only</p>
<p>it's like a data store in that case.</p>
<p>Then, right? Yeah. Yeah, exactly.</p>
<p>So mostly on the storage,</p>
<p>you know, the ingest, you know,</p>
<p>the CRUD operations</p>
<p>and not as much on the on the compute.</p>
<p>Okay.</p>
<p>So then I mean, that has limited use,</p>
<p>as you were saying.</p>
<p>So then it moves into</p>
<p>you said analytics comes next.</p>
<p>Is that where you're seeing things</p>
<p>migrate to?</p>
<p>Yeah, exactly.</p>
<p>So we kind of see these in like three</p>
<p>different kind of graph compute domains.</p>
<p>So you've got kind of the the graph query,</p>
<p>those are your graph database</p>
<p>operations, right? Your CRUD operations.</p>
<p>And then you have the second</p>
<p>domain is graph analytics and mining.</p>
<p>So that's where you have kind of PageRank</p>
<p>algorithms, clustering algorithms, right?</p>
<p>Those have started</p>
<p>to become really popular.</p>
<p>And then the third area that we see as,</p>
<p>you know, graph air and machine learning.</p>
<p>So this is where graph neural networks</p>
<p>really come into the picture</p>
<p>and there solutions like solve,</p>
<p>you know, you know,</p>
<p>kind of there's point solutions out there</p>
<p>that will solve specific parts</p>
<p>of those domains, but the graph sits</p>
<p>at the intersection of those.</p>
<p>That's</p>
<p>what we do that is really important.</p>
<p>So it's it's the three domains.</p>
<p>I want to make sure I got it right.</p>
<p>It's your graph databases,</p>
<p>right for your normal like storing</p>
<p>and your normal querying</p>
<p>type things, right analytics.</p>
<p>And then I and,</p>
<p>and it's the convergence of all three.</p>
<p>I mean, why do why do I care?</p>
<p>Why not just stick with</p>
<p>what's already been out there?</p>
<p>I mean, we know the benefits</p>
<p>of an individual graph database,</p>
<p>but why not just convert</p>
<p>or take snapshots of that data</p>
<p>and put it in your traditional data</p>
<p>lake and run analytics there?</p>
<p>Why not just do that? Yeah.</p>
<p>Yeah.</p>
<p>So what we found is that, you know,</p>
<p>each of these are important.</p>
<p>You know,</p>
<p>you need all three of these, right?</p>
<p>To have a successful platform and,</p>
<p>you know, kind of</p>
<p>to walk through an example, right?</p>
<p>If you're trying to do machine learning,</p>
<p>you need the other two domains, right?</p>
<p>You need to be able to run graph query</p>
<p>to prepare the graph.</p>
<p>You know, when you first ingest the data</p>
<p>into a graph,</p>
<p>there's a lot of transformations</p>
<p>that need to be done</p>
<p>to prepare it for machine learning.</p>
<p>And so if you don't have this</p>
<p>all in one solution,</p>
<p>it's going to take you a lot of time</p>
<p>for that pipeline, right?</p>
<p>To get to the machine learning</p>
<p>or to the analytics, it's a lot of pain</p>
<p>to, you know, to send the data out,</p>
<p>read it back in.</p>
<p>And there's a lot of iteration that goes</p>
<p>on, right?</p>
<p>You need to be able to iterate</p>
<p>on this whole pipeline quickly.</p>
<p>So by going</p>
<p>to a full graph platform,</p>
<p>what you're telling me is</p>
<p>I can decrease the amount of times</p>
<p>I have to transform the data.</p>
<p>That's what I'm doing. Is that. Right?</p>
<p>Yeah.</p>
<p>You got it. Yeah.</p>
<p>So we have an in-memory representation,</p>
<p>so that's going to in our API,</p>
<p>you can just operate on that same graph</p>
<p>object through that whole lifecycle</p>
<p>so you can adjust it.</p>
<p>And then, you know,</p>
<p>we're very data scientist friendly.</p>
<p>So it's all Python operations that you can</p>
<p>do just through that whole pipeline.</p>
<p>So that's pretty cool.</p>
<p>So not only does that decrease time, I'm</p>
<p>guessing that also decreases</p>
<p>the amount of storage that you use</p>
<p>and also possibilities</p>
<p>of screwing things up.</p>
<p>Right.</p>
<p>I mean, anytime you touch and transform</p>
<p>data, there's an opportunity to</p>
<p>to lose data, right?</p>
<p>Yeah, absolutely.</p>
<p>Yeah.</p>
<p>When you're trying to write back</p>
<p>and send it between platforms</p>
<p>and transform it, yeah,</p>
<p>there's a lot of room for error, so.</p>
<p>Yeah. And then also with our,</p>
<p>you know, we're a cloud native platform.</p>
<p>So being able to separate the storage</p>
<p>and compute, you know, if you ever want</p>
<p>to, you know, parse, you can stop,</p>
<p>you know, save a checkpoint off</p>
<p>for that graph, spend down the cluster,</p>
<p>spit it back up later and start</p>
<p>right back off where you left it.</p>
<p>So oh, wait, that's that's really cool.</p>
<p>So what you're telling me is I can take a</p>
<p>snapshot of my graph in this case, right?</p>
<p>So, hey, I run into this one area</p>
<p>that I know</p>
<p>the next steps may be risky.</p>
<p>I don't know what the right word is.</p>
<p>It could corrupt my data, possibly.</p>
<p>So I want to take a snapshot and keep that</p>
<p>so I have some temporal aspect to it.</p>
<p>Right. And then I can carry on.</p>
<p>And then possibly if that mess things up,</p>
<p>I, I can wipe that out</p>
<p>and go back to my original.</p>
<p>Is that part of this whole platform idea?</p>
<p>Yeah, absolutely. Yeah.</p>
<p>So if you're a data scientist and you're</p>
<p>running various experiments, yeah,</p>
<p>you're</p>
<p>not exactly sure what you're going to get.</p>
<p>So you want</p>
<p>to save a checkpoint at the beginning,</p>
<p>try some things out and then go back.</p>
<p>Right. But also if you're passing it</p>
<p>between teams, right?</p>
<p>So in these large organizations, typically</p>
<p>you'll have a data management team</p>
<p>that's they're the ones that understand</p>
<p>the source data.</p>
<p>They're the ones they're going</p>
<p>to build the graph for you, right?</p>
<p>So they could build a graph</p>
<p>in our platform, save it off.</p>
<p>And then the data scientists,</p>
<p>the data science team, they can pick it</p>
<p>right up from from that point.</p>
<p>Give me a use case.</p>
<p>So show me how I would use this</p>
<p>whole platform with one of your customers,</p>
<p>maybe someone that you've helped recently.</p>
<p>Yeah, sure.</p>
<p>So we've got a great demo that we that</p>
<p>we walk through around fraud detection.</p>
<p>So there's this Bitcoin transaction</p>
<p>data set, right?</p>
<p>There's a tool called the elliptic Bitcoin</p>
<p>data set</p>
<p>and we go through</p>
<p>and we can ingest that data.</p>
<p>So you have the basically the way</p>
<p>the data is structured is you have</p>
<p>Bitcoin wallets are the nodes in the graph</p>
<p>and then you have the edges</p>
<p>between those are the transactions, right?</p>
<p>So it's a pretty simple graph</p>
<p>you have. Yeah.</p>
<p>The wallets</p>
<p>are these accounts, these account nodes</p>
<p>and then you're transferring data</p>
<p>between the different nodes</p>
<p>so that that's the structure.</p>
<p>And then we're trying to basically predict</p>
<p>if Bitcoin wallet is fraudulent, right?</p>
<p>In this case, it's illicit or illicit.</p>
<p>So these have been previously labeled as,</p>
<p>you know, for,</p>
<p>you know, money</p>
<p>laundering, trafficking, drug, right.</p>
<p>Any of these kind of things.</p>
<p>They flagged it as illicit.</p>
<p>And so in the task we're trying to predict</p>
<p>with a new account that comes in</p>
<p>if it's fraudulent or not.</p>
<p>So we and the first step is to, you know,</p>
<p>ingest that data into our platform.</p>
<p>We built a graph and then we want to do</p>
<p>some future preparation.</p>
<p>So if you think about each one of these</p>
<p>Bitcoin accounts, they have a whole set</p>
<p>of numeric features, right?</p>
<p>And to start the machine learning process,</p>
<p>you need to do some,</p>
<p>some setup preprocessing to that, right?</p>
<p>You need to get it ready for machine</p>
<p>learning.</p>
<p>That in itself is really challenging.</p>
<p>We have actually designed a set of APIs</p>
<p>to address that problem.</p>
<p>Right, to quickly normalize one hard code.</p>
<p>All these things that data scientists</p>
<p>do to prepare their features,</p>
<p>you can do that.</p>
<p>So now you've got the graph ready to</p>
<p>to put into the machine learning model.</p>
<p>And then from there</p>
<p>it goes into the machine learning model.</p>
<p>You train it right.</p>
<p>And using graph</p>
<p>neural networks, which I think we're going</p>
<p>to get into in another episode,</p>
<p>you can you start to learn about,</p>
<p>you know, how</p>
<p>to classify these accounts</p>
<p>as fraudulent or not.</p>
<p>So that's kind of an example of,</p>
<p>you know, for fraud detection,</p>
<p>how you would go through that process.</p>
<p>So you guys offer one platform</p>
<p>that lets a data</p>
<p>scientist work on</p>
<p>and your data engineers, right?</p>
<p>Work on that whole thing from one platform</p>
<p>instead of piecing things together.</p>
<p>Is that the best way</p>
<p>to think of the platform concept?</p>
<p>Yeah, exactly, exactly.</p>
<p>I of very, very cool stuff.</p>
<p>What other benefits do</p>
<p>I get from using a platform</p>
<p>as I heard of ease of use decrease in</p>
<p>time.</p>
<p>Yeah. What other things.</p>
<p>What other things are there.</p>
<p>Yeah.</p>
<p>So another one is total cost of ownership.</p>
<p>So when you think about running this,</p>
<p>this pipeline</p>
<p>and you're using a large amount of data,</p>
<p>there are certain patterns</p>
<p>where you can actually have</p>
<p>to leave off the whole graph database</p>
<p>running all the time.</p>
<p>So when you have a new,</p>
<p>we take our example from before.</p>
<p>If you have a new fraudulent,</p>
<p>you have a new transaction</p>
<p>comes in, you want to run</p>
<p>inferencing against that data, right?</p>
<p>And so in a lot of these cases,</p>
<p>you have to keep up this cluster,</p>
<p>which is very expensive. Right.</p>
<p>And you have to have it</p>
<p>running all the time.</p>
<p>But with the way</p>
<p>that we design our pipelines</p>
<p>and the way because of the separation</p>
<p>of storage and compute,</p>
<p>we can easily spin up our cluster,</p>
<p>do some batch processing beforehand,</p>
<p>and then you can run inferencing</p>
<p>kind of in a separate system</p>
<p>and we can still leverage</p>
<p>what we generated in the graph.</p>
<p>So this really lowers the total cost</p>
<p>of ownership by a lot, right?</p>
<p>You're only spinning up your cluster</p>
<p>when you need it.</p>
<p>You don't have to</p>
<p>have it online all the time.</p>
<p>So that that's pretty</p>
<p>cool because I can like you said,</p>
<p>I mean, if you're running in the cloud,</p>
<p>you're paying</p>
<p>whether you're using it or not, right?</p>
<p>Yeah, exactly. Yeah.</p>
<p>You have to have it up for inferencing.</p>
<p>You've got to have it up 24 seven.</p>
<p>And it's got to be</p>
<p>you've got to have the whole data loaded.</p>
<p>Yeah.</p>
<p>So so that's that's</p>
<p>I guess another question I have for you.</p>
<p>How long does it take for?</p>
<p>All right, I've to spin up a cluster to do</p>
<p>my training.</p>
<p>Is that a substantial amount of time?</p>
<p>Because some of these graph databases</p>
<p>are pretty large, or does it load things</p>
<p>dynamically as it needs them, or</p>
<p>does it have to load it all into memory?</p>
<p>What's what's the how does that work?</p>
<p>Yeah.</p>
<p>So, you know, in terms of actually</p>
<p>deploying the cluster,</p>
<p>you know, we have a,</p>
<p>you know, a deployment method to do that.</p>
<p>And once the cluster is up,</p>
<p>you know, that takes a little bit of time</p>
<p>to get it configured.</p>
<p>But then once it's stops,</p>
<p>you can easily stop and start it, right?</p>
<p>But now when we talk about adjusting data,</p>
<p>this might be getting to your point.</p>
<p>We can at any time when we first load</p>
<p>our load is very fast and it's because</p>
<p>we don't load all the data that we need</p>
<p>at, you know, at the beginning, right?</p>
<p>So we haven't got a smart way</p>
<p>to load the data.</p>
<p>And then as you work</p>
<p>through that pipeline, as you need</p>
<p>certain properties on the graph,</p>
<p>then it will actually load those.</p>
<p>So we do have a dynamic way to load data</p>
<p>all the only load stuff that you need.</p>
<p>So I don't</p>
<p>have to, I don't</p>
<p>have to load the whole thing in the memory</p>
<p>because I know in the past</p>
<p>when I've worked with graph databases</p>
<p>to get them started at the beginning,</p>
<p>I'd have to load everything up into memory</p>
<p>and then I could work on it.</p>
<p>And then as the changes came through,</p>
<p>it stored the deltas out.</p>
<p>But you guys, obviously</p>
<p>you're beyond that now, right?</p>
<p>I mean, that was</p>
<p>that was probably an old clunky, you know,</p>
<p>neo 4G install at the time.</p>
<p>So I'm able to I'm able to quickly</p>
<p>bring things up.</p>
<p>And obviously, if if you're hammering the</p>
<p>if you're hammering the graph,</p>
<p>it's going to take some time to get</p>
<p>those nodes loaded at first.</p>
<p>But after that, it'll be fast, right?</p>
<p>Yeah. Yeah, exactly.</p>
<p>And you know, a lot of this technology,</p>
<p>this is, you know,</p>
<p>kind of our core competencies</p>
<p>in this area.</p>
<p>So our founder, Dr. Bishop in Galway.</p>
<p>Right.</p>
<p>And his team, this is where they focus</p>
<p>their research for, you know,</p>
<p>the last ten years was around</p>
<p>these optimizations to be able to do this</p>
<p>in parallel and to do it very fast.</p>
<p>Very cool.</p>
<p>Now tell me a little bit more</p>
<p>about on the analytics side,</p>
<p>because there are platforms</p>
<p>that have been out there for some time.</p>
<p>I know the same techniques don't</p>
<p>don't mean anything like MapReduce doesn't</p>
<p>really apply into a graph database nearly</p>
<p>like it does in a relational database.</p>
<p>Right.</p>
<p>Because you have to do that in order</p>
<p>to split everything up across a cluster.</p>
<p>But what kinds of operations</p>
<p>what can I do on the analytics side?</p>
<p>Because I don't want</p>
<p>to get into the side yet.</p>
<p>We're going to do a whole</p>
<p>nother podcast about that.</p>
<p>But what about on the analytics side?</p>
<p>What sorts of things</p>
<p>can I do with a graph?</p>
<p>Database can do everything</p>
<p>I normally did with my relational deck.</p>
<p>What are the limitations</p>
<p>and maybe what's better in graph?</p>
<p>Yeah, sure.</p>
<p>So yeah, we talk about analytics.</p>
<p>Maybe we could talk about some of the</p>
<p>when we talk about analytics,</p>
<p>we think about graph algorithms</p>
<p>like PageRank from band.</p>
<p>So maybe we could talk about those too.</p>
<p>But in terms of</p>
<p>like your generalized analytics</p>
<p>that you would want to do in a, in</p>
<p>a, like a relational table,</p>
<p>the real benefit</p>
<p>that you get for doing that in a graph,</p>
<p>the first</p>
<p>benefit is having a singular data model.</p>
<p>Right?</p>
<p>So you probably talked a little bit</p>
<p>about this with Heidi, but being able to</p>
<p>if you have ten different data</p>
<p>sets, right,</p>
<p>and if you're an analyst</p>
<p>and you're trying to figure out</p>
<p>how do I join these together</p>
<p>to write a query,</p>
<p>you know, that's that's very cumbersome</p>
<p>and it's very error prone.</p>
<p>Now, when you're</p>
<p>when you're using a graph, right,</p>
<p>you have a singular model, right.</p>
<p>That's already been predefined and built.</p>
<p>So as an analyst is data.</p>
<p>So I'm just trying to do queries</p>
<p>and try to understand the data</p>
<p>and what's some basic analytics</p>
<p>that's going to be a much easier</p>
<p>right to do that with a graph</p>
<p>because my date is already connected.</p>
<p>I can, you know, I can intuitively</p>
<p>see how the data is related, right?</p>
<p>So so you guys have in</p>
<p>your analytics toolbox</p>
<p>the, you've given the ability to actually</p>
<p>peruse the graph itself</p>
<p>so I can see how things are related.</p>
<p>Is that part of your</p>
<p>analytics platform? Because</p>
<p>I know,</p>
<p>I know</p>
<p>some, some of the stuff that I write</p>
<p>because I'm a software engineer</p>
<p>and some of the things that I write,</p>
<p>I start seeing new relationships</p>
<p>between objects in my system</p>
<p>that I didn't know</p>
<p>when I first designed it.</p>
<p>And they just pop out because, oh,</p>
<p>those two things are related,</p>
<p>let's connect them.</p>
<p>So some of these, they're not very</p>
<p>well-defined data schemas sometimes.</p>
<p>Is that. Yeah. Is that fair to say.</p>
<p>Yeah, that makes sense. Yeah.</p>
<p>At our focus. Right.</p>
<p>Kind of initially is really on</p>
<p>the data scientist kind of experience.</p>
<p>Right.</p>
<p>So we have a Jupiter notebook interface,</p>
<p>but we do have some native</p>
<p>visualizations in there</p>
<p>where you can inspect the graph.</p>
<p>Right?</p>
<p>You can see the graph schema,</p>
<p>you can explore it a little bit.</p>
<p>So we do have some</p>
<p>capabilities around that.</p>
<p>Oh, that's cool.</p>
<p>And then</p>
<p>it sounds like you geared it specifically</p>
<p>for data scientist Jupyter Notebooks,</p>
<p>very common for the data scientists</p>
<p>that are out there,</p>
<p>which then gives you, as you mentioned</p>
<p>before, on the data scientist side,</p>
<p>I have that ability</p>
<p>to write my Python scripts to</p>
<p>bring data in or traverse the traverse</p>
<p>the graph as I need to,</p>
<p>those sorts of things.</p>
<p>Is that pretty safe to say?</p>
<p>Yeah, exactly.</p>
<p>Yeah, you got it.</p>
<p>And one of the features</p>
<p>that I really like about that</p>
<p>that we just introduced was Dest data</p>
<p>frame importer.</p>
<p>So Dash is a really common</p>
<p>framework similar to Spark, right?</p>
<p>Where you can do</p>
<p>parallel processing on data frames.</p>
<p>And so data scientists are very used</p>
<p>to working with these structures.</p>
<p>And so we have a way, instead</p>
<p>of the traditional way to do this in graph</p>
<p>databases, you have to learn a complicated</p>
<p>mapping syntax,</p>
<p>right, to be able to map</p>
<p>it from relational to graph.</p>
<p>But using those data data frame,</p>
<p>the data scientists can just work</p>
<p>with the data frames they're already using</p>
<p>and then directly ingest those into</p>
<p>a ton of crap. Right?</p>
<p>So it provides this really seamless way</p>
<p>to get started using Cortana.</p>
<p>So you've simpler, you've,</p>
<p>you've radically simplified things</p>
<p>it sounds like.</p>
<p>As far for the data scientists.</p>
<p>Yeah, exactly.</p>
<p>Yeah.</p>
<p>They don't have to worry</p>
<p>about learning a new syntax,</p>
<p>they can just do data frame,</p>
<p>they can use the data frames are using it</p>
<p>and then just those.</p>
<p>Are very cool.</p>
<p>Now a lot of times and this may be off</p>
<p>subject is tell me but a lot of times</p>
<p>what I found was data scientists</p>
<p>it sounds like you are one</p>
<p>a lot of times it</p>
<p>it seems to me like data scientists</p>
<p>work on a project</p>
<p>get it all working, give the results out</p>
<p>and then they move on to the next thing.</p>
<p>And they don't really the company doesn't</p>
<p>offer really operationalized</p>
<p>is not the right word</p>
<p>operationalize that data</p>
<p>because it's it</p>
<p>I got my experiment it's done and it's out</p>
<p>but I want real time data.</p>
<p>I want this continuous thing.</p>
<p>Does this platform help with that</p>
<p>or have you guys built that in?</p>
<p>We're a I've I've got my</p>
<p>I've got my analytics all set up now</p>
<p>set it out there</p>
<p>and then when new things come in</p>
<p>tell me what's changed</p>
<p>or things like that.</p>
<p>Is that part of a platform like this?</p>
<p>Yeah, absolutely.</p>
<p>Yeah.</p>
<p>DevOps is a big part</p>
<p>of what we're trying to accomplish, right,</p>
<p>and what we're trying to facilitate</p>
<p>with our platform.</p>
<p>So, you know,</p>
<p>one of the ways that we help with that is</p>
<p>and now we can easily integrate</p>
<p>into existing machine learning pipelines.</p>
<p>Right.</p>
<p>And this is I kind of alluded this before,</p>
<p>but when we run our our</p>
<p>our machine learning,</p>
<p>our graph neural networks, right,</p>
<p>we can export the embeddings, right?</p>
<p>These are the basically features</p>
<p>we've generated from the graph</p>
<p>and we can send those to a downstream</p>
<p>machine learning process.</p>
<p>So the integration becomes a lot simpler</p>
<p>and a lot easier.</p>
<p>Production allows because you're right,</p>
<p>it's really easy to, you know, design</p>
<p>a, you know, design a model and then just,</p>
<p>you know,</p>
<p>it's it's hard to operationalize,</p>
<p>but with the way that we can figure out</p>
<p>pipelines is, you know, it's</p>
<p>a particular with fraud detection</p>
<p>like we were talking about earlier.</p>
<p>It's really easy</p>
<p>to put that into production, right.</p>
<p>It's going to easily plug into</p>
<p>whatever downstream machine learning model</p>
<p>platform you're already using.</p>
<p>Very cool.</p>
<p>So it sounds to me</p>
<p>like you guys have thought about</p>
<p>that whole experience of the data.</p>
<p>The data ops is out a word.</p>
<p>Yep. DevOps.</p>
<p>Yeah. Yeah, you got. Yeah, data.</p>
<p>It's like data data DevOps</p>
<p>data dev, data ops.</p>
<p>You know, it's</p>
<p>all it's going to be all over the place.</p>
<p>So you, you guys have built that</p>
<p>into your platform.</p>
<p>So I can I can do the work.</p>
<p>I can create these pipelines</p>
<p>that can then be deployed</p>
<p>on my live</p>
<p>data and produce value coming out.</p>
<p>That sounds like.</p>
<p>Yeah, exactly.</p>
<p>Yeah.</p>
<p>We're working with some really common</p>
<p>you know, model registry metric tracking</p>
<p>platforms that are open source</p>
<p>that you can easily integrate with.</p>
<p>So yeah, we definitely want to make it</p>
<p>as easy as possible</p>
<p>and as seamless as possible</p>
<p>to plug into those existing pipelines.</p>
<p>It sounds like,</p>
<p>why would I ever use a relational database</p>
<p>analytics platform anymore?</p>
<p>I mean, you guys have simplified</p>
<p>this quite a bit.</p>
<p>Is that is that what you said?</p>
<p>Do you do you think that I can I can move</p>
<p>away from your relational stuff?</p>
<p>Would you ever move petabytes</p>
<p>of relational data into a graph?</p>
<p>Does that make sense or not?</p>
<p>What do you think?</p>
<p>Yeah, I think it does.</p>
<p>I think there are certain things</p>
<p>when you talk about latency, right,</p>
<p>because we're we're in a analytics</p>
<p>platform.</p>
<p>Right.</p>
<p>We're really built around</p>
<p>kind of overlap functionality.</p>
<p>So certainly there'll be some,</p>
<p>some things that you'll want to do</p>
<p>a lot more in the online environment</p>
<p>that you would want to have</p>
<p>you could have a relational database for.</p>
<p>But yeah, absolutely, for all out</p>
<p>type workloads</p>
<p>where you're running these large scale</p>
<p>analytics and machine learning,</p>
<p>yeah, it makes all the sense to to do it</p>
<p>in a graph graph database because</p>
<p>even if you want to do some of these</p>
<p>other traditional machine learning</p>
<p>models, like a</p>
<p>deep, deep neural networks and lshtm</p>
<p>and all these things,</p>
<p>you can still do that</p>
<p>in our platform, right?</p>
<p>So you're not excluded.</p>
<p>You're not you're not excluded</p>
<p>from using those types of models</p>
<p>and those types of processes.</p>
<p>You're just getting the additional benefit</p>
<p>of the graph data management</p>
<p>on the backend and then also leveraging</p>
<p>some of these graph</p>
<p>deep learning frameworks.</p>
<p>So super, super cool.</p>
<p>Wow. Craig,</p>
<p>you've given us so much information.</p>
<p>It's I think it's almost overwhelming,</p>
<p>right.</p>
<p>What you guys are able to do here.</p>
<p>Where do you see five years from now?</p>
<p>Where do you see these types of platforms?</p>
<p>You see any additional</p>
<p>types of things in here besides the three</p>
<p>that you've talked about.</p>
<p>Where do you see it moving forward?</p>
<p>Yeah, that's a good question.</p>
<p>I think in terms of where I see it going,</p>
<p>you know,</p>
<p>I would envision this</p>
<p>in some of these banks that I've worked in</p>
<p>as kind of like the centralized repository</p>
<p>where you're analyzing</p>
<p>all of your customer data, for example.</p>
<p>Right?</p>
<p>Or you've got your</p>
<p>your marketing data, your credit data.</p>
<p>And you know, what we found</p>
<p>is when you run these machine</p>
<p>learning models, you can use them</p>
<p>for multiple purposes, right?</p>
<p>There's a bank out there that's done.</p>
<p>They basically ran a machine</p>
<p>learning model.</p>
<p>They built a machine learning model,</p>
<p>and they use the outputs from it</p>
<p>for both credit risk</p>
<p>and also for fraud detection.</p>
<p>Right.</p>
<p>So I think that's kind of the</p>
<p>the next level is being able</p>
<p>to really generate kind of the 360 view</p>
<p>or have it as a centralized repository</p>
<p>and then feed it out to the different,</p>
<p>you know, the different departments,</p>
<p>the different groups.</p>
<p>Right, right.</p>
<p>That's marketing or credit or,</p>
<p>you know, what, what it may be,</p>
<p>but that I think that's a big part of a.</p>
<p>That's really interesting because today</p>
<p>that would be different groups</p>
<p>that were doing that</p>
<p>and creating their own models from that.</p>
<p>So what they're saying is a mm.</p>
<p>Yeah.</p>
<p>A common model.</p>
<p>Right.</p>
<p>They, they could work off</p>
<p>of a common model in this case.</p>
<p>Yeah exactly.</p>
<p>They're using siloed datasets right there.</p>
<p>A lot of replication,</p>
<p>a lot of duplication between the groups.</p>
<p>It's mostly the same data</p>
<p>with a few extra fields,</p>
<p>but you know, you'd be able to</p>
<p>synchronize it all within a graph and run</p>
<p>all of your,</p>
<p>you know, your workloads off of that.</p>
<p>That very, very, very cool stuff.</p>
<p>Well, hey, Greg,</p>
<p>thanks for coming on the show today.</p>
<p>This has been wonderful.</p>
<p>You've opened my eyes</p>
<p>and hopefully our listeners eyes as well.</p>
<p>Yeah. Thanks, John.</p>
<p>Appreciate the opportunity.</p>
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
