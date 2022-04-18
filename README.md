# NYU OpenPLC Trojan Edition (TE)

This repository contains NYU's implementation of the OpenPLC hardware. 
Several important modifications are included, notably, a socket for a second
microcontroller (a Raspberry Pi Pico) which can act as a 'Hardware Trojan'.
Different Hardware Trojan capabilities can be enabled and disabled depending on the configuration of a number of jumpers located around the PCB.

There are a small number of known issues with the v0.1 board. 
These include the usage of a now-obsolete accelerometer, and poor component
choice for on-board power measurement circuitry.

These will be remedied for version 0.2 of this work.

This PCB was used in the paper,
"Detecting Hardware Trojans in PCBs Using Side Channel Loopbacks"
by Hammond Pearce, Virinchi Roy Surabhi, Prashanth Krishnamurthy,
Joshua Trujillo, Ramesh Karri, and Farshad Khorrami.
Published in IEEE TVLSI, 2022.

## Repository contents

`/final-outputs-v0.1` - this includes the schematic files, BOM CSVs, PDF layout files, and final production gerbers of the PCB manufactured for use in the paper.

`/kicad-files-v0.1` - this contains the KiCAD project used to make the project.

## New versions of the PCB

Newer versions (v0.2 and above) are currently under active development and will be released through this repository upon validation.
