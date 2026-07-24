# Project Specification

## Project Title
Li-Ion Battery Protection & Voltage Monitoring PCB

---

## Objective

Design a compact, manufacturable PCB that protects a single-cell Li-Ion battery against reverse current while providing an analog battery voltage output suitable for connection to a microcontroller ADC.

---

## Functional Requirements

The PCB shall:

- Accept power from a 3.7 V Li-Ion battery.
- Protect the battery using a resettable PTC fuse.
- Prevent reverse current using a Schottky diode.
- Provide a protected battery output connector.
- Provide a battery voltage sense output.
- Filter ADC noise using an RC low-pass filter.
- Include a power indication LED.
- Include test points for battery ADC and ground.
- Be suitable for low-cost PCB manufacturing.

---

## Electrical Specifications

Input Voltage:
3.0–4.2 V DC

Nominal Voltage:
3.7 V

Maximum Current:
500 mA (PTC limited)

Protection:
Reverse Current Protection

Voltage Divider:
100 kΩ / 100 kΩ

ADC Output:
Battery Voltage / 2

Filter Capacitor:
100 nF

LED Current:
≈6–8 mA

---

## PCB Specifications

Board Size:
90 mm × 40 mm

Layers:
2

Copper Weight:
1 oz

Power Trace Width:
0.8 mm

Signal Trace Width:
0.25 mm

Ground Plane:
Front Copper Pour

Mounting:
18650 Battery Holder

---

## Design Constraints

- Use only commonly available components.
- Use KiCad.
- Pass DRC with zero errors.
- Generate standard Gerber files.
- Keep routing simple and manufacturable.

---

## Deliverables

✔ Schematic

✔ PCB Layout

✔ Gerber Files

✔ Drill Files

✔ BOM

✔ Documentation

✔ Manufacturing Package

✔ GitHub Repository