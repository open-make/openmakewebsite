---
title: 'Interview: Ultrasound device'
author: 
  - Open make interview team
  - Luc Jonveaux
date: '2024-05-20'
slug: interview-ultrasound
categories: [interview]
banner: img/banners/fixme
tags:
  - technology
  - open hardware
  - personal story
---
# Interview: Ultrasound device

Luc Jonveaux has been developing some ultrasound devices in open source in his spare time for several years. His motivations have been to have fun and give back to the commons. Different devices were created in his small apartment in Paris, and they were used by quite a large community of enthusiasts.  


*by the Open make team, Luc Jonveaux. Copyright to the authors, distributed under a CC-BY 4.0 licence.*



**Sections:**
- [The project](#the-project)
- [The hardware](#the-hardware)
- [The research outputs](#research-outputs)
- [The participants](#participants)

*Banner image: fixme, By CERN, distributed under a CC-BY-SA 4.0*

>Interviewee: Luc Jonveaux 
>
>Interviewers: Robert Mies (TU Berlin) & Moritz Maxeiner (FU Berlin)
>
>Transcription and editing: Diana Paola Americano Guerrero, Robert Mies, Fabio Reeh, Moritz Maxeiner & Julien Colomb

<img src="images/Screenshot.png" alt="screenshot of the interview" width="60%"/>

*Screenshot of the interview.*



{{< card  "The un0rick in a nutshell">}}

![FIXME](images/FIXME.jpg "WR Switch") 

*Photos of FIXME*

- Main website: http://un0rick.cc
- Project start: 2018
- Core development team size: 1-5

### Hardware products
un0rick has a modular concept where the different functional blocks of the hardware split into individual physical elements.
The latest is the lit3rick board, which are smaller, approximately the size of a Pi Zero or Raspberry Pi’s.

### Hardware maturity
lit3rick is market ready
### Rebuilds
Some used the sources to do their own batches through fabs and produced it on their end.

{{< /card >}}






## The project

{{< card2 "Project start">}} 
I was a research engineer at Philips in medical imaging. we were working as a company on a low cost medical imaging device and they decided not to proceed with the product.

In 2014 Mehdi, another doctor, Olivier and I, started echOpen as an association to post the technical project of having open source with ultrasound.
I left in 2016. echOpen was more going into medical device. I wanted to focus on opening the technology to let people play with the tech. 

{{< /card2 >}}

> How did the project open source ultrasound start?

{{< expand "Show answer">}}
The project, platform and names of the products are around providing an Arduino of ultrasound to researchers, academics and makers because nothing existed in the market. Long story short, I was a research engineer at Philips in medical imaging for more than 10 years. 
2007 I went into research. One of the things that bugged me is that we were working as a company on a low cost medical imaging device and they decided not to proceed with the product. We had the proof of concept but not the product. In terms of marketing, why should you sell something 1000 times when you already sell something one and 1000 times. That was the  additional gain there. I have technical skills in ultrasounds and ultrasound measuring. In 2014 Mehdi Benchoufi and I had an initial discussions for what became echOpen afterwards. 

Mehdi, another doctor, Olivier and I, started echOpen as an association to post the technical project of having open source with ultrasound. I left the administration of the association in 2016 or 2017 because I wanted to focus on something that would be used by makers, hackers and layman. echOpen was more going into medical device. It has been two different approaches. I wanted to focus on what I thought was the priority, which is to open the technology to let people play with the tech. 
In 2016 and 2017, I started a couple hardware pieces, which we had pitched in Grenoble at the time. It was around a modular approach with the different functional blocks of an ultrasound system, fragmented in different modules that you could assemble to other working systems. 
That went to some extent and confirmed the interest from a community. That evolved in terms of mentality towards a more integrated system and more proficient system. The un0rick board is interesting, I am not an electrical engineer, therefore I knew nothing about electronics design. The project reflects my technical knowledge, because in the beginning it had low complexity. The more I knew about the project, the more I was able to concentrate on my skills and vice versa. 

I improved my skill and by this the complexity of the project. The un0rick worked but with the pandemic in 2020 and the supply shortage I did’t have the chips and couldn't move forward. Therefore I stopped developing the product. 
It was a pain in the backside.  What was mature enough was going to into the hands of users. Then I started developing a new series of board delay tricks which are smaller, cheaper and have a bit more performance. I appreciated that this is a preliminary step into next stages of the project which I discuss with the MRI people. 

I think what I've done for Ultrasound could be replicated in the MRI space. If we look purely at the technology, we are talking about signals in the megahertz range. What we're discussing right now is to what extent we could build a common tool, a  basic Arduino, that could be used with another board for both technologies, ultrasound or MRI. 
But in the end, I have this hybrid approach to MRI and ultrasound. This is where I'm playing and that's where the lit3rik has been used as a test bench for exploring that.


{{< /expand >}}

{{< card2 "Project process">}} 
I egoistically started with documenting what I was doing. 
When you do that in evening and weekends or from time to time, you take a break and never know when you come back to experiment. You don't know where you’ve been. 
It's quite helpful to have a documentation.

People come to me by email and I have a open Slack channel to allow people to talk to me and to a wider community.

A good consequence of the bottleneck of time is that hardware takes time.
I can put everything on hold for two months and just keep the communication in the community. Because it's a side project, that doesn't bother me.

I don't have a roadmap. It's just what is fun at the moment.
{{< /card2 >}}

> What was the core benefit of the project?

{{< expand "Show answer">}}
The core benefit is to be honest that I have a blast and  I learn. 

The side benefit is to generate something you can share. I see value in providing something to others. It’s another egoistic benefit to know that you can make benefits to provide benefits to others. Apart from this, the greatest benefit is that I like to believe my users are getting access to technology that they wouldn't have access to normally.  My users are academics who want to have a system to test ideas. 
I've seen startups using that to develop proof of concepts. I've seen teachers using that to add a demo tool for their courses. I've seen even institutional organization working with me on customizing it. It feels like I can contribute to the academic world to some extent. The benefit is to make it available and allowing people to  test the ideas for educational purposes.


{{< /expand >}}

{{< card2 "Funding">}} 
I'm not making any money out of that. The community helps keeping the cost down when doing a batch. 

When it comes to get funding and institutional support or knowing an email address to be able to register on any research publication institute, it's impossible. 

From my pocket I spent maybe between 5 and 10 000 € over the past five years.
{{< /card2 >}}

> Is the project funded in some way?

{{< expand "Show answer">}}
It's funded by me as an individual and  we have a discussion with, for example, JOGL. You may know Thomas Landrain of the one giant lab initiative.

As an individual maker, I have no structure in terms of business. When I'm doing batches of boards, I could have benefits of scale for launching sets.
When I'm developing one board for myself, I make a bunch of choices that I make available to the community.  They can pay for that and by this it pays itself. 

I'm not making any money out of that. The community helps keeping the cost down when doing a batch. 
Funding is a good question.  I've tried publishing articles about the open hardware, methodologies and sources I'm using, but I'm not affiliated with any lab. 
When it comes to get funding and institutional support or knowing an email address to be able to register on any research publication institute, it's impossible. 
I'm on a position in my day work. I’m working, for example, on Horizon 2020 projects. I'd like to get involved as an individual from this hardware perspective. 
I'd like to be involved in this project, but I can't because I'm not affiliated with an organization, which can point me a key to this space. 
JOGL is just one chain. How could we get access to the space?  When it comes to funding and resourcing connection, we are missing that.

{{< /expand >}}
> How much money have you put in yourself?

{{< expand "Show answer">}}
That's a good question. From my pocket I spent maybe between 5 and 10k over the past five years.

In practice, I have a bit in order. When I was doing an order and trying to get money, pharmacists were interested in the board. The overall budget is a little bit larger, I would say. Maybe an order has the factor 10 or 15 because I'm doing 20 to 30 board batches.

{{< /expand >}}

{{< card2 "Work Coordination">}} 
I don't want to  be a bottleneck in the community communication. 
Most of the interactions are through slack.

A bit of physical interactions occur because a few current members came through Paris or London and we meet to chat in meetings.

It's pretty much organic and defined in the long term.

The institutions I work with and I define the requirements. We have extensive periods of exchanges about  their needs. To some extent, they drive the decision of the joint project. 
Later I provide more support and know what I'm taking back from that.


{{< /card2 >}}

> Could you describe the overall process?

{{< expand "Show answer">}}
Community-wise, an open source starts with documentation. I egoistically started with documenting what I was doing. 
When you do that in evening and weekends or from time to time, you take a break and never know when you come back to experiment. You don't know where you’ve been. 
It's quite helpful to have a documentation. The documentation brought the interests of some people and publications. I've done a couple of publications on, for example, the Journal of Open Hardware. That raised the profile of the project. People come to me by email and I have a open Slack channel to allow people to talk to me and to a wider community.

I don't want to  be a bottleneck in the community communication.  If I were to be hit by a bus tomorrow, I still want the community to organize itself. Therefore I set up this place. The most of the interactions are through slack.  A bit of physical interactions occur because a few current members came through Paris or London and we meet to chat in meetings, like what we did in Grenoble. 

To have the opportunity to meet with the wider open community is interesting. I'm still in touch with echOpen as part of the open ultrasound wider community. 
I want to bring people to the documentation first and then to Slack, if they have any question.

It’s pretty much organic. Today,  on the Slack are around 240 participants. I won't teach anything, it's in your papers, I think we have 20 active members. 
It’s more if you consider people who have an interest for school or an academic project that would be disconnected for six months and then disappear. 
The activist circle would be five. The latest paper I published was with these guys. We have a community paper that has been published. 

{{< /expand >}}
{{< card2 "Major issues">}} 
There is no real issue because un0rick is a side project. My life doesn’t depend on that.
As a side project, I develop it when I want to and when I have the time to. 

Components shortage over the last year  froze the development of what I'm doing.

I'm developing that at home on a 65 square meter flat in Paris. The smaller my bench is the better. That's why I focused on electronics.
{{< /card2 >}}

> What major issues have you come across during the project and how did you resolve them?

{{< expand "Show answer">}}
There is no real issue because un0rick is a side project. My life doesn’t depend on that. If someone makes me angry, I don't answer them.  I never had any issues after that. The major bottleneck is time. As a side project, I develop it when I want to and when I have the time to. 
There is a minor bottleneck which has been the components shortage over the last year and it froze the development of what I'm doing.
I'm not in a position to put new boards on the market. Giving something to the community from our perspective is impossible. 
That's development of the community. Another advantage is hardware takes time. 
A good consequence of the bottleneck of time is that hardware takes time. If you wait two months for a board and you can't do anything,  I put everything on hold for two months and just keep the communication in the community. Because it's a side project, that doesn't bother me.
It's pretty much organic and defined in the long term.

{{< /expand >}}
{{< card2 "Core team and community">}} 
Today, on the Slack are around 240 participants.
I think we have 20 active members.

The agreement I have with institutions is that I advise them on the sector on something they do not know, and in exchange, they put technical and professional skills into the project, which is fed back to the project.

 Most of the active contributors have this willingness to share back. It's the mentality  of playing around.
{{< /card2 >}}
> Do you have to make decisions in the project or how are they made?

{{< expand "Show answer">}}
We thought to make decisions as in a design.  I make decisions based on my requirements. Because I'm the primary user and make that primarily for me. 
I'm collaborating with, for example, institutions. The process I follow to take the decisions is quite simple. The institutions I work with and I define the requirements. We have extensive periods of exchanges about  their needs. To some extent, they drive the decision of the joint project. 
Later I provide more support and know what I'm taking back from that. It can be an interesting byproduct in terms of consultancy that these guys are not against showing what they've done in the open space. 

I'm advising them to have the technical skills or skills to develop new things. They would develop new things and that would come back to the project. The agreement we have is that I advise them on the sector on something they do not know, and in exchange, they put technical and professional skills into the project, which is fed back to the project.
The perfect example is the latest iteration of the lightning bolt as being co-designed by professionals from a Canadian institution. It was a bit messy before. They have come in, reviewed it and optimized stuff. 
They use that for their project, but I've asked them to give back with that produced. 
Coming back to the decisions, I don't have a roadmap. It's just what is fun at the moment. The perfect example is what we'd like to do with open MRI initiative. The challenge is to find common themes between MRI and ultrasound. There is an intellectual challenge there. That has driven the decision of pursuing something together. 



{{< /expand >}}

## The hardware

{{< card2 "Hardware components">}} 
The firs version was around a modular approach with the different functional blocks of an ultrasound system, fragmented in different modules that you could assemble to other working systems. 
That evolved in terms of mentality towards a more integrated system and more proficient system.

The project reflects my technical knowledge, because in the beginning it had low complexity. The more I knew about the project, the more I was able to concentrate on my skills and vice versa. 

Then I started developing a new series of board delay tricks which are smaller, cheaper and have a bit more performance. I appreciated that this is a preliminary step into next stages of the project which I discuss with the openMRI people. 

We are discussing to what extent we could build a  basic Arduino, that could be used with another board for both technologies, ultrasound or MRI.
{{< /card2 >}}

> What hardware products have you developed?

{{< expand "Show answer">}}
The first was the Murgen board, which was a Beaglebone add-on. It’s a plugin like the hats on the Raspberry. Then I developed the modular concept where the different functional blocks of the hardware split into individual physical elements. This was the  echomods project. The third iteration was the un0rick with the bigger blackboard. The latest is the lit3rick board, which are smaller, approximately the size of a  Pi Zero or Raspberry Pi’s.
Those are the main hardware solutions that I've used. While prototyping the hardware, I've used different developer boards and kits to help me play and assess it before committing to a design.

{{< /expand >}}
> How would you classify the product? Is it mainly a board, or are there other components, like mechanical or software, that you had to develop? 

{{< expand "Show answer">}}
It's electronics at heart. One of the constraints that I've had is to compare with what a company is doing. I'm developing that at home on a 65 square meter flat in Paris.  I can't afford to add a 3D printer there to the test bench. The smaller my bench is the better. That's why I focused on electronics.

{{< /expand >}}
> I see that the board has FPGAs on it. Did you develop any gateware, or is that up to the end user?


{{< expand "Show answer">}}
The Gateware has been developed. I was wondering when you ask about the stuff, if I should mention that. FPGAs are a little bit more complex than the microcontrollers. They have been traditionally and historically a closed community and proprietary tools. Fantastic work was done by Claire Wolf and its team on developing an open source tool chain for a specific family of FPGA. This work was fundamental for my shift of going from the modules to  separating the functional blocks into physical elements on a single board. The single board was made possible by FPGAs. 
The FPGAs were made accessible to me because of this tool chain. 
Around this spot are different tools to keep the gateware, proprietary tools and some basic shell tools to synthesize. More recently, there has been something called a studio. It’s a visual tool where you can click and hide links between components and blocks.
 That helps the end user, not me, to find a custom gateware. But they can play around easily if they don’t know about Verilog or VHDL. 
A very good example of that is my work with a non descriptive testing team. The hardware is used medically. You can send MDT, non descriptive testing. The guys didn't know anything about FPGAs, but with the visual interface,	 it was easier for them to go into that. They tweaked around a few variables and tweaked the firmware of the gateware to their specific needs. This path FPGAs were instrumental in the shift and the resolution  of the project and the product.

{{< /expand >}}

> Where would you rate the maturity of the product in terms of prototype, demonstrator  or market ready?

{{< expand "Show answer">}}
The lit3rick is market ready. It's to some extent due to  the collaboration with professionals in the sector. I know that they are using that in their solutions 
and it has gone through their tests. I call it market ready. 
From an Arduino perspective, I would have no shame in putting it to fab line, making a batch of that and ensuring that the quality would match what the users expect.

{{< /expand >}}
> Has the hardware been built or produced by others independently?

{{< expand "Show answer">}}
All of the sources are open. I believe we changed to say that I'm still using Altium, which is not 100% open or not open at all. At least the source is there and people can use it.
Some used the sources to do their own batches through fabs and produced it on their end. I know of people who have used the designs for their own purpose and they have reused parts completely and did some slight adjustments to the way before  sending it for production. A very simple example from 2018 is the modular approach.  A team was working on tomography for non descriptive testing and used a copy of what had been developed by users, but didn’t mentioning it. I chased them to try and make them recognize that they had been not developing something from scratch. But at least it was good to see. When people are cooking what you're often cooking,  it's a good sign for the recipe. 


{{< /expand >}}
> Did these people modify it as well?

{{< expand "Show answer">}}
If you imagine, for example, a boat, you have a design and you see the boat, which is two times your design with the same layout,  components and units. There has been some copying.


{{< /expand >}}

## Research outputs

{{< card2 "Academic outputs">}} 
The activist circle would be five. The latest paper I published was with these guys. We have a community paper that has been published. 

I've got two papers on the journal of open hardware about Ultrasounds. I've published a couple of other notes on Zenodo for the CERN people to get some results out. 
{{< /card2 >}}

> What were the envision envisaged outputs of the hardware development in terms of publications, the hardware itself and documents?

{{< expand "Show answer">}}
From a perspective, where I just wanted to get some stuff to play with, the first output was to get something like an arduino ultrasound, the board. That was really the first thing, but then I realized that the documentation was really needed to achieve that. 

The documentation itself became the top one priority. And an example of that is, I'm quite lazy. When I'm running some by myself and trying to document that I've made scripts, for example, to automatically classifies the pictures, screenshots, gas generated from the data of the experiment. 

The data of the experiments is tagged with meta data that allows me to find back what were the conditions of the experiment. If I'm adding the signal, I need to know the target and parameters of the experiment. All of that is in pictures. I'm using the EXIF meta tags to tag the image. I run the scripts since 2016. I haven't touched the scripts a lot, but they are still used in generating the documentation. It’s been real helpful not only for me. When I'm onboarding people, I can point them to a session where I tried tomography and  where we would find the gateware for the FPGA. They would find the scripts that I have used. They can reuse my setup very easily. That became the primary output. The board is an enabler to get some information. 
I think, the board and documentation have been the focused outputs. The community is a byproduct. I have no objectives when it comes to community. You can say fun is the number one expected output.

{{< /expand >}}
{{< card2 "Hardware importance">}} 
I think, the board and documentation have been the focused outputs. The community is a byproduct. I have no objectives when it comes to community. You can say fun is the number one expected output.
{{< /card2 >}}
> Did you publish your project findings in relation to the hardware somewhere?

{{< expand "Show answer">}}
There are a couple of papers that are not exceptional, to be honest, but at least the knowledge is out. I've got two papers on the journal of open hardware about Ultrasounds. I've published a couple of other notes on Zenodo for the CERN people to get some results out. 
I added them to use publications in PDFs which are doubled as zips. If you don't read my article, you can renamed the PDF in zip. If you unzip it, you get access to the source files. It's an all in one piece of documentation.  For a publication, I archive the documentation on GitHub. You could call that a not formal academic publication.

{{< /expand >}}

{{< card2 "Publication strategy">}} 
I've done a couple of publications on, for example, the Journal of Open Hardware. That raised the profile of the project

I publish in my GitHub the design files. The core publications are my online material, which would be in GitHub and Zenodo.
{{< /card2 >}}

> What kind of information have you shared regarding the bill of materials, CAD files and assembly instructions?

{{< expand "Show answer">}}
There are no mechanical elements. We have no CAD files, documentation mission, pictures, decks, Python scripts or instructions.  When I'm doing an experiment, I'm sharing the data of the experiment. It's hard to  keep track of what I've done during the experiment. 

{{< /expand >}}
> How did you publish the hardware besides in journals? Did you publish the hardware overall?
 
{{< expand "Show answer">}}
I publish in my GitHub the design files. The core publications are my online material, which would be in GitHub and Zenodo.
I had a prepaid bird, possibly on archiveX or archive. 

{{< /expand >}}
> Why did you choose these platforms?

{{< expand "Show answer">}}
I choose GitHub because that's easy and universal. It provides integrally the version control system. I choose Zenodo because I wanted to have an independent platform to store notes with some DOI for further referencing. 

{{< /expand >}}
> Were there any barriers in using these platforms?

{{< expand "Show answer">}}
The learning curve for GitHub is low if you're doing some software already . Zenodo is straightforward without  a barrier.

I experimented with a platform called Vector, which is an online hardware editor. I had an issue with my computer that let the interface crash. The designs for the lit3rick and the un0rick are available there but not maintained. I'm not using these platforms anymore because it was not suiting and working with my computer.

{{< /expand >}}
> Is there anything you didn't publish? 

{{< expand "Show answer">}}
Apart from my holiday pictures, I've published everything I've done. Apart from the hardware, I've experimented with Chinese Ultrasound Probes in USB. It’s not purely hardware but it's linked to. I wanted to get the benchmark from a proficient piece of equipment. The issue is these probes were the drivers. You never know what you install on your computer.  I retro-engineered the driver for these probes and made my own. I had the agreement of one of the Chinese fabs to do that. I haven't checked with the others. It's a grey area, I don’t see any problem in publishing some drivers. If I had a doubt that would be in that space. When it comes to the hardware, everything is published.

{{< /expand >}}

{{< card2 "Successes and failures">}} 
I have no objectives unless having fun. It was successful in having fun.

Component shortages frustrates me a lot.
{{< /card2 >}}

> What was successful about the project and what wasn't successful?

{{< expand "Show answer">}}
That's a good question. You can be successful if you know your objectives and I have no objectives unless having fun. It was successful in having fun. The pains I had were mostly around this last month about component shortages. It frustrates me a lot. We have no ways of tackling that. That's for me a big interrogation.  I'm doing open hardware because it’s fun. But if the supply chain is broken and I can't do that anymore, should I spend more time into developing open source hardware?  I know that the world is not collapsing. It's not an encouragement to proceed in open source.

{{< /expand >}}

{{< card2 "Local production">}} 
In 2020 and the supply shortage, I did’t have the chips and couldn't move forward
{{< /card2 >}}
## Participants

> How did you end up working on the project?

{{< expand "Show answer">}}
That was  a history of me being frustration from a big company and the big appetite in open source. I do believe that giving back to the commons and being open are some of the ethics when you're into technology. That drives me in my day to day work. It's about how can we, as an organization, safely  contribute and give back to the comments.

{{< /expand >}}
> How many members have worked on the project and hardware?

{{< expand "Show answer">}}
It depends on the metrics.  I've done a bit of publication on Hackaday at the time. I think there are a couple of followers of this project. I haven't looked at that.  The community's on slack are 240 participants, which is my only metric for the moment.
I'm having a look at my projects on Hackaday. On the Murgan board, I have 2300 followers on Hackaday. I've got slightly less on the other projects.
On Hackaday, you see 2000 and more, it could be a vanity metric.

{{< /expand >}}

> Do you know anything about the occupations of the people that have worked on the project with you?

{{< expand "Show answer">}}
Most of them are Ultrasound professionals or start ups.  I've been approached by startups to supply the piece of hardware, equipment and advisory services. I'm involved on a number of advisory boards for different startups. Other people are teachers who use the devices for their courses. I want to help them with experiments for the classes.

If you look at the map of the purchases, there is a higher amount, for example, in Korea. They have a very strong medical imagery ecosystem as well. In the States, the orders come from mostly universities, a couple of startups and friends. 


{{< /expand >}}
> Have all these different groups contributed to your project? How many people have contributed?

{{< expand "Show answer">}}
About 20 people have regularly contributed and 5 to 10 have rarely contributed.

{{< /expand >}}
> How did you find suitable project members to contribute? 

{{< expand "Show answer">}}
I'm not finding them, they are finding me. It's where I'm at. I'm actually not active in this project. I've just opened a room for discussion. People sometimes drop by and some stay or  people contribute. I don't have the energy nor the time to go outside and have a look for skills.

{{< /expand >}}
> How did you coordinate the work between the members?

{{< expand "Show answer">}}
Slack is transparent about what is happening at a given point. People have their own projects where they come in. They're talking about their different projects and what they're doing. It creates a discussion. It's not as if I'm coordinating a room where people can come and work together. I can coordinate by saying here is X and they are doing Y. When I’m advising the development of a fork of the product, there is a bit of coordination but it's mostly driven by the users.




{{< /expand >}}
> Can you say how the members or the contributors have benefited from their work on the project?

{{< expand "Show answer">}}
The guys, who contributed, are curious people. They want to learn and find and are a bit similar to me. Maybe that's a bias in selecting and engaging with the community. Most of the active contributors have this willingness to share back. It's the mentality  of playing around. A couple of professionals wanted to have tools and are stuck because they found a cool place to talk. My users benefit because they use the hardware. One of the categories of the contributors would be academics and researchers with an obligation to publish. With that respect, they've shared, for example, a master thesis or their research work. 
That helped the community. 
 I think the exchanges, they've had, were beneficial for them to build  their own thesis. One   example is the latest thesis I shared on the Slack. The guy was looking to get a platform to do ultrasound testing. He got that and the paper is titled like: Exploration of an Open Source Ultrasound Hardware. 
It's an advertisement for my board saying, I've done, could be doing or explored that. 
It's a win-win situation where I give information and get back information. 
One of the project’s benefits  is the mature on enrichment of what we do.

{{< /expand >}}

{{< card2 "Personal gain">}} 
The core benefit is to be honest that I have a blast and  I learn.

Having a nice challenge can be fun.

I see value in providing something to others. 
My users are getting access to technology that they wouldn't have access to normally.
The benefit is to make it available and allowing people to  test the ideas for educational purposes.

To have the opportunity to meet with the wider open community is interesting. 

I do believe that giving back to the commons and being open are some of the ethics when you're into technology.
{{< /card2 >}}

> How did you benefit from the project?

{{< expand "Show answer">}}

I benefited by learning and talking to people with great ideas and having an intellectual challenge. The work is amazing.  It’s a bit different from my background. I'm a research engineer and add a physics or electronics challenge is refreshing. Having a nice challenge can be fun.

{{< /expand >}}
> Would you do it again if you if you think back?

{{< expand "Show answer">}}
Yes, definitely. Hardware takes time and you need to take time. That leaves time to reflect on what you do. I like this process because it give me a different perspective on software development. I would do it again. We're discussing the same adventure in a different space right now with the MRI guys.
I'm curious and talking with the guys in Berlin or Aberdeen is the opening door to come and discuss about what they or I do. 
I'd love to go to a university and have access to an MRI machine to play around with it. 


