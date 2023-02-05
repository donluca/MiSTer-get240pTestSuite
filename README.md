# 240p Test Suite downloader and updater for MiSTer FPGA

## What is this?

This is a script which will let you download and keep updated all of the 240p Test Suites for several game consoles in one go on your MiSTer FPGA.  
The [240p Test Suite](https://junkerhq.net/xrgb/index.php?title=240p_test_suite) is a collection of tools originally developed by [Artemio Uribna](https://junkerhq.net/) and later ported to several platforms by other developers to diagnose and calibrate monitors to make sure your gaming consoles will look their best on your setup.  
Some platforms have also [MDFourier](https://junkerhq.net/MDFourier/) included which is an audio analysis tool to diagnose and make sure that the audio coming out from your console is correct and not altered or degraded.  
It can be used from the GUI (in this case it will automatically download and/or update the various 240p Test Suites) or from command line with the following syntax:  
```
Usage: ./get240pTS.sh <Platform> (z)  
 
Platforms supported:  
 
GB (Nintendo Game Boy)  
GBA (Nintendo GameBoy Advance)  
MCD (SEGA Mega Drive/Genesis + Mega CD/SEGA CD)  
32X (SEGA Mega Drive/Genesis + SEGA 32X)  
MD (SEGA Mega Drive/Genesis)  
NES (Nintendo Entertainment System/Famicom)  
PCE (NEC PC Engine/TurboGrafx-16)  
PCECD (NEC PC Engine/TurboGrafx-16 + TurboGrax-CD/CD-ROM)  
PCESCD (NEC PC Engine/TurboGrafx-16 + Super CD-ROM)  
PS1 (Sony Playstation)  
SMS (Sega Master System/Mark III)  
SNES (Nintendo Super NES/Super Famicom)  
ALL (Download all of the above)  
 
If the file is zipped, you can unzip it by adding z to the command  
 
Example: ./get240pTS.sh MD z  
This will download the Mega Drive 240p Test Suite and unzip it  
```

## Installation

You can install this script by downloading get240pTS.sh from this repository and copying it to /media/fat/Scripts (the Script folder on your SD card).  

## Credits  

[Artemio Urbina](https://junkerhq.net/): Dreamcast, Game Cube, MegaCD, Mega Drive, PCEngine, PCEngine CD, PCEngine SuperCD, SNES, Wii  
[PinoBatch](https://github.com/pinobatch/240p-test-mini): NES, Game Boy, Game Boy Advanced  
[Daustin](https://github.com/Dasutin/32X240pTestSuite): SEGA 32X  
[Filip Aláč](https://github.com/filipalac/240pTestSuite-PS1): Playstation  
[sverx](https://github.com/sverx/SMSTestSuite/): Master System  
