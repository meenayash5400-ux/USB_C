# USB-C Power Supply — Project Overview

## Project files
This repository contains project documentation and design exports for the USB-C POWER SUPPLY project.

## Design source
- Native project format: EasyEDA Pro project (`.epro2`)
- Native document format: EasyEDA Pro document (`.epro2`)
- Schematic export: DXF
- PCB/schematic exports: Altium Designer and PADS formats
- Bill of Materials (BOM): CSV

## Main components listed in the BOM
- CH224A USB Power Delivery controller
- TPS70933 3.3 V regulator
- MC14051BDR2G analog multiplexer
- USB Type-C 16-pin connector
- 2N7002T MOSFET
- Input/output connectors, LEDs, resistors, capacitors, and diodes

## Notes
- Open native `.epro2` files with a compatible EasyEDA Pro version.
- Altium `.SchDoc` / `.PcbDoc` files require compatible Altium software.
- PADS ASCII exports can be opened/imported with compatible PADS tools.
- DXF is a schematic drawing export; it is not the native editable schematic.
- Verify the design against the original schematic, component datasheets, and intended USB-PD voltage/current ratings before manufacturing. This file is an inventory, not an electrical safety certification.
