# Solar Powered Boat
2017/18 Final-year project, Self-guided boat

This repo contains many software tools (some of which may be redundant), the ardupilot software, schematics and notes about the construction. Feel free to clean things if you want.

## Firmware
Contains the firmware for the ardupilot microcontroller. The module we are using is the APMrover2 module. 
Calling make in the Firmware directory should build correctly, but you might find it easier to work in the APMrover2 directory directly.

While in APMrover2 call `make apm2` to build APMrover2.elf. Once built, `make apm2-upload` to upload to the microcontroller.

## Dependancies
You will need an install of the arduino development libraries and gcc-avr to build the project and avrdude for uploading the firmware.
