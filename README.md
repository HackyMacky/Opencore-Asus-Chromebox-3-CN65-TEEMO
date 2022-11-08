# Opencore-Asus-Chromebox-3-CN65-TEEMO
A working DEBUG repository of Opencore configuration for Asus Chromebox 3 CN65 Teemo

## DISCLAIMER 
I will not be held responsible for any damage, permanent loss of data or any sorts of consequences that may arise by using my configuration files on your devices. Please use at your own risk.

## Current Release
- Opencore 0.8.5 (Debug)
- Monterey 12.6.1
- All latest kexts as of Nov 1, 2022

## Device Specifications

| Specification  | Model |  Remark  |
| ------------- | ------------- | ------------- |
| Chipset  | Intel | N/A |
| CPU  | Intel i7-8550U (Kaby Lake Refresh)  |
| iGPU  | Intel UHD Graphics 620 | 
| Storage  | Micron 256GB M.2 SATA SSD 2280   |
| RAM  | 16GB (2x8GB)2666 MHz DDR4 |
| Ethernet  | Realtek PCIe GbE  |
| Wi-Fi  | Fenvi (BCM94360NG)  |
| Bluetooth  | Fenvi (BCM94360NG)   |
| Audio  | N/A   |


## What's working
- Wi-Fi & Bluetooth (PLEASE TAKE NOTE THIS BUILD USES A FENVI BCM94360NG WIFI NIC)
- Ethernet (Ensure to use your own Mac Address for fallbackMAC value in the RealtekRTL8111.kext)
- Display output HDMI
- USB ports mapping

## What's not working
- Hardware Acceleration
- Speaker, Headphone jack, microphone
- Sleep/wake/shutdown
- SD Card Reader
- Display USB-C to HDMI

## Not tested
- AppleID and iServices
- All Continuity & Handoff features

## Quirks/issues
- Major issue at the moment is getting Hardware Acceleration to work with UHD 620. Following the instruction on OC guide to set device-id completely renders the unit stalling boot. 
- Audio driver is unknown as there is no driver available even on Windows


## Credits
- All credits & rights goes to the maintainers, contributors and developers of the Opencore project and respective kernel extensions.
- Apple Inc.
