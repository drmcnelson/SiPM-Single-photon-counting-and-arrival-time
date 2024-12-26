# SiPM-Single-photon-counting-and-arrival-time

This is a design for a silicon photo-multiplier sensor and amplifier with time to digital converter (TDC) system with 25 picosecond resolution.  Bill of materials costs are currently under $40 for each of the sensor, and the amplifier and time to digital converter.   We are asking for contributors and sponsors to move the project forward.

Measuring and recording arrival times and counts for single photons, is a cornerstone capability for studying fluorescent lifetimes and also a wide range of quantum phenomenon.
Normally these experiments can only be done in well funded well equipped laboratories.
In our case, we have decades of experience in designing fast measurements of this type, which we want to contribute to making this capability more widely available.
And as we mentioned, the cost in parts to do this is very much in the range that almost any researcher might afford out of pocket. 

Gerbers, schematics and a bill of materials for two boards, reflecting our current design have been uploaded.
The first is the sensor board hosting a silocon photomultiplier (SiPM)  with space for a thermoelectric cooler.
The second is the amplifier and time to digitial converter.
Note that these are designs only and have not yet been built and tested.

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

If you would like a preassembled board, please consider sponsoring (click the button at the top of the page) and please contact me so that I can get the current cost of materials.
