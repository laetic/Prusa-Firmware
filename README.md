# Prusa i3 MK2 Firmware for Lathe Printer

## General instructions

Pre-compiled hex output on PRUSA RESEARCH site: http://prusa3d.com/downloads/firmware/

Just download and flash it to the electronics

## Build instructions

### Step 1

Install arduino

### Step 2

Remove Liquid Crystal library from your arduino or rename it

### Step 3

Install the arduino addon located in the root of this repo. Don't forget to install correct version!

### Step 4

Copy the configuration file matching your printer from variants folder to the the Firmware folder

### Step 5

Rename it to "Configuration_prusa.h"
Note: Modifications to the configuration for the drum printer are already in Configuration_prusa.h in the Firmware folder

### Step 6

Compile the firmware

### Step 7

Upload the firmware to board, ATMega2560





