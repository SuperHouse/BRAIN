Building Brain Home Automation Controller
==========================================
Copyright 2016-2018 SuperHouse Automation Pty Ltd  www.superhouse.tv  

Home automation controller based on a Raspberry Pi. A Raspberry Pi 3
attaches to this board, which is Arduino-compatible (ATmega328P) and
includes a switch-mode power supply for the Pi, plus 433MHz transmitter
and receiver modules connected to the Arduino. The Arduino can
communicate with the Pi via serial using onboard 3.3V/5V level
shifters, and can send / receive RF messages using the 433MHz modules.

Features:

 * ATmega328P MCU
 * 5V switchmode power supply
 * 433MHz transmitter
 * 433MHz receiver
 * Status LEDs


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to the project.


CREDITS
-------
Designed by Jonathan Oxer jon@oxer.com.au


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
