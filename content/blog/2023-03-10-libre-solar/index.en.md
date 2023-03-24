---
title: 'Interview: Libre Solar'
author: 
  - Open make interview team
  - Michel Langhammer
date: '2022-10-20'
slug: interview-libre-solar
categories: [interview]
banner: img/banners/libresolar.png
tags:
  - technology
  - open hardware
  - personal story
editor_options:
  markdown:
    wrap: 80  
---

# Interview: Libre Solar

*by the Open make team and Michel Langhammer. Copyright to the authors,
distributed under a CC-BY 4.0 licence.*

**Sections:**

-   [The project](#the-project)
-   [The hardware](#the-hardware)
-   [The research outputs](#research-outputs)
-   [The participants](#participants)

*Banner image: fixme, By CERN, distributed under a CC-BY-SA 4.0*

> Interviewee: Michel Langhammer
>
> Interviewers: Robert Mies (TU Berlin) & Moritz Maxeiner (FU Berlin)
>
> Transcription and editing: Diana Paola Americano Guerrero, Robert Mies, Fabio
> Reeh, Moritz Maxeiner & Julien Colomb

<img src="images/Screenshot.png" alt="screenshot of the interview" width="60%"/>

*Screenshot of the interview.*

FIXME

{{< card "The Libre Solar in a nutshell">}}

![FIXME](images/FIXME.jpg "WR Switch")

*Photos of FIXME*

-   Main website: <https://libre.solar>
-   Project start: 2015/2017
-   Core development team size: 7 people

### Hardware products

The libre solar is a set of (mostly electronic) products like a portfolio. You
have different components for different requirements and can mix them to build
up a system.

### Hardware maturity

Different products are at different development stage, it is declared for each
product on the website.

### Rebuilds

We have test fields of friends who are living in rural areas. They build up the
off grid energy system completely by themselves

{{< /card >}}

## The project

{{< card2 "Project start">}} 
It was developed in Hamburg by Martin Jäger, who’s the main developer and founder of the Libre Solar project. 
Martin Jäger is a mechanical engineer. For him, it was tinkering around and learning about power electronics and software development. In 2017, people started to kick in, mainly in the firmware development. 

When I jumped in concerning the educational resource, the benefit was to have open source resources for redesigning new components.
{{< /card2 >}}

> How did the project Libre Solar started?

{{< expand "Show answer">}} The Libre Solar project started in 2017. It was an already
existing set of electronics developed by Martin Jäger, who began in 2015. It all
started with a Arduino based charge controller for photovoltaic systems. It was
back on Arduino base with low entry and later developed to a next generation of
electronic charge controller with a STM 32. The higher demand regarding
resolution and calculation time required the upgrade of the hardware component.
Further we built the Libre Solar around or with that component and started
prototyping. There were different prototyping phases of different components. It
was always developing one component and testing it. Based on the test we
implemented new requirements. An example would be power classes and how to get a
higher current out of the system. There were different development stages from
the component. Now it's a set of hardware components used as charge controllers.
Besides, it's a different set. It's for battery management systems and a modular
setup, in case you want to use different types of batteries. You need a
different type of components, for example, a battery management system for
lithium ion batteries, if you want to use them. {{< /expand >}}

{{< card2 "Project process">}}

There were different prototyping phases of different components. It was always
developing one component and testing it. Based on the test we implemented new
requirements.

We do not write down the issues, we just make an iteration of the documentation.

We did the entry workshop about how to use Git with a colleague of ours.
GitHub is really comfortable because you have version controlling and all this DevOps functionalities behind it.
{{< /card2 >}}

> Where was this developed?

{{< expand "Show answer">}} It was developed in Hamburg by Martin Jäger, who's the main
developer and founder of the Libre Solar project. He mainly developed this by
his own in the beginning. Later, people started to kick in, mainly in the
firmware development. First the hardware was development of the PCB electronic
layout and afterwards the firmware. In the firmware development was another
contributor who kicked in mainly concerning the modularization of the software.
We have one main firmware repository where we can modularly choose the different
type of hardware and the firmware adapts to that. {{< /expand >}}

> What was the core benefit of this project? How does the hardware fit in the
> overall project?

{{< expand "Show answer">}} The main benefit from the Libre Solar project was learning about
about power electronics. Martin Jäger doesn't come from the field of electronic
development, he's a mechanical engineer. For him, it was tinkering around and
learning about power electronics and software development. It's mainly the
benefit for him as a developer. When I jumped in concerning the educational
resource, the benefit was to have open source resources for redesigning new
components, like our Libre Solar Box where we can develop an application out of
the electrical component from the Libre Solar project. This was the benefit from
my point of view as a student. The benefit for the people who are using the
component is to build it by themselves. We have test fields of friends who are
living in rural areas. They build up the off grid energy system completely by
themselves. For example, there were users in South Germany who rebuilt the
charging sensor node in a rural area. Besides, we have research projects. As
example, in Rwanda in Africa, we built up a test system with these components.
The benefit there for the people is that they can run an energy grid system with
open source hardware components. They are now able to redesign it by themselves.
But the knowledge level is still needed to know how to adapt and how to redesign
it. There're different layers of benefits. {{< /expand >}}

{{< card2 "Funding">}} 
The first development stage was made without funding.
Open educational resources creation was funded by the city of Hamburg by the Hamburg Open Online University.
(All the money wasn’t spend on people but on external resources.)

A research fund from Scotland helped with development together with partner startups.

The university didn't have the infrastructure for us. That's why we went to a Fab Lab.
{{< /card2 >}}

> How were the different parts funded?

{{< expand "Show answer">}} The first development stage was voluntary funded. All the
development was made free. At the education project we derived open educational
resources out of the existing design documents. This was funded by the city of
Hamburg by the Hamburg Open Online University. This was one funding pot mainly
for creating educational resources. And then the research projects. Another
funding was a research project from Scotland together with partner startups who
are interested in this field. This was financed by a research fund from
Scotland. {{< /expand >}}

> Did the Rwanda project come from Scotland as well?

{{< expand "Show answer">}} I think this was from Scotland. {{< /expand >}}

> How much money did you receive overall? Can you provide some ballpark numbers?

{{< expand "Show answer">}}

I don't know the size of the overall funding on the project. I have numbers for
the educational part. It was around 70,000. It were two funding rounds where we
got money. For the Rwanda project I have no numbers. {{< /expand >}}

> Could you describe the overall process? How did you organize it?

{{< expand "Show answer">}} With our student group, we replicated the Libre Solar component,
it was a community based workshop run in a FabLab. In the planning process, we
got a bill of materials and saw what components we needed. We divided the
replication into PCB replication and the actual solar box replication. Within
PCB replication we decided between to order a full assembled PCB or to order the
circuit board without parts on it. It was like the PCB without components. With
the ordered components we went to the Fab Lab and did the usual process steps to
do for electronics. Afterwards it was about testing to see if all the components
were assembled in the right direction and currency. Then we flashed the PCBU.
Finally, we had a ready to use charge controller. {{< /expand >}}

> How did you organize the development process?

{{< expand "Show answer">}} The development process for the PCB mainly took place in GitHub
as a collaboration platform. The repository is placed in GitHub. For the
electric design, I'm using KiCad as a development tool to design components as
being offline. When it's ready, you place the design fire to play some guitar
and make some comments. To get a workflow you have to use the tools placed on
GitHub and then iterating if you want to go into selection. {{< /expand >}}

{{< card2 "Work Coordination">}} 
It’s like the usual software kit workflow where you have other people contribute, make a pull, push or merge requests or give comments.

Different people are working with different styles and the documentation gets a little bit unstructured and messy,
contribution guideline for the hardware design help mitigate these issues.

If you don't have proper documentation, people don't have a good starting point where they can jump in the development.

Within the forum, you can  see a lot of people who are interacting and making questions because they replicate the components by themselves.

We had a telegram channel where we had ad hoc communication. We built up a GitHub repository where we had issue-based coordination. We had weekly meetings at a Fab Lab
{{< /card2 >}}

> Would you do this from different locations?

{{< expand "Show answer">}} The electrical design is mainly developed by Martin. I have to
look up if there're some other comments. Especially in electric designing
hardware is designed without many contributors because you need technical
knowledge. It's like the usual software kit workflow where you have other people
contribute, make a pull, push or merge requests or give comments. That's a
typical good workflow. {{< /expand >}}

{{< card2 "Major issues">}} 
From the development and production side the main issues was safety, quality and secureness. Esxpecially when you work with batteries some people have been insecure how to handle the safety issues: You can’t shortcut them otherwise they will explode.
{{< /card2 >}}

> During that process or the project overall, what major issues have you come
> across and how did you resolve them?

{{< expand "Show answer">}} About development process issues, I can't tell much because
Martin is the main developer of it. I know what the issue are regarding
contribution guidelines. Especially for the firmware, you stick to a code style
but different people are working with different styles and the code gets a
little bit unstructured and messy. For people to learn the code, it's important
to have a common structure. This was one case of a contribution guideline for
the hardware design, but I can't say too much because I'm not too much
contributor in it. If you don't have proper documentation, people don't have a
good starting point where they can jump in the development. A proper
documentation is crucial. The same counts for modular development that people
can contribute to specific modules or sub components of your hardware. From the
development and production side the main issues was safety, quality and
secureness. When you work with batteries some people have been insecure how to
handle the safety issues. You can't shortcut them otherwise they will explode.
There you need expertise and a guide how to trust the people you're working
with. Some of us had an electrical background. The people, who didn't have the
background in electrical engineering, were more insecure about handling
batteries. {{< /expand >}}

> Did you them some idea what not to do?

{{< expand "Show answer">}} This was one issue besides the quality testing. For quality
parameters was not so much documentation done. About this we depended on
expertise. {{< /expand >}}

> Did you receive some outside expertise from people?

{{< expand "Show answer">}} We had Martin as the main developer with the main expertise. If
he wasn't there, it would have been harder to do the quality test.
{{< /expand >}}

{{< card2 "Decision making">}} 
Martin made most of the decisions because he had the main expertise.

For the educational part, it was made in a group of seven people by consensus. 
{{< /card2 >}}

> How were the decisions made within the project all the time?

{{< expand "Show answer">}} Martin made most of the decisions because he had the main
expertise. What he said should fit. Other people had expertises which been
discussed. For the educational part, I was the project leader on the
administration side but I didn't make any decisions. It was made in a group of
seven people by consensus.

## The hardware

> What hardware components have you developed in this project?

{{< expand "Show answer">}} It's been mainly electronics (PCBs). {{< /expand >}}

> Were those PCBs parts of multiple products or were they all part of the same
> product?

{{< expand "Show answer">}} I would call it more a set of products like a portfolio. You had
different components for different requirements. You could mix them to build up
a system out of it. {{< /expand >}}

> Could you give maybe a quick overview over those products or are there too
> many?

{{< expand "Show answer">}} No, it's similar to charge controllers. One product is like DC-DC
converters and charge controllers with different types depending on power class.
The second type is a battery management system which have different types
depending on how many cells you want to connect. The third are communication
gateways to connect to server based applications. {{< /expand >}}

> How would you classify the products in terms of mechanical, electrical
> andsoftware?

{{< expand "Show answer">}} First was the electrical classification. {{< /expand >}}

> Did you have some mechanical issues, e.g.with the panels?

{{< expand "Show answer">}} No, the panels, batteries, cable and plugs were sourced.
Everything was sourced. There was no mechanical frame. We had a solar box. This
is one application but it's not the main component of the Libre Solar project,
it's in our student project. The solar box has a mechanical frame we can
consider. The Box is one application you can make. Firmware would be another
class. {{< /expand >}}

> How would you rate the maturity from prototype, demonstrator to market ready?

{{< expand "Show answer">}} We declared on our website the different development stages. I
don't have it all in my head. If you look here, you can see the development
stage declared for each product. {{< /expand >}}

> Have these hardware components been built, produced or modified by others
> outside of the project independently?

{{< expand "Show answer">}} Yes, definitely. We had a maker space in South Germany who
replicated one charge controller completely by themselves, we didn't even know
about. Afterwards they sent us a link to the forum when he discussed it. They
replicated it and used it for a sensor node as well. This is one independent
replication of the component.

We have a forum in the project. Within the forum,
you can see a lot of people who are interacting and making questions because
they replicate the components by themselves. I don't have an exact number.
{{< /expand >}}

> Is the project still ongoing and you're working together in a group?

{{< expand "Show answer">}} The hardware development of the electrical layout is mainly done
by Martin Jäger. I have to look in the GitHub if there are more contributors.
I'm doing the educational part. I'm designing the resource contents for
education. Katherine, who was in the Open Hardware Summit, works in the
educational part because she's in the library and does a little bit of software
for data visualization. On the data software side are contributors, but we
aren't in a local group here in Hamburg. It's distributed in the world.
{{< /expand >}}

> Are you all working on the same hardware what can be found on the repository?

{{< expand "Show answer">}} Yes, everything around the hardware components within the Libre
Solar project. {{< /expand >}}

## Research outputs

> What were or still are the envisioned outputs of the hardware development in
> terms of publications, the hardware itself, documentation, learning and
> experience?

{{< expand "Show answer">}} My wish is to build up Libre Solar as the Arduino for renewable
energy systems. I always want to have an open hardware base for learning and
building up its own renewable energy system for everyone. It's for industrial,
private or educational use. We aim for a ready to sell product and we are nearly
there. It's just because of the CE certification. We already did a few tests in
the laboratory for measuring the CE standards but we were out of range and
didn't get the CE certification. That's why we can't legally sell the products,
but it's a goal. Right now we have the supply shortage of microcontrollers which
causes the prototyping process to hold because we can't source STM 32
microcontrollers. In the beginning, the goal is to have a set of hardware
components ready to sell with a portfolio for educational reasons and research
institutes. There was a connection with the Uni Freiburg and different other
universities who are interested. This is a low entry point because you don't
need the proper certification if you just use it in research environment.
{{< /expand >}}

> Would those be your customers?

{{< expand "Show answer">}} This would be one channel. For example, we think of sensor nodes
for agricultural applications, which we test here in Hamburg for loading stations
for mobile farm. It's energy supply, we can use it for nearly everything which
needs electrical current. {{< /expand >}}

> Do you combine the Libre Solar with other hardware?

{{< expand "Show answer">}} The hardware is just a load for us.

{{< /expand >}}

{{< card2 "Academic outputs">}} 
It’s not the main goal.
{{< /card2 >}}

> What do you think about publications in scientific journals or in hardware
> journals?

{{< expand "Show answer">}} It's not the main goal. I'm a researcher now. I talked with
Martin about the publication of one paper, for example, from Joshua Pierce on
Hardware X. There you can publish open source hardware projects, but it's not
the main focus. {{< /expand >}}

> Did you publish project findings in relation to the hardware like issues you
> faced in the development process and what you learned in the development
> process along with the individual bill of materials, CAD files, assembly
> instructions, guidelines, essentially and everything you found out during the
> process of development?

{{< expand "Show answer">}} Not specifically, our feedback or the issues is that we make an
iteration of the documents and republish the documentation. If we see that there
is something missing within the documentation, we redevelop the documentation
and publish it. But it's not explicitly a publication about the issues. We're
thinking about a blog. If you have a blog post, you can say here is something we
made. It's a little bit like issue tracking using GitHub. While we were in a
replication workshop, we didn't write down the issues. We just make an iteration
of the documentation. {{< /expand >}}

> The research output was the hardware itself and not any publications around
> it?

{{< expand "Show answer">}} Yes, no publications. {{< /expand >}}

> What kind of information have you shared in terms of the bill of materials,
> CAD files, assembly instructions, warning and safety guidelines.

{{< expand "Show answer">}} I could have a look in the repository. It's mainly for the
hardware with common information like design files, CAD files and interactive
bill of materials. We didn't provide an assembly guideline for electronics but
we made a guideline how to source the components. It's like our educational
resource website where we put in everything concerning assembly processes.
{{< /expand >}}

{{< card2 "Publication strategy">}} 
We published it only on GitHub. There’re some linkings to the wiki from Open Source Ecology in Germany. 

Open Source Ecology helped to disseminate or promote the project in a way.
We provide information on different platforms to draw more people for us and the Open Source Ecology.
{{< /card2 >}}

> How did you publish the hardware?

{{< expand "Show answer">}} We published it only on GitHub. There're some linkings to the
wiki from Open Source Ecology in Germany. The key entry in this platform is
describing a so called Open Nano Grid. This would be another application you can
make with hardware components from the Libre Solar project. {{< /expand >}}

> Why did you choose GitHub and the Open Source Ecology?

{{< expand "Show answer">}} GitHub was like the poster in this time, Martin Jäger choose it.
I think it was the most common collaboration platform for software development
and electronics. It's really comfortable because you have a version controlling
and all this DevOps functionalities behind it. {{< /expand >}}

> Was using this platform for development easy or have you faced any barriers?

{{< expand "Show answer">}} The starting point is a little bit tricky. For people, who come
from outside and aren't aware of software, it's hard to interact with GitHub or
Git-based repositories. {{< /expand >}}

> Why didn't you publish issues you came across? Was there any active decision
> making?

{{< expand "Show answer">}} No, I think it wasn't a high quality notes document that we had.
We didn't have the time to make it in a qualitative documentation to publish.
{{< /expand >}}

{{< card2 "Core team and community">}} 
The creating of more content is limited by the amount of people, time and financial resources. Everything is on a voluntary basis.

With master students from electrical engineering, renewable energy systems and mechanical engineering, we mainly replicated the Libre Solar hardware and redesigned the solar box.
I was introducing it to all the courses. They wrote me they were interested.

We used a typical forum where people can add questions and threads.
It’s very good because you see people contributing in this topic.
This shows that different people come with different requirements. 

{{< /card2 >}}
> Is there something else besides the time constraints?

{{< expand "Show answer">}} Yeah, that's one of the main main components and maybe the amount
of contributors. If you have more contributors who feel more safe with the thing
you develop, you will get more feedback and you can optimize the product better.
When Martin Jäger is the only developer here, he always doesn't know if the
design is the best design. The feedback on hardware design is crucial besides a
lot of contributors.

It would be easier because now you're developing and you maybe know that the
quality is quite good but you don't have the direct feedback. Because we don't
sell the product, we don't have a customer environment feedback process. For
now, there's not so much qualitative feedback for the design. {{< /expand >}}

> Since the project has been reproduced in independently, did they need to
> reinvent anything or did they have all the information they needed to
> reproduce it?

{{< expand "Show answer">}} From the independently replicated parts we don't have any
qualitative feedback. I can just assume and you can analyze the forum.
{{< /expand >}}

> How did you handle problems with GitHub?

{{< expand "Show answer">}} It's easy for people who have a technical or software development
background. We did the entry workshop about how to use Git. (Yeah, okay.) A
colleague of ours did a little workshop. The graphical interface of GitHub makes
it much more esay using it and it was like trial and error or working with it
together. It helped to focus on the main features. With time the people got used
to it. It's like a learning curve for platforms. {{< /expand >}}

> Could you explain the connection to Open Source Ecology Germany?

{{< expand "Show answer">}} Yeah, it wasn't directly to GitLab from Open Source Psychology
but to the wiki from Open Source Psychology. Open Source Psychology Germany is
running a wiki. There they can maybe just search for the entry. It was like one
article where they mentioned the Libre Solar project. But we are documenting it
mainly on GitHub. Other people, who are reusing the component, are documenting
it and the key focus was ecology. They helped to disseminate or promote the
project in a way. Some people informed others that there's this component you
can use to build up an open nano grid. This was the system they introduce.
Therefore, they link to the Libre Solar project and say that this is the open
hardware component you can use for building up such a system. {{< /expand >}}

> All right. And so you you use these pages as well, I mean, I see I see your
> name here. You use this to and to draw more people, I guess, at least a couple
> of people.

{{< expand "Show answer">}} We provide information on different platforms to draw more people
for us and the Open Source Ecology. That project pays to show the interlinking
or the collaboration between the organizations. Indirectly, it's to draw more
people and to reach out from the different organizations. {{< /expand >}}

> Could you explain the connection with the POC 21 of Libre Solar?

{{< expand "Show answer">}} I wasn't involved there, this was before my time. Martin Jäger
attended at the POC 2021 meeting in Paris. I don't know how he got there and
under which circumstances. He was asked for something that I don't know. He got
to know different people from this from the Open Source Hardware community and
they're still connected there. {{< /expand >}}

{{< card2 "Local production">}} 
I think because the documentation is there. They're replicating it.
 
The second part in the educational part is the production.
We have development and production stage and now the usage stage. Each component has a user manual.
It would contain the data acquisition, data analyzes of energy systems and improvements. 
The fourth stage would be recycling or upcycling of such components.
{{< /card2 >}}

> How would you classify the overall information you've put out?

{{< expand "Show answer">}} The main clustering was the hardware, education and maybe the
website. Then it's three or four if you want to consider the forum as an
information base. It's like the hardware information. This was mainly the
repository you have on GitHub. The hardware information is consisting of the
design files, BOM file, readme file and an overview. This is the technical
documentation of the hardware. It's one main information cluster. For all the
components exists a separate or a dedicated repository with these informations.
The second information cluster is the learning the learning cluster. It's the
open education resources. The main idea behind it is to give a basic information
about the used technologies within a system. It's divided in two chapters. One
is a system view to have an overall view of what we are here talking about
regarding the nano grid system, renewable energy and PV battery. The second part
is the component part. It's to dive in into the components. For example, how is
a charge controller built up? What does a charge controller contain? It has a
power electronics, measuring and communication stage. I'm clustering it in the
subcomponents of the hardware. The idea behind it was that people who want to
contribute in the development have a starting point of what do they want to
develop. If you have an electrical engineering background, you don't need this
because this what you learn in university. But if you don't have and you're
interested in renewable energies, you can use the educational resources to get
the basic overview. The second part in the educational part is the production.
It's about how to replicate and produce such components. I'm oriented on the
lifecycle process. We have development and production stage and now the usage
stage. Each component has a user manual. For learning environment, user usage
and documentation it would contain the data acquisition, data analyzes of energy
systems and improvements. But this isn't yet developed. The fourth stage would
be recycling or upcycling of such components. {{< /expand >}}

> All right, yeah.

{{< expand "Show answer">}} The forum was a typical forum where people can add questions and
threads. It's very good because you see people contributing in this topic. There
is one about the development of a new charge controller and this was a very
active thread where people give their feedback to it. It went on for some time.
It results in a new development of a hardware. This shows that different people
come with different requirements and make up their mind for the development of a
new 20 ampere maximum power point checker. {{< /expand >}}

> Is this on your own website again? It's like a repository blog.

{{< expand "Show answer">}} It's made with static site generator called viewpress and a git
repository. There's a framework and broad usage. Within viewpress are different
content blocks. This forum is based on this course an open source forum
platform. {{< /expand >}}

> Do you publish everything there?

{{< expand "Show answer">}} GitHub is the main backbone of all information and data. It's
linked to two other front end websites. {{< /expand >}}

> Did you publish everything you have?

{{< expand "Show answer">}} Yeah, everything is published. For example, the main development
of the battery management system, which got funded by energy access, is within
one repository. Energy access funds open hardware project in the field of
renewable energy.

The creating of more content is limited by the amount of people, time and
financial resources. Everything is on a voluntary basis. {{< /expand >}}

{{< card2 "Successes and failures">}} 

 
 Successful is the ready to use prototype we developed.
 
 In my opinion, it's a very high quality documentation of all the components, it’s very structured. We were able to develop educational resources within such a hardware project which isn’t typical.
 
  The idea behind the open education resources was that people who want to contribute in the development have a starting point of what do they want to develop.
 
  The feedback on hardware design is crucial. It would be easier with a lot of contributors. For now, there's not so much qualitative feedback for the design.
 It would be nice to have more contributors dedicated on the electrical hardware design.
 
 If we would have people who manage the feedback and community work, we could get more qualitative feedback out of it. 

{{< /card2 >}}

> What was successful and what wasn't about the project?

{{< expand "Show answer">}} Successful is the ready to use prototype we developed. I would
declare it a prototype because of this legal issue of the CE certification and
not call it a product. It's ready to use and people are using it with off grid
applications all around the world. We have a feedback loop from the research
project how the system is running. It's running. This is the main success. The
documentation is a success, too. In my opinion, it's a very high quality
documentation of all the components, it's very structured. We were able to
develop educational resources within such a hardware project which isn't
typical. The contribution in the hardware design is improvable. This is still a
gap. It would be nice to have more contributors dedicated on the electrical
hardware design. We had some reviewers which was good. We need to know how to
improve the EMC within the electrical component. There was a review but not an
active contribution to this. {{< /expand >}}

> What kind of contributions are you looking for?

{{< expand "Show answer">}} A review was there because it was from friends. We had the direct
contact. It wasn't on a GitHub sphere or distributed community sphere. It would
be nice to have a review and improvement suggestions for the design. A complete
redesign isn't the goal behind it. If someone would redesign it and make a
suggestion, that would be very cool. But it's not the main goal. {{< /expand >}}

> Do the universities and others, who are using it already, contribute ?

{{< expand "Show answer">}} They don't contribute in the electrical electrical layout. I
think, the users are mainly people who need the current and want to have
renewable energy. The main reason is always the software part. You have open
interfaces where you can extract data out of it and you can control data out of
it. You have the operating power for the system. You can use it for your
requirements. If the current flow is not 99%, these users doesn't care about if
they see a failure. Till now, they wouldn't contribute to erase this failure to
improve function. {{< /expand >}}

> How do people use it? Do you sell it and they put it together? How far is the
> reach of the hardware?

{{< expand "Show answer">}} They're building it by themselves. I think because the
documentation is there. They're replicating it. We had one hardware where we
made a little batch of 100 components and this was sold. Now the batch is empty.
We had no CE certification for one component, therefore it was only for
educational and tinkering purpose. Another example, at the CCC Congress we had
around 10 and we sold three out of it. It were Universities from France and UK.
The third I don't know anymore, but there were people who were interested and
said to buy a new one, because they have a research topic and it costs like 50
or 60€. There were distributed server applications and they wanted to test how
servers can run on renewable energy systems. This was the perfect use case for
them because they can extract all data out of the charge controller and they can
correlate with their process data. They are still running on those parts and
sharing with us information.

If we would have people who manage this feedback and community work, we could
get more qualitative feedback out of it. {{< /expand >}}


## Participants

> What brought you to this project?

{{< expand "Show answer">}} At this time, I was a member of the Open Source Ecology
association in the field of open source hardware community. I was attending some
lab meetings. I was definitely convinced by the idea of open source hardware and
I was intrinsically motive interested in renewable energy systems. I studied
electrical engineering with the focus on automation systems and therefore my
interest are energy systems and the automation aspects behind it. When I moved
to Hamburg, there was one member of Open Source Ecology who said to me that
there is the Libre Solar project and Martin Jäger, the developer, lives in
Hamburg. This was a coincidence. Besides I found a call from the open Hamburg
online university to contribute to a project of open education resources.
Afterwards I made a concept to build a box which I've seen in the Open Source
Ecology wiki. It was a solar box. But it used different types of PCBs of solar
charges. At this time, it was a solar charger developed by a Canadian developer.
So my idea was to take this solar box and take the Libre Solar components out of
it. I already had the electrical expertise to design this a little bit in my
head.This was when I called Martin Jäger and introduced him to this idea and he
was interested. That's how I jumped in. It was mainly within the development of
open educational resources. {{< /expand >}}

> Was this like a thesis or how did this project start?

{{< expand "Show answer">}} It was a funding project of the Hamburg Open Online University.
They had a funding round and they were very interested of students who
contribute. At this time it was mainly professors, researcher and staff. I was
like a student which they were very interested in. This time I got funded. It
was like 25,000 Euro. It was like the first funding project for me. I was a
completely unexperienced with such things. I was just a student.

My professor was the mentor because that was needed from the Hamburg open online
university. I was a student and the project leader of this funding project.
That's how we started. In this project we didn't pay any people. This was my
idea to have people who are intrinsically motivated who would join without
money. We took all the money for buying hardware, to rent fab labs and the
machines and producing a promo video. It's a little YouTube video of introducing
open source hardware. All the money wasn't spend on people but on external
resources. {{< /expand >}}

> Have other grants been used to pay people?

{{< expand "Show answer">}} The second grant we get was used to pay student assistants. They
created the content. Our idea was bigger and it was to much to write this
content all in our free time. {{< /expand >}}

> What were the occupations of the people who contribute?

{{< expand "Show answer">}} It wasn't directly to the Libre Solar project. With the beginning
of this open educational resource, I started a student group with my professor
as a mentor and we called the student group "collective open source hardware".
„Cosine eight" was the name behind it. We were the seven people in the student
group. We mainly replicated the Libre Solar hardware and redesigned the solar
box. {{< /expand >}}

> Were all of you students? Could elaborate if there're other postdocs or
> professors.

{{< expand "Show answer">}} My old supervisor, or professor, wasn't in the content. He wasn't
really part of it. He was very interested and he gave me all the possibilities.
I started to introduce this project in all courses within the university. I
jumped in 20-25 courses and introduced it to the students with his help because
he introduced myself. It made it a little bit easier to introduce my project
because he said it's a good project and you should listen to it. In the group we
were students and Martin Jäger has a PhD degree. He worked part time in the
automotive industry and part time developed the Libre Solar project. The others
were all mainly master students from electrical engineering, renewable energy
systems and mechanical engineering. In the Hamburg open online university we had
some communication designers who did the logo and other icons. They designed it
for us or helped us to design it. They were employed at the Hamburg Open Online
University. It was a service they gave us for free. {{< /expand >}}

> How did you find all these people?

{{< expand "Show answer">}} I was introducing it to all the courses. It acquired them by
myself and some of them I knew already. With two of them I had direct contact
and the others were interested after introducing it. They wrote me an email and
told to be interested.

We had two students who made their student project work in this area. They took
a solar box and made the testing. They tested all the parameters of the solar
box, for example current versus saturation. But it didn't went so good to be
honest because they didn't document anything. It was for them to do it but not
on a qualitative level. They just did it for getting the credit points without
the open source community documenting. It was a project work they had in one
course. {{< /expand >}}

> Did all students receive credit points for the work?

{{< expand "Show answer">}} No, it were only two of them. They said they had to do a project
work. They asked if they can do this project work in this field. For myself, I
didn't get any credit points because we didn't have a project work where we
could use this for. But I did my master thesis in the Libre Solar project. I
asked my professor if I can do my master thesis there. I introduced the topic,
it was about control systems {{< /expand >}}

{{< card2 "Personal gain">}} 
Some students perceived a benefit, they could get credit points. For the others, it was fun. You're playing football and others are tinkering in a Fab Lab.
It provided a learning effect. Application oriented learning I would call it now. 
{{< /card2 >}}

> How did the different members benefited from the work?

{{< expand "Show answer">}} I think, Martin Jäger's was happy that people were interested in
his project. In terms of community reach out, this supported community building
for him. The main idea of the student group was to get more students in the
field of open source hardware. In 2017, no students knew what open source
hardware is. This was in my field, I was very pity that no one knew what open
source hardware is, especially engineering students, because there's so much
potential behind. It's still the case. I think, this was for Martin a motivation
because we talked about it. He said that's a good idea to disseminate the idea
of open source hardware within engineering students. Some students perceived a
benefit, they could get credit points because they had this project work where
they got credit points. For the others, it was fun. You're playing football and
others are tinkering in a Fab Lab. For some, it was the first time of
manufacturing. For example, I studied electrical engineering and I've never
picked and placed a PCB. I've never saw a PCB production. It was in theory
taught but we never experienced it in the laboratory. It provided a learning
effect. Application oriented learning I would call it now. {{< /expand >}}

> Who got paid from the grants?

{{< expand "Show answer">}} Martin Jäger got a little bit of this money because he has this
high education level and he put a lot of time in it. We said to Martin to write
a receipt because he's working so much in this field. Even though he didn't want
it to but we said that's money for your work. Besides we did the video I
mentioned. It was a video creator who got paid for doing information videos.
{{< /expand >}}

> Didn't anyone receive payment for a longer period?

{{< expand "Show answer">}} In the second phase we got students paid as student assistants
and paid students for creating the content. {{< /expand >}}

> How many student assistants did you have?

{{< expand "Show answer">}} We had two. I think they worked for a year or a year and a half.
There was Corona and maybe it was extended by half a year. {{< /expand >}}

> Was all of this still at the Hamburg Open Online University situated?

{{< expand "Show answer">}} All of this was at the Hamburg Open Online University.
{{< /expand >}}

> How did you coordinate the work?

{{< expand "Show answer">}} The coordination of the development was quite easy because Martin
was the only developer at this time. The software development coordination went
through Git. The research projects had a typical research project coordination
with Martin as a partner. But I don't know the exact constellation of the
research project he worked with. For our student work the coordination was made
by me. We had a telegram channel where we had ad hoc communication. We built up
a GitHub repository where we had issue-based coordination. This was a little bit
of our project management behind it. Besides, we had weekly meetings at a Fab
Lab. This was every Thursday, it was meeting in the evening with discussing and
thinking about the design and requirements. It was in the Fab Lab St. Pauli.

Martin was there before us. His first prototype and first testing system was
build in the Fab Lab St Pauli. At the Fab Lab St. Paul was a solar panel
charging a battery. This is why we went to the Fab Lab St Pauli, too.
{{< /expand >}}

> Why didn't you meet at the University?

{{< expand "Show answer">}} The university didn't gave us a room. We asked for it. They
brought us then in an old laboratory, where we could hang around. But this isn't
a good place to work. Then they build up a Fab Lab but it wasn't open for
students. We asked for it but it's just for startups and some ecosystem share
stakeholders.Further, there was a Fab Lab with 3D printers. But it wasn't a Fab
Lab where you can like tinker around, it was just for 3D printing. The
university didn't have the infrastructure for us. That's why we went to a Fab
Lab. {{< /expand >}}

> How many members were in the project?

{{< expand "Show answer">}} We were seven people.




{{< card2 "Hardware components">}} 
{{< /card2 >}}














It's really comfortable because you have version controlling and all this DevOps functionalities behind it.

