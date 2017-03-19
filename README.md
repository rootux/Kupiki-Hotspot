![License Creative Commons](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)

# Kupiki-Hotspot v0.1

### This project is using part of the [netinstall version of Raspbian](https://github.com/debian-pi/raspbian-ua-netinst)

## Features
- Minimal Raspbian up to date (it will download latest packages)
- DHCP configuration (you can configure a static IP)
- A Wifi hotspot using the integrated wifi chipset
- A captive portal based on coovachilli
- An authenticate control based on freeRadius
- An interface for freeRadius based on daloRadius

## Requirements
- a Raspberry Pi model 3
- a minimal 2Gb SD card
- a working Ethernet connection with Internet connectivity

## Installing the Hotspot
1. From your favorite OS, format your SD card as a FAT32 disk. One partition is enought (On Mac OS X, partition needs to be in MBR).
2. Copy all files on your SD card
3. Put the SD card in the Raspberry Pi, power it on and cross your fingers will the system is installed

## Logging in
Username:root
Password:raspbian


This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License.

Please read [LICENSE.md](LICENSE.md) file
