# Breadboard Power Supply

A compact PCB breadboard power supply designed to provide clean, stable **3.3V and 5V** rails for prototyping. It features onboard regulation, switchable voltage outputs, and full compatibility with standard breadboards—making it ideal for hobbyists, students, and rapid development workflows.

---

## Features

- Selectable **3.3V / 5V** regulated outputs  
- Standard breadboard-friendly dual-rail layout  
- Barrel jack + toggle power switch  
- High-quality capacitors for stable operation  
- Compact through-hole design, easy to assemble  

---

## Bill of Materials (BOM)

|            | Reference Designator | DNP | Part Name                 | Manufacturer                                      | MPN                       | Qty | Footprint | Link | Notes | Price | Total Price |
|-----------:|----------------------|-----|---------------------------|---------------------------------------------------|----------------------------|----:|----------|------|-------|------:|------------:|
| 1 | J1 | No | Barrel Jack Switch | MPD (Memory Protection Devices) | EJ508B | 1 | THT | Link | 12V | 1.22 | 99.29 |
| 2 | S1 | No | Switch | E-Switch | EG1218 | 1 | THT | Link | — | 0.84 | — |
| 3 | C1 | No | Capacitor | TDK Corporation | FK20X7S1H106KR000 | 1 | THT | Link | 10uF | 1.04 | — |
| 4 | C2 | No | Capacitor | Murata Electronics | RCER72A105K2DBH03A | 1 | THT | Link | 1uF | 0.79 | — |
| 5 | C3 | No | Capacitor | Vishay Beyschlag / Draloric / BC Components | S104Z93Z5VL83L0R | 1 | THT | Link | 0.1uF | 2.49 | — |

You can view the **full BOM** spreadsheet using the link below:  

[Full BOM (Google Sheets)](https://docs.google.com/spreadsheets/d/1jAm3g67_ThedoSjCjsSPfpU4eJjXTLUuRc0bo3Tdfd8/edit?usp=sharing)

---

## Assembly

1. Solder all passive components first (capacitors, resistors if any).  
2. Install connectors and switches.  
3. Add voltage regulators and verify orientation.  
4. Test each rail individually before inserting into a breadboard.  

---

## Usage

1. Plug the module into your breadboard rails.  
2. Connect power via the barrel jack.  
3. Use the onboard switch to turn the supply on/off.

---

## License

This project is released under the **MIT License**. Feel free to use, modify, and share.
