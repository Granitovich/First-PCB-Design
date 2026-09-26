# First PCB Design: STM32G0B1KET6 Custom Board

A custom PCB design built around the **STM32G0B1KET6** microcontroller. This project contains a complete hardware design for a minimal development board featuring power management, debugging interfaces, and a directly mounted TFT display.

<img width="640" height="976" alt="image" src="https://github.com/user-attachments/assets/0dbe2fa1-5f7f-4347-945e-5a17f299b345" />

## 📌 Features

* **Microcontroller:** STM32G0B1KET6 (ARM Cortex-M0+, 512 KB Flash, 144 KB RAM, up to 64 MHz).
* **Display Interface:** Dedicated pinout and footprint for mounting a TFT LCD module directly on top of the PCB.
* **Power Supply:** 
  * Linear voltage regulator (LDO) to step down input voltage to +3.3V.
  * Decoupling and bulk capacitors for stable operation and MCU noise suppression.
* **Programming & Debugging:** Standard SWD (Serial Wire Debug) header for ST-LINK / J-Link programmers.
* **System Essentials:**
  * Reset circuit with an onboard tactile button and debouncing.
  * Status LEDs for power indication


## 📁 Repository Structure

```text
├── # Schematics, PCB layout files, and KiCad/Altium project source
├── production/        # Production-ready Gerber files, drill files, and pick-and-place (CPL)
├── BOM/               # Bill of Materials (components list with manufacturer part numbers)
└── README.md          # Project documentation
