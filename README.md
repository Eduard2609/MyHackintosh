# MyHackintosh
Installation guide for my Hackintosh build dual-booting macOS Monterey and Windows 10.
This build is based on [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/).

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/eduardolteanu)

## Table of Contents
* [Specs](#specs)
* [Installation](#installation)

## Specs

* **CPU:** Intel Core i5-10600K
* **CPU Cooler:** be quiet! Pure Rock SLIM
* **Motherboard:** MSI MAG B460M BAZOOKA
* **Memory:** ADATA GAMMIX D20, 8GB DDR4, 3200MHz CL16
* **Storage (macOS):** Solid-State Drive (SSD) Kingston NV1, 500gb, NVMe, M.2
* **Storage (Windows):** Solid-State Drive (SSD) Kingston A2000, 1 TB, NVMe, M.2
* **Video Card:** AMD Radeon R9 290X
* **Power Supply:** EVGA 700B Power Supply
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

  
