# Gigatron-CAD
Eagle CAD Files for the Gigatron TTL Computer - Based on the design by Marcel van Kervinck

These files contain the Gigatron TTL computer schematics transcribed to Eagle CAD - using the IC numbers used in the original KiCAD.

For anyone wanting to build a machine based on the Gigatron design, the Eagle CAD schematic offers a known starting point.

Minor alterations have been made to allow easier routing specifically in the ALU section, where all 74HCT153 multiplexers use the same multiplexer section - and the logic constants into the other mux are the same for all devices.

There are both PDF and PNG overviews of the ALU and Memory sections - a convenient way of representing the complete design.

Certain components substitutions have been made for convenience of layout or saving space

74HCT273 has been exchanged for the more bus friendly 74HCT573

74HCT240 and 74HCT244 have been exchanged for 74F540 and 74F541 - again to give better bus flow.

The diode matrix in the control unit now uses SOT-23 dual common anode diodes to reduce space

Eagle CAD allows all of the major IC packages to be easily swapped to their SMT equivalents

If you want to make a very compact Gigatron using 74F series SMT packages.

Gigatron has been run at between 12.5 and 15MHz using 74F series ICS

The 128K byte RAM expansion and additional 8-bit input and 8-bit output ports (for SPI) are also included in this version

Use sch files at your own risk - I cannot guarantee that they are free from errors


