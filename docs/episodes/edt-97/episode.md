---
layout: posts
title: "Put the Title Right Here"
number: 97
permalink: EDT97
has_children: false
parent: Episodes
nav_order: 97
tags:
    - EDT111
    - EmbracingDigital

date: 
guests:
    - Darren W Pulsipher

img: TBD
summary: "Summary"
---

{% include soundcloud.html id="edt97" title="#97 Put the Title Right Here" %}

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
<p>On today's episode,</p>
<p>the benefits of Graph Databases</p>
<p>with Hadi Amadi,</p>
<p>Director of Product Solutions</p>
<p>at Katana Graph.</p>
<p>Hadi, welcome to the show.</p>
<p>Thank you so much for inviting me</p>
<p>and giving me this opportunity</p>
<p>to be able to talk about this</p>
<p>interesting topic.</p>
<p>Well, it's really interesting</p>
<p>because when I first talked to you guys</p>
<p>about graph databases, I was like, yeah,</p>
<p>I know a little bit about graph databases.</p>
<p>Then you blew my head off</p>
<p>because you taught me a whole lot more</p>
<p>and what you could do.</p>
<p>But before we get into that, Haddie,</p>
<p>tell us a little tell</p>
<p>my audience a little bit about yourself.</p>
<p>Sure. Thanks.</p>
<p>Absolutely.</p>
<p>So let me actually start from a little</p>
<p>of my background and where I came from.</p>
<p>I got my peers in computer</p>
<p>science in 2012, did a lot of research</p>
<p>in cryptography, network</p>
<p>information security</p>
<p>and were in academia</p>
<p>for in a couple of years</p>
<p>after then moved the industry</p>
<p>and focused on different aspects</p>
<p>of security solutions from identity</p>
<p>and access management to other things.</p>
<p>But I think it was since 2015</p>
<p>or so that I started to learn</p>
<p>more about graph</p>
<p>data modeling, graph databases,</p>
<p>graph structure.</p>
<p>And it was interesting enough for me</p>
<p>to actually start thinking how we could</p>
<p>model some of these complex problems</p>
<p>in my field of study</p>
<p>and see whether we can benefit</p>
<p>from a graph later</p>
<p>modeling</p>
<p>and how we can possible better solve them.</p>
<p>And that was interesting enough</p>
<p>for me to be able</p>
<p>to actually do this kind of things.</p>
<p>And the results were very promising.</p>
<p>You know, I had a lot of products</p>
<p>worked on and that actually made me</p>
<p>decide, you know, I want to dedicate</p>
<p>more of my time to grasp.</p>
<p>And that's why I jumped on a graph.</p>
<p>And I'm now there as a director</p>
<p>of solution architecture and also work</p>
<p>on the product, very happy to do so</p>
<p>and trying to actually be</p>
<p>finding those interesting problems</p>
<p>that are complex enough</p>
<p>that the existing alternative</p>
<p>solutions cannot tackle.</p>
<p>And hence the graph.</p>
<p>So this is really interesting</p>
<p>because you guys are trying to</p>
<p>in some respects displace</p>
<p>a technology that's been around</p>
<p>Right.</p>
<p>Those have been around since the dawn of.</p>
<p>All. Of your data structures</p>
<p>and things like that.</p>
<p>Right. Exactly.</p>
<p>Well, let me first,</p>
<p>I know that most of you know people</p>
<p>that are probably listening</p>
<p>to our conversation already know about</p>
<p>this concept of the graph graph structure.</p>
<p>But to respect everybody</p>
<p>who might be interested in the podcast,</p>
<p>let me tell you first, what do we mean</p>
<p>when we talk graph reference?</p>
<p>Okay, that sounds great.</p>
<p>First of all, we're not really talking</p>
<p>about graphs as charts or</p>
<p>graphical interfaces or things like that.</p>
<p>Not even put that matter either.</p>
<p>A graph</p>
<p>in a way of visually visualizing data,</p>
<p>using those images that could be a side</p>
<p>benefit or some product.</p>
<p>But you're really talking about a way</p>
<p>to structure your data in a storage level</p>
<p>so that you can retrieve</p>
<p>and process this data</p>
<p>for some of the complex problems,</p>
<p>especially if this data is interconnected.</p>
<p>On that note,</p>
<p>I should say that it's not.</p>
<p>That graph is going to do the magic and</p>
<p>solve all the problems and we're not here.</p>
<p>At least that's my belief</p>
<p>that to to replace or complete</p>
<p>the existing data structures or solutions</p>
<p>is probably complementing those</p>
<p>for some of the problem</p>
<p>that they can tackle.</p>
<p>Still, if you look at the</p>
<p>some of the problems, some of the data</p>
<p>and hopefully we can talk about that,</p>
<p>the nature of the data will be in a way</p>
<p>that you could still benefit from a key</p>
<p>value datastore relational database model</p>
<p>or or object storage for that matter.</p>
<p>So it doesn't mean that graphs</p>
<p>are there to solve all the problems.</p>
<p>We really need to look at data and see</p>
<p>whether we can benefit from graphs.</p>
<p>Okay.</p>
<p>So that brings up an interesting point</p>
<p>because graph graph databases</p>
<p>are great for linkages</p>
<p>and relationships, right?</p>
<p>Yeah.</p>
<p>But isn't that a relational database?</p>
<p>I mean, the relational database</p>
<p>is all about relationships.</p>
<p>Has it has it in its own right?</p>
<p>It has it in its term.</p>
<p>So what's the key</p>
<p>differentiator differential here?</p>
<p>I know relational databases.</p>
<p>I've got a table, I've got you know, I can</p>
<p>relate from one table to another table.</p>
<p>So what's the key differentiator?</p>
<p>Differentiator here? Fair enough.</p>
<p>Now that's very valid.</p>
<p>Very good question.</p>
<p>I'm glad that you asked that.</p>
<p>Yeah, you're right.</p>
<p>And relational databases are all also</p>
<p>about respecting relationships.</p>
<p>The main difference</p>
<p>is that in relational databases,</p>
<p>we actually took this relationship,</p>
<p>the metadata level and the schema level</p>
<p>browsing graph database is going to be</p>
<p>data driven relationships.</p>
<p>So relationships are going to be part</p>
<p>of the data</p>
<p>versus part of the relational side.</p>
<p>So in other words,</p>
<p>in relational databases, we are letting</p>
<p>tables, columns off the tables basically.</p>
<p>And if you want to introduce</p>
<p>a new relationship, basically,</p>
<p>you need to change a schema in a way.</p>
<p>Whereas Graph provides</p>
<p>this code on clothes schema</p>
<p>less infrastructure</p>
<p>for you to be able to actually add</p>
<p>a little bit of more structure</p>
<p>around your data, but still be flexible</p>
<p>so you can ingest any sort of unstructured</p>
<p>data as well.</p>
<p>Okay.</p>
<p>So it's great at unstructured data coming</p>
<p>in and seamless, which means great for</p>
<p>crave for data.</p>
<p>I don't quite know what the schema is yet.</p>
<p>Right.</p>
<p>So I can see</p>
<p>I can see those those benefits of.</p>
<p>But isn't</p>
<p>everything already stored in a database.</p>
<p>It is.</p>
<p>No, absolutely.</p>
<p>It's just a fact that, again,</p>
<p>the main risk that</p>
<p>you're not facing is big computation.</p>
<p>So we have had a conversation</p>
<p>around big data</p>
<p>for a long while and that thanks</p>
<p>to a lot of technology,</p>
<p>basically that has been has been built</p>
<p>and provided</p>
<p>within the last few years,</p>
<p>we have been able to collect a lot of data</p>
<p>from different sources.</p>
<p>So more than half of the world's</p>
<p>data has been created</p>
<p>within the last couple of years,</p>
<p>but only. At.</p>
<p>Less than 2% of it has been analyzed,</p>
<p>which means that, again,</p>
<p>thanks to those data</p>
<p>like sort of experiences,</p>
<p>you can slowly collect data, however,</p>
<p>and then it gets to processing.</p>
<p>That data is not enough.</p>
<p>It can do</p>
<p>so you want to have a way to flexibly</p>
<p>add a little bit of a structure</p>
<p>to this data, not really much.</p>
<p>And it's dynamic enough that you can</p>
<p>easily change it if you're uncertain.</p>
<p>What still benefit</p>
<p>from optimized advanced computation on it</p>
<p>and graph is an excellent way to do so.</p>
<p>So with only 2%</p>
<p>of the data being analyzed,</p>
<p>most of that data analyzes structured data</p>
<p>today.</p>
<p>Right? Yeah.</p>
<p>But what percentage is that</p>
<p>unstructured data</p>
<p>that that's sitting out there</p>
<p>have all this new data being generated?</p>
<p>Yeah, it's a very valid question</p>
<p>and a very good question.</p>
<p>I don't really know the exact,</p>
<p>you know, basically fraction of that data,</p>
<p>but assume that all of that unstructured</p>
<p>data now is is being tackled</p>
<p>using low level APIs of the data</p>
<p>like experience, which works excellent.</p>
<p>But the problem is</p>
<p>it lacks the optimization</p>
<p>because if you deal with on a structured</p>
<p>low level data, you can't really do</p>
<p>any sort of independent.</p>
<p>Okay.</p>
<p>So how does how does graph database</p>
<p>help with that unstructured data or</p>
<p>give it give us some examples.</p>
<p>Yeah, no, fair enough.</p>
<p>So as I said before, again,</p>
<p>the let me let me start with this again.</p>
<p>I would love to just make sure that I stay</p>
<p>fair with this concept that, hey,</p>
<p>if you do have a data that or a problem</p>
<p>deals with data that's that's isolated.</p>
<p>I mean, you have a bunch of a key values</p>
<p>documents you want to store and retrieve.</p>
<p>You don't really need graph</p>
<p>if you of your use.</p>
<p>This is all about storing data</p>
<p>lots of storage.</p>
<p>You could use</p>
<p>an object solution with that.</p>
<p>But if you you're actually trying to work</p>
<p>with correlated data, interconnected</p>
<p>data, that's where you would benefit</p>
<p>from graph because of the relationships.</p>
<p>And this comes almost in any industry</p>
<p>because the</p>
<p>the unstructured data</p>
<p>usually comes from a variety of sources</p>
<p>and variety of structure</p>
<p>or I should say natures.</p>
<p>And when I can give an example</p>
<p>that I may be more versatile</p>
<p>as let's say we want to go and do</p>
<p>cyber security solutions,</p>
<p>looking at the logs and audit trails</p>
<p>that come from the network</p>
<p>environments, the cloud infrastructure,</p>
<p>the end point hosts</p>
<p>and all that, and these are all coming</p>
<p>from different sources.</p>
<p>The data is different.</p>
<p>Some of them are coming from directories,</p>
<p>some from raw log files and so on</p>
<p>and so forth.</p>
<p>And we would like to have a way to be able</p>
<p>to correlate the data because typically</p>
<p>an identity or a user</p>
<p>that could be part of a log</p>
<p>that comes from our identity</p>
<p>management system could be the same user</p>
<p>that triggers a process in a laptop</p>
<p>or maybe downloads</p>
<p>an attachment from an email</p>
<p>and then out of that.</p>
<p>So if you can actually use</p>
<p>the correlational linkage between</p>
<p>this data, you can get more insight</p>
<p>from it by just analyzing those patterns.</p>
<p>So this is what I'm trying to say.</p>
<p>It doesn't matter</p>
<p>how or where your data is coming from,</p>
<p>but providing that sort of linkage</p>
<p>between these data points,</p>
<p>you will be able to learn more about each</p>
<p>and every record</p>
<p>by looking at the context of them.</p>
<p>So I like the context part of part of this</p>
<p>because that's where I can really start</p>
<p>looking at real data analytics,</p>
<p>where did my data come from?</p>
<p>What else is it related to?</p>
<p>I love the example of an email because</p>
<p>I can't imagine</p>
<p>building a relational database</p>
<p>that shows an email.</p>
<p>Well, I mean, that would be really hard</p>
<p>because, oh,</p>
<p>I've got attachments to it,</p>
<p>I've got responses, I've got for my data.</p>
<p>Tables would be massive</p>
<p>and there would be so many of them to show</p>
<p>all the different relationships.</p>
<p>Yeah.</p>
<p>So, so in graph databases</p>
<p>I can form these relationships</p>
<p>dynamically as,</p>
<p>as my data structures are dynamic.</p>
<p>Is that.</p>
<p>Is that right. Absolutely.</p>
<p>Make it</p>
<p>maybe even to make it more sort of bold</p>
<p>as you know,</p>
<p>if you have a problem anywhere</p>
<p>and you think you can just go to a</p>
<p>whiteboard and just model your data with,</p>
<p>you know,</p>
<p>just some hyper friendly sort of notes</p>
<p>that are connected with edges,</p>
<p>then it seems like it can benefit</p>
<p>from a graph that you don't want</p>
<p>to downgrade that model.</p>
<p>You have in mind to tackle,</p>
<p>but just, you know, make it a</p>
<p>two dimensional data</p>
<p>structures, tables and rules and columns.</p>
<p>You would actually be able to store</p>
<p>it as is</p>
<p>I emphasize</p>
<p>as is the graph data structure.</p>
<p>So one it.</p>
<p>Yeah no I like that.</p>
<p>I like that a lot</p>
<p>so I can see one of the benefits.</p>
<p>One is</p>
<p>I don't have data transformation issues,</p>
<p>so that's going to speed up things</p>
<p>dramatically.</p>
<p>Right, because I'm not trying to represent</p>
<p>complex relationships</p>
<p>in several tables,</p>
<p>so I'm decreasing also the</p>
<p>storage requirements, right?</p>
<p>That is correct.</p>
<p>That is correct.</p>
<p>I mean, it would be one of those,</p>
<p>you know,</p>
<p>double resource</p>
<p>that depending on how you model data,</p>
<p>but you're right</p>
<p>that, you know, let let me just maybe</p>
<p>talk about this social network</p>
<p>because that's very easy.</p>
<p>Oh, social network.</p>
<p>That's a great. One. Yeah.</p>
<p>So to me,</p>
<p>if we want to make it very simplistic,</p>
<p>the graphs and relational databases</p>
<p>or relational database function in general</p>
<p>are very compatible.</p>
<p>The no types look like the tables.</p>
<p>So I have a node, cyber sibeko</p>
<p>that's a person.</p>
<p>And then I could have a table called</p>
<p>personal relational.</p>
<p>That is great.</p>
<p>I might have another.</p>
<p>No talk call location and connect</p>
<p>my person to specific location.</p>
<p>Of course I can have a table call location</p>
<p>and connect them to foreign keys.</p>
<p>Awesome.</p>
<p>Now I have this</p>
<p>relationship of friendship.</p>
<p>A friend person is a friend of person</p>
<p>in my graph model is just so loop</p>
<p>kind of thing, right?</p>
<p>That would allow me to just model</p>
<p>that schema if I want to.</p>
<p>In in a relational database,</p>
<p>I need to create</p>
<p>this new table for friends</p>
<p>and then I need to connect it.</p>
<p>So even at the schema level, I'm</p>
<p>adding some redundancy and some structure</p>
<p>over the top of it.</p>
<p>And if I need to add a new concept</p>
<p>of friendship or relationship,</p>
<p>I need to create new tables. Yeah.</p>
<p>So that is the redundancy of complexity.</p>
<p>So hey, you're right.</p>
<p>And it does add a lot of complexity</p>
<p>on traversing tables to get information</p>
<p>on maintenance, management,</p>
<p>building indices.</p>
<p>All that stuff now becomes more complex</p>
<p>the more relationship of tables</p>
<p>that I have.</p>
<p>So I really kind of</p>
<p>I like this a lot in that what,</p>
<p>what other benefits do I get from a graph</p>
<p>database over relational?</p>
<p>Yeah.</p>
<p>The one other thing about graph databases</p>
<p>is this whole area of graph on elements</p>
<p>in the graph.</p>
<p>I, I'm not going to go into details</p>
<p>of those things.</p>
<p>And basically</p>
<p>the idea of being able to now model</p>
<p>your data and be able to find patterns</p>
<p>on your data based on that.</p>
<p>The way that data is connected is great.</p>
<p>An example could be PageRank</p>
<p>algorithm, which is put forth by Google</p>
<p>to be able to actually now</p>
<p>sort the the pages that have been searched</p>
<p>over time.</p>
<p>You know, what is the most linkages</p>
<p>to the page and all that?</p>
<p>So once you have a data model as a graph,</p>
<p>then you can simply go on a page</p>
<p>like algorithm across a graph</p>
<p>and find a rank for each</p>
<p>and every note based on</p>
<p>how they are connected to the others.</p>
<p>The other example,</p>
<p>to be finding the components.</p>
<p>So you have this this big data, you don't</p>
<p>you have a problem to solve.</p>
<p>You don't know how to tackle this</p>
<p>in a relational database,</p>
<p>but if your data was in the graph,</p>
<p>the one thing that you could do</p>
<p>possibly can make sense depending on</p>
<p>your problem would be to divide</p>
<p>and conquer, to use a connected component</p>
<p>sort of algorithm</p>
<p>with some sort of community</p>
<p>detection algorithm on the graph</p>
<p>to be able to try to get off the sub</p>
<p>graphs, which are our focus.</p>
<p>And then you could go</p>
<p>and look at a specific subgroup</p>
<p>of certain size</p>
<p>and be able to solve your problem.</p>
<p>That is specific.</p>
<p>Some graph that's normal.</p>
<p>So you're how help me understand</p>
<p>what I think I heard was</p>
<p>I can decrease the data set</p>
<p>that I am searching through or analyzing</p>
<p>because of the relationships I can I can</p>
<p>prune things down to a more substantial</p>
<p>set instead of searching everything.</p>
<p>Exactly. Exactly. It's like that's.</p>
<p>Using the the power of data</p>
<p>to even in our data in order</p>
<p>this is connected performance</p>
<p>and things like that would be even looked</p>
<p>at as</p>
<p>ways of doing feature engineering</p>
<p>for our email layer</p>
<p>where you can take advantage of it.</p>
<p>And this information</p>
<p>may not be explicitly given</p>
<p>by a relational or any sort of data,</p>
<p>but it can be found using some sort of</p>
<p>graph mining data mining your data.</p>
<p>So, so the algorithms in a graph database</p>
<p>are very different than the algorithms</p>
<p>that we've seen in relational databases</p>
<p>that so and better optimize you think,</p>
<p>oh I can get,</p>
<p>I can get to large sets of data faster.</p>
<p>Absolutely.</p>
<p>I mean better optimized for those.</p>
<p>Again, for the purpose of data.</p>
<p>I mean, if you're talking about</p>
<p>graph algorithm, which is about,</p>
<p>you know, that first search,</p>
<p>you need a graph in the structure</p>
<p>if you want to use a relational data</p>
<p>or anything else, that would be to.</p>
<p>Let's say that I just had</p>
<p>one big table and I'm just doing raw</p>
<p>searches for I need</p>
<p>I need everyone with this zip code.</p>
<p>A relational database</p>
<p>would probably be the way to go.</p>
<p>Absolutely.</p>
<p>I mean, if those are the queries</p>
<p>that you want to get, that would be.</p>
<p>But if you're in the realm of,</p>
<p>let's say, manage massive data management</p>
<p>for some sort of entity,</p>
<p>basically entity resolution,</p>
<p>those kind of things that actually would</p>
<p>benefit from a modeling your data in a way</p>
<p>that you can actually find patterns</p>
<p>and patterns between different entities.</p>
<p>Then relational database</p>
<p>can help you in a scalable right.</p>
<p>And again, I'm saying.</p>
<p>In a scalable.</p>
<p>Way, you can definitely model anything</p>
<p>that today we have in a graph database</p>
<p>with a relational data structure</p>
<p>and vice versa.</p>
<p>It's all about when data skills,</p>
<p>one of them can't keep up.</p>
<p>Gotcha.</p>
<p>So let's talk about scale a little bit.</p>
<p>When you say scale,</p>
<p>I mean, how big are we talking?</p>
<p>I mean, in relational databases,</p>
<p>we talk about number of rows.</p>
<p>Yeah. Right.</p>
<p>That would be comparable</p>
<p>to number of nodes in a</p>
<p>in a graph database, correct.</p>
<p>Pretty much, yes.</p>
<p>You're right.</p>
<p>The number of nodes</p>
<p>for that give you actually a number</p>
<p>of those times</p>
<p>the tables in a relational database.</p>
<p>Plus you do have</p>
<p>the relationships here as well</p>
<p>that could add to the complexity of this.</p>
<p>So how big can these graphs get.</p>
<p>That that's also a very great question</p>
<p>because again, the way that graphs work</p>
<p>or this graph it is the structure</p>
<p>makes it a bit hard to scale and chart</p>
<p>a relational database.</p>
<p>It's easy to cut a table</p>
<p>and put it on two servers.</p>
<p>Right.</p>
<p>And that would allow you</p>
<p>to be able to more.</p>
<p>I would say intuitively, partition</p>
<p>your data and go with your scalability</p>
<p>beyond a specific basically</p>
<p>one server</p>
<p>so you can go with much, much bigger data.</p>
<p>And that that's that that has been</p>
<p>one of the drawbacks of the graph data</p>
<p>or earlier graph database technologies</p>
<p>that they were all</p>
<p>actually designed</p>
<p>or built to be a single whole solution.</p>
<p>So you have a bigger graph</p>
<p>if you want to have a bigger,</p>
<p>you know, make it</p>
<p>even bigger, you need to scale</p>
<p>up, add more memory or more CPU too.</p>
<p>Yeah, we yeah, we like it</p>
<p>when they have more CPU's</p>
<p>and maybe some persistent memory</p>
<p>from Intel.</p>
<p>There's that would be great.</p>
<p>It's just awesome and that's great.</p>
<p>But I can't scale to that</p>
<p>to buy it right. Now.</p>
<p>If you do have that,</p>
<p>you know you get definitely it still</p>
<p>you want to vertically scale</p>
<p>as much as possible</p>
<p>thanks to the technologies</p>
<p>like Intel VMs and all that.</p>
<p>But then once you get to basically</p>
<p>a place that you want to actually work</p>
<p>with petabytes of data,</p>
<p>then you would want to scale horizontally</p>
<p>and the new technologies</p>
<p>on the on the graphic to platforms</p>
<p>like ourselves</p>
<p>are actually all about distributed</p>
<p>computing.</p>
<p>And distributed</p>
<p>computing is basically allowing us to now</p>
<p>short the graph, basically just look out,</p>
<p>you know,</p>
<p>in terms of just using a scissor</p>
<p>and cutting the grass and multiple pieces</p>
<p>and just make sure those edges</p>
<p>of those linkages are kept a preserve.</p>
<p>And then you can split or the problem</p>
<p>into multiple small pieces</p>
<p>and have each graph</p>
<p>work up a small part of the graph</p>
<p>and give you the final solution.</p>
<p>Okay.</p>
<p>So there are so this is</p>
<p>this is a new things very distributed</p>
<p>distributed graph databases</p>
<p>because</p>
<p>I like how you mentioned that</p>
<p>that has been a limitation in the past.</p>
<p>Right.</p>
<p>A graph database can only be as big as</p>
<p>the amount of memory you have on your box.</p>
<p>Basically, which makes some screaming</p>
<p>fast, write very things in memory.</p>
<p>But now you're now you're saying</p>
<p>they do have distributed techniques.</p>
<p>Now I can.</p>
<p>So how big</p>
<p>can I make a distributed graph now?</p>
<p>Is there any limitation.</p>
<p>From our technology or what</p>
<p>I can say we have proven like, you know,</p>
<p>you could use 256 machines or beyond</p>
<p>to be able to actually process your data.</p>
<p>So if you multiply by those, it's</p>
<p>arbitrary.</p>
<p>You can easily get</p>
<p>to tens of terabytes of data in memory.</p>
<p>Yeah, yeah.</p>
<p>Tens of petabytes. Yeah.</p>
<p>That's a lot of data.</p>
<p>That's right.</p>
<p>And all in one go all connect.</p>
<p>That's in that's incredible. Yeah.</p>
<p>That's absolutely</p>
<p>because that, that actually matches</p>
<p>some of the existing requirements</p>
<p>that we have from graph</p>
<p>that are dealing with, you know, daily</p>
<p>collecting logs, data and being able</p>
<p>to analyze it and bring it back</p>
<p>to the downstream systems.</p>
<p>The usually atomized data,</p>
<p>especially for the companies</p>
<p>that provide SAS solutions</p>
<p>to their customers</p>
<p>and they want to have across</p>
<p>customer analytics</p>
<p>that's really very popular.</p>
<p>So the users.</p>
<p>RDR, our</p>
<p>DB CMS has been around a long time,</p>
<p>a lot of tools around backup</p>
<p>and restore on</p>
<p>managing indexes</p>
<p>and in purging parts,</p>
<p>you know, cleaning of database.</p>
<p>All this has been around for a long time.</p>
<p>What about for graph databases?</p>
<p>Do I have the same issues</p>
<p>or is it different</p>
<p>because it's stored differently</p>
<p>because you're storing the model</p>
<p>instead of a representation of the model?</p>
<p>I mean, what's built up around it?</p>
<p>And do I need an ecosystem like I've had</p>
<p>to build with relational databases?</p>
<p>Yeah, pretty much similar.</p>
<p>Maybe graph is a little bit more dynamic</p>
<p>and might be a little more flexible</p>
<p>to tackle, but I would say that we do if</p>
<p>if you are providing graph database</p>
<p>management system,</p>
<p>you would need to go through</p>
<p>the same process very much like data is.</p>
<p>And thankfully</p>
<p>those have already been resolved</p>
<p>now. Okay.</p>
<p>If you want to move to</p>
<p>graphs data analytics platform,</p>
<p>which is beyond</p>
<p>just the operational databases,</p>
<p>you could take advantage of other things</p>
<p>like data warehousing capabilities, data,</p>
<p>native communities.</p>
<p>You know, one of them</p>
<p>would be just a storage of separate</p>
<p>the separation of the storage and compute,</p>
<p>meaning that especially</p>
<p>for those graph processing technologies</p>
<p>that are doing everything in memory</p>
<p>don't really need to rely on storage</p>
<p>that is attached to the services.</p>
<p>So you can have a totally different</p>
<p>storage service.</p>
<p>What we use, for example, is object</p>
<p>storage and then we want to compute.</p>
<p>We opportunistically load whatever we want</p>
<p>from the graph to the memory,</p>
<p>distributed memory of all those machines.</p>
<p>There's a computation, bring the data</p>
<p>back in immutable way of the storage.</p>
<p>So in that case,</p>
<p>even if you destroy the whole cluster</p>
<p>and that's something that you would see</p>
<p>data scientist,</p>
<p>the analytics use cases are a lot.</p>
<p>You don't lose anything.</p>
<p>All your data is already there</p>
<p>warehouse and you just need to actually</p>
<p>be able to run that you will.</p>
<p>Got to know that.</p>
<p>So what you're telling me</p>
<p>is all the things that I can find in</p>
<p>relational databases,</p>
<p>analytics packages, backup and restore</p>
<p>maintenance, all that stuff exists</p>
<p>for graph databases too.</p>
<p>Is that okay?</p>
<p>So I'm not I'm not bleeding bleeding edge</p>
<p>out here</p>
<p>where I'm all alone and I have no support.</p>
<p>There's lots of</p>
<p>there's open source graph databases</p>
<p>and there's commercial ones.</p>
<p>There's,</p>
<p>there's more than just one out there.</p>
<p>But again, we could talk about this things</p>
<p>and these are all valid concerns</p>
<p>because as you said,</p>
<p>the relational database with others,</p>
<p>these are mature fields and ground</p>
<p>is a bit newer.</p>
<p>But one thing is absolutely</p>
<p>some of this needs to be tackled.</p>
<p>One of the other limitations</p>
<p>that I should say</p>
<p>that people mentioned about graph data</p>
<p>and these tools is about the language,</p>
<p>lack of standard language to fully grasp</p>
<p>and is on the way to go.</p>
<p>Now, open software is a de facto</p>
<p>standard way of talking to graph.</p>
<p>It's it's</p>
<p>very slow like a SQL, I would say,</p>
<p>but definitely more intuitive for graphs.</p>
<p>And then</p>
<p>we are on the horizon to see a Google,</p>
<p>which is a graph</p>
<p>which is going to be a standard one</p>
<p>which is, you know,</p>
<p>pretty much basically deciphered.</p>
<p>So, so soon enough we're going to see</p>
<p>really standard language</p>
<p>to be able to talk the graphs.</p>
<p>Oh, that would be great,</p>
<p>because then I have that portability</p>
<p>that I worry about, right,</p>
<p>as a practitioner.</p>
<p>So SQL statement, has anyone written</p>
<p>and asked you all the graph.</p>
<p>Oh interesting.</p>
<p>Non no.</p>
<p>Of what you know there is</p>
<p>graphs fill in a graph</p>
<p>like school statements or this is.</p>
<p>Well some of them won't make sense.</p>
<p>Yeah exactly.</p>
<p>Like join.</p>
<p>I'm going to join. What.</p>
<p>No there aren't tables.</p>
<p>There aren't tables to join.</p>
<p>Yeah it should be an easy task.</p>
<p>But if you do have the graph, I would say</p>
<p>if you do have the graph capabilities,</p>
<p>you want benefits from them,</p>
<p>you don't want to downgrade your income.</p>
<p>You don't want to downgrade.</p>
<p>Yeah, yeah, yeah.</p>
<p>But on the service layer, I've seen a lot.</p>
<p>I mean, now there's this graph tool,</p>
<p>basically framework</p>
<p>and we allow us to connect to any sort</p>
<p>of relational document or graphing</p>
<p>and basically that might be able</p>
<p>to provide an API</p>
<p>and and graph actually is doing a good job</p>
<p>and it's based on a graph data</p>
<p>back can like can work for anything.</p>
<p>So that would be probably a very nice they</p>
<p>have to do this interfaces some of this.</p>
<p>Oh this has been insightful I like because</p>
<p>this is a big conundrum</p>
<p>for a lot of people,</p>
<p>especially as our data is exploding,</p>
<p>especially unstructured or semi-structured</p>
<p>data.</p>
<p>Sounds like graph</p>
<p>databases is a good way to go,</p>
<p>but like you said, not for everything.</p>
<p>So do you.</p>
<p>Do you ever see anyone maybe going</p>
<p>to a graph database first and then saying,</p>
<p>hey, I understand the structure</p>
<p>well enough, I'm going to drop it into</p>
<p>a relational database for index</p>
<p>speed and things like that</p>
<p>or how do you see it?</p>
<p>I think I think everybody that well,</p>
<p>this is based on my view and little or</p>
<p>no sign of the new,</p>
<p>I'll get 100% certainty in my view.</p>
<p>But based on my I would say about a year</p>
<p>being experienced in the field and talking</p>
<p>to some stakeholders and customers,</p>
<p>people that</p>
<p>use graphs to immediately</p>
<p>see the benefit they don't want to draw.</p>
<p>The main reason that they may drop</p>
<p>it is because some of the technologies</p>
<p>cannot keep up in terms of scalability</p>
<p>and or maybe they're just expensive.</p>
<p>So the work that some of the other graph</p>
<p>technology out there is doing is</p>
<p>try to make graphs</p>
<p>more like very commodity tool</p>
<p>that people can use for different things</p>
<p>rather than luxuries in that database.</p>
<p>Gotcha. Yeah.</p>
<p>Like I'm only targeting it to this problem</p>
<p>because it's perfect for graph.</p>
<p>The cost benefits are huge.</p>
<p>So I see where you're going.</p>
<p>You want to make it more commonly used.</p>
<p>That makes. Sense. Yeah.</p>
<p>And I'm, I'm working with companies now.</p>
<p>We're actually providing</p>
<p>graph based solutions.</p>
<p>Everything is graphs</p>
<p>and graphics solutions for identity,</p>
<p>for massive data management and all that.</p>
<p>And they see the benefits immediately</p>
<p>that they can easily downgrade</p>
<p>back to the version of news.</p>
<p>And that again, I'm not saying that</p>
<p>these are replacing each other</p>
<p>is that maybe it's still relational data.</p>
<p>Is it going to be used for some purposes,</p>
<p>but not for the problems</p>
<p>that necessarily</p>
<p>deal with interconnectivity.</p>
<p>Now that that makes sense?</p>
<p>I mean, that makes some sense.</p>
<p>So this</p>
<p>this will cover almost any vertical I can.</p>
<p>I can see applications, especially for Iot</p>
<p>types of devices. Right.</p>
<p>So we can see this span of verticals.</p>
<p>Well, what would you say are the hottest</p>
<p>the hottest use case,</p>
<p>the hottest verticals right now</p>
<p>that you guys are seeing</p>
<p>the most traction? Yeah, definitely.</p>
<p>I mean, graph in general</p>
<p>started from those,</p>
<p>I would say early invention of graph</p>
<p>solutions specific to some products,</p>
<p>you know, companies</p>
<p>like LinkedIn and Facebook,</p>
<p>they have their own social graphs</p>
<p>and all that</p>
<p>more textbook.</p>
<p>Now, you know, a very good example</p>
<p>could be in e-commerce, right</p>
<p>on the problem of recommendation</p>
<p>engine, basically.</p>
<p>I'll recommend. It. Yeah.</p>
<p>I mean, this is huge because</p>
<p>just to look at it again,</p>
<p>I try to just imagine my mind.</p>
<p>I'm going to work around and try</p>
<p>to actually now abstract this problem.</p>
<p>What I'm talking about,</p>
<p>I'm talking about customers accounts,</p>
<p>purchases of products and services</p>
<p>and other things, right?</p>
<p>And as soon as I actually can find</p>
<p>this connection</p>
<p>between them</p>
<p>and how customers do some actions,</p>
<p>maybe they review a product, a purchase,</p>
<p>and they click on a link.</p>
<p>And if I can have this basically graph</p>
<p>made based on this</p>
<p>behavior</p>
<p>of the customers that I can easily now</p>
<p>look at a specific customer</p>
<p>that now has signed into my</p>
<p>e-commerce website and look</p>
<p>what attributes they have, what kind of,</p>
<p>you know, purchases they've done before,</p>
<p>what other customers are similar to you.</p>
<p>But just finding this patterns</p>
<p>of traversing to the graph</p>
<p>and what customer to the others</p>
<p>on all the similarity measures</p>
<p>and then be able to provide</p>
<p>the recommendation</p>
<p>right away to that customer.</p>
<p>So this is something that, again,</p>
<p>you couldn't do it with any single</p>
<p>data store graph.</p>
<p>That's so it's great.</p>
<p>It's great for like real time</p>
<p>relationships reversing.</p>
<p>I love that. Right.</p>
<p>Because otherwise can you imagine</p>
<p>the the relational database queries</p>
<p>on one on that you'd be hitting</p>
<p>all the tables in in your e-commerce.</p>
<p>Yeah.</p>
<p>And the joins would be extraordinary</p>
<p>and it wouldn't be in seconds</p>
<p>it would be in minutes</p>
<p>if. You were like. Exactly.</p>
<p>Especially in this case,</p>
<p>you already have a starting point.</p>
<p>This means that look at you</p>
<p>have your your your source</p>
<p>and possibly going to,</p>
<p>you know, maybe you're looking</p>
<p>how to work from that source</p>
<p>and find some destination packet there.</p>
<p>Yeah.</p>
<p>In relation to this, this problem</p>
<p>is not really meant to be solved that way</p>
<p>and graph is just walking with the graph.</p>
<p>Simple.</p>
<p>That's walking.</p>
<p>Yeah.</p>
<p>Walk in the graph</p>
<p>which which I really like a lot.</p>
<p>Well a howdy this has been great.</p>
<p>Thank you for coming on the show.</p>
<p>I, I learn a lot every time I talk to you.</p>
<p>I learn something new, which I appreciate</p>
<p>and and thank you for coming on the show</p>
<p>also.</p>
<p>Well, thank you so much for again</p>
<p>inviting me to this podcast,</p>
<p>having this conversation.</p>
<p>It was lovely, having a chat with</p>
<p>you also learned a lot from</p>
<p>from your comments and your feedback.</p>
<p>Any time, you know,</p>
<p>I'll I'll be happy to help anybody</p>
<p>that is interested about this council</p>
<p>and also learn more about</p>
<p>great.</p>
<p>If you guys want to find out more on</p>
<p>how to contact Hadi,</p>
<p>take a look at our blog</p>
<p>at embracingdigital.org</p>
<p>and we'll have we'll have an email address</p>
<p>up there.</p>
<p>Is that okay, Hadi? My pleasure.</p>
<p>All right.</p>
<p>There you go.</p>
<p>Thank you for listening</p>
<p>to Embracing Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcasting site or YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>and embracingdigital.org next</p>
<p>time, Go out and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
