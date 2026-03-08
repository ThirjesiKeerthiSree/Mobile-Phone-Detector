# RF Mobile Phone Detector

## Overview
The RF Mobile Phone Detector is an analog electronic circuit designed to detect electromagnetic signals emitted by active mobile communication devices. The system senses radio frequency (RF) signals typically generated during phone calls, messaging, or data transmission and provides a visual alert when such signals are detected.

The circuit operates within the **800 MHz – 2.5 GHz frequency range**, corresponding to common mobile communication bands. Weak RF signals captured from the environment are amplified and used to trigger an indicator.

## Objective
- Detect electromagnetic emissions from nearby mobile phones.
- Develop a compact and cost-effective RF detection circuit.
- Demonstrate practical RF signal sensing using analog electronic components.

## Working Principle
The circuit captures RF signals emitted by mobile devices using a sensing network connected to a **CA3130 operational amplifier**. The op-amp amplifies weak RF signals present in the surrounding environment.

When the amplified signal exceeds a threshold level, a **BC548 transistor** acts as a switching device and activates an **LED indicator**, providing a visual alert that mobile phone activity has been detected.

## Components Used
- CA3130 Operational Amplifier  
- BC548 Transistor  
- Resistors (100 kΩ, 2.2 MΩ, 1 kΩ)  
- Capacitors (47 pF, 0.22 µF, 100 µF)  
- LED Indicator  
- 9V Battery  
- Breadboard / PCB  


## Applications
- Exam halls for detecting unauthorized phone usage  
- Security-sensitive environments  
- Hospitals and ICUs where RF interference must be minimized  
- Corporate meeting rooms and confidential areas  

## Future Improvements
- Increase detection range using improved antenna structures  
- Integrate audio or buzzer alerts for enhanced indication  
- Implement digital signal processing for more precise RF detection  
