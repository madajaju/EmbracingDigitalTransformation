---
layout: posts
title: "2022 Year In Review"
number: 117
permalink: EDT117
has_children: false
parent: Episodes
nav_order: 117
tags:
    - 2022
    - EDT117
    - EmbracingDigital
    - Edge Computing
    - AI
    - Hybrid Workspace
    - Multi-Cloud
    - Cybersecurity
    - Data Management

date: 2023-01-05
guests:
    - Darren W Pulsipher

img: thumbnail.png
summary: "In this episode Darren reviews 2022. He identifies the most talked about topics on the podcast in 2022 including Data Management, Artificial Intelligence, Cyber Security, Edge Computing, and Hybrid Workspaces. "
---

{% include soundcloud.html id="edt117" title="#117 2022 Year In Review" %}

{% include youtube.html id="lxRMINWH48g" %}

---

2022 was a banner year for embracing digital transformation, with an uptick in listeners and several external guests interviewed this year. Eight guests were executives or former executives of government agencies and private sector organizations, including finance, manufacturing, and healthcare. In over 60 episodes, six topics emerged as necessary to our listeners and in the industry as a whole, namely: Hybrid workspaces, cybersecurity, multi-hybrid cloud, edge computing, data management, and artificial intelligence.

# Hybrid Workspace

After fighting COVID restrictions and keeping companies running in 2020 and 2021, organizations looked at optimizing the “New Normal” operating mode. This new normal decreased the bureaucratic impediments of pre-COVID days. However, controls and processes around the rapid pace of change during the pandemic to control costs and improve reliability began to emerge. Companies struggled with remote work policies as we saw organizations quickly switch between work-at-home, hybrid work, and everyone-in-the-office approaches, leaving IT organizations with complex workspace solutions. They began to develop architectures that could handle rapid change and flexible working models to handle constantly changing policies. Are flexible hybrid workspaces here to stay? Only the next couple of years will tell.

# Multi-Hybrid Cloud

Another big trend in 2022 was the migration and the repatriation of workloads to and from the cloud as organizations scammer to provide hybrid workspaces for their employees. IT organizations began to look at the operational costs of running and migrating workloads to the cloud. Many organizations found the lift and shift methodology of moving to the cloud was much more costly than initially estimated due to a lack of requirements gathering, understanding of cloud operating models, and understanding primarily egress network costs in the cloud.

The rapid adoption of the cloud during the pandemic left many global cloud service providers flat-footed in providing the high-reliability organizations required, overwhelming several cloud service providers and causing significant outages across the global CSP ecosystem. Many organizations started looking at multi-hybrid cloud architectures to improve reliability, decrease cost, and increase the predictability of workloads running across multiple private and public clouds. Regional cloud service providers took advantage of the stumble of the global cloud service providers. They provided higher reliability and boutique services in the SaaS and PaaS cloud offerings, competing head-to-head with the larger CSPs.

# Edge Computing and Industry 4.0

Industry 4.0 continue to make inroads into manufacturing and has a worker shortage force the hands of many organizations to look to automation to continue their operations. Additionally, OT and IT data began converging as organizations looked to optimize their business and operational processes. Advancements in CPU and storage technology moved more computing to the edge, making edge devices more intelligent and capable of performing tasks previously done in the data center. Connectivity between edge devices, data centers, and public clouds improved with the adoption of private 5G technologies across the sector. However, adoption still needs to catch up to previous predictions due to concerns about OTC cybersecurity. This is especially true around critical infrastructure management.

# Data Management

Hybrid workspaces, cloud adoption, and edge computing have created a data management nightmare for most organizations as their data has been spread across these somewhat disconnected and distributed environments. to manage data across this ecosystem effectively, new architectures began to emerge, including data mesh, distributed data lakes, and data networks. Organizations began to focus on four key data elements: location, classification, governance, and protection.

Privacy laws and regulations are driving organizations to correctly classify their data to protect the privacy of employees, customers, and constituents. Additionally, an uptick in cyber and ransomware attacks has forced organizations to better protect and govern their data in use, at rest, and in transit. Effectively managing who has access, how long they have access, and how long data resides is a critical element of data governance that organizations are beginning to understand.

# Cyber Security

2022 was a big year for cyber security, and it showed in the podcast with over 18 episodes talking about cybersecurity. The year’s big buzzword was zero trust architecture, which has been turned into an overused marketing term. Instead of focusing on zero-trust architecture, Darren tends to concentrate on zero-trust principles that architectures can support.

Even with an increased emphasis on cybersecurity, there were primary data and infrastructure breaches this year, including critical infrastructure attacks. Many cyber professionals attribute this uptick to the war between Ukraine and Russia, as we saw the effectiveness of cyber warfare and physical warfare working in conjunction.

Another central concern in cybersecurity concerns the exposure of third-party software across the application ecosystem (log4J vulnerability). Many organizations need help finding direction due to the widely used log4J in their product offerings, back-office processing, and customer interfaces. A significant push for standardized software bill of materials to help identify vulnerabilities in software packages is being driven by several organizations and governments.

# Artificial Intelligence

Artificial intelligence continues to make improvements in techniques and operational processes. The big AI news of the year was ChatGBT, which has a wide range of uses, including writing blog posts, code, and papers and aiding IT help desk problems. Additionally, adopting AI silicon chips in the cloud service providers has expanded the availability of AI to the masses. This availability allows organizations to experiment more with AI algorithms in their day-to-day business operations. Organizations are starting to operationalize some of these experiments to run and automate processes previously performed by employees that are hard to find in a tight job market.

# Conclusion

2022 was a rough year for many tech companies as we saw a decrease in IT spending over the previous “pandemic years of spending.” This expected downturn surprised many high-tech companies with how quickly things changed. Despite the downturn, technology continued to grow, and the adoption of new technologies in edge, cloud, AI, data management, and cybersecurity continues to grow. 2023 should be an exciting year as we see the maturation of some of these technologies. Organizations will continue investigating ways to decrease costs through automation, optimizing workloads across multi-hybrid clouds, and protecting against increased cyber security threats.

[![Youtube Video](https://img.youtube.com/vi/lxRMINWH48g/maxresdefault.jpg)](https://www.youtube.com/watch?
v=lxRMINWH48g)

<video src="https://youtu.be/lxRMINWH48g"></video>


<details>
<summary> Podcast Transcript </summary>

<p>﻿1</p>
<p>On today's episode,</p>
<p>a look back at 2022.</p>
<p>Hey, today it's just me on the podcast</p>
<p>talking about the big trends</p>
<p>that we saw in 2022,</p>
<p>especially on our podcast.</p>
<p>And it was really kind of fun to go back</p>
<p>and take a look at all</p>
<p>the different podcasts</p>
<p>that we did over this last year</p>
<p>and find out, yeah,</p>
<p>where do we spend most of our time?</p>
<p>And I actually had a lot of fun doing this</p>
<p>because it brought back</p>
<p>memories of people I interviewed.</p>
<p>We did eight executive interviews</p>
<p>this last year,</p>
<p>great interviews</p>
<p>with former CEOs, CTOs, CEOs.</p>
<p>It was wonderful talking to them</p>
<p>about their experience in managing</p>
<p>organizations through technology</p>
<p>transformations and and all the above.</p>
<p>And in those interviews</p>
<p>and several other interviews that we did,</p>
<p>we found six really major trends</p>
<p>that we saw in 2022.</p>
<p>The trends are here you go.</p>
<p>Drum roll, please.</p>
<p>Hybrid workspace,</p>
<p>cybersecurity, cloud technology,</p>
<p>edge computing, data management,</p>
<p>and of course, the one that everyone's</p>
<p>thinking about, artificial intelligence.</p>
<p>We're still waiting for the,</p>
<p>you know, the the A.I.</p>
<p>to take over the world.</p>
<p>Hasn't happened yet.</p>
<p>Don't think it will in 2023.</p>
<p>But we saw an emergence</p>
<p>of some really cool AI tools in 2022.</p>
<p>Let's dive right into each one of these</p>
<p>and let's start with probably</p>
<p>the most profound thing that we saw in</p>
<p>At the beginning of 2022,</p>
<p>it was just getting out of COVID.</p>
<p>People were starting</p>
<p>to go back to the office.</p>
<p>There were a lot of fits and starts</p>
<p>on that because of outbreaks and caution.</p>
<p>And but during COVID,</p>
<p>it moved really fast.</p>
<p>They move really fast to get people</p>
<p>working from home at Starbucks,</p>
<p>in cabins in the mountains. It was crazy.</p>
<p>People were working</p>
<p>from all over the place</p>
<p>and people started</p>
<p>going back into the office.</p>
<p>So we needed this real flexibility</p>
<p>on, Hey, where is my work?</p>
<p>Is my work just on my laptop?</p>
<p>Is it up in the cloud?</p>
<p>Is it in virtual</p>
<p>desktops, in VDI, in my data center or in</p>
<p>It was it was an interesting</p>
<p>time to see what was going on.</p>
<p>At the same time,</p>
<p>we saw a lot of pressure,</p>
<p>a lot of pressure from cost pressures</p>
<p>on a decrease.</p>
<p>It cost because during COVID we kind of</p>
<p>let it costs run a little rampant</p>
<p>because we wanted people working so</p>
<p>that we can continue the business growing.</p>
<p>This was great for I.T.</p>
<p>They were able to move very quickly</p>
<p>and got the funding that they needed.</p>
<p>But 2022 saw a pullback</p>
<p>a little bit on that.</p>
<p>We got to control costs.</p>
<p>We still need to move fast like we did,</p>
<p>and we showed that</p>
<p>we could during the pandemic,</p>
<p>but we also needed</p>
<p>to put some controls in place so we didn't</p>
<p>blow things out of proportion.</p>
<p>We didn't, you know, blow, blow</p>
<p>the budget on everything.</p>
<p>So it was an interesting time in 2020</p>
<p>to have lots of podcast</p>
<p>episodes on the normal getting back</p>
<p>to the new normal and what that means</p>
<p>and cultural change during the pandemic</p>
<p>and how that affected everyone.</p>
<p>Go back and listen to</p>
<p>those are fascinating</p>
<p>discussions that we had with people</p>
<p>from several different industries</p>
<p>inside Intel as well as outside of Intel</p>
<p>in government and industry.</p>
<p>It was really fascinating.</p>
<p>Another major trend that we saw was cloud</p>
<p>computing,</p>
<p>another uptick in cloud computing,</p>
<p>more people moving to the cloud.</p>
<p>And we also saw a big surge</p>
<p>in regional clouds,</p>
<p>smaller cloud service providers</p>
<p>that are more a little bit more boutique</p>
<p>and can provide different services than</p>
<p>the big global cloud service providers.</p>
<p>And we saw people moving to them</p>
<p>because as from reliability,</p>
<p>we had several</p>
<p>cloud outages in the major CSPs this year.</p>
<p>I think the massive growth got a little</p>
<p>in front of them, a little bit.</p>
<p>Also, the cloud service</p>
<p>providers of global ones were moving up</p>
<p>the stack into new SAS</p>
<p>and Paths platforms, which</p>
<p>they maybe weren't architected completely.</p>
<p>Great. So we ran into some problems.</p>
<p>There were some outages that caused</p>
<p>some major outages</p>
<p>for for large companies.</p>
<p>So we started seeing also these companies</p>
<p>look at not just putting all their eggs</p>
<p>into one cloud service provider,</p>
<p>but into multiple cloud service providers</p>
<p>and also on their own data centers</p>
<p>in private cloud, we saw an interesting</p>
<p>uptick in private cloud.</p>
<p>We're seeing a lot of rumors around</p>
<p>Broadcom buying VMware,</p>
<p>which is the largest</p>
<p>private cloud software vendor, VMware.</p>
<p>And we saw some competitors</p>
<p>make some really strong</p>
<p>footholds in the private cloud space.</p>
<p>And competition is always good.</p>
<p>We like competition because it improves</p>
<p>the technology and the offerings</p>
<p>and possibly will decrease in price</p>
<p>in the private cloud.</p>
<p>So the multi hybrid cloud really started</p>
<p>to take its form this last year</p>
<p>because of some faltering that we saw</p>
<p>in the typical cloud service providers.</p>
<p>Another thing that we saw</p>
<p>that people were a little bit shocked of,</p>
<p>we had three episodes on this alone</p>
<p>was controlling costs in the cloud.</p>
<p>A lot of people see this sticker shock</p>
<p>when they first</p>
<p>get their first monthly cloud bill</p>
<p>and they're like, Oh my goodness,</p>
<p>that was more than what I expected.</p>
<p>There are a lot of</p>
<p>there are a lot of nuances to cloud costs,</p>
<p>especially when it comes to egress</p>
<p>and network.</p>
<p>Network costs.</p>
<p>Those things</p>
<p>tend to get people a little off guard</p>
<p>because they're not quite</p>
<p>used to the change</p>
<p>in operating that you do when you move to</p>
<p>a cloud service providers.</p>
<p>A lot of people</p>
<p>that got stuck with really large</p>
<p>cloud bills were the lift and shift.</p>
<p>I'm just going to lift</p>
<p>what I have shift in the cloud</p>
<p>and and work like normal day.</p>
<p>They typically ran into higher costs</p>
<p>in what they expected.</p>
<p>So again, we see cloud strategy</p>
<p>really taking place in 2022, really</p>
<p>that multi hybrid cloud as options</p>
<p>that people are looking for.</p>
<p>Now, another really big trend that we saw</p>
<p>in 2022 was edge computing.</p>
<p>And as the edge has become more capable,</p>
<p>we can do really crazy things on the edge.</p>
<p>Now because there's so much compute power</p>
<p>in these small form factors</p>
<p>and low wattage that we're starting</p>
<p>to see more capabilities out to the edge,</p>
<p>which means we have a lot</p>
<p>of really interesting things</p>
<p>going on out there</p>
<p>like t operational technology and i.t.</p>
<p>Information technology,</p>
<p>convergence is starting to happen</p>
<p>where i'm moving data across</p>
<p>those typically air gapped boundaries</p>
<p>and that</p>
<p>in itself has caused a whole bunch</p>
<p>of interesting problems in cybersecurity,</p>
<p>which we'll get to later.</p>
<p>And we're certainly seeing it across</p>
<p>multiple verticals health care,</p>
<p>manufacturing, energy</p>
<p>production, transportation.</p>
<p>We're starting to see</p>
<p>the promises of industry</p>
<p>for auto really starting</p>
<p>to take</p>
<p>really starting to come come about.</p>
<p>It's really starting to happen.</p>
<p>It's not moving as fast as we had hoped.</p>
<p>But I think that the emergence of private</p>
<p>And we saw some of the private 5G</p>
<p>offerings happen this year,</p>
<p>which is great with Flex</p>
<p>Ran and things like that,</p>
<p>a lot more flexible.</p>
<p>The barriers to entry into private</p>
<p>than it is for 4G</p>
<p>and other technologies like that.</p>
<p>So edge computing</p>
<p>I think is going to be big again</p>
<p>in 2023 and 2024.</p>
<p>Now that I have all my data scattered</p>
<p>in the cloud, in the data center</p>
<p>and out on the edge everywhere, guess what</p>
<p>the next major thing that we saw this</p>
<p>last year, and I think it's an emerging,</p>
<p>it's very nascent right now.</p>
<p>You're right, it's data management.</p>
<p>So data management took a major,</p>
<p>major role this last year</p>
<p>and people are still trying to grasp it.</p>
<p>They're trying to get their head around it</p>
<p>because my data is now</p>
<p>scattered everywhere.</p>
<p>And so how do I manage all that data?</p>
<p>How do I protect all that data,</p>
<p>and then how do I classify that data?</p>
<p>So those are kind of the</p>
<p>the four key pillars of data management</p>
<p>that we saw location,</p>
<p>classification, governance and protection.</p>
<p>On the classification</p>
<p>side, we're seeing organizations</p>
<p>being I don't know what the right word is</p>
<p>burdened with data</p>
<p>classification because of regulation.</p>
<p>There's a lot of regulations</p>
<p>around data privacy.</p>
<p>That means I have to do a better job</p>
<p>at classifying my data, making sure</p>
<p>that who has access to my data</p>
<p>and the right data</p>
<p>at the right time also ties in to that,</p>
<p>which is data governance, right?</p>
<p>Who has access for how long,</p>
<p>and then how long do I need to keep</p>
<p>keep that data</p>
<p>under this specific classification?</p>
<p>And then the fourth pillar,</p>
<p>of course, is protection.</p>
<p>Really interest</p>
<p>staying interesting and growth</p>
<p>in data protection specifically around</p>
<p>confidential computing.</p>
<p>So if you don't know</p>
<p>what confidential computing is,</p>
<p>we had like four podcasts</p>
<p>on confidential computing.</p>
<p>Really fascinating stuff.</p>
<p>It's protecting our data in use.</p>
<p>So encrypting our data while we're using</p>
<p>our data in the CPU and protecting it from</p>
<p>from attacks, cyber attacks and threats,</p>
<p>keeping my secrets secret</p>
<p>and not out on disk and things like that.</p>
<p>Some really cool technology</p>
<p>around encryption</p>
<p>encryption in silicon.</p>
<p>So that gives us the ability to encrypt in</p>
<p>use at rest and in transit.</p>
<p>So take a look at those</p>
<p>those podcasts on confidential computing,</p>
<p>great,</p>
<p>great new technology is like SGX and tDCS,</p>
<p>of course by Intel are available</p>
<p>there that really open the doors to that.</p>
<p>And the great news is some of the cloud</p>
<p>service providers have adopted</p>
<p>those technologies and other technologies</p>
<p>around confidential computing.</p>
<p>So it's now available</p>
<p>to try out in the cloud.</p>
<p>And then also you can buy it</p>
<p>in your own data centers, too.</p>
<p>So really interesting stuff</p>
<p>around this data management concept.</p>
<p>Now the next the next one</p>
<p>and probably in fact,</p>
<p>it was the one that had the most episodes</p>
<p>this year</p>
<p>in 2022 was cybersecurity.</p>
<p>We had oh, 18 to 20 AI.</p>
<p>Some of them were fudged a little bit</p>
<p>because we ended up</p>
<p>talking about cybersecurity,</p>
<p>even though the topic may have been</p>
<p>data management</p>
<p>because cybersecurity plays everywhere.</p>
<p>But there were 18 to</p>
<p>and wow, incredible episodes.</p>
<p>Everything.</p>
<p>Everything from ransomware attacks</p>
<p>to thwarting ransomware attacks to</p>
<p>new ways of looking at micro segmentation</p>
<p>for protection and firewall management.</p>
<p>Really interesting things.</p>
<p>All of us circling around the big buzz</p>
<p>word of the day</p>
<p>is zero trust architecture.</p>
<p>I know we've all heard it.</p>
<p>It's a big buzzword,</p>
<p>it's a marketing term, but</p>
<p>zero trust architecture</p>
<p>principles are real</p>
<p>and they're starting to be used</p>
<p>more and more.</p>
<p>So this is something</p>
<p>we most definitely want to keep an eye on.</p>
<p>We saw a lot this year in Zero Trust.</p>
<p>Everyone says they have zero trust.</p>
<p>Look at the principles.</p>
<p>It's not just an architecture.</p>
<p>It's also has to do with process</p>
<p>improvement that you need to put in place.</p>
<p>It's a new way of thinking about</p>
<p>security in the cloud,</p>
<p>in your data center</p>
<p>and also on the edge as well.</p>
<p>Also, we saw major breaches</p>
<p>in ransomware attacks in security,</p>
<p>critical infrastructure,</p>
<p>security was attacked heavily this year.</p>
<p>The war between the Ukraine</p>
<p>and Russia unleashed</p>
<p>a bunch of cyber attacks during that war</p>
<p>on each country</p>
<p>and also our allies to those countries.</p>
<p>So really interesting to see how</p>
<p>cyber security and cyber warfare</p>
<p>is going to play</p>
<p>with physical warfare</p>
<p>in conjunction in the future.</p>
<p>Interestingly enough,</p>
<p>a lot of surveys were done this last year</p>
<p>on cyber security.</p>
<p>Number one,</p>
<p>threat number one attack, phishing.</p>
<p>It still remains the primary attack vector</p>
<p>because humans are involved.</p>
<p>I myself have fallen.</p>
<p>I've fallen to the phishing attacks</p>
<p>that are it</p>
<p>department does on its own employees.</p>
<p>So I've had to take the training</p>
<p>a couple of times</p>
<p>because I said, Oh,</p>
<p>that looks really interesting.</p>
<p>I think we all kind of fall for that.</p>
<p>Sometimes.</p>
<p>Got to be more careful.</p>
<p>So we have to be cautious of the</p>
<p>phishing attacks that are out there.</p>
<p>And then probably the most notarized</p>
<p>or our of those famous</p>
<p>things that happened this year</p>
<p>where software supply chain attacks,</p>
<p>we had log forge with vulnerabilities</p>
<p>that were exposed.</p>
<p>Right.</p>
<p>That was huge because</p>
<p>almost everyone uses log for G</p>
<p>and it caught a lot of i.t organizations</p>
<p>and software development organizations</p>
<p>a little off,</p>
<p>off foot,</p>
<p>maybe on their back foot a little bit</p>
<p>because they weren't</p>
<p>sure if they had log, forge or not.</p>
<p>So we saw a big huge cry for</p>
<p>we need software bill of materials</p>
<p>when you're delivering software</p>
<p>or using software.</p>
<p>And there's been some standards groups</p>
<p>that have come up like ECF</p>
<p>s bomb group, the software bomb group</p>
<p>that have come up with some standards</p>
<p>around</p>
<p>software bombs,</p>
<p>how to use them, how to produce them</p>
<p>so that we can get a better idea</p>
<p>of where we do have vulnerabilities</p>
<p>in our workloads, in our infrastructure,</p>
<p>both in the cloud, on the edge</p>
<p>and in the data center.</p>
<p>So cybersecurity will continue</p>
<p>to be big in 2023.</p>
<p>Kind of check out my next episode</p>
<p>where I go in</p>
<p>depth on 2023 what I think the big items</p>
<p>will be that year</p>
<p>and we'll get some feedback</p>
<p>from you guys, my listeners</p>
<p>too, to see what you think about that.</p>
<p>Now the last one</p>
<p>and probably the coolest one, right?</p>
<p>Because it's bleeding edge stuff.</p>
<p>No, it's not Quantum computing.</p>
<p>There were some inroads in quantum,</p>
<p>but artificial intelligence</p>
<p>AI that that was a big one.</p>
<p>This last year.</p>
<p>We did several episodes on the podcast</p>
<p>about it.</p>
<p>Probably the biggest news in</p>
<p>AI this last year and towards</p>
<p>the end of the year was open A.I.</p>
<p>releasing Chat GB t</p>
<p>Pig. You know, I played around with it</p>
<p>a little bit.</p>
<p>It's pretty cool, I have to admit,</p>
<p>and it possibilities of it.</p>
<p>My brain are just starting to wrap around</p>
<p>what can I really do with this thing?</p>
<p>And it's pretty impressive.</p>
<p>So a generalized solution like that</p>
<p>that I can use</p>
<p>in several different things,</p>
<p>even maybe even responding</p>
<p>to your comments on my podcast,</p>
<p>my come from Chat GB t,</p>
<p>I don't know, we'll have to wait and see,</p>
<p>but it can also help write code.</p>
<p>It can help.</p>
<p>There's a lot of things in chat Gee GB t</p>
<p>that we're seeing interesting things now.</p>
<p>Also this last year</p>
<p>we saw a huge uptick in AI silicon chips.</p>
<p>So these are chips, neuromorphic computing</p>
<p>chips that are available</p>
<p>to purchase</p>
<p>and or rent from the cloud</p>
<p>service providers</p>
<p>where many of the cloud service</p>
<p>providers have adopted</p>
<p>neuromorphic computing as an offering</p>
<p>where it is so screaming fast</p>
<p>when it comes to training and inference</p>
<p>and things like that,</p>
<p>much faster</p>
<p>even than the GPUs at a lower wattage.</p>
<p>Those are now available in the cloud</p>
<p>or for purchasing your own data center.</p>
<p>And some of the wattage is even so small</p>
<p>that we can push it down into edge</p>
<p>devices.</p>
<p>We're talking 2 to 5 watts type of thing.</p>
<p>So really cool stuff for the Edge</p>
<p>and A.I.</p>
<p>chips that came out this this year.</p>
<p>Also, we're starting to see organizations</p>
<p>move out of using</p>
<p>AI in a science experiment</p>
<p>into operationalizing AI</p>
<p>in their day to day</p>
<p>workflows that they're doing in their</p>
<p>in their day</p>
<p>to day business that they have.</p>
<p>So that's another major uptick.</p>
<p>And we're feeling</p>
<p>the growing pains around operationalizing</p>
<p>A.I..</p>
<p>We're starting to see the emergence of</p>
<p>AI ops, just like DevOps.</p>
<p>We've got air ops</p>
<p>and we're seeing and we're bumping up</p>
<p>against some of the rough edges.</p>
<p>It'll get polished off, Will will grow</p>
<p>over the next couple of years</p>
<p>in the air space as it becomes</p>
<p>more readily available and operational.</p>
<p>I so I can, I can churn out</p>
<p>a I applications more readily.</p>
<p>Now another thing that we saw</p>
<p>and this is really interesting</p>
<p>is we saw new types of cyber attacks.</p>
<p>Again, cyber cyber security comes up,</p>
<p>but new types of cyber attacks on A.I.</p>
<p>and and A.I.</p>
<p>because A.I.</p>
<p>has more moving parts than a typical</p>
<p>application,</p>
<p>because I have my application,</p>
<p>I also have my data</p>
<p>that's driving the application</p>
<p>and the data that I'm analyzing</p>
<p>and the data them spitting out.</p>
<p>So lots of moving parts there.</p>
<p>And a lot of times with A.I.,</p>
<p>I'm dealing with the real world.</p>
<p>There's been some interesting</p>
<p>AI attacks that we've seen</p>
<p>that are attacking both the model</p>
<p>by changing parts of the model</p>
<p>or attacking the model</p>
<p>through the input coming in</p>
<p>by sending different types of disruption</p>
<p>into those input data streams.</p>
<p>We're starting to see the AI models</p>
<p>miss things and things.</p>
<p>So cyber attacks and I are increasing.</p>
<p>Research is being done on this</p>
<p>to how that's worked out as well.</p>
<p>So I hope your 2022 was a good year.</p>
<p>It was a transformational year</p>
<p>for a lot of people.</p>
<p>I think we saw that in the tech markets</p>
<p>as tech kind of stumbled a little bit</p>
<p>this last year</p>
<p>as far as we had this big, huge</p>
<p>two years of just spending like crazy</p>
<p>to keep every everything going.</p>
<p>And we had what I would call</p>
<p>a typical drawback after that.</p>
<p>And we had some stumbles,</p>
<p>but we absolutely do.</p>
<p>The chip shortage being one of those</p>
<p>stumbles, which</p>
<p>we continue to go through, the chip</p>
<p>shortage, especially on edge devices.</p>
<p>The automotive industry, for example,</p>
<p>is still has a major</p>
<p>chip shortage</p>
<p>that we're trying to get through still.</p>
<p>But 2023</p>
<p>I think will be an interesting year.</p>
<p>I think it's another transition year.</p>
<p>I'm hoping towards the end of the year</p>
<p>we'll see this massive</p>
<p>growth in these technologies</p>
<p>and maybe more.</p>
<p>But check out my next podcast episode</p>
<p>where we'll go more in</p>
<p>depth in what I see coming in 2023.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
