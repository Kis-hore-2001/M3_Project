# Abstract
### In automobiles, particularly cars, autos and heavy vehicles, there are wipers.
### Wipers are used to clean the windshield of the cars to operate these wipers, motors are used. these motors are designed to operate in 90 degrees or 150 degrees, depending on the use.
### This is so because Qemu supports only those things.
### We use single press and long press to denote ON/OFF and frequencies to denote varoius wiper operations.
### I have not used 180 degrees here, because no wiper in real time rotates 180 degrees.
### As STM32IDE is used, along with Qemu, we will show this operation using only 4 LEDs and a switch.
# Introduction
### This project is all about designing a wiper control system for cars.
### We denote intensity of rain by the frequency in which the lights alternate between the four colours.
### The switch indicates ON/OFF
### We use STM32cube IDE and Qemu for emulating the operation.
### As qemu supports only 4 LEDs and a Switch, we make use of LEDs to notify the operations.
# SOFTWARE REQUIREMENTS
### STM32 CUBE IDE
# COMPONENTS
### STM32F4O7VG MICROCONTROLLER BOARD
# DESCRIPTION
### STM32F407VG
### The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.
# FEATURES OF STM32F407VG MICROCONTROLLER
### In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
### On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
### USB ST-LINK with three separate interfaces and re-enumeration capability.
### Virtual Com port Debug port (with new order code only).
### Large-scale storage (with new order code only).
### Board power is supplied through USB or an external 5 V supply source.
### 3 V and 5 V external application power supply.
# WORKING PRINCIPLE
### Assume that the automobile is the microcontroller. If the button is hit, the first led (red) will turn on, Clicking again  the wiper will start, and the second led (blue) will turn on for a desired rate. If the button is pressed again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.
# 4W's and 1H
# QUESTION EXPLANATION
### What? It is a wiper control system that is used to operate the wipers.
### Who? This system can be used by anyone operating a vehicle using the wiper system.
### When? This system can be used when the weather conditions prevent clear view of anything in front of the vehicle when driving.
### Where? It can be used anywhere like roads in cities, deserts, etc.
### How? First the switch is pressed to operate the wiper. Then the switch positions are changes to vary the wiper speeds.
# HIGH LEVEL REQUIREMENTS
## ID Description status
### HLR01 vehicle switched ON Implemented
### HLR02 Wiper switched ON Implemented
### HLR03 Wiper switched OFF Implemented
### HLR04 Car turned OFF Implemented

