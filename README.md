# Car 12V Power Distribution PCB

Simple 12V distribution block for supporting multiple interior (12V+)accessories. Note: Some accesories mentioned such as dashcam and charger have downstream 5V regulators. PicoSpox contacts are rated for 3A each with 24AWG wire.

## Contents
- `car-12v-power-distribution-pcb.kicad_sch`
- `car-12v-power-distribution-pcb.kicad_pcb`

## Notes
- Footprints are Molex PicoSpoX-style SMD footprints. 
- Inputs:
  - `12V+` (+12V battery)
  - `12V_ACC` (+12V accessory)
  - `GND` (ground)
- Output (3-pin): `+12V_BATT`, `+12V_ACC`, `GND`
- Output (4-pin): `+12V_BATT`, `+12V_ACC`, `+12V_HEADLIGHT`, `GND`
- PCB uses 40 mil traces for all nets. 
- Board outline is 1.5" x 2".
- 3D printed caddy will require strain relief and a mobile loop of wire to move with the opening/closing of the drawer.

## Schematic
![Schematic](docs/schematic-screenshot.png)

## Layout
![Layout](docs/pcb-screenshot.png)

## 3D
![3D](docs/3d-screenshot.png)
