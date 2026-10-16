# USB-C Power Supply — Project Notes

## Project contents
This repository contains the native design files and exported manufacturing/design representations supplied for the USB-C power-supply project.

### Folder guide
- `hardware/source/easyeda/` — Original EasyEDA Pro `.epro2` project and library/document archives; keep these as editable source files.
- `hardware/BOM_USB-C_POWER_SUPPLY.csv` — Bill of Materials in CSV format.
- `hardware/exports/dxf/` — Schematic DXF drawing and original export archive.
- `hardware/exports/altium/` — Altium schematic (`.schdoc`) and PCB (`.pcbdoc`) exports plus original archive.
- `hardware/exports/pads/` — PADS schematic text, PCB ASCII file, associated `.c`/`.d` files, and original archive.

## BOM quick summary
- BOM line items: 14
- Total quantity across listed BOM rows: 34
- USB-C receptacle designator: `J1`
- USB-PD controller listed: `CH224A` (`U1`)
- 3.3 V regulator listed: `TPS70933DBVR` (`U2`)
- Analog multiplexer listed: `MC14051BDR2G` (`U3`)

The BOM is a design inventory, not a substitute for checking electrical ratings, footprints, component availability, or the current schematic before ordering or manufacturing.

## Suggested review before fabrication
1. Open the native project in a compatible EasyEDA Pro version and confirm the schematic and PCB are linked to the intended revision.
2. Run electrical-rule checks and PCB design-rule checks.
3. Verify USB-C CC/PD behavior, connector pin mapping, power-path limits, thermal performance, and protection components against the intended operating envelope.
4. Compare BOM designators and footprints with the schematic and PCB; confirm manufacturer/supplier part identifiers are current.
5. Inspect Gerber/drill outputs and board stack-up before sending the design to a fabricator. No Gerber/drill manufacturing package was included in the supplied files.

## Source and export handling
Original archives are retained alongside extracted copies for convenience. Filenames may contain spaces; preserve directory context when opening files in EDA software. The native `.epro2` files retain their embedded assets and document structure.

No README was added, as requested.
