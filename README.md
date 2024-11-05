# HEOL60 - OL Keyboard with Hall Effect Switches

Forked from the (Moonboard Keyboard)[https://github.com/certainly1182/MoonBoard]. See the original README.md content at the bottom of this file.

Planned Tasks:
- Remove stabs; not needed for OLKB.
- Reduce PCB size to try to fit GH60 Keyboard PCB dimensions (285 * 9.45 cm). This will lower the cost of the keyboard case/plate.
- Reduce switch count from original MoonBoard 80 sensors/switches to HEOL60 70 switches.
- Remove OLED because of size constraints.
- Rename to HEOL60 (check LICENSE)
- TBD: Maintain top right encoder or use a switch instead?
- TBD: Move USB unified daughterboard schematics to the main PCB to keep GH60 top left USB positioning for cases. Feasible?

# MoonBoard - 75% ISO Keyboard with Hall Effect Sensors
This repository contains the hardware for a 75% ISO keyboard powered by hall effect sensors.<br />
[Click here for the firmware repository!](https://github.com/RephlexZero/qmk_firmware/tree/adc_testing)

## Features
- Hall Effect Sensors for configurable trigger point & "rapid trigger" functionality.
- Per-key RGB Lighting.
- USB connection uses [Unified Daughterboard](https://unified-daughterboard.github.io/).
- STM32 Microcontroller.
- Buzzer.
- 128x32 OLED Display.
- Rotary Encoder.
- Powered by QMK Firmware.

## Images
![top](https://certainly1182.github.io/MoonBoard/top.png)
![bottom](https://certainly1182.github.io/MoonBoard/bottom.png)
