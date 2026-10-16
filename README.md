# Ender-3-NG-from-scratch

A custom 3D printer build: CoreXY motion, enclosed frame, direct drive extruder and a Klipper-based electronics setup. This repository contains the bill of materials (BOM) and build notes for my version of the printer.

NOTE:this repo was created to help people building this printer without the need for an existing ender 3 version 

> **Credit:** This build is based on the original design by **RH3D** ([@radkoko on Printables](https://www.printables.com/@radkoko)): Ender 3 NG coreXY conversion, [link to the model page]. All design work, STL files and the Configurator belong to RH3D. This repository only documents my own parts list and build.

## What is in this repo

| File | Description |
|------|-------------|
| `BOM.csv` | Full bill of materials, grouped by category |
| `README.md` | This ur reading now|

## Overview

- **Motion:** CoreXY gantry with NEMA 17 steppers (2.5 A on the gantry), GT2 belts, 8 mm rods for X/Y, 12 mm rods and T8 leadscrews for Z (single or triple Z)
- **Frame and enclosure:** V-slot extrusions (4040, 2040, 2020) with polycarbonate panels
- **Electronics:** 32-bit mainboard (BTT SKR Mini E3 or Octopus), 24 V power supply (350 W or higher), Klipper recommended
- **Tool head:** direct drive extruder (BMG or Orbiter) with a hotend of your choice (Volcano, Dragon, etc.)

## Bill of materials

The full list is in [`BOM.csv`](BOM.csv). It is split into four categories:

1. Frame and enclosure
2. Motion system
3. Electronics and tool head
4. Hardware and fasteners

Each row has a quantity and a notes column. Where a quantity depends on your configuration (single or triple Z, number of fans), the range is written in the notes. The `Unit Price` and `Supplier/Link` columns are empty so you can fill them in with your own sources.
!! you can get the configurator file from RH3D web site : rh3d.xyz

## Printed parts

A substantial number of parts must be printed from the official STL files on Printables. The Configurator generates a printed parts list tailored to your configuration. Print with a well-calibrated printer and the recommended filament (ABS, ASA or PETG for structural parts).

## Build notes

- Check the frame dimensions against your chosen configuration before cutting or ordering extrusions.
- Heat inserts (M3 and M5) are used throughout the printed parts, so order enough of them.
- Fastener counts in the BOM are for the full build. Order a few extra of the small sizes (M3).

## Contributing

Found a mistake in the BOM or have a better part suggestion? Open an issue or a pull request.

## License and attribution

The original design is by RH3D and is shared under the license shown on its Printables model page: [CC BY-NC-SA 4.0]. Anyone building from this repo must follow that license and credit RH3D.

This repository does not include or redistribute RH3D's STL files. Download them from the original model page :
https://www.printables.com/@radkoko

The BOM and documentation in this repo (my own work) are released under: [CC BY-NC-SA 4.0].

## Credits

- Original design, STL files and Configurator: RH3D, https://www.printables.com/@radkoko
- BOM and documentation: [safi Toumi] from SAFI's LAB 
