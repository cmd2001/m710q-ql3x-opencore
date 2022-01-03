# m710q-ql3x-opencore

macOS Monterey(12.1) EFI(Opencore 0.7.6) for Lenovo M710q QL3x


## My Hardware

* CPU: Intel QL3X
* Graphics Card: HD630
* Motherboard: Lenovo M710q
* Wi-Fi & Bluetooth: Intel AC8265
* Network Adapter: Intel i219v2
* Audio Card: Realtek ALC294 (AppleALC Layout: 21)

## Tested macOS Version

macOS Monterey (12.1)

## Compatibility

* Intel QL3X
* Lenovo M710q or M910q
* All Intel WiFi & Bluetooth

## What Works

* Video Acceleration
* Audio
* USB ports
* CPU Power Management (Intel Power Gadget)
* WiFi
* Bluetooth
* Wired Network
* iMessage
* Handoff (sometimes works)
* Universal Clipboard
* Virtualization

## What does not Work

* Airdrop (please refer to itlwm repo)

## What will never Work

* Hibernation (since Intel ME is disabled)

* Things do not work when Intel ME is diabled (Hibernation, Intel SGX, etc)

## BIOS Settings

* Turn off: CSM

# SMBios Settings

* Suggested Model: MacMini 8,1
* **This EFI does not contain Model Settings, you need to add it by OC Configurator before first boot**

# About BIOS.bin

This is a modified version of BIOS to support all 1151/1440 CPUs on Lenovo M710q/M910q.

Flash it with CH341A Programmer.

**ALERT: FLASHING BIOS IS RISKY AND MAY IRREVERSIBLY DAMAGE YOUR HARDWARE, DO IT ON YOUR OWN RISK**