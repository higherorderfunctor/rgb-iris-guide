# RGB Iris Build Guide

## Disclaimer
My electronics knowledge is limited to soldering a Planck, Let's Split, and a few $10 soldering kits from Amazon.  My design comes from Googling, testing, and viewing examples over a period of a couple months.  I have no theoretical knowledge in electrical engineering.  I completely disregarded things like trace width of the power rails on the PCB.  That said, this guide is for informational purposes only.  If you attempt to reproduce any of my results, it is at your own risk.

## Parts and Tools
* https://goo.gl/Nj8QVM [Google Docs]

## Guide
### Bare PCB
Here is a photo of the bare PCBs before starting any work.  I apologize for the potato quality, I only have a cell phone for a camera and mediocre lighting.

![Bare Iris PCB](images/bare_pcb.jpg "Bare Iris PCB")

### Mount the Diodes

Replace the tip that came with the solder paste with a smaller gauge one and apply to the underside of each PCB on all the diode pads.

![Bare Iris PCB](images/nop.jpg "Bare Iris PCB")

Using precision anti-static ESD tweezers, carefully place all the diodes with the line facing the square through-hole pad.  Use magnification if needed.

![Bare Iris PCB](images/nop.jpg "Bare Iris PCB")

Melt the solder with the Hot-Air rework station.  I opted for 210° C.  The data sheet for the 2427 LEDs indicates they can withstand temps of 217° C for 60-150 seconds when wave soldering.  The data sheet for the paste indicates it will melt at 183° C.  I chose a point between the two temperatures.
