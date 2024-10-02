# ECET 430 Solder Practice Board: Badge

This is a KiCad design to practice surface mount soldering.

## Purpose

Easy surface mount and a few through hole parts to practice working with a stencil, pick and place, and reflow soldering.

## Repo Layout

- `kicad` KiCad project with schematic, pcb layout
- `graphics` Graphic files for outline and silk development
- `fabrication` BOM and Gerbers for manufacturing
- `plots` Board renderings and schematic

## Usage

Practice board assembly by hand or with tools available.

## Design

The CMOS version of the popular 555 timer drives 8 LEDs. Configured as an astable multivibrator, its timing is determined by an RC combination.Four LEDs are active on the low portion of the output square wave, and four are set to be active on high or low based on solder jumper settings.

## Author

Written by Christian H, info@eeproto.com, 2024

## License

This work is available under the [Creative Commons Attribution-ShareAlike License 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) CC BY-NC-SA 4.0.
