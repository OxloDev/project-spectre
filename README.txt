Oxlo Project Spectre
====================

Overview
--------
Oxlo Project Spectre is a custom-built, portable hardware platform. It integrates a 2.8-inch TFT touchscreen (240x320), resistive touch input, microSD storage, audio output, 
and USB programming into a 3D-printed enclosure. The platform is designed as an independent, open hardware 
project for wireless research, embedded education, and rapid prototyping.

Key Features
------------
- ESP32 dual-core SoC (up to 240 MHz, Wi-Fi 802.11 b/g/n, Bluetooth v4.2 BR/EDR + BLE)
- 2.8-inch TFT LCD (JC2432A028N) with ILI9341V controller, 65K colors
- Resistive touch input via XPT2046-compatible controller
- microSD slot for logging and removable storage
- SC8002B-class audio amplifier
- RGB LED and photosensor for indicators and adaptive brightness
- DHT11 sensor header for temperature/humidity input
- BOOT and RESET tactile controls
- Power: accepts 5V input via Micro-USB or USB-C
- Typical operating current: ~115 mA
- Dimensions: 50 mm x 86 mm
- Enclosure: 3D-printed case with space for heat-set inserts

Enclosure Design
----------------
The custom enclosure was modeled for durability, portability, and modification. 
It includes screw-boss reinforcement, clearance for connectors, and cavities for 
heat-set threaded inserts to allow repeated assembly without damaging the plastic.

Credit: Enclosure design assistance by Julian (@3D-ish).

Files Provided
--------------
- Hardware design documentation and schematics
- Enclosure CAD models:
  * .3mf format for direct 3D printing
  * .f3d format (Fusion 360) for parametric editing
- LaTeX whitepaper (IEEE-style)
- README and reference documentation

Use Cases
---------
- Educational labs (MCU programming, Wi-Fi scanning, BLE exploration)
- Ethical security research with explicit authorization
- Rapid prototyping for IoT and embedded interfaces
- Portable user interfaces with logging capability

Acknowledgments
---------------
- Hardware design and documentation by Andrew Lopez
- Enclosure design assistance by Julian (@3D-ish)
- Thanks to mentors and peers for guidance and feedback

License
-------
This project is released under an open-source license (MIT).
Please review the LICENSE file for details.
