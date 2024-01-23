---
title: 'Interview: Gorgas Tracker'
author: 
  - Open make interview team
  - Guillermo Padilla Huamantinco
date: '2024-01-22'
slug: interview-fixme
categories: [interview]
banner: img/banners/fixme
tags:
  - technology
  - open hardware
  - personal story
---
# Interview: Gorgas Tracker

Guillermo Padilla Huamantinco is a PhD student at Institute for Biological and Medical Engineering, he lead the development of the Gorgas Tracker, a device that was used to track the position of people in the amazon.


*by the Open make team, Guillermo Padilla Huamantinco. Copyright to the authors, distributed under a CC-BY 4.0 licence.*



**Sections:**
- [The project](#the-project)
- [The hardware](#the-hardware)
- [The research outputs](#research-outputs)
- [The participants](#participants)

*Banner image: fixme, By CERN, distributed under a CC-BY-SA 4.0*

>Interviewee: Guillermo Padilla Huamantinco
>
>Interviewers: Robert Mies (TU Berlin) & Moritz Maxeiner (FU Berlin)
>
>Transcription and editing: Diana Paola Americano Guerrero, Robert Mies, Fabio Reeh, Moritz Maxeiner & Julien Colomb

<img src="images/Screenshot.png" alt="screenshot of the interview" width="60%"/>

*Screenshot of the interview.*

FIXME

{{< card  "The GORGAS Tracker in a nutshell">}}


<img src="images/GORGAS_tracker_v6_explode.png" alt="Parts of the Gorgas tracker" width="80%"/>

*3D view of the parts of the Gorgas tracker.*

- Main website: https://github.com/healthinnovation/gorgas_tracker/
- Project start: 2019 ?
- Core development team size: 6

### Hardware products
The GPS tracker is based on the geo kit of RePhone.
We found this hardware, the RePhone, and all these different models that allow to develop a wearable device for doing this tracking.
This device uses small, rechargeable batteries. We could develop like a small device that patients, in this case, could use daily.
### Hardware maturity
prototype to demonstrator
### Rebuilds
no known rebuilds

{{< /card >}}





## The Project

{{< card2 "Funding">}} 
Some of the fund was from the Institute of Tropical Medicine.  Gabriel got a funding from that Institute. It wasn’t a small budget.
{{< /card2 >}}

>How did the project Gorgas tracker start?

{{< expand "Show answer">}}
This project started with the funding from the Institute of Tropical Medicine. Gabriel Carrasco, who was the principal investigator of this project, asked me to join, because I was working in some other projects related to public health. I was working with the Department of Engineering. He asked me if we could develop something to track a patient's movement. He wanted to understand the relationship between population mobility and malaria transmission. They have been several studies using this strategy to understand and to see if there is a relationship between these factors and how to control malaria transmission. One of them was using GPS trackers to do that and to see how the behavior of these patients was as part of this study. The main challenge to do this study and to collect data from from patients‘ mobilization was the device. In previous studies, researchers used a commercial GPS tracker, a small one. I don't remember the brand of this tracker. It seems that the brand, that they mentioned in one of the studies, was  the favorite for these kinds of studies. 
A proprietary system that everyone uses.


This device was adapted for this kind of study, because you could track and load the different data while you were moving. It was used more for other purposes and not necessarily to understand  population mobility. They adapted and it seemed to work well. One problem was about the sign up. If you start to communicate with satellites from these devices, it's different in urban areas than in rural areas. If you try to use it in the Amazon, for example, you have a  problem with the weather and trees. You can lose data and you have to assume or predict the movement, for example, if the patient goes from one point to another one. There was a limitation for doing these kinds of research. The other problem is about the technical side. Because it was a commercial device and we had to import it to Peru. Further the budget, that we had at the time,  wasn't enough to do that. If we wanted to do other studies or maybe other people would like to reproduce it, it would be difficult because they need to get the same device to get the same quality of data. 

{{< /expand >}}

{{< card2 "Hardware components">}} 
RePhone is a GPS tracker with the main function to gather  data. The device records the data and is connected to the satellite and gets the latitude.

In previous studies, researchers used a commercial GPS tracker. 

Other limitations were about the technical features.
One problem was about the sign up. If you start to communicate with satellites from these devices, it's different in urban areas than in rural areas.

The other problem is about the technical side.
Because it was a commercial device and we had to import it to Peru. Further the budget, that we had at the time,  wasn't enough to do that.
{{< /card2 >}}


{{< expand "Show answer">}}
The other limitations were about the technical features, the designer and the weather. You don't have the same behavior of these devices, when you are  in rural or urban areas. You could have some variability in this data. Because of those limitations we started to search if there were other projects. In this case we looked for open source projects. I joined the open source movement as I started building 3d printers by using all information from the RepRap project. That's why I knew about this movement and all these different devices. I knew about the DIY movement and then how the open hardware was used for biology. That's why Gabriel asked me if I knew something that would help us for this project. At the beginning, I didn't know. We started to search some other projects, but at that time, we didn't find anything for doing this kind of research. Most of the projects, that we found, were related to conservation in the study of animal behavior and animal mobility. There are some open source projects for tracking animals in general. 

We found it challenging  to replicate or to use the same hardware for our projects. When Gabriel contacted me, I had a RePhone, which are open source cell phones. They launched a crowdfunding campaign to back this project. After I knew about this project, I wanted to know if I could use it for some research. We decided to use the RePhone because you have a platform same as Arduino. In this case, you only have a small board. If you wanted to develop something related or any wearable device, that could be helpful. That's why we decided to use this platform. You can get several kits with this platform. One of them is a GPS module that you could add to the RePhone. We did some tests at the University. It  worked well. That's why we decided it could be an option for doing these kinds of devices and could be suitable in this project to study a population or village.
{{< /expand >}}

{{< card2 "Project start">}} 
This project started with the funding from the Institute of Tropical Medicine. 
We wanted to understand the relationship between population mobility and malaria transmission.

The main challenge to do this study and to collect data from from patients‘ mobilization was the device.

I knew about the DIY movement and then how the open hardware was used for biology. That's why Gabriel asked me if I knew something that would help us for this project.

{{< /card2 >}}

>At the time, were you working as a researcher or research associate?

{{< expand "Show answer">}}
Yes, I was a research associate at the Department of Engineering. They had the Health Innovation Lab, a leader in the startup at the time.
{{< /expand >}}

>Was this internally funded?

{{< expand "Show answer">}}
Partially, some of the fund was from the Institute of Tropical Medicine.  Gabriel got a funding from that Institute. It wasn’t a small budget.  He thought that money would be enough for doing this kind of research and to use it for a sample. When we wanted to publish the results, the reviewer told us that the sample wasn‘t enough for these kind of studies. We should prove why we use this sample for this study.
{{< /expand >}}

>Could you explain how does the hardware fit in the project?

{{< expand "Show answer">}}
We found this hardware, the RePhone, and all these different models that allow to develop a wearable device for doing this tracking. We decided to use these devices because they are small and have the power like an Arduino. At that time, it wasn’t enough using an Arduino Nano. This device uses small, rechargeable batteries. We could develop like a small device that patients, in this case, could use daily. The idea of using this was to give it to the people as part of the project and they could use it in daily activities. We wondered how the mobility was in a specific period of time. That's why it was important in this case. We wanted to understand and connect the data, that we got from these devices, to the malaria test, which we did to verify if they got this disease or not in this period of time. We needed this kind of data to see if there was any correlation.
{{< /expand >}}

{{< card2 "Core team and community">}} 
There were other students involved in this project. I lead the hardware development. There were other tasks such as programming or doing some mechanical designs involved. In this case, they are authors.
There were two other people, Gabriella and Edgar Manrique. They are biologists and work on malaria and in public health. We got feedback from them.
{{< /card2 >}}

>Did you and Gabriel work together handing out devices and making the test samples?

{{< expand "Show answer">}}
There were other students involved in this project. I lead the hardware development. There were other tasks such as programming or doing some mechanical designs involved. In this case, they are authors. In the paper related to the Gorgas Tracker, which was published in frontier, are Over, Jose and Armando mentioned. They were students that joined the team at the time. They were working with the RePhone. They had some previous knowledge for doing that.
{{< /expand >}}

{{< card2 "Project process">}} 


After we decided which device or platform to use, we knew that we needed to get some user requirements in this case. We were working mostly with the researcher from the public health or the biological side.

We decided to use some design thinking workflow to get some iterations after one cycle to have something at the beginning, that could be helpful and then try to improve this device. 

We got at least five versions of this device.

Additional, we looked for other projects that could  use the devices.
{{< /card2 >}}

>How  was the overall process organized on a technical level and project level? 

{{< expand "Show answer">}}
After we decided which device or platform to use, we knew that we needed to get some user requirements in this case. We were working mostly with the researcher from the public health or the biological side. Most of the feedback and requirements came from them. We couldn't ask patients because we were working in Lima and the patients were in the Amazon. We didn't have enough money for doing travels to the Amazon, because there are no other ways than taking the plane. Maybe you can take a boat, but it's not common to go there. All the feedback that was from researchers of the research group that was studying malaria. We decided to use some design thinking workflow to get some iterations after one cycle to have something at the beginning, that could be helpful and then try to improve this device. 

That's why we shared the several designs of all the different versions of the device in the paper. At the beginning, we got a small device and we realized that we needed something bigger, because we needed a bigger battery. The patients needed to charge as less as possible. They didn't have electricity all the time. In the Amazon, they have electricity during some hours. The electricity in general was a challenge for this project. We tried  to improve the code to have a sleep mode of the device, while there weren‘t using it or traveling. In general, these design thinking allowed us to get different versions of this device and something that could meet the user requirement, at least for researchers. 
Because we didn't involve patients and we couldn't travel to the Amazon to test the devices, we didn’t learn other things to include or improve. Again, the weather was challenging  because of the humidity and temperature. We tried to add some other accessories to avoid the humidity. Further, we decided to include some cooling or ventilation.

We got at least five versions of this device. For example, we wanted to make a device where the case could be 3d printable. We found that could be easy to replicate and try to use at least some screws and nuts for this hardware for easy assembling.
{{< /expand >}}

{{< card2 "Major issues">}} 
Because we didn't involve patients and we couldn't travel to the Amazon to test the devices, we didn’t learn other things to include or improve.

The electricity in general was a challenge for this project.
Again, the weather was challenging  because of the humidity and temperature.

Customs are always a challenge because you have to prove that these devices are not weapons and met requirements of the Ministry of Telecommunication.


Another bottleneck was the 3d printers that we had available. We had only two 3d printers, that were part of our department.

It's not simple because  you ask people to track their movements. It's difficult in terms of privacy.
{{< /card2 >}}

>Did you come across any major bottlenecks and how did you resolve them? 

{{< expand "Show answer">}}
Because of my network, in this case the open hardware community,  it was easy to contact the Seeed Studio people. They helped me to get several kits of this RePhone. We got a discount for doing this research, because they were interested to see if this device or their platform would be useful for other applications. 

They were interested if we could do something that is relevant for public health. That could be like an encased use that they could share with the community about this platform. For the platform of the RePhone it wasn’t a big deal, maybe just to ensure good shipping. Customs are always a challenge because you have to prove that these devices are not weapons and met requirements of the Ministry of Telecommunication. That was difficult, because  in Peru the Ministry of Telecommunications and Transportation regulate devices. If you have these kind of mobile phones, they have to pass all these processes of bureaucracy. Doing that for a young researcher could be worse because you need contacts, money and sometimes a lawyer. We had to say to the customs that these devices were similar to Arduinos. We proved that was more for prototyping purposes than using as a mobile devices or mobile phones. That's why we got these kits and we didn't have any problems. A challenge was to get several rechargeable batteries, in this case the LiPo batteries. We didn't know which supplier was good for this project. At the beginning, we tried to import the kit from China, it was not easy.
{{< /expand >}}

{{< card2 "Local production">}} 
It was difficult on one side to get the batteries and find suppliers and on the other side the functionality, some didn‘t work well. 

We had to say to the customs that these devices were similar to Arduinos. We proved that was more for prototyping purposes than using as a mobile devices or mobile phones.

{{< /card2 >}}

>How many devices did you make?

{{< expand "Show answer">}}
We did like 30 or more, I don‘t remember. We had to buy more than 30 batteries, because we didn't know if they work or have problems in the field and because the researchers should have some batteries to change. Overall, the battery was a problem. It was difficult on one side to get the batteries and find suppliers and on the other side the functionality, some didn‘t work well. 

Another bottleneck was the 3d printers that we had available. We had only two 3d printers, that were part of our department. Actually those 3d printers were mine. I built these 3d printers and we used them to fabricate all the pieces and the cases for the wearable device. To use 3d printers, in this case the FDM technology, is slow for some applications. In this case we tried to do several cases in a short time. The time was other other constraint. Within a short time we needed to get several 3d printed pieces to build all the pieces and to send them to the Peruvian Amazon.
{{< /expand >}}

## The Hardware


>What are the hardware products that you have developed?

{{< expand "Show answer">}}
RePhone is a GPS tracker with the main function to gather  data. The device records the data and is connected to the satellite and gets the latitude. You can program through a user interface how this device records data and what it means. We wanted to know if the patients go outside of the community. We could define by using this interface and a radius of interest and relate this case to the community. After we got the position of the community, we could tell the device the radius. The device can detect when the patients goes outside the community and moves to another different part. 
Then we could program the time we want to record data. We have the active mode and the sleep mode. For example, we can record from 8am to 7pm. Afterwards, the device turns to the sleep mode to save energy and then the recording starts again at the next day at the same hour.
{{< /expand >}}

{{< card2 "Academic outputs">}} 
We published the paper in frontiers. We choose frontiers, because it's open access.
We share on the GitHub repository almost all the information related to that project.

It's not all about research and publishing a paper. The idea is to help with this data, for example, the Ministry of Health or another initiative that could help to control malaria in the Peruvian Amazon.

{{< /card2 >}}


>How would you rate the maturity of the product, in terms of prototype, demonstrator or market ready?

{{< expand "Show answer">}}
I read your paper related to maturity level. In terms of the general functionalities, I think we met the user requirements. However, in terms of documentation and general licenses, I think we still need more work. I don't know which level of maturity it would be. At least, we got a functional prototype. We published this paper in frontiers. There is another one with the same data, we got from this device, that was published in another paper this year. In terms of the quality of data we are accurate, at least for this kind of study. We compared it with some previous studies. I can say that we got a functional device, which could be used for other studies. However, there is still more work needed in terms of design. At least if you want to use it again for doing something in the Peruvian Amazon. If you want to do something in the Andes or near the Coast, I think you won't have any problems. Because I think the weather was our main problem and other things related to the supply chain, because of the geography. 
{{< /expand >}}

## Research Outputs

{{< card2 "Publication strategy">}} 
At the beginning we wanted to have the device, that could be useful for doing these kinds of research.

We knew that we needed a paper. With that we wanted to prove to the research community that it's possible to use these kinds of devices, develop your own device and to use it for these projects.
{{< /card2 >}}

>What were the envisaged outputs of the hardware development in terms of publications, hardware prototypes, documentation, learning and processes?

{{< expand "Show answer">}}
At the beginning we wanted to have the device, that could be useful for doing these kinds of research. In this research group, they were studying Malaria. To be open source was not relevant. After they knew about this project and the possibility to use open source principles, they understood that using these kinds of approaches could be useful in general for the field. The main outcome was to have a wearable device that could be a useful for studying human mobilization. The other thing is to publish the paper. As part of almost any research in academia, these results should be in a paper. We knew that we needed a paper. With that we wanted to prove to the research community that it's possible to use these kinds of devices, develop your own device and to use it for these projects. It could be useful for other projects. Despite the paper was a requirement or maybe one of the outcome as part of this funding, we knew publishing a paper demonstrates that it's possible to get good data with open hardware. This could be useful to prove other researchers and try to encourage other researchers to use these kinds of practices.

The idea was to see if this device with these functionalities could be used in other ways. One idea was to use this device, for example, in boats from  these communities. We could record data about how traffic is throughout the rivers. We couldn't do that because of money, but we started to focus on other topics. This was one idea and we hope to do that in the future. Maybe people could use these devices to record this  data from boats, which is another way of using public transportation in the Amazon. Those were the main outcomes to publish. How was the relationship between human mobilizations and malaria transmission and to share an open source device that could be used for similar studies and other applications. Additional, we looked for other projects that could  use the devices.
{{< /expand >}}

>What kind of information did you publish and how did you publish it?

{{< expand "Show answer">}}
We published the paper in frontiers. We choose frontiers, because it's open access. As part of this paper, we share  why we choose this platform, how we developed it and what we try to translate from user needs to functionalities. As part of supplementary material, we share some fields about the different versions and some picture of the user interface. We share on the GitHub repository almost all the information related to that project. There we have the 3d printed files and a picture from the different versions. We got actually five versions of six versions of this device. We designed one that could be 3d printed without supports. There were other things, that I didn't mention, about some other considerations within fabrication, that could be useful for anyone if they wanted to reproduce this device.
{{< /expand >}}

{{< card2 "Successes and failures">}} 
If successful means to get the outcome, to get data and to study what we wanted to study, I think it was successful.

 I think, the devices could have worked better if we could include other requirements related to the environment.
 
 it's difficult to recycle electronics in general in Amazon. You could try to include sustainability as part of requirements
 
 The outcome of this project is that we saw a relationship between the human mobilization and the malaria transmission. We demonstrate with the data, that we got from this study.
{{< /card2 >}}

>What do you think was successful about the project and what was not?

{{< expand "Show answer">}}
If successful means to get the outcome, to get data and to study what we wanted to study, I think it was successful, at least for the project. However, if we go to project management, it might not be successful, because it might take more time and money. In terms of resources, maybe it wasn't successful. In terms of outcome, we got the data we wanted, at least for the number of patients that were part of the study. I think, the devices could have worked better if we could include other requirements related to the environment. There are other lessons learned regarding sustainability. I think that's not successful. We realized, it's difficult to recycle electronics in general in Amazon. You could try to include sustainability as part of requirements, but you need some other a programs in the communities that can manage the thrash or components from these devices. After the project we took all the devices back to the city. We didn't leave anything there. If you would give these devices to the people, that's something you should think about. How is the sustainability of this project around these devices? I think it's relevant for these communities. Otherwise, you would get a negative impact there. You could help and at the same time you leave something. These communities first need to implement a management of resources.
{{< /expand >}}

{{< card2 "Hardware importance">}} 
We wanted to understand and connect the data that we got from these devices, to the malaria test, which we did to verify if they got this disease or not in this period of time. We needed this kind of data to see if there was any correlation.

{{< /card2 >}}

>How was the communication with the communities?

{{< expand "Show answer">}}
I wasn't part of the research that was in the field.  Gabrielle knows more about that and the relationship between the devices and people in general. It's not simple because  you ask people to track their movements. It's difficult in terms of privacy. However, when you contact these communities, you have to first talk with the head of the community. Some people that they consider as reference or someone that they can trust.

Afterwards, you explain the study. That's how all these processes starts. You have several meetings with the participants. They have to sign a consent form for participating in this project. It's not all about research and publishing a paper. The idea is to help with this data, for example, the Ministry of Health or another initiative that could help to control malaria in the Peruvian Amazon. They have vaccinations programs, where they go directly to the community and vaccinate people. But they don't realize that the people move. If you vaccinate maybe a specific number and a specific time, maybe some of the members of this community are in other parts of the Amazon and could come with a malaria to their community again. Or if they decided to start this vaccination program in different parts of the Amazon, the Ministry of Health doesn't know if controlling only vaccinated people in the communities is enough. They should try further strategies and maybe other sites to control malaria. In general, with this data you could develop these policies.
{{< /expand >}}

>Has the hardware been built, produced or modified by others outside of your project?

{{< expand "Show answer">}}
I've seen citations from the paper and I've seen one fork. But we don't know if someone else has produced it. At least in the citations they mentioned our project because of the strategy of using open hardware or accessible devices for studying human mobilization.  I haven't seen another research group that has reproduced our device or did similar studies. We haven't seen any publication where the others show the device for the same or other applications.
{{< /expand >}}

>Why did you choose GitHub for project documentation and sharing?
Did you find some barriers ? 

{{< expand "Show answer">}}
We decided to use GitHub mainly because I have used it before for other projects. It's easier to share information and to try to create this brief documentation about the hardware.  It's one of the most known repositories in general.
{{< /expand >}}

>Did you find some limitations when sharing your files?

{{< expand "Show answer">}}
We wanted people to see the STL files before they download the files and I don't know if it was available at that time. I don't remember to be honest. We were worried about visualizing STL files on GitHub. That's something we wanted to do as part of documentation. That's why we shared some pictures. If you see the repository, there are some pictures of the device and the different versions.
{{< /expand >}}

## Participants


>What made you work on this project?

{{< expand "Show answer">}}
I was in charge of the whole process of 3d modeling and 3d printing. That was my main role. We used an end user platform, the RePhone, we only had to design the buttons that we use in this device because there didn't exist any physical interface, but this was developed for others together by one of the students that was part of the project. My main role was to the design and development with other students all 3d printed pieces and advise the electronics. The students were the developers.
{{< /expand >}}

>Did you base everything on the RePhone kit, which is an existing technology?

{{< expand "Show answer">}}
Yes,  we use the geo kit for the device. The GPS tracker is based on the geo kit of RePhone.
{{< /expand >}}

>How many people have contributed overall to the project? 

{{< expand "Show answer">}}
We were four in developing and there were 4 others who were authors of the article that we published frontiers. There were two other people, Gabriella and Edgar Manrique. They are biologists and work on malaria and in public health. We got feedback from them.
{{< /expand >}}

>What are the backgrounds of the participating people?

{{< expand "Show answer">}}
Gabriel was an associate researcher. He had a master's degree and now he's doing his PhD. Edgar had finished his undergrad studies. He was a technician and research assistant. There was another supervisor, Dr.Aleksandra Janos. He was a researcher in this group and he helped us to get some feedback.
{{< /expand >}}

>How did you find these project members, who had complementary competencies?

{{< expand "Show answer">}}
The people from the institute knew more about the environment, because they went to the Amazon for various projects.  They knew about the different challenges the hardware could face. They recommended the strategy for designing the code with active and sleep mode. They knew more about this behavior than us. Their feedback was useful and relevant for developing the user interface. We had to develop  this software and give them something that could be relevant and useful for doing the field research. We wanted to make it understandable for other researchers in this field, too. At least they could use these kinds of interfaces to get the feedback and hopefully their experience was useful. 
{{< /expand >}}

{{< card2 "Work Coordination">}} 
For documentation we use the Google Suite to share any documents. We used emails and WhatsApp to communicate between us. In current projects I mainly use slack.
{{< /card2 >}}

>How did you coordinate the work inside the team?

{{< expand "Show answer">}}
We use some platforms to  communicate between members. For documentation we use the Google Suite to share any documents or to create any new document. We used emails and WhatsApp to communicate between us. In current projects I mainly use slack.
{{< /expand >}}


>How much funding did you get?

{{< expand "Show answer">}}
To be honest, I can’t say an amount. We could pay part time for three students. With the funding we bought the components, filaments and other mechanical components. For manufacturing we didn't pay anything because they were my 3d printers. 
I was involved more because I was interested to see at least one example of doing an open source device. I would say that my payment was this motivation, the results and the paper. That's the way how I get a payment. The money was mainly for funding this part time position for the students and materials. I would say overall it was  between  \$6,000 and \$7,000. We estimated the costs for each device between 15 and 30 dollars.
{{< /expand >}}

{{< card2 "Personal gain">}} 
Students  learned a lot from this process in terms of designing, how to apply and trying to translate a requirement  to the functional prototype.
They benefit from this paper.

The main benefit for me was learning about hardware development and to use different approaches, like design thinking.

Because of the project Health Innovation Lab was started. 
Gabriel had the opportunity to start this research group at the institute.
{{< /card2 >}}

>How did the members benefit from their work in the project?

{{< expand "Show answer">}}
The students applied knowledge that they got from their undergrad studies. They apply it to a real problem. In research in Peru, it's not common to have an application of knowledge. They learned a lot from this process in terms of designing, how to apply and trying to translate a requirement  to the functional prototype. They learned about malaria and they understand the relevance in terms of public health. They benefit from this paper. If they wanted to continue their studies, while applying for a master or a PhD program, it’s good to have a publication.
For Gabriel, Edgar, me and the other authors it was good to know how are these processes for hardware development in Peru. Most of the projects import a commercial hardware for research. In my case it was my first time doing a project. 
The main benefit for me was learning about hardware development and to use different approaches, like design thinking. Maybe design thinking has limitations and you could use other approaches or you have to iterate. It makes sense to use design thinking because it's flexible to work with for these applications. 

Because of the project Health Innovation Lab was started. Gabrielle and I decided to work and start this research group at the institute, because we wanted to use open source principles or approaches for research. The other benefit was to demonstrate it's possible to use open source principles in research and that we could do more things using these principles. Gabriel had the opportunity to start this research group at the institute. Now Health Innovation Lab uses some open access and open source principles, mostly in data science. 

We  hope to start some other hardware projects using the same approach that we used for the Gorgas Tracker project. 
Other benefits were the paper, the data for doing research and to know more about the hardware development.
{{< /expand >}}


>Can you explain  the outcome  of the study?

{{< expand "Show answer">}}
The outcome of this project is that we saw a relationship between the human mobilization and the malaria transmission. We demonstrate with the data, that we got from this study, that people can get infected  in a specific period of time and the infection probability and the level of exposure increases while they were moving from one point to another. Therefore, vaccination programs should try to develop  different strategies to control malaria.
{{< /expand >}}