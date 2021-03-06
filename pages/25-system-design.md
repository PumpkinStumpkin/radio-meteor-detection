---
layout: page
title: System Design
---

### Overview

1. 4-Element Yagi Antennae
2. Antennae tower
3. Low-noise amplifier
4. Radio Reciever
5. Processing program

#### 4 Element Yagi Antennae
1. Objective: receive radio waves at 55.24 MHz, TV Channel 2
2. Operating requirements: 
* outdoors
* pointed towards Channel 2 station source
* 1.5 wavelengths high, 9 meters tall, 27 feet
3. Materials
* aluminum tubs
* coaxial cable
4. Procedures to test: create a sample radio source, find broadcasting station on air and internet

#### Antennae Tower
1. Objective: raise antennae to heigth that minimizes interference and optimizes gain for Channel 2
2. Operating requirements: 
* outdoors
* wavelength and a half, or 27' tall
3. Materials
* PVC piping 10' 3/4", 18 lengths
* Guy wires
* 4 way PVC fittings
* 44 tee bar fittings

#### Low Noise Amplifier
1. Objective: amplify recieved signal with minimal noise
2. Operating requirements: 
* outdoors
* located next to antennae
3. Materials
* packaged LNA unit

#### Reciever
1. Objective: recieve radio signals
2. Operating requirements: 
* indoors
* capable of recieving 55 MHz
3. Materials
* Raspberry Pi
* Software Defined Radio 

#### Processing
1. Objective: analyze radio signals, detect possible meteors based on signal
2. Operating requirements: 
* Python program running on Raspberry pi

#### Antennae Rotator
1. Objective: change direction of antennae to point to radio wave source
2. Operating requirements: 
* outdoors
* accessible from base of antennae tower
3. Materials
* DC gear motor 12 v 2 rpm
* lazy susan bearing
* DPDT switch
* 12 v battery
