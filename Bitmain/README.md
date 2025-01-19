# **ASIC Firmware Repository - Bitmain Antminer**

Welcome to the official **ASIC Firmware Repository** for Bitmain Antminer models. This repository provides firmware for a variety of Antminer models, organized by model and firmware version. Below you’ll find a breakdown of the latest available firmware files and their release notes. 

If you are looking for older firmware, navigate to the corresponding model directory. We recommend attempting to pull official firmware from Bitmain's site and using this source as a backup.

---

## **Table of Contents**
1. [Using This Repository](#using-this-repository)
2. [Firmware Tables](#firmware-tables)
    - [Blake256r14 Firmware](#blake256r14-firmware)
    - [Scrypt Firmware](#scrypt-firmware)
    - [SHA-256 Firmware](#SHA-256-firmare)
    - [kHeavyHash Firmware](#SHA-256-firmare)
    - [X11 Firmware](#X11-firmware)
    - [Etcash ETHW ETHASH Firmware](#Etcash-ETHW-ETHASH-firmware)
    - [Equilhash Firmware](#Equilhash-firmware)
    - [RandomX Firmware](#RandomX-firmware)
    - [Blake2B+SHA3](#Blake2B+SHA3-firmware)
    - [BTM Tensority](#BTM-Tensority-firmware)
    - [SC Blake(2b)](#SC-Blake-firmware)
    - [RandomX Firmware](#RandomX-firmware)
    - [CKB Eaglesong Firmware](#CKB-Eaglesong-firmware)
    - [ETH Graphics Firmware](#ETH-Graphics-firmware)
    - [KDA Blake2S Firmware](#KDA-Blake2S-firmware)
    - [Tools](#Tools)
    - [ALPH+Blake3 Firmware](#ALPH+Blake3-firmware)
3. [Contributions](#contributions)
4. [Disclaimer](#disclaimer)

---

## **Using This Repository**
1. **Locate Your Firmware:** Use the firmware tables to find the appropriate firmware for your specific Antminer model.
2. **Download:** Navigate to the corresponding directory and download the firmware file.
3. **Install:** Follow Bitmain's official firmware installation guidelines to update your device.
4. **Release Notes:** Review the release notes for updates, improvements, and known issues.

---

## **Firmware Tables**

## **Blake256r14 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| DR3         | DR3-201907161805-410M.tar.gz         | Support blacklist feature during updating firmware. Use new build tools to build firmware.    |
| DR5    | DR5-202111021517_sig.tar.gz           | Signed Firmware   |
| DR7         | DR7-release-202405280928.bmu         | Optimized firmware.     |

---

## **Scrypt Firmware**


| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| R3         | R3-LTC-SIA-DASH-20180815.bin          | Fixed bugs, improved stability    |
| L3++   | L3++-201907151552-450M.tar.gz           | Support blacklist feature during updating firmware. Delete uploading config file web API. Support the location feature through LED flash. Use new build tools to build firmware.  |
| L3++          | L3+-201907101440-384M.tar.gz           | Support blacklist feature during updating firmware. Delete uploading config file web API. Support the location feature through LED flash. Use new build tools to build firmware.      |
| L3          | L3-201704271449-384M.tar.gz           | Support L3 miners Remove the function: post mac address and remote stop mining interface       |
| L7          | L7-release-202405141413.bmu           | Optimized firmware. L7 miners before 2023 are strongly advised not to upgrade this firmware instead of Antminer-L7-release-202301300939.bmu.    |
| L9          | L9-CV-release-202408211920.bmu           | ANTMINER L9. initial firmware.   |

---

## **SHA-256 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| S21 XP Hyd        | S21-XP-Hyd.-release-202501061507.bmu           | Optimized firmware.    |
| S21e XP Hyd| S21e-XP-Hyd.-release-202501061507.bmu           | initial firmware.  |
| S21 XP          | S21-XP-AML-release-202411051642.bmu           | initial firmware.    |
| S21 Pro          | S21-Pro-AML-release-202408281552.bmu            | Optimized firmware.       |
| S21 Hyd          | S21-Hyd.-release-202405191051.bmu          | Optimized firmware.   |
| S21 Imm          | S21Imm-AML-release-202408061155.bmu            | initial firmware.   |
| S19k Pro         | S19k-Pro-merge-release-20240409060820.bmu             | initial firmware.   |
| T21          | T21-merge-release-20240926105845.bmu           | Implemented frequency reduction and other optimization strategies for machines that may shut down due to high temperatures.   |
| S21          | S21-AML-release-202410111634.bmu            | Implemented slight frequency reduction and other optimization strategies for machines that may shut down due to high temperatures.   |
| S19j XP         | S19j-XP-merge-release-20241014031336.bmu             | Optimized firmware.   |
| S19 XP        | S19j-XP-merge-release-20241014031336.bmu             | Optimized firmware.   |
| S19 XP Hyd         | S19-XP-Hyd.-merge-release-20240924062054.bmu              | Optimized firmware.   |
| S19 Pro+ Hyd         | S19Pro+-Hydro-release-202303081530.bmu              |  Optimize the performance of some corner cases in low-power mode. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.   |
| S19 Pro Hyd          | S19Pro-Hydro-factory-202206161349-transitional.bmu               | transitional firmware. This firmware is the transition firmware for the ANTMINER S19Pro Hyd. miner, which is suitable for the transition when some versions of the 2022 firmware cannot be directly upgraded to the release firmware. That is, for some machines that cannot directly upgrade the release firmware, please upgrade this firmware first, and then upgrade to the release firmware.   |
| T19 Pro Hyd         | T19-Pro-Hyd.-release-202404171359.bmu              | initial firmware version.   |
| S19e XP         | S19e-XP-Hyd.-release-202406241812.bmu               | initial firmware version.   |
| S19 Pro         | S19-Pro-merge-release-20221226124238.bmu               | Support S19 Pro low power mode.   |
| T19 Hydro         | T19-Hydro-release-202212121629.bmu               | Support low-power mode.   |
| S19 Hydro         | S19-Hydro-release-202212170935.bmu              | Optimized firmware.   |
| S19j Pro         | S19j-Pro-merge-release-20221226125147.bmu              | Support low power mode.   |
| S19a        | S19a-release-202212061830.bmu               | Support low power mode.   |
| S19j        | S19j-merge-release-20221226012642.bmu               | Support low power mode.   |
| T19        | T19-release-202303201213.bmu               |  Support APW1215F power supply. |
| S19        | S19-merge-release-20221227070716.bmu               |   Support low power mode. |
| S19i        | S19i-release-202104272304.bmu                |  initial firmware version. |
| S17+              | S17+-user-OM-202006021031-sig_5968.tar.gz | Enhanced miner stability under temperature extremes. Added protection during firmware updates and enhanced anti-virus capability. Improved power-off protection for planned outages. |
| T17+              | T17+-user-OM-202006021011-sig_5967.tar.gz | Similar enhancements as S17+, with improved miner stability and security.                                                                  |
| S17e              | S17e-user-OM-202004221119-sig_5818.tar.gz | Enhanced miner stability under extreme temperatures and improved anti-virus mechanisms.                                                    |
| T17e              | T17e-user-OM-202004221121-sig_5820.tar.gz | Similar to S17e: stability improvements and enhanced anti-virus features.                                                                  |
| S17Pro            | S17Pro-user-OM-202004271325-sig_5837.tar.gz| Added sleep mode, memory, and temperature module improvements. Removed voltage calibration and widened voltage inspection scope.             |
| S17               | S17-user-OM-202004271323-sig_5835.tar.gz  | Added sleep mode, enhanced memory and temperature modules, and new anti-virus capabilities.                                                 |
| T17               | T17-user-OM-202004231629-sig_5828.tar.gz  | Added enhanced anti-virus capability and widened voltage inspection scope.                                                                 |
| S15               | S15-user-OM-201912131535-sig_4864.tar.gz  | Fixed hashrate fluctuation issues, added auxiliary port for Antguard tools, and implemented sleep mode.                                     |
| T15               | T15-user-OM-201912131546-sig_4867.tar.gz  | Similar to S15: fixed hashrate fluctuation and electric current issues.                                                                    |
| S11               | S11-all-user-201908011639-sig.tar.gz      | Added anti-virus capability, secure signature, and support for both 7007 and 7010 control boards.                                           |
| S9 SE             | S9 SE-user-OM-201909181551-sig_4034.tar.gz| Improved temperature data accuracy and enhanced anti-virus capability.                                                                     |
| S9k               | S9k-user-OM-201912131001-sig_4859.tar.gz  | Optimized over-temperature handling and power-on processing. Improved temperature detection mechanism.                                      |
| S9j               | S9j-xilinx-201907311617-autofreq-user-Update2UBI-NF-sig.tar.gz | Added anti-virus capability. Secure firmware with signature. Closed SSH port.                                                              |
| S9i               | S9i-xilinx-201907311618-autofreq-user-Update2UBI-NF-sig.tar.gz | Similar to S9j: enhanced anti-virus capability with secure firmware.                                                                       |
| S9                | S9-xilinx-201907311618-autofreq-user-Update2UBI-NF-sig.tar.gz | Enhanced anti-virus capability and implemented secure firmware with signature.                                                             |
| S9 hydro          | S9_Hydro-xilinx-201909201034-autofreq-user-Update2UBI-NF-sig_4038.tar.gz | Added options for higher hashrate or lower power consumption. Secure firmware with signature.                                               |
| V9                | V9-20180312-600M.tar.gz                   | No notes.                                                                                            |
| T9+               | T9+-xilinx-201907311620-autofreq-user-Update2UBI-NF-sig.tar.gz | Enhanced anti-virus capability and secure firmware with signature.                                                                         |
| T9                | T9-all-201704280716-autofreq-user-Update2UBI-NF.tar.gz | Added memory support for 512MB/1024MB controller boards.                                                                                   |
| S7                | S7-20160523-700M-1fan-6000.tar.gz         | No notes.                                                                                            |
| S7-LN             | 2.7T_201605181458-600M-2fan-3700.tar.gz   | No notes.                                                                                            |
| S5+               | 20150929-375M.tar.gz                      | No notes.                                                                                            |
| S5                | S5-20150715-fan_ctrl.tar.gz               | Added user-defined fan speed and optimized miner status processing.                                                                        |
| R4                | R4-xilinx-201811121649-autofreq-user-UBI-NF.tar.gz | Reduced power consumption and added auto-abort on unmet upgrade criteria.                                                                  |
| S4                | initramfs.bin.SD-20150415.tar.gz          | Added anti-DDOS function and improved minerlink functionality.                                                                             |
| S4+               | SD-S4+-20150715.tar.gz                    | Added user-defined fan speed and optimized miner status processing.                                                                        |
| S3                | antMiner_S320150109.bin                   | Fixed bugs related to temperature readings and power adjustments.                                                                          |
| S2                | initramfs.bin.SD-20141029.tar.gz          | Updated cgminer to 4.6.1 and improved miner status/configuration page.                                                                     |
| C1                | SD-C1-20141217.tar.gz                     | Initial firmware.                                                                                    |
| S1                | antMiner_openwrt20131212.bin              | Discarded stale nonce and changed default IP to 192.168.1.99.                                                                              |
| S19 Pro Hydro     | S19Pro-Hydro-user-release-20230911140154-6665.bmu | Supports new power supplies (APW11b/c/d).                                                                                                  |
| R1                | AntRouter-R1-LTC-SIA-DASH-20180815.bin    | Initial firmware.                                                                                    |
| S19j              | S19j+-merge-release-20221226013227.bmu    | Support low power mode.                                                                              |
| S19j Pro+         | S19j-Pro+-merge-release-20230628120953.bmu| Optimized firmware.                                                                                   |
| S19j pro A        | S19j-Pro-A-merge-release-20221226011726.bmu| Support low power mode.                                                                              |
| S19 Pro++         | S19-Pro++-merge-release-20241106074022.bmu| Initial firmware for S19 Pro++. Ensure miner and firmware type match before upgrading.                                                     |
| S19 Pro A         | S19-Pro-A-merge-release-20221226124600.bmu| Support low power mode.

---

## **kHeavyHash Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| KS3        | KS3-CV-release-202404091643.bmu         | Optimize the firmware.    |
| KS5   | KS5-CV-release-202408281112.bmu            | This version of firmware is also available for the KS5 Pro and KS5 18T models. Updates： 1. Optimized firmware.   |


---

## **X11 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| R3       | AntRouter-R3-LTC-SIA-DASH-20180815.bin          | No Notes    |
| D3  | D3-201811131204-0M.tar.gz            | Security Firmware, Fix some security vulnerabilities.   |
| D5        | D5-mode-350M-201908192031.tar.gz          | 1. Enhance anti-virus capability；2. Use new build tools to build firmware.    |
| D7  | D7-release-202110201043.bmu            | D7 Miner initial firmware version.   |
| D9  | D9-release-202405280927.bmu             | Refine firmware.  |


---
## **Etcash ETHW ETHASH Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| E3       | E3_V540_0327.tar.gz           | 1.Extend the E3 miner life. 2.Fix corner case that E3 miner abnormal operation on ETC.    |
| E9  | 9-ETC-release-202305231828.bmu            | 1. Support ETC.2. This version of the firmware supports the E&F power mode of APW12. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.   |
| E9 Pro        | E9-Pro-ETC-release-202403211900.bmu           | Support ETC. 2. This version of the firmware supports the E&F power mode of APW12. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.   |

---
## **Equilhash Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| Z15      | Z15-user-800M-202007031139_6134.tar.gz            | Release the first version official Z15 firmware.    |
| Z11  | ANTMINER-Z11-fixed-718M-201910241109_4392.tar.gz             | 1.Update equihash Algorithm. 2.Enhance anti-virus capability. 3.Fix firmware package decompression issue.    |
| Z9        | Z9-fixed-500M-201905171645.tar.gz           | 1.Z9 security firmware.   |
| Z9 Mini        | Z9-Mini-fixed-500M-201905171644.tar.gz           | 1.Z9mini security firmware.   |
| Z15 Pro        | Z15-Pro-release-202309060712.bmu            | 1. Optimize the firmware. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.  |

---
## **Blake2B+SHA3 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| HS3      | HS3-release-202405280928.bmu             | 1. Optimize the firmware. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.    |

---
## **RandomX Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| X3      | X3-201811131315-0M.tar.gz              | Security Firmware, Fix some security vulnerabilities. |
| X5      | X5-CV-release-202406221844.bmu            | Support APW121215f power supply. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.    |

---
## **BTM Tensority Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| B7      | B7-xilinx-201910101434-500M-user-Update2UBI-NF_4196.tar.gz               | 1. Fix hashrate fluctuation in specail corner case.2. Enhance anti-virus capability.3. Support blacklist feature during updating firmware.4.You can't upgrade previous secure firmware after using this version.5. Fix decompression bug during firmware upgrade. |
| B3      | update_1000.tar.gz            | Firmware for improving hashrate，Do not power off during the upgrade！    |

---
## **SC Blake(2b) Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| R3      | R3-LTC-SIA-DASH-20180815.bin               | No Comments
| A3     | A3-201811131136-0M.tar.gz            | Security Firmware, Fix some security vulnerabilities.    |

---
## **CKB Eaglesong Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| K7      | K7-release-202403241334.bmu               | 1. Optimized firmware. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.
| K5     | K5-0-202005131621-sig_5872.tar.gz            | Support extranonce subscribe for nicehash pool. vulnerabilities.    |

---
## **ETH Graphics Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| G2      | G2-2018-07-22-clay11.9-img.rar               | G2-iso


---
## **KDA Blake2S Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| KA3      | KA3-release-202405280928.bmu                | Refine firmware. Please make sure the miner type and firmware type are the same before upgrading the miner firmware.


---
---
## **Tools**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| APMinerTool     | APMinerTool_V1.0.10.zip                | Monitor software for mining farms. Batch monitor and manage miners, scan LAN miners’ IP simultaneously, batch upgrade firmware and restart miners in bulk. |
|  BitminerTool    | BitmainMinerTool-bin.zip   | * This is binary files without installation framework.* Download and use it without installation * winXP may need install .NET framework at first . |
|  Ip Reporter   | IP Reporter.zip    | * This is binary files without installation framework.* Download and use it without installation * winXP may need install .NET framework at first . |
|  Image SD Card   | Tools and Instructions to Image SD card   | No Comment |
|  BitminerTool    | BitmainMinerTool-bin.zip   | * This is binary files without installation framework.* Download and use it without installation * winXP may need install .NET framework at first . |


---
---
## **ALPH+Blake3 Firmware**

| **Model**   | **Firmware Version** | **Release Notes**                 |
|-------------|-----------------------|------------------------------------|
| AL1    | AL1-CV-release-202408151805.bmu                 | ANTMINER AL1 initial firmware. Please make sure the miner type and firmware type are the same before upgrading the miner firmware |


---


## **Contributions**
If you have additional firmware versions or updates, feel free to contribute! Submit a pull request or reach out to us for assistance.

---

## **Disclaimer**
All firmware provided here is for informational and educational purposes. Please ensure compatibility with your devices before installation. We are not responsible for any issues arising from firmware updates.

---
