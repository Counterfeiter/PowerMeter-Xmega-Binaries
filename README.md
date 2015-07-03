PowerMeter head unit binaries
==============

This repository contains the newest releases of the PowerMeter head unit binaries.
The microcontroller project is closed source but open hardware. Also there is a free PC software (google chrome app). Please see my other repositories.
To update the PowerMeter device faster, please burn the Flip Bootloader binaries to the flash at first and start updating the PowerMeter with Atmel USB bootloader.

License
--------------
PowerMeter binaries are free to use for non commercial application!

Software
--------------
Atmel Flip Bootloader needed
see: http://www.atmel.com/tools/FLIP.aspx

Versions History
--------------
v0.1
- inital start
- usb suspend sleep is working
- hid usb is working
- adc (hall sensor) and INA219 (current and voltage sensor) are working
v0.2
- adding rs485 output for a possbile extension board