---
title: Three months in Delft, two open hardware projects
author: Package Build
date: '2023-07-28'
slug: three-months-in-delft-two-open-hardware-projects
categories:
  - progress report
tags:
  - personal story
---

# Project description: Microstimulation setup
*by Mik Schutte; Copyright to the authors, distributed under a CC-BY 4.0 licence.*

**Sections**
* The project
* The hardware
* The research outputs
* The participants

# The Microstimulation setup in a nutshell
The Microstimulation setup allows for the injection of an electrode, the delivery of an electrical current into a rodent brain, the recording of the cortical response to that stimulus, as well as the monitoring of behaviour (licking, whisking & pupil dilation). 

Core development was made during 2022 by Mik Schutte at the Humboldt University of Berlin.

![](https://i.imgur.com/dlNRHpT.png)
:::info
*Image of the setup, paradigm and behavioural detection, by Mik Schutte.*
* Main project website: https://github.com/open-make/mik-delft-microstim
* Project start: 2022
* Core development team size: 2

## Hardware products
The Microstimulation setup is a customisable, open-source experimental setup that can be used for neuroscientific experiments. It uses a micromanipulator, thungsten electrode, stimulus isolator, piezo-sensor, two high-speed cameras and a BPOD.

## Hardware maturity
The setup is roughly 80% of the intended product. With regards to performance the setup is ready for use. We are adapting the BPOD protocol for online visualisation of results and implementing neurophysiological recordings with multiple-channel probes.

## Rebuilds 
So far the Microstimulation setup has been used and built in Berlin. We hope that adoptation increases.
::: 

# The Project
The Microstimulation setup is envolved in a project that investigates the principles of systems memory consolidation in a microstimulation detection task. With this paradigm we have previously shown that the formation and consolidation of memory engrams in the neocortex depends on input from the medial temporal lobe [(Doron et al., 2020](https://www.science.org/doi/10.1126/science.aaz3136); [Shin et al., 2021)](https://www.science.org/doi/10.1126/science.abk1859). However, the setup can be utilized in a plethora of paradigms. The open-microstimulation project allows for a smoother adaptation of the method, limits time spend re-inventing the wheel and maximizes reproducability of scientific findings.

## Project start
In November 2021 I started my master project that would use the microstimulation detection paradigm. However, the setup was no longer availible in the lab. Thus, I set out to re-establish the microstimulation setup with my only source of information being an incomplete wiring diagram. Luckily, with the help of colleagues, I was able to get the basics of the setup to work: stimulate an electrode and detect licks. Next, I implemented the behavioural aquisition, meaning that I set up a camera that were able to clearly capture individual whisker movement and a camera that clearly captured the pupil. 

During this time Julien Colomb from the Open.Make team asked me if I wanted to make the setup open source. This would entail that I had to properly document the hardware, describe the protocol, re-write analysis software and get away from large pay-walls. As I already was keeping track of the hardware and writing analysis I gladly agreed which led to the creation of the Microstimulation setup as described here.

## Proccess
Initially, we seperated the setup into three distinct compartments: animal, electrical and behavioural. Together, they allow the research of animal behaviour in response to electrical microstimulation. 
* The animal compartment they allows for the restrainment of the animal and the correctly timed distribution of a water reward.
* The electrical compartment is used to generate an electrical stimulation that's emitted through the electrode.
* The behavioural compartment allows for the recording of animal behaviour such as pupil dilation and whisker movement.

Each comparment encompasses multiple components (i.e. piezo-sensor, micromanipulator or camera), and their function in the setup can be fairly complex. Therefore, we created clear definitions for each component. This way anyone from any background should be able to understand what is happening within each compartement. 

## Current state
As of April 2023 we are modifying the microstimulation detection paradigm to lower stimulation amplitudes. This entails that we are running control experiments to determine the validity of the paradigm. Additionally, we are updating video-data aquisition software to allow for the continuous capture but limited saving of frames. Moreover, Jelte de Vries is pioneering the use of [NeuroNexus Michigan probes for stimulation](https://www.neuronexus.com/products/xdaq-core/). 

## Major issues
Most of our previous problems have been because of ordering. We have had trouble getting the right components to the right location in a decent amount of time. This is internally being worked on. Additionally, there are some paywalls such as with the initial laboratory interface (Cabbridge Electronics Design) and the software for the new one BPOD (Matlab). We will look for an opportunity to transfer BPOD to py-BPOD, making it Python-based.

## Decision making
Decisions are made to maximize the efficiency of the microstimulation detection task from a neuorobiological point of view. This means that we aim to achieve a safe and functional learning paradigm, allowing the mice to learn rapidly. Also, we take into account the costs, ease-of-use and and ease-of-access of our components and associated (software) packages. These secondary considerations are mainly incorporated through using open-scource hard- and software such as: BPOD, 3D-printed components, python-based analysis and optionality within the setup. 


# The Hardware
Components are mainly 'standard' scientific setup materials like the optical breadboard, metal rods, connector-pieces and cables. There are several pre-build aquisition hardware like our open source laboratory interface: BPOD and the custom made MultiTool (Humboldt University). Additionally, there is the Electrical stimulating part and the camera part.

You can find all the specifics on our project's [GitHub page](https://github.com/open-make/mik-delft-microstim). 
## Hardware importance
The main goal was to make the setup modular, allowing for flexible adoptation and to change the laboratory interface from [SPIKE2](https://ced.co.uk/products/spike2) to [BPOD](https://sanworks.io/shop/viewproduct?productID=1035). This aims to achieve a broad adaptation of our setup where different sub-experiments can be performed using the Microstimulation setup. 


## Laboratory interface
As stated, a big part of our project has been to transition our laboratory interface from CED and SPIKE2 to BPOD. The laboratory interface is used to coordinate the experiments in our case it determines what to do with licking input, when to give a microstimulation and when to start saving frames. BPOD is a finite state machine that operates through MatLab and has an active community of users. The community provides a nice platform for individual support. However, the use of BPOD has a small learning curve and coding your own paradigm can be difficult. Luckily there is a clear to understand [wiki page](https://sites.google.com/site/bpoddocumentation/home) that guides new users through the basics. 

We tried to opt for [pyBPOD](https://pybpod.readthedocs.io/projects/pybpod-api/en/v1.8.1/) to remove the paywall that is accompanied with the MatLab software. Yet, the pyBPOD software and community are not as well developed as the original version. This made it difficult for a beginning user to code their own paradigm and led to the choice of the original version.

## Developing parts
As a side project to the Microstimulation setup we have created the [SimpleScienceSetup](https://github.com/mik-schutte/SimpleScienceSetup). This open-source hardware project aims to create a starter kit for composing experimental setups. These can in turn be utilized for all kinds of purposes (e.g. education, prototyping, low-cost alternative). Components form this nicely compliment the Microstimulation setup as it provides rod connectors, camera-holders, rodent-holders and a DIY optical breadboard. 

# The Software
Like the hardware, the software can also be devided into distinct components. 
* The laboratory interface, BPOD software
* The software for video-aquisition
* Analysis code

All can be found on the [GitHub page for Microstimulation analysis](https://github.com/mik-schutte/Microstimulation). We have already created a notebook on how to perform analysis. We highly-reccomend checking it out for those with similar data.


# Research Outputs
Microstimulation is being used in the collaborative research projects of the [SFB](https://www.sfb1315.de/) (A04, A10) and Einstein. The technique has already resulted in two Science publications. [(Doron et al., 2020](https://www.science.org/doi/10.1126/science.aaz3136); [Shin et al., 2021)](https://www.science.org/doi/10.1126/science.abk1859). We strive to have work regarding these projects published around 2026.

We aim to publish the work outlined here in early 2024 which will include complete build instruction, easy-to-use order system, BPOD with commented file that describes, habituation strategy, surgical explaination, controls, software guide through.

# Successes and failures
**Success :**
Making the microstimulation project open source with regards to both soft- and hardware has already fascilitated information transfer between colleagues. For instance, the build-instructions have been utilized to re-build the setup at the lab in my absence. Additionally, information is currently helping a collaboration with [the Gilad lab](https://medicine.ekmd.huji.ac.il/en/research/arielgi/Pages/aboutTheLab.aspx) located in Jeruzalem. Finally, our analysis software and accompanying explaination has been used by students in the lab. 

**Fails :**
In the past we have had problems with the ordering of components. This led to long delays which, in turn, caused us to be less productive during a colaboration with the [Delft Open Hardware Academy](https://www.openhardware.academy/01_Welcome.html). We also have have lost some time while trying to develop the BPOD laboratory interface in Python. [PyBPOD](https://pybpod.readthedocs.io/projects/pybpod-api/en/v1.8.1/) is a suitable product, yet I would discourage it's use for new users.

# Participants
The core team members are Mik Schutte (myself) and Jelte de Vries. Both of us are employed by the Humboldt University and PhD-students in the Larkum lab and are being supervised by Dr. Robert Sachdev. Data-management and the supervision concerning open source is done by Dr. Julien Colomb. Lastly, we thank the Delft Open Hardware Academy for its many valuable lessons in designing, project management and hardware documentation.