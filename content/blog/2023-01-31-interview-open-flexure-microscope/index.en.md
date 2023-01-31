---
title: 'Interview: Open flexure microscope'
author: 
  - Open make interview team
  - Julian Stirling
date: '2023-01-01'
slug: interview-open-flexure
categories: [interview]
banner: img/banners/flexure.jpg
tags:
  - technology
  - open hardware
  - personal story
editor_options: 
  markdown: 
    wrap: 72
---

# Interview: Open flexure microsocpe

*by the Open make team and Julian Stirling. Copyright to the authors,
distributed under a CC-BY 4.0 licence.*

**Sections:**

-   [The project](#the-project)
-   [The Hardware](#the-hardware)
-   [The Research outputs](#research-outputs)
-   [The participants](#participants)

> Interviewee: Julian Stirling
>
> Interviewers: Robert Mies (TU Berlin) & Moritz Maxeiner (FU Berlin)
>
> Transcription and editing: Diana Paola Americano Guerrero, Robert
> Mies, Moritz Maxeiner & Julien Colomb

<img src="images/screenshot.png" alt="Screenshot of the interview." width="60%"/>


*Screenshot of the interview.*

# the open flexure microscope

The OpenFlexure project makes high precision mechanical positioning
available to anyone with a 3D printer - for use in microscopes,
micromanipulators, and more.

Its core developement has been mainly organised by Julian Stirling in
the UK, in cooperation with a group in Tanzania.

{{< card "The open flexure microscope in a nutshell">}}

<img src="https://openflexure.org/assets/ofm-photos/ofm_6.1.5_wide.jpg" width="100%">

*image of a built microscope*

Project start: 2016 Core development team size: 3-5

### Hardware products

The OpenFlexure Microscope is a customisable, open-source optical
microscope, using either very cheap webcam optics or lab quality, RMS
threaded microscope objectives. It uses an inverted geometry and has a
high quality mechanical stage which can be motorised using low cost
geared stepper motors.

### Hardware maturity

I'd say, sort of 80 to 90 percent of the way to product ready. In terms
of performance, its product ready. We've done clinical evaluations that
it's good enough to diagnose malaria.

### Rebuilds

So far, it's been used and built on every continent, including
Antarctica in at least 40 countries. 250 people participated in the
forum, but it is difficult to know how may built the microscope. We
assume there are thousands of microscopes out there, but we don't know
for sure.

Lab Maker, a company in Germany, has just started selling the parts kit, not the printed parts, just the fasteners.

{{< /card >}}

## The project

{{< card2 "Project process">}}
We're very interested in medical microscopy, where to diagnose malaria, you need to look at 100 fields of view with a x100 objective and count the parasites. So it needs to be automated and reproducible.

Rather than looking at how professional metal motorized microscope are made, and building a cheap imitation, the whole thing was designed for being 3d printed from the ground up.

We are now moving on to the stage of improving the software and making it more robust as we get towards production.

The aim has always been around local manufacturing and to be maintainable : it’s not just about building it in Tanzania, it’s about being able to make the parts and service on site.
{{< /card2 >}}

> How did it all start with the OpenFlexure Microscope project?

{{< expand "Show answer">}}
I joined the open flexure microscope project: it’s building a microscope that’s 3d printed, the optics are not 3d printed, but the rest of the mechanics is.
Indeed microscope optics haven’t changed that much, for a very long time. They’re quite standard, the components are very easily available and quite standardized. Whereas the mechanics is very difficult, you’ve got to position the sample, you’ve got to position the objective relative to the sample to sub-micron accuracy. Or at least, in one direction, and you then need to move the sample around very precisely.
There are different ways to build a stage that is that accurate, but a lot of them involve very expensive machining processes to make very sort of flat ways for dovetails. What we’ve done, or what Richard had done even before I started, was to create a flexure stage, which is a monolithic part that you print in one go. It does the X, Y and Z translations, by bending of plastic.
Then you’re not limited by the fact that the 3d printer produces sort of very rough surfaces. So rather than looking at how professional metal ones are made, and building a cheap imitation, the whole thing is designed to 3d print from the ground up.
There are a lot of projects, which do open microscopy. But a lot of them might fall into the category of “cool tools”: you can stick a thing to your phone or move around this little thingy. These tools can produce really great image, but what the users don’t show you, is the time spent poking it, swearing, getting angry, shifting it around, before they eventually got an image that was worth sharing. And we’re very interested in medical microscopy, where to diagnose malaria, you need to look at 100 fields of view with a x100 objective and count the parasites. You don’t want to be sitting there fighting for every single image. It needs to be really reproducible, so you need a motorized microscope. And we’re now moving on to the stage of improving the software and making it more robust as we get towards production.

The open flexure is a digital microscope. So the computer is obviously not 3D printed, the camera is not 3D printed, the motor drivers are not, the screws are not, but the main custom components are. You take the camera, the objective, some standard motors and then all of the custom mechanical parts are 3D printed. The only exception to that is a couple of electronics parts that are custom.


{{< /expand >}}

{{< card2 "Project start" >}}
The project started as a hobby project for Richard. We got a research project which is how I became employed about two years later. Also on that research project, there was some sort of wider team around some other low cost instruments, but the main open flexure team was me and Richard and a group in Tanzania.

{{< /card2 >}}

> So could you describe a little bit the overall process to us?

{{< expand "Show answer">}}
It started probably about five or six years ago. The project started as a hobby project for Richard on a Friday that somebody showed him a 3D printed microscope and he wanted to show that he can 3D print more of a microscope. Then he got interested after talking to some people about water testing whether it would be useful if you could actually make it in countries where access to microscopy is hard. We got a research project which is how I became employed just over four years ago. 
Also on that research project, there was some sort of wider team around some other low cost instruments, but the main open flexure team was me and Richard and a group in Tanzania. We've been very much interested in building it locally in Tanzania and it's not just about building it,  it's about being able to make the parts and service themselves. Because one of the biggest problems, if you look at medical devices in Africa, is that about 70% of them are non-functioning because people can't get spare parts and people to fix them. So the aim has always been around local manufacturing and to be maintainable. There were about three people working on that project which finished a couple of years ago. We are still in contact with them and they're still working on the microscope, it's maybe not their main focus because they don't have so much funding. But I mean, for example, I talked to Paul this morning, we're still very much in contact. We've got two PhD students in the group, though only one is focused on the microscope. We've had other postdocs in the past and we had a technician. But as always with academic projects it sort of grows and shrinks based on based on grants, but they're still very active.  Richard used to be in Cambridge when he started it.  We've got different versions of the microscope, one which we call the Delta stage which is largely developed by Sam in Cambridge who's a postdoc and the malaria research grant where we're looking at how we use the microscope. We're doing a lot of that with the Ifakara Health Institute in Tanzania. Besides there are some other people in Cambridge on that project that's what pays Sam. It's always hard to work out who's the core team and who's peripherally involved. We've got some other collaborators in Peru who are using it and feeding back. Daniel Rosen is a pathologist in America who is very interested in the microscope. While they've never been on a grant that's funded by us, they're definitely some of our core community that feed back into the projects. It's very hard to estimate how big the project is because it's where the cutoff is from community member to a core project team.
{{< /expand >}}

{{< card2 "Funding">}} 
We’ve kept funding going or I wouldn’t be here.

There have been a series of different grants which are maybe not such big grants. Besides our first couple of big grants were from something called the Global Challenges Research Fund.

It’s generally been government funding, we’ve looked at a few smaller charitable things, but it’s very hard to make charitable grants work inside the university because at universities it costs a lot to employ someone and charge all sorts of extra costs.
{{< /card2 >}}

> Did you keep the project going through lots of smaller grants? You
> said it was done three years ago? Is the project finished, then?

{{< expand "Show answer">}}
I joined just over four years ago, we probably finished that specific project about two years ago. But then we had the malaria project, which was using the microscope for malaria, finished later than that. And there have been a series of different grants, which are maybe not such big grants, but for instance, one for the university to try and translate research into impact. Basically, the size of the team varies, but we've always had enough funding, therefore at least I haven't become unemployed yet.

We've kept the project going through lots of smaller grants and sort of peripheral things. I mean, my main focus is the microscope. But for instance, a lot I do is developing a program for writing our documentation since we had lots of different versions of the microscope. The setup differs in variations or configurations, you have the low cost one, the high cost one, if you want to modify it for fluorescence or to be an upright microscope. We trying to keep all of those different types of documentation in line and consistent. You end up having either one giant document which reads like a computer program, if you're doing this, then this, else do this. It becomes impossible for anyone to follow. Or you end up with lots of independent ones which are each differently out of date. Therfore we've ended up writing our own program for managing the different configurations. A lot of my time has been on that which is definitely for this project, but we hope to be more generally useful for other people as well.
{{< /expand >}}

{{< card2 "Hardware importance">}}

I mean, my main focus is the microscope. But for instance, a lot I do is
developing a program for writing our documentation since we had lots of
different versions of the microscope. We had a malaria project, which
was using (and modifying) the microscope.

{{< /card2 >}}

> Are those like government grants, or are they like from independent
> entities like GOSH or where do these grants generally come from?

{{< expand "Show answer">}}
Our first couple of big grants were from something called the Global Challenges Research Fund which is a UK Government Fund, it was part of the UK's aid budget. It was sort of both the aid budget and the science budget. It was trying to get scientists and engineers in academia, to focus on global challenges that would be aid funding eligible. If you take a charitable view of it, it was a very good way to get new people looking at development projects. You could also take the less charitable view that it was a way to double count the same money into government budgets. It would have been less rude if they just not double counted the money, but I think it was a good scheme.  That's where a lot of our money came from. Even some of the small funds went to universities to decide how they carry on the impact from these global challenges research funds. We got some smaller pots of money that we were only competing inside the university for but they were back eventually funded by the the government and then the current one. I can never quite remember what project I'm employed on, we had so many small ones. But generally, the impact ones are also the smaller ones which been decided by the university. But anyone that got funding from UKRI which is the government agency that gave us the global challenges Research Fund money, can apply for this impact grant which also comes from the government. It's generally been government funding, we've looked at a few smaller charitable things, but it's very hard to make charitable grants work inside the university because at universities it costs a lot to employ someone and charge all sorts of extra costs. You start telling a charity: "Hey, here's what we want to do." And the cost of doing it is always too high, by the time you're paying somebody to do it in a university. That is the reason we never seem a good value for money. Maybe if we find the right charity, but so I suppose that's a long way of saying mostly government funded.

{{< /expand >}}

{{< card2 "Major issues">}} 
I think one of the big problems is we just don't have the adequate hardware design tooling.
For instance, we’ve always done our CAD in OpenSCAD.
It does mean that we get some members of the community which can’t contribute because OpenSCAD is hard to learn.

Then, as I mentioned, there's a lot of problems with how we do documentation. I think documentation is just hard. But, there are some tools to help manage that: being able to openly share a design, have people track how it changes over time, have people contribute.
{{< /card2 >}}

> What major issues overall have you come across then? And how did you
> resolve them?

{{< expand "Show answer">}}
I think one of the big problems is we just don't have the tooling. Thus we've always done our CAD in OpenSCAD. Partly because physicists tend to program and think in sort of mathematical functions. I'm trained in CAD. I used CAD before I got here and found it a bit of an adjustment to use open SCAD. But then, being a physicist, I was generally fine with it. Besides it does mean that we get some members of the community which can't contribute because OpenSCAD is hard to learn. It does also mean that people become angry at us that we won't share certain types of files that OpenSCAD won't do. And trying to explain that we're not being secret and hiding the STEP file, it just doesn't exist, is a fun discussion with some members of the community. But the benefit of having used OpenSCAD is that things like GitHub and GitLab that track how your code changes over time, worked very well for us. For a really complex project with lots of parts that can make different people be working on and you can actually manage your merge requests and conflict management granularly inside Git. This is very hard to do for a graphical card unless you've got your proper PLM (Product Lifecycle Management) type program for doing all of the version management. And, you know, having sat in an office with people using SolidWorks vault shouting at each other, because they've locked a file the other one wants to use. You can avoid all of that with openSCAD and Git. But it does mean that the project, if you come to it, as an engineer, without a lot of background in software engineering, it can be quite confusing, because we're basically using software engineering processes to manage the hardware design. Then, as I mentioned, there's a lot of problems with how we do documentation. I think documentation is just hard. But finding tools to help manage that is  the whole ecosystem for being able to openly share a design, have people track how it changes over time, have people contribute. And of course, people are always upset if you don't want to do it in their favorite CAD tool. So it really is tooling that  holds us back each time we move the project through to the next stage. Because if you move through to having a bigger community, you have to worry more about how you manage that. You move through to having more software and different releases, you have to manage that. More people using it, you need to manage the software releases even better. And then as you get towards what people want to use for production, there's a whole of different levels of complication and tooling that you realize you don't have. I think we're on the bleeding edge of trying to turn something like this into production while keeping it. It would be very easy if you went through production publication and ignore the process openess, well, that's the end of the open hardware. But trying to keep the entire process open as you move into production is, it means that you start inventing processes and tools.
{{< /expand >}}

## The Hardware

{{< card2 "Hardware components">}} 
The microscope is mechanical and electrical, in terms of it’s a motorized microscope, it’s digital.
The mechanical parts of it, there’s quite a few. But most of the mechanics is in one single part, the main body. Then there’s peripherals like, we’ve got some gears and somewhere to mount the illumination and somewhere to mount the objective and a little base.

We run a client server architecture where on the microscope is a server that deals with all of the interaction with all the different pieces of hardware. That has an API.

We’re hoping, as we move towards microscope version seven, there will be something that can be sold as a product by Lab Maker and definitely others.
{{< /card2 >}}

>What products have you developed now, in terms of like, different
components? Mechanical, electrical, and software? Could you briefly
outline that?

{{< expand "Show answer">}}
The microscope is mechanical and electrical, in terms of it's a
motorized microscope, it's digital. We've got a lot of electronic off
the shelf components, it's a lot of the bill of materials cost, but
there's only a couple of them. It's a Raspberry Pi, Raspberry Pi camera,
the motor board is custom because it's unipolar motors. It's very hard
to find a motor board for driving unipolar motors. But they're very
cheap and easily available. Than the tiny little round ones that they
tend to be used in things like air conditioning units to move the fans.
We've got a custom motor driver there, which we trying to get the latest
version out, we've had some issues just, I don't do electronics,
particularly in the least at not advanced surface mount stuff, I can
solder it together and all that. That one was designed by Valerian in
Tanzania. We've also got a small, or I do have one of them, we have this
tiny little illumination. Because it turns out that one of the biggest
costs of building a microscope is free hand soldering for wires and LED,
it's actually quite a time consuming process. And of course, time is
money in production. Making a custom little board, which is basically a
constant current driver and a resistor, will save you a lot of money in
the long run. The mechanical parts of it, there's quite a few. But most
of the mechanics is in one single part, the main body. Then there's
peripherals like, we've got some gears and somewhere to mount the
illumination and somewhere to mount the objective and a little base. And
then software, there's been a huge amount of effort going into the
software which was Joel, a previous postdoc, it was mostly his work. We
run a client server architecture where on the microscope is a server
that deals with all of the interaction with all the different pieces of
hardware. That has an API. There's a client interface, which you can
communicate with that you can either run on the same computer that is in
the microscope, the little embedded Raspberry Pi, or you can run it
externally over a network. The nice thing about having the server client
interface is, scientists can use it and automate it from MATLAB or
Python. We've also got MATLAB and Python clients that can talk to the
API. The software, I think, is very mature for an open hardware project,
especially a science open hardware project. And I think especially if
you consider a lot of very expensive scientific instruments where the
user interface of the Software is often an afterthought, even for
professional instruments it is terrible. Ours is at least reasonably
good. There's a lot of things we need to fix, but it's actually quite
reasonable.
{{< /expand >}}


> And has this system been built or produced by others independently?

{{< expand "Show answer">}}
It's very hard to know. Because obviously, you only know the people
who've reported back and told you they've built it. So we did a little
sort of asking on Twitter and on our forum. Have you built it? And where
have you built it or used it? So far, it's been used on every continent,
including Antarctica. We've got a photo of somebody using it on the ice
in Antarctica. It's about 40 countries, we've got a user forum with over
250 people, we don't know if every single one of them has built and used
the microscope, some people will turn off ask questions. But if you
follow the sort of tip of the iceberg of how many people engage versus
how many people have built it, we assume there are thousands out there,
but we don't know quite how many. We've seen things randomly on
Hackaday, where somebody that we did not know had built one, and then
modified it into a laser scanning confocal microscope. We know that a
lot of people can build them, are building them, using them, and
modifying them.
{{< /expand >}}

> You see all these mods and apps. This is great. This is without any
supply of kits, is this completely independent?

{{< expand "Show answer">}}
Most of its independent. We set up a small company in the UK which is
selling 3D printed part kits and also nuts and bolts. Well, I think
illumination of fasteners because one of the lenses is very cheap, but
you have to buy in bulk. So we sell that, the LED and then all of the
screws, just because if somebody wants three of a particular screw. It's
much more efficient if somebody buys a bag of a thousand and divides
them up. But I don't know exactly how many we've sold. But I'd guess
we've sold some something in the number of 10s of kits, maybe 50 of the
fasteners, probably more like 10-20 of the printed parts kits. So while
yes, some have been sold, the vast majority are people building their
own. Lab Maker, a company in Germany, has just started selling the parts
kit, not the printed parts, just the fasteners. Interestingly, their
cost is considerably higher than ours because I've not been paying
myself for my time. And we've been trespassing on my own workshop space
and other things. We're only just breaking even on what we sell them
for, which is not sustainable. But we just wanted more people to have
them. The price for the fasteners kit is a little unsustainable. And I
think it just comes down to volume, we don't have a high enough volume.
I think it will become better if you get to a higher price thing like a
fully assembled microscope. But there's also things we can learn in
terms of moving on to this because we haven't fully got it working. But
when you don't have to spend 10 minutes soldering up each LED before you
send out the kit. That's going to make it a lot cheaper. Especially if
you're paying graduates in Germany which they are, so that that puts the
price up.
{{< /expand >}}

>Are you in contact with Labmaker? Are you assisting them in some
capacity?

{{< expand "Show answer">}}
We told them what we have, it's our bill of materials for the kit. And
we've sent a few emails, I think they wouldn't be interested in the kit
if we weren't building towards something because it's at a to low a
price point for them. While it's a price that seems too high for a kit
and too low for their business model which makes it just entirely the
wrong thing apart from that we're building a relationship. The plan is
that they start with this and learn a bit about the microscope with the
plan of actually building assembled version seven microscopes when we
release it. But we're currently on version six, and we've got an alpha
release of version seven. But our alpha release of version seven which
is about to be beta, is about as stable as six ever was. I think seven
is our point where when we release seven, we want it to be product ready
where as all the other ones were just sort of version numbered them, but
they've been very prototype like with wires sticking out everywhere.
We're hoping, as we move towards seven, there will be something that can
reasonably be sold as a product by Lab Maker and definitely others. We
know a few people in different countries that want to sell them once as
it gets more product like.
{{< /expand >}}



>What is the state of the art in terms of maturity, technology-readiness?
Is it a demonstrator already, or market ready products? And since Lab
Maker is selling it, where would you situate it, roughly?

{{< expand "Show answer">}}
I'd say, sort of 80 to 90 percent of the way to product ready. In terms
of performance, its product ready. We've done clinical evaluations that
it's good enough to diagnose malaria.


The version seven looks completely different in terms of everything is
enclosed, the wires aren't everywhere.
{{< /expand >}}

>That's a demonstrator for sure.

{{< expand "Show answer">}}
That's a demonstrator, but we're very much in the situation: "Yeah,
don't poke it there, the illumination would fall off." There's lots of
wires on the outside. The version seven looks completely different in
terms of everything is enclosed, the wires aren't everywhere, we haven't
finished the illumination wire, but the rest of them are much more
enclosed and robust, things stop falling off. We've got merge requests
in the pipeline to stop the gears falling off. And we're really in the
feature freeze of robustness. We've been a long way through because a
lot of that work was tidying up the underlying code base to make it
easier to maintain it and upgrade it. This has been a long release in
the making. But hopefully, within six months or a year, we should have
something which is product ready. Maybe not the best and most robust
product. I'm sure it will be our first. I'm a scientist that designs
things for just me in the lab, it never really mattered if there were
hundreds of wires sticking out, just don't trip over them. It's a
learning curve for us moving into that. But we're quite a long way
through having something that's robust enough that it will be a product
for lab use. We're thinking through all of the quality control for
medical use, and our partners in Tanzania want to sell it for medical
use eventually. But version seven we're seeing is the version that can
be sold, as sort of normal lab use, but not medical use, with plans to
improve it for medical use.
{{< /expand >}}

{{< card2 "Local production">}} 
We're very keen for BTech in Tanzania not to be reliant on
us. We need to make sure to provide a good enough dossier of
how everything works, so that whoever is going to be the legal
manufacturer, can write a good technical file and convince regulator
that they understand it and can maintain it for the future.

We are looking for a good way to transfer control in a sustainable way, such that
they can eventually maintain it when our funding runs out and we disappear.

{{< /card2 >}}


>That means you are next going for certification in the some midterm
future?

{{< expand "Show answer">}}
We're never going to plan to be ISO 1345 certified in the university.

You have to worry about if you're setting up a new type of colonialism
where at any day we can pull the plug in and say: "It's still ours
because it's our certification."

A lot of what we've been doing is thinking about how we improve our
processes. We've got an auditable train of all of the design decisions.
We're never going to plan to be ISO 1345 certified in the university.
You could and it's the best way to transfer the IP, where you know, it's
not IP in terms of protecting but transfer the knowledge out of the
university. We're very keen for BTech in Tanzania not to be reliant on
us because some things you could do is you could try and raise a load of
money here, set up a company that subcontracts them in Tanzania to build
the microscope. Then at least it's built locally, at least there are
engineers locally. But you have to worry about if you're setting up a
new type of colonialism where at any day we can pull the plug in and
say: "It's still ours because it's our certification." We're much more
interested in capacity building for them to be able to go through and be
the actual legal manufacturers. Where the bad side of that from their
perspective is, if you're the legal manufacturer, you're the one with
the liability. We're starting to investigate whether or not there should
be a medical device foundation. Perhaps that helps to hold some of the
liability. At least for the design side of it, where you could basically
be a design house that was ISO 1345 accredited and transfer it. Because
otherwise, you need to make sure you provide a good enough dossier of
how everything works, that whoever is going to be the legal
manufacturer, can write a good technical file and convince regulator
that they understand it and can maintain it for the future. We've done a
lot of thinking about that, we're not fully through decided how we're
doing it. But our partners in Tanzania are now registered as medical
device producers in Tanzania. They've started doing their training. In
Tanzania you have to register assets, you have to register and have your
premises inspected before you can go and training for what you're meant
to do to have your premises set up which is a very sort of interesting
situation. But they have now got through that. But it will be the first
in vitro diagnostic device to be built locally in Tanzania. There's a
lot of learning both from the regulators and from the companies inside.
We're more and less interested in doing this quickly. Because I think
what while people having access to microscopes for diagnosis is
important. I think doing it slowly, doing it well and documenting how we
get there, is actually probably more useful in the long run. There's
sort of a tried and tested way to design something at a university in
the Global North, with partners in the Global South, rather than
developing it for Africa, which is the thing that always makes me angry.
Then have a good way to transfer control in a sustainable way, such that
they can eventually maintain it when your funding runs out and you
disappear. Let's hope that we get there before our funding runs out and
we disappear.
{{< /expand >}}

## Research outputs

{{< card2 "Academic outputs">}} 
For impact, the way the university sees the transfer of knowledge into a company as impact, and they’re sort of pump priming for long term impact.

We’ve got papers on the microscope, papers on the Delta stage version of the microscope, papers on the block stage version of the similar design that’s x, y, z translator for aligning optical fibers. We’ve started publishing on individual parts of it, such as the robustness of the autofocus algorithm, publishing on the software, on how we do the camera calibration.


{{< /card2 >}}

>Let's go on the actual research output. Obviously, this was as part of
several grants and it's a research project or multiple projects. What
was the output of this hardware development so far, directly or
indirectly, academically and practically?

{{< expand "Show answer">}}
For impact, the way the university sees all of the things I'm telling
you about trying to transfer the knowledge into a company as impact and
they're sort of pump priming for long term impact.

We've done quite a bit, we've got papers on the microscope, papers on
the Delta stage version of the microscope, papers on the block stage
version of the similar design that's x, y, z translator for aligning
optical fibers. We've started publishing on individual parts of it, such
as the robustness of the autofocus algorithm, publishing on the
software, on how we do the camera calibration.

Because we do everything in Git, I don't really have anything of the
microscope that isn't shared.

There is no bill of materials directly in the repository, because the
bill of materials is explained in the documentation. But the
documentation has metadata in it. That metadata is read by a program
that generates the full documentation.

For impact, the way the university sees all of the things I'm telling
you about trying to transfer the knowledge into a company as impact and
they're sort of pump priming for long term impact. If people start
selling it as a physical device, then that is impact because people have
access to it. I mean, the real world impact, I think we've talked about
it, it's sort of used in many countries, hundreds, if not thousands of
them exist, people are looking towards manufacturing it. It's been very
interesting, trying to get a good level of academic impact out of the
project, especially from my perspective without a chance that I'm going
to get a permanent position. A lot of what I do is probably not the best
thing for getting me a permanent position because if I just moved onto
the next thing rather than documenting it easily, so everyone can
reproduce it perfectly which has taken most of the time as
documentation. That's generally not the best path to getting lots of
papers. That said, we've done quite a bit, we've got papers on the
microscope, papers on the Delta stage version of the microscope, papers
on the block stage version of the similar design that's x, y, z
translator for aligning optical fibers. We've started publishing on
individual parts of it, such as the robustness of the autofocus
algorithm, publishing on the software, on how we do the camera
calibration. It's starting to explore where I'm hoping to get ten papers
out in 2022, we've already had three out and two accepted. We're getting
more and more what I call sort of meta papers. We had one, where we took
all of our thinking about how we've carefully considered medical devices
being open, and how you track all of that knowledge. And compare that to
what we saw at the start of the pandemic, when loads of people went, I
want to be open, because that's nice. Besides I want to design a
ventilator and went down the route of designing something that will pump
air which I could connect a relay to my vacuum cleaner and produce
something that pumps air periodically. It's not a medically
certification for a ventilator. We're less facetious in the actual
paper. Here's something we've done, that's interesting and different. We
are actually getting to the point where we're getting a reasonable
number of academic papers out. But at the start of the project, there've
been two years after I came where we didn't get anything out because
there'd already been the original paper on the microscope. It's very
hard to write a paper on a small update, eventually if you've got a big
update. But now we're at the point where there are very few projects of
our size with our community and our processes have got better. We're
writing one on how we do our documentation program and all of these
different things. But it's taken a long time to build up that sort of
ecosystem that's worth publishing about. And so I'm not sure if we're
hitting a crescendo where we're suddenly going to publish a load of
papers and then be back to square one. Or if this is just a ramp up
that's going to continue. It remains to be seen.
{{< /expand >}}

{{< card2 "Publication strategy">}} 
Because we do everything in (public) git repositories, I don’t really have anything of the microscope that isn’t shared.

A lot of what I do is probably not the best thing for getting me lots of papers and a permanent position. I would get more papers if I would just moved onto the next thing rather than documenting the current thing (so everyone can reproduce it perfectly). And it is very hard to write a paper on a small update.

We’re getting more and more what I call sort of meta papers. We had one, where we took all of our thinking about how we’ve carefully considered medical devices being open, and how you track all of that knowledge.

{{< /card2 >}}

>What information have you shared mainly, on the documentation? Like,
Bill of Materials, you mentioned, CAD files, or in this case, notice
that files but other code, and so on?

{{< expand "Show answer">}}
Because we do everything in Git, I don't really have anything of the
microscope that isn't shared. Because the way we do our project
management, is in the Git issue tracker. If Richard or I want to change
something, we make a merge request. And we have a discussion in the open
about it. All of that project management is open. Then what we see,
we've got lots of repositories for the software, for the hardware. While
it's annoying, if you end up with a new computer, that you've got to
reinstall all the programs. I don't have anything on my computer which
regarding the microscope that I can't just get from Git in public
repositories. In some ways, if people look in our repository, they'll
tell us, we don't have a bunch of things because a lot of people assume
a much less automated pipeline than we have. There is no bill of
materials directly in the repository because the bill of materials is
explained in the documentation. But the documentation has metadata in
it. That metadata is read by a program that generates the full
documentation. Because there are different stages of the documentation
which are used in multiple different versions of the project. It
combines them all together. Because of many variations there's a CI
script and Docker which spins up that creates each of the STL somebody
would need to print and embeds them in the documentation. If somebody
goes to the documentation there's totally up to date renders which are
generated from the code. There's totally up to date STL files that are
generated from the code there's up to date documentation. What we have
is our working files are there and everything that people actually need
to produce it. Most people won't look at the repository, they'll look at
what is generated from the repository automatically.
{{< /expand >}}

{{< card2 "Work Coordination">}} 
We do our project
management using the Gitlab issue tracker. If Richard or I want to change
something, we make a merge request. And we have a discussion in the open
about it. All of that project management is open.

Most people won’t look at the git repository, they’ll look at what is generated from the repository automatically.
We are indeed using automated pipeline (gitlab Continuous integration) for the production of the documentation website. 

We are a bunch of nerds who are basically programmers doing a hardware project.
{{< /card2 >}}

>I can tell you, by having set up CI infrastructure in our lab, it's a
lot of work to get it right. This is this is something quite advanced in
terms of using Git. Have you seen other groups do this where you got
motivated?

{{< expand "Show answer">}}


No, I think it escalated because it was Casper who came from more of a
software background, got annoyed with something and made a CI job that
did one small little thing and automated it. Then of course, you've got
a bunch of nerds that are basically programmers doing a hardware
project. You realize that a CI can automate anything, that's a script.
Just anytime things got a bit manual, we ended up adding more things.
Our paper is both explaining our workflow as a case study, but saying,
look at what developments do in software where you've got all of your
project management, all of your data management. Besides then all of
this automation to make sure everything is consistent and built directly
from that source. You can do this for hardware as an alternative to PLM.
It's not ready because you end up writing all your scripts yourself. It
wouldn't integrate well with lots of proprietary CAD programs. But the
workflow is actually very powerful and very distributed. It's something
that I think if open hardware is going to seriously work without lots of
manual work, people are going to have to get on board with, maybe not
the GitLab CI as the only way of doing it but something along that level
with all of that sort of automation is going to be necessary. This is
sort of our very customized way of playing with a first prototype of
that system.
{{< /expand >}}

>That's very interesting. Then you have basically this output
documentation which people can generate from there and they can use it
to to rebuild the hardware. Did I get that right?

{{< expand "Show answer">}}

I mean that people don't have to build it. So nobody has to understand
how it works. Anytime I update anything on the project, it checks that
all of those things were build, all automated on the server. If I tag it
as a release, then the last stage of what it does is, it uploads it to
our website. Then all they do is, integrate to the page on our website
which is the documentation and has all of the assets. So nobody, no
normal user has to understand that we've done this. But it means that we
can consistently produce a website, which is the documentation with all
of the assets from the repository. Then a normal person can come along
and go to a website they understand, that's designed for them, rather
than having to interact with it. They don't even have to interact with
Git lab, they've got all of the things that they need to build it, but
not necessarily to modify it. If they want to modify it, then they have
to come and start playing with that interface and Git, but they still
actually never have to get any of the programs installed because in
theory, they can just change the code, upload it and it will all pass
through that pipeline. They can download the assets. We have some people
that contribute, they can't even build it locally.
{{< /expand >}}

>And was it easy? Or what were the barriers to do this so far?

{{< expand "Show answer">}}

I suppose it's very hard to say how hard or easy something was that took
years. There were definitely some aspects of it that were surprisingly
easy to set up, some aspects of it that were surprisingly hard to set
up. Because certain times you go like I just put this one YAML file into
my repository that says, run a bash script. And the bash script says,
run this program. Oh look, it works. And of course, sometimes, but that
uses OpenGL and OpenGL doesn't work in Docker, and you end up in what's
complicated is not necessarily on the face of it, what should be
complicated. So anyways, it's evolved over time as we've needed it. I
think if I said to myself, what you need to set up is what we have now,
it would have sounded impossible. And it would have been impossible in
many ways. But it's grown organically from: "Oh look, there are some
easy things you can automate, Oh, can we add this? Oh can we add this?"
But, is it possible for another project to replicate the process for
their own project? And not necessarily the microscope? Yes and No. So
some of the jobs are very specific to us and use a lot of custom code.
Some of them aren't. Alright, I think if they were in OpenSCAD, then a
lot of the build script there are simpler. Our build scripts got
complicated because we do all of our renders and everything. We do know
other people who were using our documentation, a couple of people are
using our documentation program which automatically creates the build
script to run in the server and build the documentation. The problem
with the workflow is, it's at the moment, it's ad hoc to our project.
But that's only because we wrote it ad hoc to our project and writing
something with general purpose would be more work. But there's nothing
inherent that couldn't be generalized. Except for, we don't have the
time to sit there and generalize it, especially when there's nobody that
is sitting there saying, please generalize this for us. If I got loads
of funding and we're putting actually in a big funding bid where we want
to try and generalize some of this. So if we get that, then I'll
probably move away from working directly on the hardware towards
generalizing this works.
{{< /expand >}}


{{< card2 "Successes and Failures">}} 
Now we’re at the point where there are very few projects of our size with our community. The core team sort of grows and shrinks based on grants, but community members are still very active, so it is very hard to estimate how big the project is.

I think there’s a lot of people who now have microscopes that wouldn’t. There’s a lot of people who have things that they could customize.


{{< /card2 >}}

## Participants

{{< card2 "Core team and community">}} 

It's a reasonably big project, it's not huge, like
Linux kernel development, but it's big. In total there must be 50 to 100 people sent changes to at least one version of one of the projects.

About three or four people worked on it full time. More when we had more time of our partners in Tanzania who were sort of quite actively involved. It is going to be around 10, but maybe not all of them show up in the Git repository.

Our group is mostly researchers and we have other researchers at other universities that use it and will comment. But then we’ve had people who are doctors, medical doctors who’ve got interested in it from a medical perspective and fed back a lot of information.


{{< /card2 >}}

>The question arises, of course, how did you end up working on that
project? And how many people are working on that project?

{{< expand "Show answer">}}

I saw a job advert, I came and got paid to do this project. It's
different from a lot of open source projects in that way because we're
very lucky to have the funding that we've had. In terms of how many
people have contributed and how many people actively work on it. To
actively work on it, it needs to be probably full time? About three or
four work on it full time. More when we had more time of our partners in
Tanzania who were sort of quite actively involved. It is going to be
around 10, but maybe not all of them show up in the Git repository
because Git is complicated. They're more likely to send something to
someone that puts it up there. But I always tend to think about the
microscope repository. But of course we've got the electronics
repositories, we've got the software ones. There's like 15-20 Git
repositories on the open flexure because there's some of the plugins for
the software, there's the server architecture [...]. Then there's different versions of the Delta
stage microscope, the block stage and the main microscope. What I did at
one point, I also thought of the side projects like the documentation
project GitBuilding. I ran through and wrote a script that pulls in each
of them and runs the program "jeels". It creates a visual animation of a
little meeple thing built to adding files to the repository. In total
there must be 50 to 100 people sent changes to at least one version of
one of the projects. There're also things end up in, that's a good fix
for that old version. It's definitely released somewhere in the project.
But if you only looked down the master branches, they don't necessarily
show up in that history. Of course, there's people that report issues to
us which are very actively a part of the project, even if they didn't
change things. Then you get out to the size of the community which is
about 250 participants on our forum. We've got a forum just for the open
flexure microscope. Sort of hundreds of people if you take just random
comments, otherwise around 10. It's a reasonably, it's not huge, like
Linux kernel development but it's big. It's big for a hardware project
because I think it's much harder to contribute to hardware.
{{< /expand >}}



>Absolutely, I wouldn't compare the two anyway. Can you say a little bit
about the occupations, at least from the people you know or see? Are
there doctoral researchers, postdocs, technicians, students, professors?


{{< expand "Show answer">}}


We have a really good mishmash of people. Our group is mostly
researchers and we have other researchers at other universities that use
it and will comment. But then we've had people who are doctors, medical
doctors, who've got interested in it from a medical perspective and fed
back a lot of information, even if not direct changes, more like
requests for changes: "Have you thought about doing this". This really
feeds back into the project, even if it's not a change directly to the
design. We've had a bunch of hobbyists just showing off and go, this is
interesting. I'd like to put a slightly different thing in it. Besides a
bunch of people that pop off as a name and say: "Can you do this?" I
don't send them a survey of who they are. I don't know at all. We've had
people on the forum, say, you know, I wanted a home microscope, it
seemed more fun to build my own than buy one. Here, look at this, I
found some cells, they're dividing. It's a broad church. I could not
pigeonhole the community which I think is a positive sign. Because you
can make it understandable to people with a different background while
also getting all of the advantages from from each technical field.
{{< /expand >}}

>How did you find suitable project members with the competences to work
on the project?

{{< expand "Show answer">}}

I think a lot of the bulk of it is done by people who are employed on
the research projects. While there are community contributions, most of
the community contributions are people getting involved in discussions.
Some people become more collaborators long term. Further there's
designing it here where it's me or Joel who wrote the software. With a
job advert you'd find someone but there's also routes to collaborators
where it would look very different. We'd not have the same project
without our collaborators in Tanzania. That was when Richard was looking
at water testing. He knew a charity that did a lot of work in East
Africa. They put him in contact with Stick Lab back then and now called
B Tech. That was word of mouth. A lot of that has been word of mouth at
least for and same for clinical contacts. You meet them through
different networks. A range of things.
{{< /expand >}}

{{< card2 "Personal gain">}} 
In terms of personal growth there will definitely be some, there’s lots of skills you pick up in anything. In particular, working with a much broader set of people, in a large collaboration with humanitarian goals, has definitely broaden my horizons.

If I tell people who am I, I’m still basically a physicist and engineer. I’m quite unique that I have all of those technical skills which I had beforehand but then all of this experience working in different places. I think that’s what I’ve got out of the project. I think it’s very hard to get that level of different interactions from most academic projects if you’re not open.
{{< /card2 >}}

>How have you and all these people who have contributed the project
members benefited from their work in the project? Can you say something
about that?

{{< expand "Show answer">}}
I think it's very interesting as a postdoc, in terms of how you've
benefited. If you haven't got a permanent position, you haven't got the
one benefit that you want out of a postdoc. In terms of personal growth
there will definitely be some, there's lots of skills you pick up in
anything. I don't think there's necessarily a huge numbers of technical
skills that I wouldn't have picked up in a different postdoc designing
different things. I have a much more rounded view of the world. I've
done a lot of traveling, spent a lot of time looking at not just how I
build something that works well. But how we think about production. What
happens with supply chains as you try and move them, as you try and move
things into Tanzania? Why can't we just get that? Oh, there's no Amazon.
Oh, things get stuck in the post you need, you need to understand the
local supply chains. Then there's just huge power imbalances between
trying to run an academic project between a university that holds all of
the money and expects to pay people on really slow payment schedule to
improve their cash flow. You're actually dealing with a small Tanzanian
company where the university shouldn't be just paying things slowly to
improve their cash flow. We actually started working with social
scientist to help us look inwards on the project and understand whether
that was a fair collaboration, based on how the government wanted us to
set up those and how we, without training on setting up, could run it. I
suppose as a physicist, it stopped me being an arrogant person that
ignores the social scientists. It's definitely working with a much
broader set of people in a large collaboration with humanitarian goals
has definitely broaden my horizons. If I tell people who am I, I'm still
basically a physicist and engineer. I'm quite unique that I have all of
those technical skills which I had beforehand but then all of this
experience working in different places. I think that's what I've got out
of the project. I think it's very hard to get that level of different
interactions from most academic projects, if you're not open. If you
wanted to have as many collaborators as we have, you would have only
time to fill in the NDAs by now.
{{< /expand >}}

>That's a nice analogy. And other people, how have they benefited?

{{< expand "Show answer">}}

I think there's a lot of people who now have microscopes that wouldn't.
There's a lot of people who have things that they could customize. Our
partners in Tanzania, even if they haven't produced the microscope as a
medical device yet. They are well on the way to. They are registered as
a medical device company, they've started their training, they're moving
through those processes. They've now got good connections to the health
institute that was part of the project. I think we've been a focus point
for a lot of different networking. I think everybody will get something
slightly different out of it. We've got a good community, I think.
{{< /expand >}}

> At the end we have a closing question that's just within the scope of
the question before. Did you have any students who did their bachelor or master or
something similar thesis within the scope of this project?

{{< expand "Show answer">}}

Yes, in the wider project which includes different versions of the
main microscope for the wider open flexure project. We've had a few
people work on there have been a couple of master's students that did
their project on the open flexure block stage. We made an open flexure
interferometer which we had a couple of students on, master students,
we've had some doing phase contrast with the microscope. Someone did,
that might have been a summer project for a student where she did the
upright version of the microscope because it is an inverted microscope
normally, an inverted inverted microscope. Then Ed's PhD was partly on
one of the sub parts of the block stage, but he's moved. He's not so
open flexure focused but he's open hardware focused still. Joe is a PhD
student who's very much focused on the open flexure microscope. One and
a half PhDs and maybe six masters projects on the open flexure project
so far.
{{< /expand >}}