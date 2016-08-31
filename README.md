# SCB-Control

PRIME (Purdue Rare Isotope Measurement) Lab conducts AMS (accelerator mass spectroscopy) measurements for various elements.  A new source for the accelerator is to be installed and this code is for controlling the new sample changer [including the motor (Kollmorgen PowerPac N33HRHJ-LEK-M2-00) and motor driver (Kollmorgen P70530 driver) the rotate the sample wheel] and electronics on the same HV shelf as the sample changer.

The motor driver is communicated to through a National Instruments cRIO module (NI-9512) and motor position read back via an 14-bit encoder reporting to a NI-9403 cRIO module.

Other modules in use...

Serial communications...

## Branches
master: latest working version

