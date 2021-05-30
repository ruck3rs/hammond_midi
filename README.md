# tonewheel_midi_master

## Introduction

A MIDI tonewheel organ project using setBfree on a RPI, Arduino boards and a Fatar Keyboard TP8O. Hardware (PCBs) and software will be shared here.

The goal of the project is to design a low-cost tonewheel organ MIDI controller. Some commercial alternative exist but they are quite expensive.
I wanted to buy a Fatar Keyboard TP8O (which is what is used for example on Nord Stage NS3), to create all electronics needed to convert its inputs to MIDI and to use a Rapsberry PI B4 to generate the sound. Arduino cards (One Due and 2 micropro 3.3V) are also used on the project.
Another interesting aspect of the project is that the design will be usable as a MIDI master keyboard: it has lots of inputs (potentiometers, buttons, ..) and will even feature a 4x4 button pad (from Sparkfun) usable as a drum pad.

![image](https://user-images.githubusercontent.com/67337957/120108813-0b481e00-c167-11eb-970a-776aaab56b44.png)

The case of the keyboard will be made using 3D printed PLA (for the façade) and wood for the structure.

## Price Estimate

> Just to give a general idea if anyone else want to build something similar

- Fatar TP-8O keyboard (61 keys): 180€ (Doepfer)
- Small electronics (potentiometers, buttons, Arduino cards..): 120€ (Aliexpress)
- 4x4 Sparkfun button pad: 15€
- Raspberry PI 4B 8GB + LCD display: 100€ (Kubii + Aliexpress)
- PCB ordering: 30€ (JLCPCB)

## Current state

Currently most of the hardware was ordered but the keyboard TP8O is yet to be received. The PCBs are almost done (final checks).
The set-up on the RPI (Jack + setBfree) is already working correctly.
Most of the work remaining will be assembling the PCBs, coding the 3 Arduino boards, and designing the 3D façade.
