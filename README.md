# Custom STM32-Based Electronic Speed Controller (ESC)

A comprehensive design and implementation of a Custom Electronic Speed Controller (ESC) powered by an STM32 microcontroller. This repository contains the complete project files, including the STM32CubeIDE firmware, Altium Designer schematics and PCB layouts, as well as the Gerber production files.

## System Block Diagram
Overview of the ESC architecture, power staging, and hardware components.
![System Block Diagram](images/Diagram%20Block%20ESC.jpg)

## Microcontroller Configuration (STM32CubeIDE)
Pinout mapping, clock configuration, and peripheral initialization for the STM32 microcontroller.
![STM32 Configuration](images/stm32%20configuration.png)

## 3D PCB Design (Altium Designer)
Component placement and 3D layout visualization for both top and bottom layers.
![3D PCB Top View](images/top%20pcb%203d.png)
![3D PCB Bottom View](images/bottom%203d%20pcb.png)

## Bare PCB Fabrication
Manufactured Printed Circuit Boards (PCBs) prior to component assembly.
![Bare PCB Top](images/top%20pcb.jpg)
![Bare PCB Bottom](images/bottom%20pcb.jpg)

## Physical Assembly (PCBA)
Fully assembled and soldered Printed Circuit Board Assembly (PCBA).
![PCBA Top](images/assembly%20pcb%20top.jpg)
![PCBA Bottom](images/assembly%20pcb%20bottom.jpg)

## Commutation Signal Testing (Oscilloscope)
Hardware verification of the 3-phase (A, B, C) output waveforms required for driving a Brushless DC (BLDC) motor.
![Oscilloscope Commutation Signals](images/FASA%20ABC%20100%25%20FGND%20500us.PNG)

## System Integration & Testing
Comprehensive system testing integrating the custom ESC, BLDC motor, receiver, and radio controller.
![System Integration](images/total%20sistem.jpg)

## Video Demonstration
Watch the full presentation and functional demonstration of this Sensorless ESC (Back EMF with 6-step commutation) on YouTube:

[![ESC Project Demonstration](https://img.youtube.com/vi/WF_Htxp4qzU/maxresdefault.jpg)](https://youtu.be/WF_Htxp4qzU)