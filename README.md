# High-resolution multislope ADC - MiDi

KiCad 10 project for the MiDi build of the multislope ADC developed from Kleinstein's design and Rerouter's PCB. The schematic documents the original circuit before the 2026 modifications, as saved on 18 October 2026.

## Project and downloads

Open [the KiCad project](High%20Resolution%20Multislope%20converter-modified%20rev%202.kicad_pro) with KiCad 10 and the standard KiCad symbol, footprint and 3D model libraries. Project-specific symbols are included and use relative library paths. Exports were generated with KiCad 10.0.7.

| File | Contents |
| --- | --- |
| [Schematic PDF](docs/Schematic.pdf) | Current schematic, white background and KiCad Classic colours |
| [Schematic PNG](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/Schematic.png) | Full-page preview |
| [Complete schematic BOM](bom/BOM-all.csv) | 231 positions, including 15 marked DNP |
| [BOM excluding DNP](bom/BOM-fitted.csv) | 216 positions, following the saved schematic flags |
| [Interactive PCB viewer](https://htmlpreview.github.io/?https://github.com/Multi-slope-ADC/PCB/blob/MiDi/bom/ibom.html) | Board footprints, values and routing; [download HTML](bom/ibom.html) to open locally |
| [PCB PDF](docs/PCB.pdf) | Colour copper and paste layer plots with silkscreen and drawing frame |
| [Gerber and drill files](gerber_to_order/) | Direct exports of the preserved PCB; [ZIP](gerber_to_order/MiDi-Gerbers.zip) |

## Schematic

![Current MiDi schematic](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/Schematic.png)

## PCB views

![PCB front plot](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/PCB-front.png)

![PCB back plot](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/PCB-back.png)

![PCB top, angled](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/PCB-3D-top-angled.png)

![PCB top](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/PCB-3D-top.png)

![PCB bottom](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/PCB-3D-bottom.png)

![PCB top, perspective](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/PCB-3D-top-perspective.png)

## Assembled board

![MiDi assembled board, 7 October 2026](https://raw.githubusercontent.com/Multi-slope-ADC/PCB/refs/heads/MiDi/docs/20261007_220509048.jpg)

## Background and credits

- Original design discussion: [DIY high-resolution multi-slope converter](https://www.eevblog.com/forum/metrology/diy-high-resolution-multi-slope-converter/).
- Related design discussion: [Multislope design](https://www.eevblog.com/forum/projects/multislope-design/).
- PCB ancestry: [Rerouter/Multislope-ADC-PCB](https://github.com/Rerouter/Multislope-ADC-PCB).
- Interactive PCB viewer generated with [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom).
