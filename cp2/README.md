# Course Project 2 - Layout and Post-Layout Verification

This folder contains the documentation for Course Project 2 of EE 618: CMOS Analog VLSI Design.

## Contents

- **22B3908_EE618_CP2.tex** - LaTeX report documenting the layout implementation and post-layout verification (PEX) of a two-stage NMOS-input differential OTA with RC compensation
- **images/** - Folder containing simulation results and verification screenshots from post-layout analysis

## Project Overview

This project focuses on the physical layout implementation and verification of an Operational Transconductance Amplifier (OTA) designed in Course Project 1. The design uses RC compensation technique for a two-stage differential amplifier with single-ended output.

### Design Specifications

- DC gain ≥ 50 dB
- Unity gain frequency ≥ 100 MHz
- Output voltage swing ≈ 0.6 Vpp ± 10 mV
- Slew rate ≥ 100 V/µs
- Phase margin: 60° ≤ PM ≤ 75°
- Power consumption ≤ 0.3 mW
- Supply voltage VDD = 1.2 V
- Load capacitance CL = 1 pF

### Layout Features

- Layout area: 22.5 µm × 20.4 µm
- Common-centroid techniques for matched devices
- Parasitic extraction using Quantus QRC
- Full DRC and LVS verification

## Images

The `images/` folder contains 28 screenshots documenting:

- DRC and LVS verification results
- PEX extraction summary
- Final OTA layout
- DC operating point analysis (schematic vs. PEX)
- Stability analysis (Bode plots, phase margin)
- AC analysis (differential gain, common-mode gain, CMRR)
- Transient analysis (sinusoidal input, step response, slew rate)
- Noise analysis (input-referred noise PSD)
- Comparison plots between schematic and post-layout results

## Related Files

For design calculations and schematic-level analysis, refer to the `../cp1/` folder which contains:
- Design specifications and hand calculations
- Schematic simulation results across process corners (TT, FF, SS)
- Initial design values and optimization insights

---

**Student:** Bhuvansh Goyal  
**Roll Number:** 22B3908  
**Instructor:** Prof. Rajesh Zele  
**Submission Date:** 17 Nov 2025
