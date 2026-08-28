# Bambu Studio Profile — iX14 Stand V2

The supplied Bambu Studio project contains all eight V2 printed parts arranged across four plates:

[`../bambu-studio-3mf/ix14_v2_stand_all_objects.3mf`](../bambu-studio-3mf/ix14_v2_stand_all_objects.3mf)

The project was prepared on a Bambu Lab H2C with an AMS HT and two AMS 2 Pro units. It may be adapted to another compatible Bambu printer, but always confirm the printer, plate, nozzle and filament assignments before slicing.

## Recommended material

- Bambu PETG-HF for all structural parts
- Dry PETG-HF at 65 °C for eight hours before printing
- Use the built-in **Bambu PETG HF** filament preset
- Textured PEI build plate

## Global process settings

Start with **0.20 mm Standard** and change only the following:

- 0.4 mm standard nozzle
- 5 wall loops
- 5 top shell layers
- 5 bottom shell layers
- 25% gyroid infill
- Standard speed
- No scaling or XY/hole compensation
- No ironing

## Four-plate project

| Plate | Contents | Notes |
| ---: | --- | --- |
| 1 | Both case bodies, both caps and both pivot stubs | Structural parts with per-object supports and the saved Auto brim setting |
| 2 | Replaceable detent ring | Print the detent pockets against the build plate |
| 3 | Single-color stand | No supports or brim |
| 4 | Multicolor stand with editable `LAWN-DART` text | Verify filament mapping, painted chamfers and text before slicing |

Only the filament slots used by the selected plate matter. The stored project uses Bambu PETG-HF for the active objects; unused AMS slots may still display other materials. Remap every active object to the intended PETG-HF spool before printing.

## Per-object settings

| Part | Orientation | Supports | Brim |
| --- | --- | --- | --- |
| Left and right case bodies | Supplied STL orientation | Tree (Auto), default style, build plate only | Auto brim, 5 mm width |
| Right detent pivot stub | Supplied STL orientation | Tree (Auto), default style, build plate only | Auto brim, 5 mm width |
| Left plain pivot stub | Lay on its side as arranged in the 3MF | Tree (Auto), default style, build plate only | Auto brim, 5 mm width |
| Left and right caps | Flip 180° so the joiner/mating face is on the build plate | None | Saved Auto setting; no manual brim required |
| Replaceable detent ring | Flat with detent pockets downward | None | None |
| Stand | Flat with sockets upward; rotate 90° on the build plate for improved torsional layer orientation | None | None |

> **Validated Plate 1 brim setting:** the global **Auto brim / 5 mm** setting stored in the 3MF completed a successful physical print of the full plate. Leave this setting as saved; no per-object 8 mm override is required.

## Multicolor stand

Plate 4 contains the paintable stand and an editable Bambu Studio text object.

1. Assign the stand body to the primary PETG-HF color.
2. Use the paint-bucket tool to fill the continuous chamfer faces with the accent color.
3. Edit or remove the `LAWN-DART` text as desired.
4. Assign the text to the accent-color PETG-HF spool.
5. Slice and inspect Preview to confirm that every intended chamfer and letter changes color cleanly.

Suggested color combinations:

- Deadpool: black body with red chamfers, text and detent ring
- Wolverine: black body with yellow chamfers, text and detent ring

## Pre-print checklist

- PETG-HF completed an eight-hour drying cycle
- Correct printer and textured PEI plate selected
- 0.4 mm nozzle selected
- Every active object mapped to PETG-HF
- Plate 1 retains the validated Auto brim / 5 mm setting
- Supports are build-plate-only on the four supported objects
- Detent ring pockets face downward
- Caps have their mating faces on the plate
- Stand sockets face upward
- Painted stand preview shows the intended colors
- First layers observed before leaving the printer unattended
