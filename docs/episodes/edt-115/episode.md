---
layout: posts
title: Blocking and Tackling of Security
number: 115
permalink: EDT115
has_children: false
parent: Episodes
nav_order: 115
tags:
     - EDT115
    - EmbracingDigital
    - ZTA
    - ZeroTrust
    - CyberHygiene
    - Cybersecurity
date: 
guests:
    - Darren W Pulsipher
img: TBD
summary: In this episode, Darren talks about cybersecurity with returning guest John Evans, Chief Technology Advisor at World Wide Technology (WWT).
---

{% include soundcloud.html id="edt115" title="#115 Blocking and Tackling of Security" %}

{% include youtube.html id="SPmsH6Ia6pM" %}

---

Foundational to all other cyber security is basic cyber hygiene. Many companies need to do these basics. This is evidenced by recent news headlines showing an uptick in attacks like denial of service attacks which should be easy to prevent.

From his experience working with the state community, John believes most attacks follow a typical kill chain. Most attacks hitting state and local governments result from exposed network protocols or email phishing. These are attractive entry points for hackers, and once they are in, bad patching practices are a typical culprit that allows them to gain a foothold and move laterally. That, combined with weak password policies or weak enforcement of password policies and an inability to recover, can lead to disaster.

In a well-publicized ransomware incident in 2019, the affected organization assumed that since they had the same amount of data in their production and backup environments, they were safe. But they had never tested their backups or recovery capabilities, which turned out to be poor. Basic cyber hygiene could have prevented this incident.

There are four essential basics that every organization should focus on. First, they must repeatedly train people to avoid phishing scams. Training might seem repetitive or mundane, but people falling for these schemes is a significant weakness in an organization. Hopefully, in the not-too-distant future, passwords will no longer be necessary.

Second, they must configure firewalls appropriately; just because RTP or network protocol ports are closed doesn’t mean there isn’t an open port in a less prominent spot. Security by obscurity doesn’t work.

Third, they must avoid bad patching policies, both with the client and the server, in the data centers and out at the edge. Many organizations are in technical debt and can’t update their old systems, so they accept the vulnerabilities and risk because they don’t want to invest in an update.

Fourth, they must have the ability to recover. Just because you know you can back up your data, can you use and recover with the backup? Testing is essential.

These four basics, along with a few others, are enough to stop almost all attacks coming into organizations that aren’t regular targets. That model doesn’t hold with organizations hit with nation-state attacks; they are doing all these things already and need additional security measures.

A consideration for many organizations is compliance versus risk. For some organizations to be compliant, they need to upgrade old machines, applications, and processes, which involves a significant cost. For organizations with a system that can’t be patched, it could take a risk-based approach that if something happens to the system, it would cost less than what it costs to upgrade the system. Of course, the secure thing to do would be upgrading to compliance, but most people think the risk-based approach is more secure. A small business could get away with this approach, but government organizations, for example, have regulatory compliance.

There are two reasons an organization might choose compliance other than a mandate. First, it’s an easy button for many organizations that don’t understand how to measure or prioritize risk. Compliance is a generalized framework to fall back on. It is not one-size-fits-all, however, because someone else is prioritizing risk in a generalized way.  Second, if something terrible happens and you have to, for example, explain it to your board of directors, you can say that you followed accepted standards.

Compliance is a bit of a crutch mentality because you don’t have to do all the risk evaluations and figure out what needs to be done. But, for example, a small municipality without a CISO could direct a sysadmin to use a compliance framework as a good starting point. If there is no CISO on hand, there is also the option of a part-time virtual CISO for guidance. John does this for clients, which is a viable path to better security.

The concept of zero trust also looks at a level of assurance versus risk. You need to understand the risk of granting someone access to a particular system or piece of data and then have a commensurate assurance that the person is whom they say they are. The heart of zero trust is a high level of security that mitigates risk.

Zero trust does not mean everything will be locked down and slow all processes. If, for example, someone wants to get in and see rainfall levels, you don’t need a high level of assurance that the person is verified. Still, if someone wants to access your organization’s crown jewels, there must be additional controls to verify identity.

Matching the level of assurance with the level of risk is challenging; it requires decision-point architecture. In the example of the risk it has in accessing a piece of data, an organization needs to know what and categorize it based on risk. For a mature organization, this can be difficult. John knows of one federal government organization that spent over two years ensuring its data was identified, classified, and tagged correctly before moving on to any decision-point type of architecture.

Identity and data are the two starting points for zero trust. In addition, it makes sense to avoid trying and doing everything at once. Starting with a piece of an organization might make the most sense, scaling it out through the rest of the organization over time.

Digital identity is becoming more sophisticated. John believes our transactions in the future will be primarily based on a zero-trust type of approach. For example, if he wants to transfer $10,000 out of his bank into an offshore account, the bank should make sure it is him and treat that transaction as if someone is trying to access a very sensitive, high-risk piece of information. If he goes to the store to buy a dollar cup of coffee, that level of assurance that it’s him purchasing the coffee is unnecessary. Many of these zero-trust principles will make their way into our everyday lives.

User behavioral analytics will also come into play. Just as a credit card company will raise a flag for unusual purchases, for example, if a system knows that John types 20 words per minute, and then all of a sudden, he’s typing 100 words per minute and trying to access sensitive information, there’s a red flag.


<details>
<summary> Podcast Transcript </summary>

<p>﻿1</p>
<p>Hello, this is Darren Pulsipher, chief</p>
<p>solution.</p>
<p>Architect of public sector at Intel.</p>
<p>And welcome to Embracing</p>
<p>Digital Transformation,</p>
<p>where we investigate effective change,</p>
<p>leveraging people.</p>
<p>Process and technology.</p>
<p>On today's episode,</p>
<p>Blocking and Tackling of cybersecurity</p>
<p>with special guest John Evans from WWT.</p>
<p>John, welcome back to the show.</p>
<p>Thank you very much for having me back.</p>
<p>I had a great time last time and looking</p>
<p>forward to talk with you again today.</p>
<p>Well, today</p>
<p>we're expanding things a little bit.</p>
<p>Well, kind of.</p>
<p>We're actually narrowing things down</p>
<p>to cyber security</p>
<p>because we you teased me last time.</p>
<p>You teased me last time with the shared</p>
<p>cybersecurity model on cloud.</p>
<p>I said, John, we got to talk about cyber</p>
<p>security in general.</p>
<p>There's so much to</p>
<p>unpack here.</p>
<p>But let's first start by was talk about</p>
<p>just basic cyber hygiene, just the basics.</p>
<p>Where do you see a lot of companies</p>
<p>that are failing in cyber hygiene</p>
<p>and where do you see companies</p>
<p>that are doing</p>
<p>cyber hygiene</p>
<p>well and what does that look like?</p>
<p>Yeah, so I think it's a great topic and,</p>
<p>you know,</p>
<p>foundational to all the other cyber stuff</p>
<p>that that that we do.</p>
<p>So it's probably a good place</p>
<p>to start the conversation.</p>
<p>You know, when you think cyber hygiene,</p>
<p>it's those basic cyber</p>
<p>things that we all need to be doing.</p>
<p>But unfortunately,</p>
<p>not everyone's always doing them.</p>
<p>And I think that that's been evidenced</p>
<p>by news headlines recently.</p>
<p>You know, there's it's</p>
<p>you know, there's there's</p>
<p>there's been an uptick</p>
<p>even just in distributed</p>
<p>denial of service attacks, something</p>
<p>that should be relatively easy to do.</p>
<p>I mean, those have been around forever.</p>
<p>We know how to defeat those, right?</p>
<p>Yeah. It's in some cloud services.</p>
<p>It's clicking</p>
<p>a button, you know, it's, it's.</p>
<p>But I think cyber hygiene,</p>
<p>it isn't always the cool, kind of sexy</p>
<p>cybersecurity thing happening.</p>
<p>So sometimes it doesn't get the,</p>
<p>the view, you know, the</p>
<p>the level of the level of importance</p>
<p>isn't paid on it,</p>
<p>that maybe it should be in a lot of cases.</p>
<p>And that's unfortunate.</p>
<p>You know, I used to be the CSO</p>
<p>for the state of Maryland</p>
<p>and I still stay pretty</p>
<p>well plugged in with the state.</p>
<p>So, so community.</p>
<p>And I think I can say relatively certain</p>
<p>that most attacks</p>
<p>follow a common kill chain.</p>
<p>So if you think about most attacks</p>
<p>hitting state and local government,</p>
<p>it's exposed network protocols</p>
<p>like expose RTP, maybe some</p>
<p>maybe somebody put some RTP in a box</p>
<p>to make it easier</p>
<p>for them to get in to do maintenance</p>
<p>when they're not not in the office</p>
<p>might have been forgot forgotten about</p>
<p>but that exposed network</p>
<p>protocol is open to to the Internet.</p>
<p>Perhaps, and provides</p>
<p>a real attractive entry point</p>
<p>for hackers to get at once once they're in</p>
<p>that patch.</p>
<p>And practices are typically a culprit</p>
<p>that allows them to be able</p>
<p>to gain a foothold,</p>
<p>start to move, move laterally.</p>
<p>Now you combine that with weak</p>
<p>password policies</p>
<p>or weak enforcement of password policies</p>
<p>and then an inability to recover.</p>
<p>I was involved directly in</p>
<p>a very large cyber incident that happened</p>
<p>in 2019.</p>
<p>So people can go back,</p>
<p>they can read the headlines, whatever.</p>
<p>You can figure it out</p>
<p>really, really easily.</p>
<p>What it was probably.</p>
<p>But basically it was a ransomware attack</p>
<p>where the affected organization</p>
<p>they basically kind of said, well,</p>
<p>we know that</p>
<p>we've got the same amount of data</p>
<p>in our production environment</p>
<p>and in our backup environment.</p>
<p>Therefore we must be good.</p>
<p>But they never tested</p>
<p>their backups, never tested recovering.</p>
<p>So poor, poor recovery capabilities.</p>
<p>But yeah, it's a fairly common kill chain.</p>
<p>They get in from one or two places,</p>
<p>mostly either email, which.</p>
<p>Phishing attacks.</p>
<p>Write phishing attacks</p>
<p>or expose net network protocols.</p>
<p>There's very often</p>
<p>some poor patch compliance</p>
<p>type of component to it</p>
<p>and then an inability to recover.</p>
<p>So cyber hygiene is still very important.</p>
<p>We need to be, I think, putting more</p>
<p>emphasis on it, you know, in the future.</p>
<p>You know, this reminds me of I remember</p>
<p>I played football in high school.</p>
<p>I remember</p>
<p>we had a horrible, horrible game</p>
<p>and we had all the talent in the world.</p>
<p>And the coach said, back to basics, man,</p>
<p>back to basics, blocking and tackling.</p>
<p>And I hated that week.</p>
<p>That was a miserable week</p>
<p>because it was the same thing</p>
<p>over and over again until we got it right.</p>
<p>So that sounds like if we were to say</p>
<p>the blocking and tackling</p>
<p>of cybersecurity are</p>
<p>phishing.</p>
<p>Right?</p>
<p>Right.</p>
<p>Making sure that you're training</p>
<p>people on phishing.</p>
<p>We get this intel all the time.</p>
<p>I get phishing.</p>
<p>I like to say</p>
<p>it just wants me to take more training</p>
<p>because I'm, you know, fish bait, right?</p>
<p>That's me. Right?</p>
<p>I'm like, oh, that looks interesting.</p>
<p>Now I'm learning it takes me some time.</p>
<p>But so training your people on phishing</p>
<p>is, number one,</p>
<p>exposing network protocol.</p>
<p>So this is configuring your firewalls</p>
<p>appropriately, basically, right.</p>
<p>Having something in front of them</p>
<p>if you're going to have them.</p>
<p>Yeah.</p>
<p>I don't care if it's VPN or but don't</p>
<p>but don't have it just exposed and</p>
<p>you know, one of the things that we found</p>
<p>was, you know,</p>
<p>I'd go into agencies and say, you know</p>
<p>what, we're going to do a full port scan.</p>
<p>They would show me port</p>
<p>scans of the standard ports and say, well,</p>
<p>we don't have anything exposed.</p>
<p>And it's like, well.</p>
<p>No, I.</p>
<p>You mean 22 was closed in 80.</p>
<p>Yeah, just. In four for three.</p>
<p>Yeah. Those are the ones you closed.</p>
<p>Just because your standard, you know,</p>
<p>RTP or network protocol ports are closed</p>
<p>doesn't mean somebody couldn't</p>
<p>have put it somewhere else.</p>
<p>And we very often would find that</p>
<p>that was the case.</p>
<p>So security</p>
<p>biosecurity doesn't doesn't doesn't work.</p>
<p>I like how you said that because a lot of</p>
<p>people rely on security by obscurity.</p>
<p>But that doesn't it doesn't work.</p>
<p>No, not at all.</p>
<p>I mean, especially now with all the tools</p>
<p>that that hackers have out there,</p>
<p>even scripts, script kiddies are</p>
<p>much more sophisticated probably</p>
<p>than they were just a few years ago.</p>
<p>There's so many tools out there, so many</p>
<p>scanners available.</p>
<p>Nobody's just looking</p>
<p>at the standard ports anymore.</p>
<p>Yeah, another thing that you saw,</p>
<p>the third one was bad patching policies.</p>
<p>You're talking about client patching,</p>
<p>but also in the server,</p>
<p>in the data centers as well.</p>
<p>And even out on the edge, right?</p>
<p>Oh, absolutely.</p>
<p>Absolutely.</p>
<p>We have you know,</p>
<p>I imagine there's a lot of organizations</p>
<p>that have we were talking about</p>
<p>technical debt last time a little bit.</p>
<p>Yeah.</p>
<p>And I imagine</p>
<p>there's a lot of organizations</p>
<p>that have acquired a lot of technical debt</p>
<p>in certain systems,</p>
<p>and now they're at a point</p>
<p>where they can't even update those systems</p>
<p>because.</p>
<p>The software has been eold, right?</p>
<p>Yeah.</p>
<p>So they know that they have to run on this</p>
<p>outdated operating system</p>
<p>that has all these vulnerabilities</p>
<p>associated with it.</p>
<p>And it's just a risk that they accept</p>
<p>because they don't have or they</p>
<p>they don't want to invest the money</p>
<p>into updating this system.</p>
<p>It's a large undertaking, perhaps, but</p>
<p>so they're just sitting out there</p>
<p>as known vulnerabilities.</p>
<p>So would you say if and the other.</p>
<p>I want to quickly go over the other ones.</p>
<p>I want to kind of the weak</p>
<p>password policy.</p>
<p>I totally get it. I'm horrible at this.</p>
<p>If you hack one of my passwords, you can</p>
<p>figure out all the other ones guaranteed.</p>
<p>And it doesn't take long.</p>
<p>So we need to do a better job at password.</p>
<p>But can we get rid of passwords?</p>
<p>I know that's a whole nother story,</p>
<p>but and this goes into digital identity,</p>
<p>which we're going to talk about</p>
<p>another time.</p>
<p>That'd be great.</p>
<p>Yeah.</p>
<p>I'm I'm hoping that that we can</p>
<p>in the not too distant future.</p>
<p>I think there's a lot of organization</p>
<p>that are still going to be reluctant</p>
<p>to give up their passwords.</p>
<p>But I think that a</p>
<p>good intermediate step is MFA everything.</p>
<p>MFA everything.</p>
<p>Yeah, I think MFA</p>
<p>everything is a great intermediate step.</p>
<p>And then hopefully that will take us</p>
<p>to the promised land of of Passwordless.</p>
<p>Which would, which would be nice.</p>
<p>And the last one I think is, is</p>
<p>really important, the ability to recover.</p>
<p>And I love how you said, yeah,</p>
<p>oh you back things up.</p>
<p>Can you actually use the backup right</p>
<p>now? Well, I've never tested it.</p>
<p>I don't know. Right.</p>
<p>Yeah.</p>
<p>I mean, when this big event</p>
<p>happened in 2019, they found</p>
<p>they didn't have a lot</p>
<p>of their organizational structures,</p>
<p>so they had the raw data.</p>
<p>Yeah, but then. Yeah, yeah.</p>
<p>What a nightmare, you know.</p>
<p>Oh, we don't have the right accounts</p>
<p>to access that,</p>
<p>that data</p>
<p>or the applications don't have the right.</p>
<p>There's, there's a whole list of</p>
<p>would you say if I</p>
<p>did these four basic things, how,</p>
<p>how much of the security issues</p>
<p>that I'm having in</p>
<p>my organization would go away?</p>
<p>I think it depends on the type</p>
<p>of organization that you're in.</p>
<p>I think if you're talking about</p>
<p>and maybe it's not for we</p>
<p>we chose to hit on four I think.</p>
<p>Yeah,</p>
<p>those are the four. Of the most important.</p>
<p>Yeah.</p>
<p>But you know, maybe it's, you know,</p>
<p>six or seven things, it's certainly</p>
<p>less than ten probably that we could</p>
<p>really come up with a solid list and say,</p>
<p>you know, if you're an organization</p>
<p>that isn't getting hit with zero day</p>
<p>type threats, that isn't getting hit</p>
<p>with nation state type attacks,</p>
<p>we can stop, you know,</p>
<p>I mean, you could probably</p>
<p>stop 98, 99% of attacks</p>
<p>coming into your organization.</p>
<p>If you do these half dozen things.</p>
<p>Well, that that model doesn't hold true.</p>
<p>If you're talking about three letter</p>
<p>agencies, you know.</p>
<p>They better be doing all those things</p>
<p>already.</p>
<p>Anyway, that's that's that's true.</p>
<p>That's a good point.</p>
<p>I'm sure that they are.</p>
<p>But there's a lot more resources being</p>
<p>thrown at those types of organizations.</p>
<p>So that model doesn't hold true</p>
<p>for for those types of organizations.</p>
<p>But if you're talking about</p>
<p>most state,</p>
<p>local education, small businesses,</p>
<p>those types of things probably holds</p>
<p>pretty, pretty true, I would say.</p>
<p>No. Very cool.</p>
<p>All right.</p>
<p>So you mentioned one thing</p>
<p>and it was around patching.</p>
<p>Now, this is really interesting</p>
<p>because this ties us</p>
<p>into our second topic,</p>
<p>which is really compliance versus risk.</p>
<p>And the reason I tie this to patching a</p>
<p>little bit, because you mentioned before,</p>
<p>I may have</p>
<p>machines that I can't patch anymore.</p>
<p>So now you got a way</p>
<p>to be compliant.</p>
<p>I would have to upgrade all those machines</p>
<p>and upgrade applications</p>
<p>and change my process.</p>
<p>Big cost,</p>
<p>but what is the real risk involved?</p>
<p>So there's this this push and pull</p>
<p>on compliance and risk.</p>
<p>And if I am completely compliant,</p>
<p>does that mean that I'm completely secure?</p>
<p>Then there's all these questions</p>
<p>I've got in my in my head.</p>
<p>So teach me.</p>
<p>Oh, great, John.</p>
<p>Well, so you brought up</p>
<p>an interesting use case for it</p>
<p>because that's not one that people</p>
<p>typically think of when they think of or</p>
<p>when they start discussions on compliance</p>
<p>versus risk.</p>
<p>What you kind of brought up is a use case</p>
<p>where compliance might</p>
<p>potentially lead you to the better place,</p>
<p>which isn't a use case.</p>
<p>What I mean by that is if I've got a</p>
<p>system that</p>
<p>I'm unable to to patch,</p>
<p>I could make a risk</p>
<p>based approach that says, you know what,</p>
<p>if something bad happens to the system,</p>
<p>the cost of that bad thing happening</p>
<p>costs me more.</p>
<p>Or I'm sorry,</p>
<p>the costs are going up</p>
<p>and it costs me less than what it's going</p>
<p>to cost me to actually update the system</p>
<p>in order to patch it.</p>
<p>Therefore,</p>
<p>I might just let that bad thing happen,</p>
<p>or I might just run the risk of</p>
<p>of having that that that bad thing happen</p>
<p>in that case compliant being,</p>
<p>you know, I would be out of compliance</p>
<p>if I tried to get into compliance.</p>
<p>It may be valid</p>
<p>from a risk based approach,</p>
<p>but the more secure thing to do</p>
<p>would be to be compliant in that case,</p>
<p>which is an odd kind of call out the way,</p>
<p>because most people think of</p>
<p>the risk based</p>
<p>approach as being more secure</p>
<p>than than compliance.</p>
<p>Either way, they are certainly different.</p>
<p>I think that that example shows shows</p>
<p>that they're different,</p>
<p>you know, a lot of times.</p>
<p>So I have to do</p>
<p>both is what you're telling me.</p>
<p>I can't just I can't just say</p>
<p>I'm going to using a risk based</p>
<p>approach and you can't just say</p>
<p>I'm doing a compliance based approach.</p>
<p>Well,</p>
<p>so if you're if you're a private industry,</p>
<p>if you're a small business,</p>
<p>you could probably get away</p>
<p>with just a risk based approach.</p>
<p>Most government organizations</p>
<p>can't just rely on a risk</p>
<p>because there are compliance issues</p>
<p>or compliance</p>
<p>regulatory compliance</p>
<p>that they have to adhere to. So</p>
<p>I think, you know,</p>
<p>if we have to prioritize one or the other,</p>
<p>a risk based approach is probably</p>
<p>the better choice for most cases.</p>
<p>Even in the case that we were just</p>
<p>talking about, about not patching,</p>
<p>yeah, you'd be more secure</p>
<p>with a compliance based approach,</p>
<p>but you could also argue</p>
<p>that you've wasted money</p>
<p>by using a compliance based approach.</p>
<p>So for a business, it's probably not the,</p>
<p>the, the, the best decision.</p>
<p>But, you know,</p>
<p>if you look at there's,</p>
<p>there's been a tax out there released</p>
<p>into the wild that were,</p>
<p>you know, rated very low</p>
<p>on the CD Cvss scoring.</p>
<p>And if those</p>
<p>if someone had been using more of a risk</p>
<p>based approach, they would say, you know</p>
<p>what, we're seeing an uptick in the damage</p>
<p>being done by these types of attacks,</p>
<p>remote code executable,</p>
<p>some of those other factors.</p>
<p>And you could use those.</p>
<p>You'd also look at your internal</p>
<p>organization and say, you know,</p>
<p>what do I have?</p>
<p>What what data</p>
<p>and how sensitive is that data?</p>
<p>That is susceptible</p>
<p>to this type of an attack?</p>
<p>Do I have mitigating controls</p>
<p>in front of it?</p>
<p>Therefore, I don't need to prioritize</p>
<p>it quite as quite as high. So</p>
<p>using that risk based approach</p>
<p>will allow you to, one,</p>
<p>really spend your money</p>
<p>where it needs to be spent</p>
<p>and focus your resources,</p>
<p>where they should be focused</p>
<p>ultimately with the goal of making it</p>
<p>more secure in the long run. But,</p>
<p>you know, it's</p>
<p>it's it's really about in a lot of</p>
<p>and I would say it's mostly really</p>
<p>about that prioritization</p>
<p>of your resources and your money</p>
<p>being able to make a risk based decision.</p>
<p>So why even do compliance</p>
<p>does it every and no, it's an</p>
<p>honest question why it why is government</p>
<p>because it sounds like maybe compliance</p>
<p>might just be</p>
<p>a heavy handed</p>
<p>way of doing risk</p>
<p>or someone's already decided</p>
<p>this is too risky so you can't do it.</p>
<p>Yeah.</p>
<p>I mean, I think it's two reasons.</p>
<p>I think one is it's</p>
<p>it's somewhat of an easy button</p>
<p>for a lot of organizations.</p>
<p>If organizations don't understand</p>
<p>how to prioritize risk or how to measure</p>
<p>risk, it's very difficult.</p>
<p>So then you can fall back on a compliance</p>
<p>based type of an approach where they have</p>
<p>sort of generalized risk for you</p>
<p>in some sort of framework,</p>
<p>because that's really what they're trying</p>
<p>to do in a lot of the cases.</p>
<p>They feel like the CIS, where they</p>
<p>prioritize the different controls,</p>
<p>they're sort of trying to prioritize risk</p>
<p>for you, but in a very generalized way.</p>
<p>It's not a one size.</p>
<p>It shouldn't be a one size fits all.</p>
<p>They're kind of trying</p>
<p>to make it do that, but.</p>
<p>But their lead.</p>
<p>I see where you're saying</p>
<p>they're leading you down a path today.</p>
<p>Are these types of things are risky,</p>
<p>right?</p>
<p>You need to pay attention to these things</p>
<p>and put some kind of risk measure</p>
<p>against it.</p>
<p>Yeah.</p>
<p>So, you know, the other thing is</p>
<p>it gives you a sort of a CIA position.</p>
<p>If you say, well, I followed these,</p>
<p>I follow national standards</p>
<p>and something bad happens, you can fall</p>
<p>back on that when you're trying</p>
<p>to explain it to your board of directors</p>
<p>or trying to explain it to the governor</p>
<p>or whoever you need to to</p>
<p>to explain that that that issue, too.</p>
<p>And then thirdly, and probably</p>
<p>the biggest reason it's done within</p>
<p>government is because you have to do it</p>
<p>according to some mandate.</p>
<p>So like state, local government,</p>
<p>if you want your money from CMS</p>
<p>to pay for your billion dollar</p>
<p>Medicaid system, you have to be compliant</p>
<p>with Marcy if you're not and you may not</p>
<p>get your your your your funding.</p>
<p>And that's a huge amount of funding</p>
<p>coming into the States. So.</p>
<p>Gotcha.</p>
<p>Well, in general, do you</p>
<p>do you believe that some of these</p>
<p>security frameworks or standards, do</p>
<p>they help the industry as a whole,</p>
<p>or do you see them as a crutch that,</p>
<p>oh, I just did the compliance</p>
<p>and that's good enough.</p>
<p>Where are you seeing that vetting?</p>
<p>Yeah, I think</p>
<p>there's a little bit</p>
<p>of the crutch mentality.</p>
<p>I think there you know, if you look at,</p>
<p>you know, saying it's a way to kind of</p>
<p>cover yourself, that that that goes back</p>
<p>to the kind of crutch mentality, I think.</p>
<p>And then I think there's a little bit of</p>
<p>I don't want to call it laziness,</p>
<p>a little bit of, you know,</p>
<p>this is good enough.</p>
<p>I do this.</p>
<p>I don't have to spend the time</p>
<p>doing all of my risk evaluations</p>
<p>and really figuring things out</p>
<p>for what needs to be done.</p>
<p>I can just kind of follow</p>
<p>this, this, this, this playbook.</p>
<p>So, yeah,</p>
<p>I would say I think in some ways</p>
<p>it is a bit of a crutch having it's a.</p>
<p>Little more</p>
<p>let's say that I'm a small municipality,</p>
<p>going to a compliance framework</p>
<p>may be a good start for me because I don't</p>
<p>I can't afford a C, so I just have this,</p>
<p>you know,</p>
<p>this sysadmin that says he likes security.</p>
<p>I can point him in this direction and say</p>
<p>there is a good starting point for you.</p>
<p>Right?</p>
<p>I mean, they're not all bad.</p>
<p>Yeah.</p>
<p>I mean, you know, another thing</p>
<p>to consider and I actually do this for</p>
<p>I have a call later today</p>
<p>or think about it.</p>
<p>I think I moved to tomorrow actually, but</p>
<p>so through WWT</p>
<p>and this isn't this wasn't planned</p>
<p>not trying to create a picture</p>
<p>but you know I do virtual</p>
<p>CSO types of engagements.</p>
<p>So there's a county I'm meeting with this</p>
<p>week to talk to them about</p>
<p>where we're kicking off the engagement</p>
<p>actually.</p>
<p>So, you know, the contracts</p>
<p>been signed, everything. So</p>
<p>but we actually do some,</p>
<p>some pieces of work.</p>
<p>I do some</p>
<p>directly with some different customers.</p>
<p>So I would say, you know,</p>
<p>if you don't have the staff on hand,</p>
<p>it doesn't have to be hundreds</p>
<p>of thousands of dollars either to get</p>
<p>some part of part time of a virtual saw.</p>
<p>So we'll be able to help walk</p>
<p>you through sort of</p>
<p>some of these risk based</p>
<p>and prioritization of of activities.</p>
<p>You know, so, I mean, I would say that</p>
<p>that's a a a feasible path</p>
<p>maybe for some of these municipalities</p>
<p>also to kind of take.</p>
<p>Great.</p>
<p>All right.</p>
<p>Let's talk a little bit.</p>
<p>Let's extend this risk based</p>
<p>to zero trust,</p>
<p>because all that's all the buzz right now.</p>
<p>Zero trust is zero trust.</p>
<p>My product has zero trust,</p>
<p>but I have a lot of ideas around this</p>
<p>and strong opinions about zero</p>
<p>trust, philosophy and principles,</p>
<p>which I think is more important than zero</p>
<p>trust architecture.</p>
<p>And you and I talked about this before,</p>
<p>and that's the same.</p>
<p>But really, when you look at Zero Trust,</p>
<p>you're really looking at level</p>
<p>of assurance versus level of risk as well.</p>
<p>That's a great way to say it.</p>
<p>There's a you need to know the level</p>
<p>of risk with somebody or with a set</p>
<p>with with access to a particular system</p>
<p>or piece of data in you to understand</p>
<p>what the risk could be</p>
<p>with granting access to that, if,</p>
<p>you know,</p>
<p>could it be disclosed or altered.</p>
<p>So you need to understand the risk</p>
<p>and then you need to have a commensurate</p>
<p>level of assurance that what's trying</p>
<p>to access the person or system,</p>
<p>trying to access that that that data</p>
<p>is who they say they are</p>
<p>and they're supposed to have access.</p>
<p>So it's exactly what you just said.</p>
<p>It's risk of accessing something</p>
<p>and assurance that I.</p>
<p>Know who that other person</p>
<p>or entity really is.</p>
<p>Entity is and that they're supposed</p>
<p>to have access to it. Yeah.</p>
<p>So would you say that's it in zero trust?</p>
<p>Zero Trust is high level of assurance</p>
<p>mitigated by risk.</p>
<p>Mitigated mitigates risk.</p>
<p>That's a yeah.</p>
<p>I mean at the heart of zero</p>
<p>trust that's, that's what zero.</p>
<p>I mean that's really sort of what it is.</p>
<p>It's that security decision</p>
<p>point architecture that says</p>
<p>based on the level of risk</p>
<p>associated with accessing this thing,</p>
<p>I am going to put more stringent controls</p>
<p>or more stringently evaluate,</p>
<p>make sure that I have a higher level</p>
<p>of assurance</p>
<p>that this entity is who they say they are</p>
<p>and that they're supposed to be accessing</p>
<p>this data.</p>
<p>So people talk about zero trust.</p>
<p>I think they get you know,</p>
<p>I think it's a term that some people</p>
<p>are a little overwhelmed by at times.</p>
<p>But at the heart of it,</p>
<p>that's really all it is.</p>
<p>So if we think practically, you know, if</p>
<p>if I've got somebody</p>
<p>who's trying to to get in to see,</p>
<p>you know, rainfall levels,</p>
<p>I don't need to verify that</p>
<p>with much level of,</p>
<p>you know,</p>
<p>very high</p>
<p>level of assurance</p>
<p>that person is who they say they are,</p>
<p>that they're supposed</p>
<p>to have access to that data.</p>
<p>But if it's my crown jewels,</p>
<p>I need to make sure</p>
<p>that there are some additional controls</p>
<p>put on that to really make sure</p>
<p>that this person is who they say they're</p>
<p>in, that they're supposed to have access.</p>
<p>I really like how you describe that,</p>
<p>because when I first heard about</p>
<p>Zero Trust, I thought, Oh,</p>
<p>they're going to lock everything down</p>
<p>and everything is going to have</p>
<p>temporal access.</p>
<p>I mean, I only have access</p>
<p>for a short period of time</p>
<p>and high assurance on everything and know</p>
<p>that this is going to be ridiculous.</p>
<p>Because if I do want to find out</p>
<p>how much it rained last night,</p>
<p>they have to authenticate who I am.</p>
<p>And I can only look for 30 seconds.</p>
<p>I mean, that's just not reasonable.</p>
<p>So I love how you said that.</p>
<p>It is.</p>
<p>It's not</p>
<p>I don't trust anyone all the time.</p>
<p>It's I'm weighing</p>
<p>that assurance with the risk involved</p>
<p>in accessing an asset or data.</p>
<p>And you're the only one</p>
<p>I've heard really talk about it that way.</p>
<p>So you should write a book.</p>
<p>John Okay.</p>
<p>You made it so easy to understand.</p>
<p>Frankly.</p>
<p>No, thank you.</p>
<p>I try to.</p>
<p>That's</p>
<p>you know,</p>
<p>you're not always going to have the luxury</p>
<p>of being able to explain it to people</p>
<p>like yourself who are, you know,</p>
<p>very knowledgeable, very educated</p>
<p>in the technologies.</p>
<p>If that's the philosophy, the principles.</p>
<p>Right.</p>
<p>Matching the</p>
<p>level of assurance with the level of risk.</p>
<p>How about implementing that? Is that hard?</p>
<p>Are there tools that I can just use today</p>
<p>that let me do that effectively?</p>
<p>Or does this mean</p>
<p>a completely re architecture of the way</p>
<p>that I do access management</p>
<p>and the way that I do</p>
<p>everything that I've been doing</p>
<p>for 30 years, 40 years even?</p>
<p>Yeah.</p>
<p>So there's a lot to unpack in there</p>
<p>in that question.</p>
<p>I'm going to sort of try to take it piece</p>
<p>by piece or say at a pretty high level</p>
<p>because there's a lot of depth,</p>
<p>a lot of places you can go.</p>
<p>That was a big question to answer,</p>
<p>sort of.</p>
<p>Is it hard? I mean, it can be.</p>
<p>I think it depends on the level</p>
<p>of maturity of your organization.</p>
<p>One of we talked about</p>
<p>the risk associated with</p>
<p>accessing a piece of data</p>
<p>as a as an example.</p>
<p>If my organization doesn't know what data</p>
<p>I have out there</p>
<p>and if I can't categorize that data,</p>
<p>if I can't assign a risk</p>
<p>scoring basically to that data,</p>
<p>then it can be real.</p>
<p>It can be real hard</p>
<p>because I know a pretty mature</p>
<p>federal government organization</p>
<p>talking to their CTO.</p>
<p>They spent over two years</p>
<p>just making sure that they have their data</p>
<p>identified, classified, tagged</p>
<p>correctly before they moved on to</p>
<p>any sort of the decision</p>
<p>point type of architecture. So</p>
<p>so it sounds like</p>
<p>the first thing you have to do is</p>
<p>identify your data and classify it,</p>
<p>but sounds like that's</p>
<p>one of the first steps.</p>
<p>Yeah, it's it's definitely one of them.</p>
<p>You know, identity</p>
<p>and data are probably the two big things</p>
<p>that you want to start start off with.</p>
<p>If you don't have a good handle</p>
<p>on your identities</p>
<p>and you don't have</p>
<p>a good handle on your data,</p>
<p>you can run those tracks in parallel,</p>
<p>and you probably should</p>
<p>because both of those can take quite up</p>
<p>quite a bit of time</p>
<p>to get them into a place</p>
<p>to really move you to towards</p>
<p>zero zero trust.</p>
<p>The other thing I would say is</p>
<p>maybe</p>
<p>pick up a piece of your organization.</p>
<p>Don't try to boil</p>
<p>the ocean. Don't do everything over.</p>
<p>Yeah, maybe pick a piece of it</p>
<p>and work through it there.</p>
<p>Get some muscle memory work,</p>
<p>working through it there</p>
<p>and then start kind of scaling that out</p>
<p>to other pieces of of your organization.</p>
<p>It's interesting.</p>
<p>You threw in identity again.</p>
<p>Yeah, no identity.</p>
<p>Yeah.</p>
<p>This is a big topic</p>
<p>then I digital identity and.</p>
<p>Yeah well you know it's interesting too so</p>
<p>I'm going to</p>
<p>transition if it's okay with with with you</p>
<p>so digital identity</p>
<p>you mentioned that digital identity</p>
<p>if you think about,</p>
<p>you know, digital identity,</p>
<p>we have identity proofing,</p>
<p>making sure that this person is</p>
<p>who they say they are.</p>
<p>You know, we're getting into</p>
<p>more sophisticated ways of doing that.</p>
<p>But if we think about how</p>
<p>this all plays out in the future, move,</p>
<p>move it moving forward,</p>
<p>I think our identities are going to be</p>
<p>almost based on our transactions.</p>
<p>I should say, in the real world,</p>
<p>are going to be based on the zero</p>
<p>trust type of an approach.</p>
<p>So as a for instance, if I need to</p>
<p>or, you know, if John is transferring</p>
<p>$10,000, let's say, out of his bank</p>
<p>account to an offshore account</p>
<p>somewhere, my</p>
<p>my bank should make real search for that.</p>
<p>This is me trying to make that</p>
<p>make the transaction just as if someone's</p>
<p>trying to access some very sensitive</p>
<p>high risk piece of information.</p>
<p>Whereas if I'm going to the store</p>
<p>and buying a cup of coffee,</p>
<p>you may not need the same level</p>
<p>of assurance that that, you know,</p>
<p>it's actually</p>
<p>John who's who's making this transaction,</p>
<p>the impact, the</p>
<p>risk associated with</p>
<p>it is much lower in those cases. So</p>
<p>I think we're going to see a lot of</p>
<p>a lot of the principles</p>
<p>that we're learning and or that we're</p>
<p>developing around zero trust,</p>
<p>making their way into our everyday.</p>
<p>Life or day lives as.</p>
<p>We start to stop doing more of the</p>
<p>of the digital identity type of</p>
<p>type type of framework.</p>
<p>You know,</p>
<p>something else just popped into my head.</p>
<p>It's not just the one event</p>
<p>either</p>
<p>that you have to be able to identify.</p>
<p>And this is where I think we're going</p>
<p>to start seeing some interesting plays</p>
<p>in a I and access over over time.</p>
<p>If Darren's acts if Darren buys</p>
<p>coffee every day at a certain place</p>
<p>which I don't drink coffee so that should</p>
<p>raise red alarms everywhere.</p>
<p>But we already see this</p>
<p>with credit card transactions.</p>
<p>If I do something outside of the ordinary</p>
<p>of my normal buying patterns,</p>
<p>they flag it, right.</p>
<p>We should see the same sorts of things</p>
<p>when I'm accessing data as well</p>
<p>inside at different classification levels,</p>
<p>because I think you and I both know</p>
<p>I can gather</p>
<p>a bunch of data from unclassified areas</p>
<p>and one piece of data</p>
<p>from classified area</p>
<p>and create top secret data. Yep.</p>
<p>And have situational awareness</p>
<p>that no one else would have,</p>
<p>which would make me a threat in that case.</p>
<p>So I think I think we're going to see</p>
<p>an extension</p>
<p>to zero trust to a</p>
<p>I don't know what you would call it,</p>
<p>but it's almost like what is your access?</p>
<p>What is your zero trust access over time?</p>
<p>And are you</p>
<p>is that developing some kind of a threat?</p>
<p>I mean, user behavioral analytics,</p>
<p>UVA is hugely important.</p>
<p>We you're talking about</p>
<p>the concept of zero trust.</p>
<p>And, you know, that's that's</p>
<p>part of what you're talking about there is</p>
<p>yeah I know some of that</p>
<p>some of the super principles of</p>
<p>if the system is keeping track</p>
<p>and it notices that John Hunt impacts,</p>
<p>you know,</p>
<p>per minute in in the system.</p>
<p>And he's that's been pretty steady over</p>
<p>the course of his of his tenure there.</p>
<p>And all of a sudden.</p>
<p>He's talked for 100 words per minute.</p>
<p>Yeah, I'm type</p>
<p>And I'm trying to access</p>
<p>one of the most sensitive things</p>
<p>that my account has access to.</p>
<p>You know, that that that's a that's.</p>
<p>A really good that's a really good point.</p>
<p>Hey, John, this has been</p>
<p>absolutely wonderful, very enlightening.</p>
<p>Thank you again for coming on the show.</p>
<p>And of course, we're going to talk</p>
<p>about digital identity.</p>
<p>So you got to come back</p>
<p>or you're going to come back for me.</p>
<p>I would love to.</p>
<p>I would love to.</p>
<p>I've had a great time talking with you</p>
<p>both times now.</p>
<p>Digital identity is something that</p>
<p>I'm near and dear to me.</p>
<p>It's something I've been,</p>
<p>you know, learning more and more about.</p>
<p>So I would love to come in and talk</p>
<p>talk with you more about that.</p>
<p>Sounds great.</p>
<p>Thanks again, John.</p>
<p>And I can't wait to talk to you again.</p>
<p>Looking forward to it. Thank you.</p>
<p>Thank you for listening to Embracing</p>
<p>Digital Transformation today.</p>
<p>If you enjoyed our podcast,</p>
<p>give it five stars on your favorite</p>
<p>podcast and site or YouTube channel.</p>
<p>You can find out more information</p>
<p>about embracing digital transformation</p>
<p>and embracingdigital.org.</p>
<p>Until next</p>
<p>time, go out and do something wonderful.</p>

</details>

<details>
<summary> Published Assets </summary>


</details>
