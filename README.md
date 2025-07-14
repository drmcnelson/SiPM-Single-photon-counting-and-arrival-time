# SiPM-Single-photon-counting-and-arrival-time

This is a design for a photon counting and tagging device with 25 picosecond resolution, comprisong a cooled silicon photo-multiplier (SiPM), a amplifier and time to digital converter (TDC) board with an SPI interface, and a system controller based on a Teensy 4.x.  Bill of materials costs are currently under $40 for each of the sensor, and the amplifier and time to digital converter.   We are asking for contributors and sponsors to move the project forward.

Measuring and recording arrival times and counts for single photons, is a cornerstone capability for studying fluorescent lifetimes and a wide range of quantum phenomenon.
Normally these experiments can only be done in well funded well equipped laboratories.
The design here brings this capability within in the range that almost any researcher might afford out of pocket. 
This repo hosts Gerbers, schematics and a bill of materials for the SiPM board and the amplifer and TDC board.
Note that we have not yet been built and tested these.

<img src="https://github.com/user-attachments/assets/c80aea53-cabe-48d9-a1c9-c742df434c67" height=400>

<img src="https://github.com/user-attachments/assets/7d67d5c5-aa69-479b-b640-69460ece610e" height=400>

The system will be operatied by either of our [Teensy 4.0 based controller](https://github.com/drmcnelson/SPI-Instrumentation-Controller-T4.0) 
our [Teensy 4.1 based controller](https://github.com/drmcnelson/SPI-Instrumentation-Controller-T4.1).
These are preferred over the UNO R4 because the T4 provides faster transfers between both the TDC and controller and between the controller and host computer and because it has the faster more capable M7 cross-over processor.
The T4.1 can host 16MB of local RAM.
The controllers have standardized interfaces for signals and power for all of the boards in our SPI instrumentation project.

## Availability and Sponsorhip
This repo and its contents are provided without warranty or representation of suitability for any purpose whatsoever.

Additionally, please note these are designs only.  First build and testing is pending contributions and sponsorship.  

The intent is to support access to doing good science for those who are not as well funded as others.  Commercial use is subject to review and approval, per this criterion.

If you would like a preassembled board, please consider sponsoring (click the button at the top of the page) and please contact me for current costs of materials etc.
