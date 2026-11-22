# Project Overview

I made a lighting control system using **KiCad** and **Fusion 360**.

## How to Open the Project

To open this project:
1. Download or clone this repository.
2. Install [KiCad](https://www.kicad.org/).
3. Open the `.kicad_pro` project file.
4. Explore the schematic and PCB layout.
5. Make modifications or improve the design.

## How Does It Work?

The system can receive electrical power from different sources:
- **Outlet:** The main power source.
- **Solar panel:** Provides power using sunlight.
- **Wind generator:** Can also be connected as an alternative renewable energy source.

Once powered, the system uses a **photoresistor** to detect the surrounding light level.
An **ATtiny microcontroller** processes the sensor readings and controls a relay, which automatically switches the light ON or OFF.
After designing and developing the electronic circuit, I designed the PCB using **KiCad**. Once the PCB design was completed, I moved on to creating a custom enclosure using **Fusion 360**.

## Tools I used

- **KiCad:** Schematic and PCB design.
- **Fusion 360:** 3D designing.
