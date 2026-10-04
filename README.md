# Seeed Studio RS485 Extension Board — Reverse Engineering

A reverse-engineering and PCB recreation project of the **Seeed Studio RS485 Extension Board**.

The objective of this project is to understand the original board's electrical architecture, reproduce its schematic and PCB layout in KiCad, and generate a fabrication-ready design.

---

## 📌 Project Overview

This project involves analyzing the original Seeed Studio RS485 Extension Board and recreating its:

- Electrical schematic
- Power supply architecture
- RS485 communication interface
- Protection circuitry
- PCB layout
- Component footprints
- Manufacturing files

The recreated design is developed entirely in **KiCad**.

---

## 🎯 Objectives

- Reverse engineer the original RS485 extension board
- Understand the power and communication architecture
- Recreate the schematic in KiCad
- Select appropriate components and footprints
- Recreate the PCB layout
- Verify electrical connections and design rules
- Generate Gerber and drill files for PCB fabrication

---

## 🔧 Hardware

### Main Interfaces

- RS485 communication interface
- External power input
- Microcontroller/interface connection
- Protection circuitry

### Design Considerations

The design includes consideration for:

- RS485 differential signalling
- 120 Ω termination
- Fail-safe biasing
- Power regulation
- Reverse-polarity / transient protection
- Proper PCB grounding
- Controlled differential routing

---

## 🖥️ Software & Tools

| Tool | Purpose |
|------|---------|
| **KiCad** | Schematic and PCB design |
| **Git** | Version control |
| **GitHub** | Project hosting |
| **Datasheets** | Component verification |

---

## 📁 Repository Structure

```text
.
├── Home_Automation_v1.kicad_pro
├── Home_Automation_v1.kicad_sch
├── Home_Automation_v1.kicad_pcb
│
├── Home_Automation_v1.pretty/
│   └── Custom footprints
│
├── Final_Files/
│   ├── Gerber files
│   ├── Drill files
│   └── Gerber job file
│
└── README.md
