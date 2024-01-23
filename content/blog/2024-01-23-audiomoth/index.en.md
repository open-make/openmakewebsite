---
title: 'Interview summary: audiomoth'
author: 
  - Open make interview team
  - Alex Rogers
date: '2024-01-23'
slug: interview-fixme
categories: [interview]
banner: img/banners/logoaudiomoth.png
tags:
  - technology
  - open hardware
  - personal story
---
# Interview: audiomoth

Alex Rogers is an associate professor who lead the team that developed the audiomoth, a low-price passve sound recorder that detects bats activity in the wild.

*by the Open make team, Alex Rogers. Copyright to the authors, distributed under a CC-BY 4.0 licence.*



**Sections:**
- [The project](#the-project)
- [The hardware](#the-hardware)
- [The research outputs](#research-outputs)
- [The participants](#participants)

*Banner image: logo of the openacousticdevices company, By openacousticdevices, distributed under a CC-BY 4.0*

>Interviewee: Alex Rogers
>
>Interviewers: Robert Mies (TU Berlin) & Julien Colomb (HU Berlin)
>
>Transcription and editing: Diana Paola Americano Guerrero, Robert Mies, Fabio Reeh, and Moritz Maxeiner
>
> Editing and summary writing: Julien Colomb

<img src="images/Screenshot.png" alt="screenshot of the interview" width="60%"/>

*Screenshot of the interview.*



{{< card  "The audiomoth in a nutshell">}}


<img src="images/Audiomoth.jpg" alt="audiomoth v1.2" width="80%"/>

*Photos of the audiomoth setup*

- Main website: https://www.openacousticdevices.info/audiomoth
- Project start: 2015
- Core development team size: 3

### Hardware products
AudioMoth is basically a single board PCB. It's mounted directly onto the battery holder.
That’s the minimal assembly requirement. The hardware on here is a microcontroller, an SD card, the microphone and some memory.

HydroMoth is one version that can be deployed underwater.

### Hardware maturity
It is market ready, but not certified.
### Rebuilds
A few people did it. We expected more people to do so.

{{< /card >}}

## The project

### Project start
We figured out that it'd be handy to put some recorders into the forest and leave them. We looked at commercial recorders that did that. At the time they were all about $1,000. We saved a lot of money and made our own small low cost recorder.

*the project was pitched and two PhD student (Andy and Peter) were inteseted and worked on audiomoth development.*

### Project process

*The process included discussions with end users early on, and a particular care in designing things that can be easily manufactured.*

There's a challenge to overcome the inertia and actually make the connections by going out and talking to people, finding end users. 
If you just ask the end user, they give you a wish list. That doesn't help you making any decisions. You need to interact with them and discuss the possibilities.

Sharing isn't the end.
To our average user it’s more valuable that the project exists than some hardware designs being available that they’re never going to use anyway.
Typically people want to get a hold of the hardware. It gives them some comfort that the design is available. But most users aren't going to manufacture it for themselves.

I think designing for scale at the very earliest stage is really important.


### Funding

It's generally  hard to fund this type of work because it's not seen as computer science research.  I'm indirectly funded through small pots of innovation based funding. But the two PhD students in Southampton were funded by EPSRC which is the standard funding body.

### Major issues

One of the challenges was to find end users who are willing to work with prototype hardware.

Using machine learning tools effects a bit the energy consumption because you typically try to minimize energy and running your models is quite expensive in terms of computation. But computation tends to be a little bit cheaper than writing to the SD card.

### sucess and failures

*The project gots useful for us and for others.*

A general thing is designing with a view of being manufacturable.

There’re lots of early design choices which can impact the deliverability of the device. Another point are batteries: with removable batteries, you can post it to people and they can put the batteries in. Some of these very early design choices are quite critical to how it’s used. 

## The hardware 

### hardware importance in the project

The idea was to deploy some loggers (recorders) that would last for a year and continuously listen to the forest and counting gunshots in parallel. At the end of that year, they understood some of the distribution of where and when people hunted and what at time of the day or night they come. It was about collecting information for future protection measures and initial basics of data to understand what was actually happening in the forest.

### hardware components

Particularly at AudioMoth, we sacrifice lots of technical requirements. For example, the top standard would be to not have the microphone on the same PCB as the SD card.
But, if you separate them, the assembly gets incredibly expensive.

Another thing is that we put a huge AudioMoth logo on the front of the device which seems quite trivial.

### Decision making

It didn't seem different from a regular PhD research project, but it was more interactive. The students talked much more to people than a typical computer science or engineering PhD.

But most of the time the students reported back to me the findings and I validated them, and most of the time they made the right decisions.



### Production

We made it available to people through the GroupGets campaign. We open sourced the design but then tried to figure out how to actually get it in the hands of people who just wanted to buy the hardware and not to assemble hardware themselves.

There’re a couple of models. [LabMaker manufactures and sells AudioMoths](https://www.labmaker.org/products/audiomoth-v1-2-0). They manufacture them and sell with slightly more service. Their thing is manufacturing open source designs.
GroupGets is another model. GroupGets are little bit more hands off the actual process. They're much more about collecting the auditors together. They're slightly different models on the same thing, but they're both focusing on how do you get open source designs manufactured at scale and distributed to people.

But it's a way of putting orders together. GroupGets is really good for exploring demand.

## Research outputs

## publication strategy
I think we shouldn't be driven by publications. The metric should be if it’s useful.

The final point of the two PhD theses were a hardware publication in a proper journal publication. They needed it for their PhD.


If you're open source, GitHub seems to be the first choice.
For a while, we experimented with circuit hub which is an interesting model.Circuit hub is a bit like GitHub for hardware designs. All the designs are available but they're connected directly to a PCB assembler.

The only thing is that open acoustics keeps the current design to themselves. Because one way of supporting it is through hardware sales on GroupGets. If that goes away, there's no way to support the device anymore. It would become another open source design which no one is using and supporting.

Our application notes are interesting things that we’re doing with AudioMoth. They're on the open acoustics website.


## Participants

### personal gains

Peter and Andy did their PhD and created a company. 

It definitely changed the things  I focus on. When I think about what PhD student projects I could supervise, I'm interested in where does this go beyond the end of the three year PhD.
