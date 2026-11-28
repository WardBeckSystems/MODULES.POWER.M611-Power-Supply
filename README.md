# M611 Power Supply · Power

Ward-Beck Systems M611, 1982|15. Wiki page: [M611 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M611.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 17 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 7 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 10 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 14 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1982 - M611 - M611A Power Supply - 003.jpg](MANUALS/1982%20-%20M611%20-%20M611A%20Power%20Supply%20-%20003.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Output voltage** |  |
| &nbsp;&nbsp;Output 1 | 12 volts dc nominal _ Output 2: 20 volts dc nominal |
| &nbsp;&nbsp;Load current |  |
| &nbsp;&nbsp;Output 1 | 6 A maximum Output 2: 250 mA maximum. |
| &nbsp;&nbsp;Ripple |  |
| &nbsp;&nbsp;Output 1 | 2.5 volts P/p maximum_ Output 2: 1 volt P/p maximum |
| **Power requirements** | M611 115 volts ac, 60 Hz. nominal; prir mary strapping provided for 105V ac and 125V ac. M61IA 230 volts ac, 50Hz _ nominal; primary strapping provided for 210v ac and 250v ac. |
| **Ambient temperature** | 0 to 60 degrees Celsius |
| **Dimensions** | 5.1&quot; wide X 3.4&quot; high X 13.7&quot; deep (130 mm X 83 mm X 336 mm) |
| **Weight** | 8.5 Ib _ (3.85 kg) |

## Circuit description

From [1982 - M611 - M611A Power Supply - 004.jpg](MANUALS/1982%20-%20M611%20-%20M611A%20Power%20Supply%20-%20004.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M611/m6I1A Power Supply is designed to be used as a primary power supply for WBS TTL Logic Cards utilizing 5 V regulators_ One output delivers 12 volts at a maximum load of 6A _ A second output, rated at 20 volts, 250 mA is provided to supply a negative biasing voltage. Two power supply versions are available. The M611 operates from a 115v AC, 60 Hz power source while the M6IIA operates from 230v AC 50 Hz. Primary taps at the power transformer permit ac input variations of +/ -10% to be accommodated_ Two separate secondary winding in conjunction with two bridge rectifiers are utilized to provide complete electrical isolation between the two outputs. The primary and secondary fuses are conveniently located at the front panel _ A power ON/OFF switch and a LED indicator are also mounted on the front panel AMI connections are made via the MF6 frame receptacles_ The MF6 connectors are wired for the required ac and dc operating conditions of the M611/M6IIA module Modules may therefore be interchanged without affecting the operation of the system _ The module size of 5.1 X 3.4 X 13.7 inches allows three M611/M6IIA power supplies to be accommodated in one standard rack mounting (191 X 3.5H) MF6 equipment frame_ Perforations in the mounting frame and module assure adequate vertical ventilation by natural convection

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1zvZukZz2QWibvBeoCX-S8UBstcp5XM6t/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1zvZukZz2QWibvBeoCX-S8UBstcp5XM6t" width="240" alt="1982 - M611 - B 611-02-001 - M611-M611A POWER SUPPLY - SCHEMATIC.jpg"></a><br><sub>1982|15 · B 611-02-001 - M611-M611A POWER SUPPLY - SCHEMATIC · <a href="SCHEMATICS/1982%20-%20M611%20-%20B%20611-02-001%20-%20M611-M611A%20POWER%20SUPPLY%20-%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1y8kQyyqUHpWh1u59L3naES4Flvj396Bp/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1y8kQyyqUHpWh1u59L3naES4Flvj396Bp" width="240" alt="1982 - M611 - B 611-06-001 - M611-M611A POWER SUPPLY - COMPONENT LAYOUT.jpg"></a><br><sub>1982|15 · B 611-06-001 - M611-M611A POWER SUPPLY - COMPONENT LAYOUT · <a href="SCHEMATICS/1982%20-%20M611%20-%20B%20611-06-001%20-%20M611-M611A%20POWER%20SUPPLY%20-%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1988 - 3642-02-010 - POWER SUPPLIES SCHEMATIC - DRN DS - ENG PA - ISS 4 (2).jpg`, `1988 - 3642-02-010 - POWER SUPPLIES SCHEMATIC - DRN DS - ENG PA - ISS 4.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1s6_E61yz1p4EanQ8xgy9wsGap3VH6sXK/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1s6_E61yz1p4EanQ8xgy9wsGap3VH6sXK" width="240" alt="1982 - M611 - B 611-04-001 - M611-M611A POWER SUPPLY - CONNECTOR LAYOUT.jpg"></a><br><sub>1982|15 · B 611-04-001 - M611-M611A POWER SUPPLY - CONNECTOR LAYOUT · <a href="PINOUTS/1982%20-%20M611%20-%20B%20611-04-001%20-%20M611-M611A%20POWER%20SUPPLY%20-%20CONNECTOR%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-3 | AC TAP 105/210 V | strap |  | high |
| P1-4 | AC TAP 115/230 V | strap |  | high |
| P1-5 | AC TAP 125/250 V | strap |  | high |
| P1-6 | AC INPUT TAP COMMON (STRAP) | strap |  | high |
| P1-7 | AC LINE IN | power | AC INPUT | high |
| P1-16 | AC LINE IN | power | AC INPUT | high |
| P2-2 | -20 V UNREGULATED | power |  | high |
| P2-5 | +12 V UNREGULATED | power |  | high |
| P2-6 | +12 V UNREGULATED | power |  | high |
| P2-7 | +12 V UNREGULATED | power |  | high |
| P2-8 | +12 V UNREGULATED | power |  | high |
| P2-10 | +20 V UNREGULATED | power |  | high |
| P2-12 | CHASSIS GROUND | ground |  | high |
| P2-13 | 12 V COMMON | ground |  | high |
| P2-14 | 12 V COMMON | ground |  | high |
| P2-15 | 12 V COMMON | ground |  | high |
| P2-16 | 12 V COMMON | ground |  | high |

**Straps:** M611 MAINS TAP: P1-6 P1-5 · M611A MAINS TAP: P1-6 P1-5

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1bxxWOQqkPw09GwRexwnSvFaGSF9cjn6c/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1bxxWOQqkPw09GwRexwnSvFaGSF9cjn6c" width="240" alt="1982 - M611 - M611A Power Supply - 000.jpg"></a><br><sub>1982|15 · M611A Power Supply - 000</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1V_x4s5u22zfYZsY_qNvhLZAgchTh3BZC/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1V_x4s5u22zfYZsY_qNvhLZAgchTh3BZC" width="240" alt="1982 - M611 - M611A Power Supply - 001.jpg"></a><br><sub>1982|15 · M611A Power Supply - 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1Wel3g0BjLCjT1lyZi49P5S1RyafJC-8g/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1Wel3g0BjLCjT1lyZi49P5S1RyafJC-8g" width="240" alt="1982 - M611 - M611A Power Supply - 003.jpg"></a><br><sub>1982|15 · M611A Power Supply - 003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1Zv56dxUpU-v2UqIizoNqUo44yHJL91aU/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1Zv56dxUpU-v2UqIizoNqUo44yHJL91aU" width="240" alt="1982 - M611 - M611A Power Supply - 004.jpg"></a><br><sub>1982|15 · M611A Power Supply - 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1sNZ3i9g_7JzcQ98NSVVz_ww0l6M3sP5R/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1sNZ3i9g_7JzcQ98NSVVz_ww0l6M3sP5R" width="240" alt="1982 - M611 - M611A Power Supply - 005.jpg"></a><br><sub>1982|15 · M611A Power Supply - 005</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1in14__dEF2RKhg8-1PvSZtGpeHtEVdd7/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1in14__dEF2RKhg8-1PvSZtGpeHtEVdd7" width="240" alt="1982 - M611 - TABLE OF CONTENTS M611-M611A POWER SUPPLY.jpg"></a><br><sub>1982|15 · TABLE OF CONTENTS M611-M611A POWER SUPPLY</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZTRBMFRmN1FMeGM/view?resourcekey=0-Ki-cItFZyd5mClfrgAVYTA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZTRBMFRmN1FMeGM&resourcekey=0-Ki-cItFZyd5mClfrgAVYTA" width="240" alt="19xx - M611 - DOC - 005.jpg"></a><br><sub>19xx - M611 - DOC - 005</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKamx6SzBqeWx2V28/view?resourcekey=0-Qk_mzl4u7t3c2eZoRsDliw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKamx6SzBqeWx2V28&resourcekey=0-Qk_mzl4u7t3c2eZoRsDliw" width="240" alt="19xx - M611 - DOC - 012.jpg"></a><br><sub>19xx - M611 - DOC - 012</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcktuT3phVlllM0k/view?resourcekey=0-54T6H43B01J3csvOTc_ydA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcktuT3phVlllM0k&resourcekey=0-54T6H43B01J3csvOTc_ydA" width="240" alt="19xx - M611 - DOC - 033.jpg"></a><br><sub>19xx - M611 - DOC - 033</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1982 - M611 - B 611-02-001 - M611-M611A POWER SUPPLY - SCHEMATIC.kicad_sch](KICAD/1982%20-%20M611%20-%20B%20611-02-001%20-%20M611-M611A%20POWER%20SUPPLY%20-%20SCHEMATIC.kicad_sch)
- [1988 - 3642-02-010 - POWER SUPPLIES SCHEMATIC - DRN DS - ENG PA - ISS 4 (2).kicad_sch](KICAD/1988%20-%203642-02-010%20-%20POWER%20SUPPLIES%20SCHEMATIC%20-%20DRN%20DS%20-%20ENG%20PA%20-%20ISS%204%20(2).kicad_sch)
- [1988 - 3642-02-010 - POWER SUPPLIES SCHEMATIC - DRN DS - ENG PA - ISS 4.kicad_sch](KICAD/1988%20-%203642-02-010%20-%20POWER%20SUPPLIES%20SCHEMATIC%20-%20DRN%20DS%20-%20ENG%20PA%20-%20ISS%204.kicad_sch)
- [M611.kicad_sym](KICAD/M611.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
