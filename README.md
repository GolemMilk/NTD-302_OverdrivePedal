# NTD-302(Overdrive-Pedal)
Korg Nutube overdrive pedal

## License

NTD-302 is licensed under the CERN Open Hardware Licence Version 2 – Strongly Reciprocal (CERN-OHL-S v2).

© 2026 GolemMilk

Any derivative hardware must also be released under the same license.


# NTD-302

**NTD-302** is a high-voltage Nutube preamp module designed for guitar and bass applications.  
It features an onboard boost converter generating 30V for the Nutube plate supply and a dedicated 5V regulated heater supply.

The circuit is optimized for low-noise operation using star-ground topology and separated power domains.

## Features

- KORG Nutube 6P1 based preamp
- Onboard 30V boost converter (NJM2360)
- Onboard 5V heater regulator
- Star-ground architecture for ultra-low noise
- Compact stompbox-oriented PCB layout
- Designed for true bypass 3PDT switching

## Power

- Input: 9V DC (Center Negative)
- Internal rails:
  - 30V (plate)
  - 5V (heater)

## License

NTD-302 is licensed under the **CERN Open Hardware Licence Version 2 – Strongly Reciprocal (CERN-OHL-S v2)**.

© 2026 GolemMilk  
Any derivative hardware must also be released under the same license.

![2026-01-10 20 05の画像 2](https://github.com/user-attachments/assets/91695e07-f42f-4a5e-9dc7-f6c8ca5a7d07)
![2026-01-10 20 05の画像](https://github.com/user-attachments/assets/4b3addf2-38ee-4aec-8c8b-0cd521078e7b)
![IMG_2757](https://github.com/user-attachments/assets/b2d1404a-a9f0-44b6-bf8a-9a64f0d4b056)
![IMG_2756](https://github.com/user-attachments/assets/eb781937-6ccf-4e56-a6de-8b8028fcf7cd)
## Manufacturing Files

This repository contains all production-ready files required to build the NTD-302 pedal.

### Gerber Files (PCB Manufacturing)

The folder `pcb/` includes the complete Gerber data set for direct submission to PCB manufacturers such as:

- JLCPCB  
- PCBWay  
- Elecrow  
- Seeed Studio  

**File:**
- `NTD-302_v1.0_Gerber.zip`

These files can be uploaded directly to the manufacturer's quotation page without any modification.

---

### BOM (Bill of Materials)

The folder `bom/` contains the full Bill of Materials:

- `NTD-302_v1.0_BOM.csv`

This BOM can be used for:
- Manual parts ordering
- JLCPCB SMT Assembly (PCBA)
- Digikey / Mouser ordering

All reference designators match the KiCad schematic and PCB silkscreen.

---

### Pick & Place File (PCBA)

If you plan to use JLCPCB SMT Assembly, the Pick & Place file is also included:

- `NTD-302_v1.0_PickPlace.csv`

This file defines the exact SMT placement coordinates and rotation data.

---

All files are verified on a physically built and tested prototype.
[bom.csv](https://github.com/user-attachments/files/24546895/bom.csv)
[NTD-302.zip](https://github.com/user-attachments/files/24546897/NTD-302.zip)
