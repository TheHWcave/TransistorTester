# TransistorTester
Configurations and hex files for 2 firmware versions of an ATmega328P based transistor tester kit

These are firmware versions for the Transistor Tester as described on my YouTube channel:

https://www.youtube.com/c/TheHWcave

The firmware is based on  https://github.com/mikrocontroller-net/transistortester

I marked all my changes in the makefile (for the K-version) or the .h files for the M-version with "TheHWcave"


1_13K is Karl Heinz Kuebbler's MEGA328_COLOR_KIT 1.13K with a few tweaks to the makefile
1_46M is Markus Reschke's 1.46M configured for an ATmega328P board similar to the MEGA328_COLOR_KIT. 

The .hex file are to be loaded into the FLASH memory
The .eep file are to be loaded into the EEPROM
The .conf file is the configuration (ATmega328P fuses)

