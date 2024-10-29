# HighHat for Voron 0.2


### HighHat is possible thanks to the work of many others including:

mjonuschat's [NightOwl](https://github.com/mjonuschat/NightOwl) - A fully self-enclosed dual filament AMS system<br>
[Filamentalist Rewinder](https://github.com/Enraged-Rabbit-Community/ERCF_v2/tree/master/Recommended_Options/Filamentalist_Rewinder) - from the ERCF Community<br>
Fysetc's [ERB 2.0 MCU](https://github.com/FYSETC/FYSETC-ERB/tree/main/V2.0) - A commercially available MCU meant for AMS systems<br>

## Assembly Notes

For detailed assembly instructions, please see HighHat_Assembly.pdf

### Printed Parts

All printed parts should be printed using the [standard Voron recommended settings](https://docs.vorondesign.com/sourcing.html):
- Layer height: 0.2mm.
- Extrusion width: 0.4mm, forced.
- Infill percentage: 40%
- Infill type: grid, gyroid, honeycomb, triangle, or cubic.
- Wall count: 4.
- Solid top/bottom layers: 5.
- Supports: NONE

STLs marked with [A] are reccomended to be printed in your accent color of choice<br>
STLs that should be printed with a quanity of more than 1 will have the quantity denoted at the end of the file name (ie x2)

### Prior to Beginining

You will need to source and install any v0.2 hotend design that has a toolhead AND filament entry sensor. If you use the [LDO Picobilical](https://docs.ldomotors.com/en/voron/voron01/Picobilical) you already have two GPIO pins reserved for this purpose in the lower left hand corner of the board. Plan AHEAD of time how you intend to handle your wiring, as this will save a LOT of headaches down the road.

### Firmware Flashing and Config

You should follow the manufacturs instructions for your specific MCU, this project assumes you will be using the Fysetc ERB 2.0, but alternatives could be used.

A sample config file is included in this repository (sampleconfig.config)

