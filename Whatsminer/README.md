# **ASIC Firmware Repository - Whatsminer**

Welcome to the official **ASIC Firmware Repository** for Whatsminer models. This repository provides firmware for a variety of Whatsminer models, organized by model and firmware version. Below you’ll find a breakdown of the latest available firmware files and their release notes. 

If you are looking for older firmware, navigate to the corresponding model directory. <b>As of right now we highly recommend downloading from the whatsminer official site. This directory isn't complete.</b>

---

## **Table of Contents**
1. [Using This Repository](#using-this-repository)
2. [Firmware Tables](#firmware-tables)
    - [H3 Firmware](#H3-firmware)
    - [H6 Firmware](#H6-firmware)
    - [H60s Firmware](#H60s-firmware)
    - [M10 & D1 Firmware](#M10-&-D1-firmware)
    - [M2x Firmware](#M2x-firmware)
    - [M3+M5+M6x Firmware](#M3+M5+M6x-firmware)
    - [M3 Firmware](#M3-firmware)
    - [Tools](#Tools)
3. [Contributions](#contributions)
4. [Disclaimer](#disclaimer)

---

## **Using This Repository**
1. **Locate Your Firmware:** Use the firmware tables to find the appropriate firmware for your specific Whatsminer model.
2. **Download:** Navigate to the corresponding directory and download the firmware file.
3. **Install:** Follow Whatsminer official firmware installation guidelines to update your device.
4. **Release Notes:** Review the release notes for updates, improvements, and known issues.

---

## **Firmware Tables**

## **H3 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| H3 (M3x, M2x series) | H3 SD card Program-20220422.zip | 1. Applicable mode 1.1 M3x, M2x series； 2. Details 2.1 H3 control board card brush system file, including instructions and burning software； 2.2 If 201-8410 error codes come out after flashing the program, then you need to upgrade the *.bin firmware with whatsminertool to solve it.   |
| H3 (M3 Only)  | M3-H3 SD card Program.zip  | WhatsMiner M3 only；  |
| H3 (MM10, D1 only)  | M10 and D1-H3 SD Card Program.zip   | WhatsMiner M3 only；  |
---
## **H6 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| H6 (M3x, M2x series) |  H6 SD Card Program-20210121.zip
 | 2.1 H6 control board card brush system file, including instructions and burning software； 2.2 After that you will need to upgrade the latest firmware,if the miner is not upgraded, there will be error code 201-8410;   |
| H6 (M10, D1)  | M10 and D1- H6 SD Card Program-190404.zip  | WhatsMiner M10, D1；  |
---
## **H60s Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| H60s (M3x, M2x series) |  H6os SD Card Program-20220422.zip  | 1. After that you must upgrade the latest firmware, if the miner is not upgraded, there would be error code; 2. Applicable to M5x, M3x and M2x series；   |
| H60s (M10, D1)  | M10 and D1-H6os SD Card Program.zip   | WhatsMiner M10, D1；  |
---
## **H616 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| H616 (M6X, M5x and M3x series) | H616 SD Card Program-20240328.zip   | After that you must upgrade the latest firmware, if the miner is not upgraded, there would be error code; |
| H60s (M54&M64 series)  | M54&M64 control board flashing.zip    | Used for M54&M64 series with H616 control board burning. After flashing, please use WhatsMinerTool to upgrade the new firmware online, otherwise the machine maybe not running normally.  |
---
## **M10S, D1 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| M10S, D1 | upgrade-whatsminer-h6-20190404.18.bin    | 1.1 M10S, D1 etc； 1.2 Applicable to H6 control board； |
---
## **M2x Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| M2x | Whatsminer-M2x-all-20220919.15.bin     | 1. Applicable mode 1.1 M21S, M20S, M21,etc; 1.2 High mode can not be supported; 2. New version highlights 2.1 Support Pool TLS safety transportation protocol; 2.2 If the miner firmware is before 2021, it is recommended to upgrade the firmware after SD-card flashing; 2.3 Strengthen the safety of firmware: device will reboot 2 times during upgrading,the version name will be end with"NeedUpgradeAgain" at 1st time，please wait for 2nd reboot, after that it will be changed to target version; 2.4 Fixing other bugs; 2.5 Online upgrading to version earlier than 20210602 is prohibit，suggest to match with tool whatsminertool-8.1.34; 2.6 The WhatsMiner API version is V2.0.5; |
---
## **M3x & M5x & M6x Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| M3x & M5x & M6x | Whatsminer-M3x-all-20241108.23.bin     |  1. Applicable mode 1.1 M60 series/ M50 series/ M30 series etc.； 1.2 Support for H616 and H6OS (CB6 and CB4_V10) type, for other type(CB2), please contact after-sales service 2. New version highlights 2.1 Support Pool TLS safety transportation protocol; 2.2 Support to get miner SN by API; 2.3 Strengthen the safety of firmware: device will reboot 2 times during upgrading,the version name will be end with"NeedUpgradeAgain" at 1st time，please wait for 2nd reboot, after that it will be changed to target version; 2.4 Support API V3 on CB4_V10 controller; 2.5 Online upgrading to version earlier than 20231213 is prohibit，suggest to match with tool whatsminertool-9.0.4; 2.6 Support some new coin type on SHA256; 2.7 If your whatsminer firmware version is newer than this firmware version, please do not upgrade! |
---
## **M3 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| M3 | upgrade-whatsminer-bt1000-20190404.18.1.bin     | 1.1 M3, M2 and M1 only；1.2 Applicable to H3 control board；1.3 Need to use old version of Whatsminertool to upgrade it; |
---

## **Contributions**
If you have additional firmware versions or updates, feel free to contribute! Submit a pull request or reach out to us for assistance.

---

## **Disclaimer**
All firmware provided here is for informational and educational purposes. Please ensure compatibility with your devices before installation. We are not responsible for any issues arising from firmware updates.

---
