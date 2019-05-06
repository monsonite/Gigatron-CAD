# Gigatron-CAD
Eagle CAD Files for the Gigatron TTL Computer

These files contain the Gigatron TTL computer schematics transcribed to Eagle CAD - using the IC numbers used in the original KiCAD.

There are both PDF and PNG overviews of the ALU and Memory sections - a convenient way of representing the complete design.

The files have been posted - so that anyone who wants to build on the Gigatron design, has a known starting point in EagleCAD.

Certain modifications have been made in the process.

74HCT273 has been exchanged for the more bus friendly 74HCT573

74HCT240 and 74HCT244 have been exchanged for 74F540 and 74F541 - again to give better bus flow.

The diode matrix in the control unit now uses SOT-23 dual common anode diodes to reduce space

Eagle CAD allows all of the major IC packages to be easily converted to the SMT equivalent

- if you want to do a very compact Gigatron using 74F series SMT packages

Gigatron has been run at between 12.5 and 15MHz using 74F series ICS

The RAM expansion and additional SPI I/O ports are included in this version

Use sch files at your own risk - I cannot guarantee that they are free from errors


