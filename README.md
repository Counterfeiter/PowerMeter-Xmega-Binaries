PowerMeter binaries
==============

This repository contains the newest releases of the PowerMeter head unit binaries.
The microcontroller project is closed source but open hardware. Also there is a free PC software (google chrome app). Please see my other repositories.
To update the PowerMeter device faster, please burn the Flip Bootloader binaries to the flash at first and start updating the PowerMeter with Atmel USB bootloader.

The newest release of the PowerMeter Display Extension is also here as binarie file available.

A beta version of the PowerMeter CSharp Application for 64 Bit Windows systems is also available. You will need this software to change the scale values because the open source google chrome app issn't ready for this usecase.

License
--------------
Please see Atmel Flip Bootloader license at chapter "Software" (link) for ATXMega32A4U bootloader binaries license
PowerMeter binaries are free to use for non commercial application!
PowerMeter Display EADOG Extension binaries are free to use (GPLv2). Source code is available.

Software
--------------
Atmel Flip Bootloader needed
see: http://www.atmel.com/tools/FLIP.aspx

Versions History head unit
--------------

v0.1

- inital start
- usb suspend sleep is working
- hid usb is working
- adc (hall sensor) and INA219 (current and voltage sensor) are working

v0.2

- adding rs485 output for a possbile extension board

Versions History Display EADOG Extension
--------------
v1.0

- inital start
- recv. on two RS485 lines Data from to different PowerMeter head units
- display data on a 2x16 Char. LCD
- display min, max, mean and rms values for current and some data for power measures

v1.1

- run at 24 MHz with 8 MHz crystal
- fix bootloader starting workaround 

Versions History CSharp Application
--------------
Implemented:
- change scale values
- select current source
- start bootloader
- display and record graphes
- record a lot of PowerMeters at the same time
- set a easy trigger
- set measure and average box
- save graph to a picture (but not *.csv at the time)