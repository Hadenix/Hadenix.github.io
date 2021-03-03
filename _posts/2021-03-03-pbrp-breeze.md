---
layout: post
title: PitchBlack Recovery Project For UMIDIGI A5 Pro [A5_Pro][UNOFFICIAL]
category: blog
excerpt: 3.0 [STABLE]
author: Kirill Yaroshevich
---

![PitchBlack Recovery logo](https://raw.githubusercontent.com/Hadenix/Hadenix.github.io/master/images/umidigi-a5-pro/PitchBlack%20Recovery.jpg)

**Pitch Black Recovery is a fork of TWRP with many improvements to make your experience better. It's more flexible & easy to use. Pitch Black Recovery was started in March 18 2018 with the movement to enhance TWRP with better customizatons, themes and features.**

### Whats not working ?
* Decryption with default password

### Changelog
03-03-2021
- Fix MTP and ADB
- Updated recovery.fstab
- Kernel update from ROM V1.8
- First release

* PBRP Changelog
  * [View](https://t.me/UMIDIGIA5Pro)

### Downloads & Device trees
* PBRP for UMIDIGI A5 Pro - [View](https://sourceforge.net/projects/umidigi-mt6763-dev/files/PBRP/)
* ADB/Fastboot Tool - [View](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)
* Magisk - [View](https://github.com/topjohnwu/Magisk/releases)
* Data decryption patch - [View](https://androidfilehost.com/?fid=6006931924117935374)

### You can Donate Me if you like my work
* PM me on Telegram: [Click here](https://web.telegram.org/#/im?p=@Hadenix)

### Installation
* Unlock bootloader
* Place recovery image in ADB tool's folder.
* Then open a CMD window inside that folder. To do that, Shift + Right click on any empty white space inside the folder and then select Open command window here.
* Connect your Android device to the PC. Type the following into the command window to boot your device into bootloader/fastboot mode:
```
adb reboot bootloader
```
└ If your asks for permission to “Allow USB debugging”, tap OK.
* Once your device boots into bootloader mode, type this into the command line.
```
fastboot flash recovery recovery.img
```
* Power off device.
* Pick up your phone and press power button, volume up and down keys at same time. It will boot into Bootloader then boot into twrp.
* Format data, Flash Magisk and data decryption patch.
* Reboot your device.
* Done
