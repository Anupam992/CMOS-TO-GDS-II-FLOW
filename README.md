# Design, Analysis, and Implementation of an SRAM Architecture from CMOS to GDSII

Summer Internship Project — NSDCS Lab, IIT Indore

**Guide:** Dr. Santosh Kumar Vishvakarma, Professor, Dept. of Electrical Engineering, IIT Indore
**Mentor:** Mr. Shashank Singh Rawat, PhD Scholar, Dept. of Electrical Engineering, IIT Indore
**Submitted by:** Anupam Tiwari, Integrated M.Tech Fourth Year, School of Electronics, DAVV Indore

## Overview

This project covers the complete design and verification of an 8×8 SRAM memory system, from schematic-level 6T bit-cell design to a DRC/LVS-clean, tapeout-ready GDSII layout, implemented in Cadence Virtuoso using TSCL 180nm technology.

## Work Covered

- 6T SRAM bit-cell design and Hold/Read/Write functional verification
- Peripheral circuit design: 3×8 row decoder, YSR-controlled column mux, precharge circuit, differential sense amplifier, write driver
- 8×8 array implementation with peripheral integration and full-array simulation
- Physical layout: array stamping, contact sharing, PR boundary definition
- I/O pad ring integration and dummy region filling for density compliance
- DRC and LVS verification (clean/matched)
- GDSII export
- Performance characterization (power, delay, energy) and SNM/Monte Carlo stability analysis, pre- and post-layout

## Repository Contents

- Full report with detailed methodology, schematics, layouts, and results — see the report file in this repo
- Screenshots of each design stage (schematics, layouts, simulation waveforms, DRC/LVS results) included in the report for self-verification

## Notes

Refer to the report for step-by-step details, result tables (single cell and 8×8 array, pre-layout vs. post-layout), and Monte Carlo worst-case SNM values across process corners.
