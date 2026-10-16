# Design Exports

This folder inventory describes the export formats supplied for the USB-C Power Supply project.

## Supplied formats
- **EasyEDA Pro**: native project/document archives (`.epro2`)
- **DXF**: schematic drawing export
- **Altium Designer**: schematic (`.SchDoc`) and PCB (`.PcbDoc`)
- **PADS**: schematic text export, PCB ASCII export, and library decal files
- **CSV**: bill of materials

## Suggested organization
Keep native source files separate from interchange exports so the original design can be edited without confusing it with generated files.

Recommended paths:
- `hardware/source/easyeda/`
- `hardware/exports/dxf/`
- `hardware/exports/altium/`
- `hardware/exports/pads/`
- `hardware/BOM_USB-C_POWER_SUPPLY.csv`

## Important
The export archives are not interchangeable with one another. Preserve original filenames and verify that schematic and PCB revisions correspond before using an export for manufacturing.
