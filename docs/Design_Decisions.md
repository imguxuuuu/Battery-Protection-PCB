# Design Decisions

## Objective
Design a compact, manufacturable PCB for a 3.7 V Li-ion battery protection circuit.

## Decisions
- Board size: 90 × 40 mm
- 500 mA resettable PTC fuse
- 1N5819 Schottky diode for reverse-current protection
- 100k/100k voltage divider for ADC
- 100 nF ADC filter capacitor
- 0.8 mm power traces
- 0.25 mm signal traces
- Front-layer GND copper pour
- Test points for BAT_ADC and GND
- DRC passed with zero errors
