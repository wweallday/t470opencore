# T470 OpenCore Hackintosh (Ventura)

This repository contains the OpenCore EFI for the Lenovo ThinkPad T470 running macOS Ventura.

**Note:** I will no longer update this repository as I have upgraded to the X1 Carbon Gen 6, which better suits my workflow needs. I will continue using Hackintosh on the X1 Carbon and plan to provide updates on that model in a future repository.

### Important Information for T470 Users:
If you encounter issues such as system freezes or graphical glitches while using hardware acceleration, this could be due to the default 32MB DVMT-preallocation limitation. For optimal performance, consider modding the BIOS to increase the DVMT-prealloc to 64MB. 

I plan to modify the BIOS on the X1 Carbon Gen 6 once my **CH341a SPI Programmer** and **SOIC8 Clip** arrive. I will provide updates on this in the X1 Carbon Gen 6 repository.

For more information on how to mod the BIOS, please refer to this [video tutorial](https://youtu.be/ce7kqUEccUM).

### System Specifications

| Component  | Description                                |
|------------|--------------------------------------------|
| **CPU**    | Intel Core i5-6300U                        |
| **RAM**    | 16GB DDR4 2133MHz                          |
| **iGPU**   | Intel HD Graphics 520                      |
| **SSD**    | 256GB Kioxia BG5 (2280)                    |
| **Note**   | The original SSD that came with the laptop is not compatible with Hackintosh. |

### OpenCore Version
- **Version:** 1.0.1

### Features

- **What Works:**
  - Sleep functionality
  - HDMI output
  - USB (custom patching recommended)
  - Hardware Acceleration (with occasional graphical glitches)

- **What Doesn't Work:**
  - Thunderbolt
  - Hibernate

---

Currently, the system is mostly functional. However, hardware acceleration may occasionally result in glitches, such as display artifacts or graphical trails, which can typically be resolved by restarting the machine.

---

This revision organizes the content for clarity and professionalism, making it easier for users to understand the setup and known issues.