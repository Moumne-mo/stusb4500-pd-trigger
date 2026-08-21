# STUSB4500 USB-C PD Trigger Board

A compact, standalone USB Power Delivery (PD) sink trigger board based on the STUSB4500 controller[cite: 1, 4]. Automatically negotiates high-voltage profiles (up to 20V @ 3A+) using internal NVM in Auto-Run mode, eliminating the need for an external MCU during standard operation[cite: 1].

## Key Features
* **Input Interface:** USB-C Receptacle (USB4125)[cite: 4]
* **Output Paths:** 5.08mm Phoenix Screw Terminal Block & 2.54mm Pin Socket[cite: 4]
* **Power Path:** Cascoded PMOS high-side load switch with active discharge logic[cite: 1]
* **Protection:** Direct VDD bootstrapping via Schottky reverse protection diode[cite: 1, 4]
* **Configurability:** Breakout 4-pin I²C header (`Vdd_mcu`, `SCL`, `SDA`, `GND`) for NVM programming[cite: 1, 4]

## Board Specs
* **Layer Count:** 2-Layer PCB[cite: 1]
* **Trace Sizing:** >1.3mm VBUS path rated for continuous 3A delivery[cite: 1]
* **Target PDOs:** Customizable 5V, 9V, 15V, and 20V profiles

## Production Files
Ready-to-manufacture files are available in the `/gerbers` directory:
* `Gerber_STUSB4500_v1.0.zip` (Standard 1.6mm FR4, 1oz Cu specs)
* `BOM_STUSB4500.csv`

## License
Distributed under the CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P-2.0).
