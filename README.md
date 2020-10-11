# Power switching system

Realization of a power supply board with four switches for switching between several power sources.

## Check list

- [x] Analysis of the specifications
- [x] Choice of components and case
- [x] Order components
- [x] Validation of the schematic
- [x] Definition of the PCB outline from the internal dimensions of the case
- [x] Validate component placement and lock footprints
- [x] Routing validation
- [x] Screen printing validation
- [x] Generating design files
- [ ] Assembly of components on the PCB
- [ ] Functional test of the electronic board and validation of the specifications
- [ ] Integration of the electronic card in the case
- [ ] Final test and document review
- [ ] Device delivery

---

## Tools used

### KiCad

[KiCad EDA - Schematic Capture & PCB Design Software](https://kicad-pcb.org/), version: 5.1.7

Open source EDA / electronics CAD software for Windows, macOS and Linux.

### FreeCAD - 3D parametric modeler

[FreeCAD](https://www.freecadweb.org/?lang=fr), version: 0.18.4

## Electrical diagram

![schematic-switching-external-pwr-supplies](Docs/schematic-switching-external-pwr-supplies.png)

---

## Integration into the housing

[Hammond 1599HGYBAT](https://www.hammfg.com/part/1599HGYBAT)

Enclosure - plastic, size: 220 mm x 110 mm x 44 mm (L x W x H)

## PCB outline, size: 213,00 mm x 96,60 mm (L x W), from FreeCAD

<img src="Docs/pcb-contour-layer.png" width="800">

## Component placement and silk screen

|                        Placement                         |                      Silk screen                      |
| :------------------------------------------------------: | :---------------------------------------------------: |
| <img src="Docs/pcb-component-placement.png" width="400"> | <img src="Docs/pcb-front-silkscreen.png" width="400"> |
|           F.Mask + Edge.Cuts + F.CrtYd + F.Fab           |                  F.SilkS + Edge.Cuts                  |

|                      Placement and Silk screen                      |
| :-----------------------------------------------------------------: |
| <img src="Docs/pcb-component-placement-silkscreen.png" width="800"> |
|           F.SilkS + F.Mask + Edge.Cuts + F.CrtYd + F.Fab            |

<!--
### Component placement

<img src="Docs/pcb-component-placement.png" width="800">

F.Mask + Edge.Cuts + F.CrtYd + F.Fab

### Silk screen

<img src="Docs/pcb-front-silkscreen.png" width="800">

F.SilkS + Edge.Cuts
-->

## Front Copper layer

<!-- ![pcb-front-copper-layer](Docs/pcb-front-copper-layer.png) -->
<img src="Docs/pcb-front-copper-layer.png" width="900">

## Back Copper layer

<!-- ![pcb-back-copper-layer](Docs/pcb-back-copper-layer.png) -->
<img src="Docs/pcb-back-copper-layer.png" width="900">

## 3D rendering

<img src="Docs/pcb-component-placement-3d.png" width="800">

## Integration of the electronic card in the case with the [FreeCAD](https://www.freecadweb.org) software

<img src="MECA/mechanical-integration.bmp" width="800">

## Sectional view

<img src="MECA/mechanical-integration-sectional-view-1.png" width="800">

---

## [CHANGELOG](CHANGELOG.md)
