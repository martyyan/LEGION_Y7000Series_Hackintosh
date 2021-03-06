![image](https://github.com/xiaoMGitHub/LEGION_Y7000Series_Hackintosh/blob/master/Picture/macOS_Big_Sur.png)

## Introduction

[中文版](https://github.com/xiaoMGitHub/Lenovo_Y7000-Y530_Hackintosh/blob/master/README.md) | [English](https://github.com/xiaoMGitHub/Lenovo_Y7000-Y530_Hackintosh/blob/master/README-en.md)

Our purpose is to allow LENOVO LEGION Y7000/Y7000P-2018、Y7000/Y7000P-2019、Y7000/Y7000P-2020、Y9000K-2020、Y530、Y540、Y545、legion 5i、legion 7 laptop to run mac OS as natively as possible

Tips: Y530/Y540/Y545/legion 5i/legion 7 does not have whitelist upon WLAN hardware, you even do not need to modify your BIOS

## Releases
The latest version is v3.0.2 and can be downloaded on the [release page](https://github.com/xiaoMGitHub/LEGION_Y7000Series_Hackintosh/releases).

## What do you need
- Catalina disk image is prepared, nomally .dmg file, macOS High Sierra (10.13.6) - macOS Big Sur has been tested
- USB storage (at least 16 Gigabyte)

## BIOS Configration
- Boot mode: UEFI
- security boot should be disabled
- Storage mode: AHCI

## Full Compatibility
- Boot clover/OC with UEFI mode
- Built-in keyboard (Function key and Num keyboard works well)
- native USB3 / USB2 ports 
- AppleHDA native audio, Speakers + Internal Mic + Headphone
- Built in Camera
- Native power management
- Battery Status (Percentage can be displayed)
- Brightness control (can be adjusted by function key with hotpatch)
- Backlit keyboard
- INTEL iGPU (DGPU has been disabled by hotpatch)
- Ethernet port
- Mac App Store works normally
- CPU SpeedStep
- Sleep + Wake (Waked by mouse, keyboard, and power button)
- Wireless LAN (Broadcom BCM943602CS)
- Bluetooth (Broadcom BCM943602CS)
- Touchpad
- Sidecar
- 4K Display
- iMessage/FaceTime

## Disabled devices
- HDMI, HDMI port is connected with disabled NVIDIA DGPU

## After the installation is complete
```
sudo sh -c "$(curl -fsSL https://gitee.com/xiaoMGit/Y7000Series_Hackintosh_Fix/raw/master/Script/Optimize.sh)"
```

## About tipping

If you approve my work, please suppoort me to keep updating via tipping

| Paypal                                                       |
| ---------------------------------------------------------- | 
| [xiaoMGitHub](https://www.paypal.me/xiaoMGitHub) | 


