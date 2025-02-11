---
layout: post
title:  "Soly Clean Solar"
date:   2024-04-24 
categories: Projects
---
# Sol'y Clean Solar
A self cleaning solar panel system

### Context: Solar panels get dirty
Soiling is the Process of dirt accumulating on panels and decreasing power. This can cause a 3-4% power drop, costing solar farms $5.5 billion dollars annually. The solution to this is cleaning solar panels, but this takes a lot of water. It takes 300,000 gallons per acre per year to clean a solar farm.

### Objective: make a self cleaning solar panel
<img src="/assets/images/SolyCleanSolar/systemDiagram.png"/>


## My Contributions: Electrical and Firmware
We wanted an IOT data monitoring system for the solar panel to track energy output and initiate cleaning when efficiency drops. I built one based on Open Green Energy's [Solar Panel Monitoring System V2][inspo-link]. 
The System tracks voltage, current, and temperature, and uploads it to a BLYNK web interface

<img src="/assets/images/SolyCleanSolar/breadbord.png"/>

<img src="/assets/images/SolyCleanSolar/fullBreadboard.png"/>

<img src="/assets/images/SolyCleanSolar/IMG_5353.jpeg"/>

I also designed the electrical system and wrote the firmware for controlling the pannel movement, so that the pannel could track the sun. This involved a lot of high power electronics, which was new for me. To control the linear actuators I used relays in an H-Bridge, and to control the central dc motor I used another relay plus a DC Motor Speed Controller Switch.
<img src="/assets/images/SolyCleanSolar/Full Solar_system 2_bb.png"/>
<img src="/assets/images/SolyCleanSolar/motorController.jpg"/>
<img src="/assets/images/SolyCleanSolar/LinActControl.png"/>

Evidently I did not get any good pictures of the whole system, but here is what it kinda looked like:

<img src="/assets/images/SolyCleanSolar/IMG_5584.jpeg"/>
