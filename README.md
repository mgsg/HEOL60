# HEOL60 - OL Keyboard with Hall Effect Switches

Forked from the [Moonboard Keyboard](https://github.com/certainly1182/MoonBoard). See the original README.md file content [in this link](/README_MoonBoard.md).

## Planned Features

- 14x5 keys in ortholinear arrangement.
- All keys are 1u. If 2u is preferred (space, enter, backspace,...), the switch can simply be removed (no stabs though).
- Keycaps in uniform profile preferred (XDA,...).
- Maintain QMK Firmware compatibility.
- MIDI Support.
- 60% keyboard case (GH60) compatible... This will lower the cost of the keyboard case/plate.
- But more in the 65% / 75% keyboard class due to the extra space provided by ortholinear 1u keys (enter, capslock, backspace, modifier keys,...).

## Planned Tasks

- Rename to HEOL60 (check LICENSE/author).
- Remove some components from Kicad (schematics, PCB, BOM,...):
  - Stabs; not needed for OLKB since all keys are 1u.
  - OLED Display - No space for it (size constraints).  
  - TBD: Buzzer.

- Reduce switch count from original MoonBoard 80 sensors/switches to HEOL60 70 switches.
  - Reposition keys. (Beware open circuits!).
  - Reassign some of the keys to a different row (Change mux to be used).
  - Reduce PCB size to fit GH60 Keyboard PCB dimensions (285 * 9.45 cm). 

- Replace some basic components for cost/availability reasons:
  - TBC.
- TBD: Maintain top right encoder or use a switch instead?
- TBD: Move USB unified daughterboard schematics to the main PCB to keep GH60 top left USB positioning for cases. Feasible?


