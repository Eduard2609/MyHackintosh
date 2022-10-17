# MyHackintosh
Installation guide for my Hackintosh build dual-booting macOS Monterey and Windows 10.
This build is based on [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/).

![win](https://user-images.githubusercontent.com/59319107/196250897-9f45250d-2b0a-426f-bac2-56fa1027b5e0.png)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/eduardolteanu)

## Table of Contents
* [Specs](#specs)
* [Installation](#installation)

## Specs

* **CPU:** [Intel Core i5-10600K](https://amzn.to/3D1TDpA)
* **CPU Cooler:** [be quiet! Pure Rock SLIM](https://amzn.to/3TerLUX)
* **Motherboard:** [MSI MAG B460M BAZOOKA](https://amzn.to/3yNvxMU)
* **Memory:** [ADATA GAMMIX D20, 8GB DDR4, 3200MHz CL16](https://amzn.to/3eAB7vk)
* **Storage (macOS):** [Solid-State Drive (SSD) Kingston NV1, 500gb, NVMe, M.2](https://amzn.to/3zaozlt)
* **Storage (Windows):** [Solid-State Drive (SSD) Kingston A2000, 1 TB, NVMe, M.2](https://amzn.to/3eE4IUC)
* **Storage (Extra):** [WD Blue 3.5 1TB 7200rpm 64MB SATA3](https://amzn.to/3Vzov85)
* **Video Card:** AMD Radeon R9 290X
* **Power Supply:** [EVGA 700B Power Supply](https://amzn.to/3SdGbDj)
* **Case:** Inaza Black Ship
* **Monitor:** Acer K272HUL
* **Keyboard:** Logitech 610
* **Mouse:** Logitech G502 Hero

## Installation

### USB Creation
The drivers, kexts, and SSDTs I used are as follows:

* ACPI
  * SSDT-AWAC.aml
  * SSDT-EC-USBX-DESKTOP.aml
  * SSDT-PLUG-DRTNIA.aml
  * SSDT-RHUB.aml
* Drivers
  * HfsPlus.efi
  * OpenRuntime.efi
* Kexts
  * AppleALC.kext
  * CtlnaAHCIPort.kext
  * Lilu.kext
  * NVMeFix.kext
  * RealtekRTL8111.kext
  * SMCProcessor.kext
  * SMCSuperIO.kext
  * VirtualSMC.kext
  * WhateverGreen.kext

  
