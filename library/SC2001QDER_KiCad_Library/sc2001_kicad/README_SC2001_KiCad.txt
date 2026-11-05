SC2001QDER KiCad Library Package
================================

Part: Southchip SC2001QDER
LCSC/JLCPCB part: C603177
Package: QFN-32-EP, 4.0 x 4.0 mm, 0.40 mm pitch

Contents
--------
- SC2001QDER.kicad_sym                 Schematic symbol
- SC2001QDER.pretty/                   PCB footprint library
- SC2001QDER.3dshapes/                 STEP and WRL 3D models

Import into KiCad
-----------------
1. Extract the complete sc2001_kicad folder into your AI Max 120 project folder.
2. In Schematic Editor, open Preferences > Manage Symbol Libraries.
3. Select the Project Specific Libraries tab, click the folder icon, and select:
   SC2001QDER.kicad_sym
4. Set the library nickname to SC2001QDER if KiCad requests one.
5. Open Preferences > Manage Footprint Libraries.
6. Select Project Specific Libraries, click the folder icon, and select:
   SC2001QDER.pretty
7. Set the footprint-library nickname to SC2001QDER.
8. Press A in the schematic and search for SC2001QDER.

Important checks
----------------
- The exposed thermal/ground pad is pad 33.
- Keep the complete folder structure unchanged so the 3D-model path resolves.
- KiCad will assign the next free U reference automatically. The reference number
  does not affect operation.
- Verify every connection against the Southchip datasheet before fabrication.
