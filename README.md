# Radar Sensor PCB – uRAD Based Compact Board

> Custom PCB design for integrating a radar sensor using the uRAD technology stack. Includes support passives, antenna feedlines, and power conditioning components.

---

## 📦 Files Included

- `Radar_Gerber/`: Gerber files for PCB manufacturing.
- `Radar_bom.csv`: Full Bill of Materials (BOM) with part details.
- `radar.sch.kicad_sch`: KiCad schematic source file.

---

## 🧩 Overview

- **Sensor Interface**: Designed for radar modules (e.g., uRAD)
- **Power Input**: Onboard regulation and filtering
- **Form Factor**: 2-layer PCB, compact and easily embeddable
- **Use Case**: Experimental radar projects, embedded sensing, motion detection

---

## 🔩 Components Snapshot

Here’s a quick glance at a few components used (full list in BOM file):

| Reference | Value       | Footprint                      | Quantity |
|-----------|-------------|--------------------------------|----------|
| C1, C14   | Capacitors  | 0603 / 0805 SMD                | Various  |
| D1        | Red LED     | APTD1608SURCK                  | 1        |
| ADDR0     | Jumper      | TSW-103-07-X-SMT               | 1        |
| U1        | uRAD SoC    | Custom/QFN package             | 1        |
| ...       | ...         | ...                            | ...      |

---

## 🛠️ How to Use

1. **Order PCB**: Use the files in `Radar_Gerber/`.
2. **Procure Parts**: Refer to `Radar_bom.csv`.
3. **Assemble**: Use reflow or hot-air soldering for SMD components.
4. **Integrate**: Wire up the radar interface and start testing with your embedded firmware or host computer.

---

## 📎 License

This hardware design is released under the [CERN-OHL-W v2](https://ohwr.org/project/cernohl/wikis/home) open hardware license.

---
