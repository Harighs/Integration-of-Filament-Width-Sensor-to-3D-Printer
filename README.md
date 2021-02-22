# 3D Printer Firmware with Sensor Integration by Hari Shankar Govindasamy (Support of Marlin)
<img align="right" src="Documentation/Logo/Marlin%20Logo%20GitHub.png" />

For Merlin Additional documentation can be found in [our wiki](https://github.com/MarlinFirmware/Marlin/wiki/Main-Page).


## About
Marling is a base source code for opeating 3d printers from start to ending procedures which consist of:
- Controlling the motion mechanism
- Controlling the Temperatures of Nozzle by PID
- Controlling of Dual materials suppport printings
- Controlling of end mechanism and timing calculation

Now for the huge plan to integrate a custom sensor to exhance the capability of the printer to give good output 
we had chosen the variable feed by measuring the output for an FDM Printer.

## Credits and Thanks to
Montan University Leoben - Austria
Department of Additive Manufacturing and Polymer Technology

Developer Credits:
 - Hari Shankar Govindasamy - Developer (Myself)
 - Santiago Diego PHD from Montan University - Support for Materials science from Polymer department
 - Prof. Joamin (Habilitate from Montan University)

## DESCRIPTION
This project has the goal of printing every material regardless of varied diameter along with the printing.
"PERFECTLY USEFUL IF you're MAKING YOUR OWN FILAMENT OR RECYCLING YOUR OLD MATERIALS AND MAKING FILAMENT OUT OF IT"
we can equip the printer with a filament sensor. Each and every details will be updated for each version of printers and different motherboards.
I had outsourced the sensor so this project
will be only focusing on the printer, firmware, and electronics of printers.

Future Support is always available for this project, I will try to help you out if you contact me
Feautures:
- Has the goal of the extruding materials with a filament sensor

- All details of Electronics, Hardware, Software and Procedures are elaborated and futuring full support if needed for you

- We are able to use normal usual thermistor which your're using now with your printer 

Thank you...
- Printing is possible from 40 degree celcius to 450 degree celcius

- Usage of real time filament measuring sensor (can automatically vary the extrusion speed)

- We can able to print not only Polymers(Plastics like PLA, ABS) but also Metals (Steel,
    Copper, and also ceramics)

## Release Branch

The Release branch contains the latest tagged version of Marlin (currently 1.0.2-2 – October 2016). It also includes a version 1.0.1 (December 2014). Any version of Marlin before 1.0.1 (when we started tagging versions) can be collectively referred to as Marlin 1.0.0.

## Patches - 1.0.x Branch

Any patches developed for this family of releases will be found on the [1.0.x branch](https://github.com/MarlinFirmware/Marlin/tree/1.0.x) of this repository.

## This Repository is Not For Feature Development

Development of future versions of Marlin is ongoing. However, to keep issues separate, that effort takes place in a companion [Development Repository](https://github.com/MarlinFirmware/MarlinDev/). Please make all suggestions for future features in that project. Issues raised here should be restricted to errors in the tagged releases.

## Current Status: In Development

Marlin development is being accelerated to catch up with a long list of issues. Check the Issues and Pull Requests links on the right to to see what we are currently working on.

[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)
[![Travis Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg)](https://travis-ci.org/MarlinFirmware/Marlin)

##### [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin)


## License for Marlin

Marlin is published under the [GPL license](/COPYING.md) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
