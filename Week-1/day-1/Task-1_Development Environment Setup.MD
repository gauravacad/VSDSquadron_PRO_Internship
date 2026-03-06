# Task-1 Installation and Settings

## Board Overview

The VSDSquadron PRO RISC-V development board features a RISC-V SoC with the following capabilities:

- 48-lead 6x6 QFN package  
- On-board 16 MHz crystal  
- 19 Digital IO pins and 9 PWM pins  
- 2 UART and 1 I2C  
- Dedicated Quad-SPI (QSPI) flash interface  
- 32 Mbit Off-Chip (ISSI SPI Flash)  
- USB-C type for Program, Debug, and Serial Communication

## System Requirements:
- Windows 7 or later.
- Windows XP and Windows Vista are NO LONGER SUPPORTED

## Download drivers
- Download Zadig from https://zadig.akeo.ie/
- Open Zadig from the location of the folder where you downloaded it. Click on ”Options” tab and select ”List All Devices”. Then select ”Dual RS-232-HS (Interface 0) as represented by 2 in Figure 1. Choose ”libusb-win32” software as represented by 3 in Figure 1. Finally click on
”Install or Reinstall Driver” as represented by 4 in same Figure 1

<div align="center">
<img width="500" height="500" alt="Screenshot 2026-03-06 104148" src="https://github.com/user-attachments/assets/6eb584d9-4837-45b4-aa67-a5e211f807d1" />
<figcaption>Figure 1: Steps to install driver using Zadig</figcaption>
</div>

## Download VSDSquadronPRO Tar GZ file
- Download Freedom Studio, preferably on the D: drive or C: drive, from this link.
- Right click on VSDSquadronPRO.tar and click on ”Extract All”, as shown in Figure 5.
- Select the destination folder and click on ”Extract”.
<div align="center">
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/3756b8bd-791d-4b3d-9516-5624012071ca" />
</div>

## Powering Up the Board
Connect the Type-C end of USB cable to the board as shown in below image and refer to Installation and Settings for programming the board.
<img width="300" height="300" alt="Screenshot 2026-03-06 102639" src="https://github.com/user-attachments/assets/a6573829-e9dc-4e0c-8147-ac8016100267" />

## Verification of Serial Communication with VSD Squadron Pro
Detecting the Serial Port:
1. Connect the VSD Squadron Pro board to your PC via USB.
2. Open Device Manager (Win + X → **Device Manager`).
3. Expand Ports (COM & LPT). You should see a new COM port appear, e.g., USB Serial Device (COM5).

