Solar Battery Charger Module (CN3065)

This is the power charging submodule of the **Modular IoT Sensor Node**, designed to safely and efficiently charge a single-cell LiPo battery using a solar panel. The module uses the CN3065 linear charging IC.

## Features

- Charges 3.7V Li-ion/LiPo batteries from a solar panel (4.5–6V)
- Current-limited charging via an external resistor
- Visual indicators for charging and charge completion
- Compact and easy to integrate into larger sensor systems

---

## Files

| File Name                    | Description                               |
|-----------------------------|-------------------------------------------|
| `Solar Battery Charger.SchDoc`       | Altium schematic of the module            |
| `Solar Battery Charger.PcbDoc`       | Altium PCB layout                         |
| `Schematic_preview.png` | Schematic preview image    |
| `project_outputs/`          | Gerber, drill files, BOM, etc.            |

---

## Schematic Overview

Key components and functionality:

- **CN3065**: Core charging IC with status outputs
- **D1 (Red LED)**: Indicates charging is in progress
- **D2 (Green LED)**: Indicates charge is complete
- **R2 (10kΩ)**: Sets charge current (~100mA)
- **C1, C2**: Input/output smoothing capacitors
- **P1, P2**: Solar panel input & battery connector

![Schematic](schematic_preview.png)

> You can adjust charging current by changing R2 (R2 = 1800/ I(charging))


## Integration Tips

- Connect the battery output to your system’s 3.3V LDO regulator
- Optionally monitor battery voltage with an ADC pin
- Keep VIN between 4.5V and 6V for optimal solar charging

---

## Project Status

- [x] Schematic complete
- [x] PCB layout done
- [x] Testing & validation

---

## Resources

- [CN3065 Datasheet](https://datasheet.lcsc.com/szlcsc/1912111433_CN3165_C22908.pdf) 

