---
layout: posts
title: An Argument for a Holistic Approach to Critical Infrastructure
number: 116
permalink: EDT116
has_children: false
parent: Episodes
nav_order: 116
tags:
    - Cybersecurity
    - Operational Technology
    - Critical Infrastructure
    - Data Management
date: 2022-12-15
guests:
    - Darren W Pulsipher
    - Dr. Anna Scott
    - Steve Orrin
img: thumbnail.png
summary: In this episode, Darren talks about the convergence of OT and IT cybersecurity with Security expert Steve Orrin and Industrial OT expert Dr. Anna Scott.
---

{% include soundcloud.html id="edt116" title="#116 An Argument for a Holistic Approach to Critical Infastructure" %}

{% include youtube.html id="DRGy_il_nUg" %}

---

## There is a real threat to Critical Infrastructure

According to Dr. Scott, OT organizations still use the traditional Purdue Model, which leverages air-gapped and firewalled-off networks. However, this model is starting to fall apart as IT and OT networks converge. Businesses are trying to get better insight into what is happening in their operational infrastructure. As a result, they punch holes in the previously well-isolated networks, exposing them to cyber threats. Additionally, cybercriminals are finding ways to circumvent air-gapped and firewalled networks.

Steve argues that leveraging IT best practices can help, but OT professionals and IT professionals have different motivators and operating models. Continuing to isolate your network is still a good strategy but should be one of many tools used in critical infrastructure cybersecurity protection. OT security should look at IT cybersecurity best practices for ideas to improve their networks and infrastructure.

## IT and OT differences impeding Best Practices

IT systems are traditionally updated quickly or continuously based on security profiles. One of the primary tools to improve security is basic security hygiene through patching operating systems firmware and software in the IT infrastructure. However, as Dr. Scott enlightens us, OT systems managing critical infrastructure cannot have downtime, and the window to update these systems is measured in years, not days. It is not uncommon in OT infrastructure devices that machines run for 5 to 10 years with no downtime, meaning no patch updates.

For example, in the oil and gas industry, refineries operate continuously for four to five years, have a one to three-week downtime for upgrades, and then operate again for four to five years. These operating models are not conducive to the traditional continuous security patching that IT organizations typically use. However, Steve elaborates on many other cybersecurity tools that should be leveraged when cybersecurity patches cannot be applied to existing devices due to their critical controlling infrastructure.

## Best Practice Risk Assessment
the primary cybersecurity best practice is risk assessment. Even though risk remediation may be different, the risk assessment process can be leveraged equally across OT and its environments. Steve argues that the first step of the risk assessment process is getting a complete inventory of hardware, firmware, and software assets in your OT environment. This first step is critical in evaluating your cyber threat position and assessing the risk your organization is willing to take. The next step is to evaluate CVEs against your known inventory.

It is critical to recognize that this is a continuous process and not to be done just once or periodically. Some OT professionals have argued that their OT environments are static and do not require ongoing risk assessment evaluation. However, Steve points out that even though OT environments may be fixed, the threat environment constantly changes, and business factors can change the organization’s risk position. Therefore continuous risk assessment must be done to protect critical infrastructure from bad cybersecurity actors.

## Dealing with OT Vendors

Another interesting factor in OT infrastructure is the shared security model with device vendors. In many cases, these embedded devices controlling multimillion-dollar critical infrastructure are managed to buy the vendor, not the OT professional. The vendor can only make cyber security patches and updates to the devices. This can sometimes lead to vulnerabilities in your OT environment, increasing the risk of cyber infiltration. Steve brings additional cyber security tools to help protect assets that cannot be patched with critical cyber security patches, including increase isolation of affected devices, deploying watchdog devices, and canary design patterns into the OT infrastructure. These tools can help protect and isolate the device to prevent the spread and access to compromised assets.

## What to do when you are compromised

So what do you do when you have a critical infrastructure that has been compromised? Can the organization handle shutting down the infected infrastructure? What business continuity plans are in place when hazardous situations occur? Can this be used when a cyber security event happens as well?

The key here is to isolate the infection as quickly as possible to minimize the impact on the critical infrastructure. I am decreasing the effect on the operating reliability of the necessary infrastructure. The goal is to reduce the impact and protect the safety of people and the infrastructure involved.

## Find out more
Continue to look for more podcasts on OT cybersecurity. Additionally, a whitepaper describes the challenges of converging OT and IT cybersecurity environments.
<details>

<summary> Podcast Transcript </summary>
<p>Hello, this is Darren
Pulsipher, chief solution,
architect of public sector at Intel.
</p>

And welcome to Embracing
Digital Transformation,

where we investigate effective change,
leveraging people process

and technology.

On today's episode,
an argument for a holistic approach

to critical infrastructure security
with our special guest, Dr.

Anna Scott and Steve Orrin.

Anna. Steve, welcome to the show.

Good to be here.

Thank you, Darren

I know it's hard to know who to go first
when I'm going to people.

To sort out at the same time say.

You guys have been on the show

several times, Steve,
I think I think you're my number one

interviewee.

I think. Anna, your second.

This is like your fifth time.

I think it's been a lot. Yeah. So.

And the reason I ask both of you
on today was I wanted to get

a different perspective
on critical infrastructure security.

First off, from a former CSO
and a security expert.

That's you, Steve, if you don't know.

And also from an industrial Iot

expert like you, Anna,
because you've been in the trenches

in industry trying to work through these

and critical infrastructure environments.

So both of you on together,
we should help figure out what's going on

as far as critical
infrastructure, cybersecurity.

So let's first get kicked off by

with you in a little bit.

Is is there a real threat to critical
infrastructure, cyber security,

or is that just a red herring or something
we're just hearing on the news

because there's nothing going on
in the news cycles to

know.

It's a huge it's a huge concern. Right.

And it's a it's a huge threat.

It it does depend a lot on

how the individual companies
are dealing with their systems.

Right.

There's still a predominance of the way
you protect

really critical systems is
you just don't let anything access them

through

through anything except
being in the same room with them.

So that that's a great way
if you can control around insider threats

because you have a very limited attack
surface

and you've got a great deal of control
in that space,

there's all sorts of reasons
why that just does not work

well in the modern world,

because that tends to prevent taking
advantage of a lot of modern technology,

especially when you get into
what you can do with analytics

and analytics across different data sets.

So so yes, you can continue
in that pattern, but you do that

at the expense
of not being able to take advantage

of those tools and bring that
competitive advantage into your space.

But as soon as you do that and you

connected to the Internet
or you can connect contributor systems,

now you've got a whole different set
of protections that you need.

And these tend to be things that are not
well understood and especially

where operational folks make the call,
which is what happens in the space,

then you have some real challenges
just in understanding

what are the real threats, what are the
real tools for to protect against them.

And the question that you addressed

with your paper, Darren, which is

can we really use I.T tools in this space
and use them to good advantage?

And I love that idea because I think
there's so much more that can be done

and much more that can be leveraged
to just deal with the,

the specific problems
that happened in the operations.

So, so what
what I heard a little bit there in is the

the Purdue model
that everyone's been using this isolation

either
firewalled off or completely air gapped.

That's a naive approach in today's

modern things because I need the data out.

Yeah, I hate to use my because I think
there's some really good reasons for it.

And I, I guess

having worked in situations
where where my life has depended

upon the systems working and not having it
having to be tampered with

and, you know, having malicious intent,
I, I'm pretty comfortable with that.

But I do think that there's a big cost
that goes that goes with that.

And so so it's really like getting
a good handle on your risk profile.

Like, I'm going to cite Steve here
because I love this so much.

Right?

It's like
if you try and figure out how to do

zero trust, what you have to start with is

what's your real risk profile
and what really matters, right?

Because if you take that type of approach,
then that helps balance off

what's really happening
when you do this connectivity

and you bring these assets
together. Right.

And so I think
you still have to do an assessment,

which is do those new capabilities

bring you enough value to overlay the risk
of the vulnerability of those systems,

especially when you know, one,
you're going to be constantly

trying to keep up with the hackers and all
of the new software and everything else.

And that is a pretty high request
and pretty difficult to do in some cases,

especially with organizations that don't
already have that type of capability.

And so really having a handle

on that relative to
what's the real benefit to your business.

Right.

So, Steve, she she quoted you,
you got to come in and cyber

and and also
I want you to address a little bit of

I call it naive and thank you, Anna, for
for correct me on it, but I still think

there's a little bit of false security
behind

a isolated network.

So, Steve.

So, Dan, I think Anna does hit it right.

It's understanding the risk profile.

I think one thing
and maybe naive is not the right term.

I think the cat is out of the bag.

Those systems,
that critical infrastructure is connected.

They're connected to IT systems.

They're being managed
in a distributed fashion.

They are getting tapped
into from the outside.

They're interconnected amongst themselves.

So the notion of a truly isolated
environment or a critical infrastructure

environment is actually a notion
that isn't true anymore.

In many cases, what's considered to be
an air gap of the old

or where you physically had space
is now more a virtual or logical air gap.

And then we're seeing attacks that can
jump that virtual or logical air gap.

And in many cases, the
what you thought was a logical or virtual

air gap is not an air gap at all.

And so

systems are much more connected
than they've ever been.

And so I wouldn't that's I call it naive.

I just say, like in some cases
it's already happened.

And so the question isn't, well,
should I open up my network,

your network,
because your systems are already open.

It's now how do I start to apply the right
controls and falling back on?

Well, I'm
just going to continually isolate

and that's been a major
approach is is a good one.

It's a tool.

It's not the only tool
and it's not the complete tool.

It's one of the tools.

So encrypting the network traffic
or providing logical firewalls to separate

networks that do network segmentation
is absolutely a great tool in the arsenal.

But it alone will not prevent
this kind of threats that these

OT and critical
infrastructure systems are seeing.

And so when you look at it
from that perspective, it's

okay, let's understand
the risks of the OT systems, understand

how they're different from the I.T systems
that many of these

security products and technologies
were originally designed for

and apply
those security controls in an old fashion.

I think that's one of the learnings both
from from the paper that you published

as well as what organisé tions
that are doing this right now are seeing

is leveraging its security capabilities
and controls

in an way.

So I think glad you said in an odd way,
because a lot of times I've seen the IT

professional, the CSO come in
with a hammer on the operational guys

and say you need to be secure,
update all your patches,

right?

Everything needs to be updated.

And Ana, is that doable?

Well, depends on
how old your equipment is, right?

Well, I mean, yeah,
some of this equipment is 50 years old.

Yeah.

And then there's a lot of diversity in it
as well. Right.

And so many of those systems were designed
so that maybe you update the firmware

once every ten years and you're going out
there with a USB stick to do that.

Right? Because it does.

Does that scare you, Steve,
when you hear that ten years

you haven't updated
your security patches in ten years?

And I wish it was something
that was novel, but we see this often

in OT edge environments, even in systems

that are supposed to be it
related, but are driving those.

So that's actually an interesting point

is when you go
look at an industrial manufacturing line

or you go look at a smart city
or any of these sort of operational

technology, critical infrastructure,
and you go look inside

the cabinets, you go look,
it looks like an I.T system.

There's a rack of servers in there
now that are driving those technologies,

monitoring them, doing the the
the operations that once was very analog.

And so that the scary part
is that those i.t systems

do need to be patched regularly.

They do have vulnerabilities.

But as I pointed out, there's a reason
why they don't get patched

the same cadence that standard i.t. Yeah.

And why is that a why?

So they really weren't designed,

they weren't designed with this whole idea
of you're connected

all of the time and you need to
be constantly updated. It's

what is

the difference between
streaming on your music, on your iPhone,

right,

where you're connected all of the time
and everything's completely up to date

and having an old iPod
where you can load it up once

and then run that sucker
until it died, right?

Or until it just really needed attention.

So and I shouldn't have you start because
that's not how you fix the old system,

but it's just kind of the idea.

It is
it is a just a completely different world.

If you are living in a space
where you're constantly connected

and so much of the legacy equipment,
it was never designed with that in mind.

It was it was hardened
in a way that once you install that,

you could really keep it going for a very,
very long period of time.

And so you have this much longer lifecycle
like so.

That the applications
that are being supported by the systems

are very different from it.

So if your email goes down
for a couple of hours, it's no.

Big deal.

Life goes on.

But many of these critical infrastructure
that are driving your power, water

treatment, you know, life
saving devices inside hospitals,

they're not meant to be taken down
by a patch that, you know, that didn't do.

It's quality assurance to the same level
and the regular cadence of being able

to do things and bring things offline
and bring them back in.

That's a modern i.t concept,
but these systems were meant to,

like I said, run for 15 years nonstop

and that's not something that is easily,

you know, deployed patches
or to be able to do, you know, inspections

and security tools that get in the way
of the operational technology.

And that's again
why I talked about it in an odd way.

So it sounds to me like there's
a total mismatch in motivation

and in in results in the space right?

High availability.

We're not talking
three nines, we're talking 12 nines.

Right.

I don't want I don't want a heart monitor
or a heart machine

to oh, I need to reboot
or I need to reboot every three days.

You don't want that.

Or even your power grid
you really don't want down.

So because the
because the motivation is so different,

can I really use
the same techniques in I.T in O.T.

or, or do I just go and I understand

the isolate myself
because I don't want any change.

Things are working.

Don't bother me. Right.

Isn't that how it's done In a.

Probably way too often.

Right.

And there's definitely a risk associated
with trying to fix your problems.

Right.

The same way there's risks

with just continuing to do nothing
and keeping your fingers crossed.

There's a lot of very clever people
that still want

to find ways to disrupt systems,
even the legacy systems.

Right.

And in some ways, many of the legacy
systems are more vulnerable

because they were designed before
modern hacking was really happening.

Right. So there's just some
some real concerns there.

But I do think that there's a real place
for having the i.t.

Tools, right?

Like, there's a lot of tools that can say
i'm going to look

at the network, I'm going to identify
everything that's on the network.

I'm going to identify
what is the current level of firmware.

And then if it's set up properly,
you can say what is,

what should be the current version
and where do you have gaps in

some of the tools where you're actually
sophisticated enough, where they can say,

What's your real risk associated
with not having those updates in place?

And when you get into that level
of sophistication and that becomes

very, very valuable, right?

Because now you have a clear picture
of what's going on

and then you have a way
to actually prioritize that risk.

Granted, I don't know that you ever want
to trust another company to do that.

You probably want to be
at least understand very clearly how

the software made the decisions
about where your risk really lies,

because there's no way a software
company knows what each of your individual

components are really controlling
and how how critical those can be.

So so you got to stay very involved.

Right?

But if you have that type of assessment,
at least you can start out and do that.

And my understanding is that's pretty
common on its systems, right?

There are tools that can do that, and
there's lots of tools that can do that.

So at least you're not just having
this big black box

and a bunch of question marks.

You can say,
let's start doing that assessment.

And if those types of tools
can find things on your network,

that means somebody who's coming into that
environment can also find things, right?

So you really do want to understand
what's discoverable

and what is its current status and
and then determine where you take this.

So that brings up
one of the best practices

that we know about in its cybersecurity,
which is risk assessment.

And Steve, can you talk a little bit
about risk assessment?

Because I know
if we ran a vulnerability scan,

there would be tens of thousands,
hundreds of thousands in any company.

You can't do them all.

So this is where
the risk assessment comes in.

So can you explain how I can leverage the
IT risk assessment?

Best practice in the OT space as well?

Absolutely.

And so it really starts
with what Hannah was talking about.

You can't secure what you don't know.

And so starting with the asset
inventory, the discovery

to understand what your assets are,
understand what's running inside the box,

what you know, what firmware,
what operating systems, what versions

you need to create that asset inventory
to be able to do the next phase.

And before you even get to your security
considerations, the next piece of this,

this is actually defined as part
of the next cybersecurity framework

is once you know what your environment is,

understanding what's what they're doing,
what is the purpose of those systems.

And this is important.

When you do your risk calculation,
you need to know what are your mission

critical, what are the necessary
support systems to keep those mission

critical systems operational
so that you can create that risk

profile and understand the prioritization
of applying the security.

So before you ever get to your first

encryption key or firewall, it's
knowing what you have in great detail,

understanding what those systems
and processes and technologies

do for your business,
for your mission systems.

And then from there
you can start to apply a risk calculus.

And that risk takes
from published vulnerability.

So databases,
there's new technology, new standards

and formats around softer built
materials and vulnerability.

And in our exchange called VEX, to be able
to give you information about

what's the vulnerable state
of the components, there's

a lot of great information out there
already in the might or frameworks

to let you do
the assessment of what you found.

So no, this version of Linux
has got this level of vulnerability

or this particular product over here
has these cves that I need

that haven't been patched in the version
I have.

So you get that information now
you have what you have, what's it called,

what's critical in your organization
and what the known vulnerability,

the other side of the risk assessment
besides the known form is understanding.

And this is where things like pen
tests, scanners and other kinds of tools

give you an idea of what
your overall threat landscape is.

Those come together
into understanding your risk profile.

So I understand what my current assets

are, what the known risk,
what the potential risk,

and then the what these things
are usually important for helps

guide the prioritization of, okay, now
I need to start planning security tools.

And it's only at this last phase

that you start applying
process, technology and procedures

to do the compensating controls to reduce
or mitigate

the risks that you've identified.

And that's your standard I.T flow
that I've been describing

can be absolutely applied
to the OT systems, understanding that the

what you actually implement the process,
the procedures have to be done

in that way.

So it's not going to be well,
I'm just gonna push a button

and patch everything or I can just put a,
you know, an encryption system onto

or an enterprise product
on to that, that PFC device.

You have to be able to apply
the right kind of controls,

but it's only at that last phase of the
process of assessing the risk environment,

your risk posture,

and then the prioritization
that your assets tell you about that,

then you can start to make the decisions
and applying budgets and actually building

your capacity and capability
to mitigate the controls.

And it's not a one and done this,
not like we're finished.

We did our assessment. Okay, we can go
back.

It's an ongoing, constant process because

even if you're in a nice, structured
environment, that never changes.

For 15 years,
the threat landscape is always changing.

Your app threat, your risk appetite
is actually always changing.

What's happening in the macroeconomic
world changes regularly.

And so reassessing and reevaluating.

Are your controls sufficient?

What's next on the list
Prioritization list to be addressed

and verifying that you're mitigating
controls are in fact doing what they said

they do are all part of the ongoing
process of securing your infrastructure.

Whether that's it or not.

I want to
I want to reemphasize what you said there.

Even if your own environment is static,
the threat environment changes

and your business motivators
can be changing too.

So you have to constantly evaluate
and nothing.

I like that you said to let's say
that I have a certain version of Linux

that has a security vulnerability
across it

and it doesn't mean
I'm patching everything on the outside.

It may be I can't patch that
because name the critical infrastructure,

so I have to come up
with a different remediation

for that device, a.k.a locking it down

completely as far as network and monitor

the firewall around that one device
more rigidly.

That might be a different remediation
than doing the patch for example.

So Darren, so two things we've seen
successful inside of environments.

These two terms
I'm going to use of that new kind

of mitigating control when you can't just
flip a switch and turn on encryption.

One is what I call watchdog approach,
where you take a modern system,

put it right up next to a legacy system
on the wire so that they can monitor

and have the advanced inspection
and detection in.

Particular, watching everybody.

On behalf of the device
that it's proxy in.

And the other approach that's often used
is what I call the canary approach,

where if you've got an environment
where you have a segmented network

of legacy systems that are hard to patch,

you can't get the right
the tight security controls.

You put a detector in there on the network
that has

those does advanced detection
and B, it becomes the canary for that.

That segment.

So it will alert, whereas legacy systems
don't have the capacity to alert

or to tell you that something is
being attacked or are being targeted.

And so that watchdog in Canary
combination is a different

kind of compensating control
that is very popular in O.T.

because it doesn't require going
and changing that policy itself.

It's about adding the right i.t
capabilities into that environment

to to proxy those systems
and to give them the capabilities

without impacting know mission
critical functions.

And there's also another thing I heard.

I was talking to our own

OT organization

and they were saying
we actually can't patch

some of the devices in our infrastructure

because we're not allowed to

because it's the vendor, right?

It's their machine, right.

If we touch it, then
our warranty on this multimillion dollar

particle accelerator
or whatever it is, right,

is is now null and void. Right.

We can't we can't enforce

some of our security things
on some of these embedded devices.

But we know that there's
a vulnerability in there.

Right.

Is that a common thing that you're
seeing as well, or is that just unique to

these really huge,
you know, manufacturing or fab

OT systems?

So I think it can definitely be
definitely be the case.

You know,
like a lot of on the industrial side,

what we really worry
about is the control systems

because because that's where
you can go in and mess with things, right?

Otherwise you have to.

Be that's where you're messing
with the physical world.

Right. Exactly.

I'm sorry.

I just got a call. So.

So updating those control systems, you're
not going to be doing that in isolation.

You're going to be doing that in close
coordination with who the vendors are

and make sure that you've got a plan
that you've executed with with them.

The other thing I wanted to mention,
because we haven't talked talked about it

yet, is often in the oh two systems,
your only window for really doing updates

is when you're shutting down
for planes, flat maintenance.

So that's another factor that comes into
it is you really do have to say,

well, when I worked in
refining, we did turnarounds

between three and
five years, depending on the type of unit.

Literally all of the updates
to major systems had to fall

within the three week period of turnaround
because that was the only time

it was really safe
to go in and change those systems.

And it was also the only time
we could actually test them to say,

Hey, we've just made this change.

Is it really ready to come back online?

And so those intervals around the planned
maintenance can also

be extremely important
as well as the point that you brought up,

which is then talk to your vendor, right,
when they're part of those

critical systems.

Because because they will
they will have strong opinions, Right?

I'm sure they will about. How to do that
properly.

Now, in a refinery where you work,
how how often are these turnarounds?

How often do you get to do that?

Once a year, six months, three years,
four years?

Well, typically, the

kind of
average cadence was about four years.

If you're really stretched on
profitability,

you try and push it to five

just because those are
extraordinarily expensive.

But yeah, so about a four,
four year time frame, right?

So if you can imagine,
you've got a control system

that's running everything

and you only get to touch it once
every four years, right?

That's that's. Crazy. You touch it.

Now you've got a window that's
maybe if you're lucky, it's three weeks.

And if it's somebody you can do the
maintenance maintenance on really quickly.

It's like one week, right?

So fit and everything.

You've got to change in a one week period
and you got to plan for that because you

know, your next opportunity for an update
is also going to be four years.

And it's a similar cadence
in a lot of military systems

as well with the tech refresh
as being once every three or more years.

One of the techniques
that we're seeing being adopted by

a lot of the more advanced organizations
and we're seeing vendors

actually supply this to their customers
of some of these

environments
is what's called a digital twin.

And the idea is that you have
a digital virtual version of that physical

asset of that policy or that controller
that you can apply changes,

you can do patches too,
and run simulations and basically run it

through its paces to see what impact
it may have on the digital twin version.

Now it's not you're still going
to want to do physical or testing,

but allows you to do a whole lot

of pre-loaded tests
before you ever get to touching that

that system
where you got that one week window

to do all of your testing
and all of your patching.

And so we're seeing digital twins come up.

I've seen them
in the construction industry.

I've seen, you know, in facts
where there's digital versions of those

that are supplied along with the product
for the contractor to basically run their

their simulations both from a patching,
but also test on load,

be able to look at the environmental
conditions and changes there

and be able to do those tests
in a virtual simulated environment.

That's one technique that can actually
be applied to security patches as well.

You know, we're also seeing
I've been approached by a couple of state

governments
to set up a site in cyber range

where in their

primary focus
has been on the electrical grid system,

which I found totally fascinating.

Right.

They want us to help them
establish a noticeable range

so they can test out
some of these new architectures

that we're talking about,
like the watchdog, the canary,

the the data diode and some new ones

that we're talking about around
one is called the

the patch here or the patch

airlock pattern,
which is an interesting pattern as well.

Do you even with these things,
we still have this long cycle time

between being able to to update

and A, do you ever see us
where we could do continuous

updates
on these critical infrastructure systems

or is there
just too much risk involved in updating,

you know, controllers
as there as they're operating?

Yeah, And I think, yes, with time and
a lot of it's redundancy of capabilities.

Okay. Right.

There's a
the there's been work going on for

it might even be seven years now

that is the Open process automation forum

and they have been leading
a consortium effort through the Open group

to really do a modernization
of control systems

for not just refining
but chemicals and pharmaceuticals

and kind of all the groups that use
those sophisticated control systems.

And there's specifically addressing this.

Right?

They've got a whole cybersecurity
subcommittee

that much of it is really coming down
to what's the design,

How do you have the redundancy set up
so that if you lose one

capability, do you have jail over
within the timeframe?

That's important.

So that does it kick out your equipment
because a lot of equipment,

if it loses a signal like a
to a power failure or even a power blink,

that'll just take it down.

So there's

there's some real hard and fast rules
there.

I think all of that is fantastic.

But I'll I'll kind of add on top of that,

the next thing that has to happen
is people have to trust those systems.

And so once they've got a good design
and they start doing those testbeds,

there's going to be a lot of rigorous
testing that goes on for years

and then deployments will be in very low
risk systems where

if you do have something, go on, go down
that it's know.

No one's going to get hurt.

No one's going to get hurt. Right.

So, yeah,
probably start out with wastewater

because wastewater is pretty
you know, it's you don't it's smelly.

That's about. It.

Well, you can kill your bugs,
but then it's easy to recover from,

or at least it's recoverable in ways
that other other technologies aren't.

So, yes, I think we will get there.

But it's it is a slow process.

You know, we.

Can't put too much reliance on
patching is the only compensating control.

I know that the security created
a lot of toxic patch.

Your system
and security hygiene is important.

Absolutely.

But as we're as end is indicating,
you don't you can't rely on that

as your only major compensating control

and that's why
when we look at an OT system security,

it's got to be an overall evaluation
from the security aspect,

not just can I patch the operating system,
the firmware.

Well, I think that's the number one tool
that it uses, right, for security?

It is. It's one of many categories.

And that's really the goal
here, is finding out the right security

control, the right security tool
to mitigate the risk.

It's not always going to be in the case
of what we're talking about,

it often can't be it can't go for years.

And that's four years of risk
that you should not be,

you know,
are accepting within your organization.

So that's where, you know, segmentation
encryption, strong

authentication inspection detects
and prevention, all these kind of things

come into play, providing the

surrounding controls to compensate
for the one that you can't use, which.

Is that you can't touch them. No, no, no.

I like to add another thing
in the OT space.

I know it's very different in i.t.

If we have an asset
that has been compromised,

we typically we isolate it.

After we've done some forensics on it,
we isolate it right?

Then we restart it,
we clean it and restart it.

That's a typical pattern.

I can't do that in the old space.

Right. I can not.

Easily not know
without a great deal of expense.

And we're taking other things
down with it. Right.

So unless you're super lucky.

Yeah.

So what approach
can I use in the Iot space if I know that

I have a device that's been compromised,
what do I do?

I if I can't take it down
because maybe I am

a policy controller in a refinery

and we know once you set a refinery down,
it takes a long time to bring it back up.

Right.

So what do I do and

what techniques do I have at my disposal?

Yeah,
and I'm trying to think through that.

And and I have to say,

that is a really good question
and what I've never asked myself.

And so I'm hoping Steve hasn't.

I'm up all night worrying about stuff.

Like this, about this,

because that's a that's a super tough one

because besides higher monitoring you

and then trying to add something else
into the chain that allows you to see

to see if that is really being exploited
or it's what the real status is.

I have no good answers for you.

So let's make a distinction
between something

that you find to be absolutely vulnerable
to an exploit

and something that has been
has been exploited.

Okay, that's fair enough.

So you've got a known vulnerability
that's active exploitation in the field.

There are controls
you can put in place to isolate

signals and inspect the traffic to

and from a device
to monitor it for aberrant behavior.

There are things you can do today
and you can do that.

The IT world.

You can do that. The world.

Oftentimes you have to do that
when you have a known vulnerability

that doesn't have a patch.
But it's active exploitation.

In the case of a zero day,
you don't have a patch, but you can turn

on, you know, turn the dial to 11
on the infrastructure of security.

Like long log log.


In the event that you have a OT system
that has been compromised.

So you're detected the aberrant behavior.

You've detected the signature
of a OT style attack

or you've noticed
the firmware has been swapped out.

That's where, you know, again,

in the good parts of systems that they're
highly redundant and often place.

So that's where you're going to kick in
your your process and procedures

that you have for
if it was a non cyber event, if it was a.

Physical,
if it is a physical event. Gotcha.

So it's the same way is

when if a power station goes down
because of a weather storm,

you have redundancy
built the system to help handle the load.

If you're under active, explain your bet.

You have been attacked.

You've identified a a power generator or
a transformer that has been compromised.

Kick in the process
you already have for dealing with the

every other kinds of outage

and take that thing offline
before it can infect the neck.

And we've seen
where cascading events can happen,

where you get one OT system, in fact,
because you don't have

often the inspection tools,

the lateral movement
can be a lot faster to the systems

that it's connected to because again,
there isn't the same level of controls

once it's into that, you know, it's
the old adage of the the egg,

you know, you've got a harder shell,
but once you get in, it's nice and soft.

OTI systems are often the same way
once you get past the door on one of those

key mission critical air

systems is compromised.

You may have to take a lot of it
offline, but

again, it's that's
where you kick in the existing processes.

And one advice that we give to CISOs
and organizations is game the system

before you ever get a vulnerability
or an exploit you have to deal with,

run the war gaming on your environment.

Actually, you know, identify a policy
and have it be quote unquote

taken out and run the course
and see what would be the problem.

Make sure you've covered all your bases
and you know what

the procedures and people
all the way at the tactical edge

and at the executive level
all know their role in the event

so will make
when it does that much smoother.

So what you're telling me is run
my own business continuity scenarios.

That's which makes.

Yeah. And I have to have them.

There's a really good context
for doing that.

Every manufacturing facility,
at least in the U.S., is required

to do what they call has ups,
and it's exactly what Steve described.

They don't tend to focus on cyber threats,
although I'm

sure that's that is definitely evolving
and that is happening now.

It tends to be more, hey, this pump fails
or we had a power failure or a.

Hurricane or tornado hit somewhere.

But it's very easy

to take that methodology and say,
now let's apply that to our system.

It's been hacked and it's been hacked
in these particular ways.

Now, what does that really mean?

And what is going to be our response and
how can we design in mitigations, Right?

And how can we change our system?

So so if it does happen,
there's much less vulnerability, right?

Or it's back to can we
can we live with that?

Because some things you can live
with. Right, right, right, right.

Guys, this
has been this has been very insightful.

As always. I love talking to you guys.

Any last words for our our listeners

today
on that are dealing with this opportunity

so things what would your advice
be to them that are that are dealing with

you know this convergence
that we're already starting to see.

We'll go with you first, Steve.

Okay.

So I think,

you know, just restating what we said
earlier is that it is already happening.

It's not a wait and see
when when this happens.

Your AT&T systems are blurring.

And so it's take to take
the measured approach

of understanding your assets, providing,
you know, doing the risk assessment

so that you can apply proper controls
and security

to the systems
you have and start planning for it.

And then the key is get out of analysis
phase, get into implementation.

So get, you know,
knowing that this is going to be ongoing.

If you spend all your time
analyzing your environment

and not only your time actually

implementing controls,
you're never going to get anywhere.

It's a feedback loop.

So you you analyze and you go deploy
feedback into the analysis and continue.

So it's going to constant processes
and continuous security assessment.

Is not a one and done.

It's not a one and done and the you know,
the key thing is to start deploying

the security now and getting that
visibility into your environment.

Is that the first step in being able
to understand what's going on

and what your risk posture is
and what your risk and be able to

then manage
that risk across your own enterprise.

Sounds good to Ana.

Yeah, and I would say on the O2 side,

you as an operational companies
start bringing in your I.T folks

and treating them like they're part
of your operations and make sure

that they understand the implications,
make sure they are equally involved

in all of these discussions
because the there is no longer,

as you know, a reasonable
that treats them in a

in isolation and just has them
worried about your pieces.

They they need to be integrally involved
in what's happening

and they need to help bridge the gap
between what we understand

of the operational systems
and all the electronics

and all of the compute
that's necessary to back that up.

Thanks, Santa.

I think that's that's absolutely critical,
I'd say on the CSO side as well.

Bring the OT guys to sit at the table
at the top of the table with you

because I've seen this before

where C so mandates down to the OT guys,
you will do this.

And they're like, No, we're not all right,
But if you're sitting at the table

with them at the front of the table,
then they have a say.

Then you can talk about the differences
and really take a look at the paper.

It is on on the website, we talk about
the differences between opportunity

and how we're going to get over this,
this division. So.

All right.

Thanks again,
guys, for coming on the show.

Thank you, Darren
Thank you, Darren Pleasure as always.

Thank you.

Anna for your insights.

Thank you for listening
to Embracing Digital Transformation today.

If you enjoyed our podcast,
give it five stars on your favorite

podcasting site or YouTube channel,
you can find out more information

about embracing digital transformation
and embracingdigital.org

Until next time, go out
and do something wonderful.

</details>
