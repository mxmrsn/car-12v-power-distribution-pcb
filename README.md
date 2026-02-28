# VW GTI 12V Distribution PCB

Simple 12V distribution block for multiple accessories.

## Contents
- `vw-gti-12v-distribution.kicad_sch`
- `vw-gti-12v-distribution.kicad_pcb`
- `PicoSpoX.pretty/PicoSpoX_1x02_P3.00mm_SMD.kicad_mod`
- `PicoSpoX.pretty/PicoSpoX_1x03_P3.00mm_SMD.kicad_mod`

## Notes
- Footprints are generic PicoSpoX-style 3.00 mm pitch SMD footprints. Verify against your exact Molex part.
- Inputs:
  - `IN_BATT` (+12V battery + GND)
  - `IN_ACC` (+12V accessory + GND)
- Outputs are 3-pin: `+12V_BATT`, `+12V_ACC`, `GND`
- PCB uses 1.2 mm traces for all nets. Adjust if you want thicker copper or different current headroom.
- Board outline is 120 mm x 160 mm. Resize as needed to fit near the fuse box.
