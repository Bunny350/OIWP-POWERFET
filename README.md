# OIWP-POWERFET
Circuit switch made for 3D printers that could replace control board power switches. This project is a part of [OitswilliamV2 project](https://github.com/Bunny350/OitswilliamV2) and is currently in EA.

<img src="https://github.com/Bunny350/OIWP-POWERFET/blob/POWERFET-G2/Media/IMG_4872.jpeg" height=400 />

* [View BOM](https://docs.google.com/spreadsheets/d/1yWVHvXTZzoCHdqzoX9jaTu7xXFzNF9WBVVh8mdETd6c/edit?usp=sharing)
* [View computer & board compatibility list](https://docs.google.com/spreadsheets/d/1SwCBzh_ZEZ5wuVRrWKhemMHNiEeyeMa_t31kVStiC5g/edit?usp=sharing)

> [!CAUTION]
> POWERFET is not an SSR (solid-state relay) replacement, and it cannot handle high voltages where the grid use. It is intended for switching the printer control boards' power.

## User guide

You can check out [the user guide here](Manuals/powerfet-assembly-usage-guide.pdf).

### Nutshell wiring guide

The unit can be connected via XT30 connector or directly wired via 18AWG wires.

* The XT30-M connector is the power input.
* Whereas the XT30-F receptacle is the switched output.
* The JST-PH connector is used for the signal.
* The Molex Micro-Fit 3.0 connector is to bypass the switched power for the buck converter (and to the host computer).

## Technical specifications

| Type           | Spec  |
| -------------- | ----- |
| MOSFET pair    | 1     |
| Recoommended current | 15A |
| Max current    | 70A (30V), 50A (60V)|
| Signal power   | 3.3 to 20V (5V recommended, as low as 2.8V) |
| Max current from standby connector | 6A |
| Width          | 42mm |
| Depth          | 38mm |
| Thickness      | 10mm approx. (1.6mm PCB)  |

