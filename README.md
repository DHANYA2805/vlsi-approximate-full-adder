# Implementation and Performance Comparison of CMOS FA and Approximate Full Adder

## 📋 Project Overview

This project implements and compares the performance of a **Static CMOS Full Adder** with **Approximate Full Adders (LCAFA3 & LCAFA4)** in VLSI design. Approximate computing techniques are applied to reduce power consumption and delay while maintaining acceptable accuracy for error-tolerant applications such as image processing and machine learning.

## 👥 Team Members

| Name | Roll Number |
|------|-------------|
| Nithujaa J | 23BEC1354 |
| Dhanya S | 23BEC1432 |
| Monish Krishnanand | 23BEC1464 |
| Rajana Pranav | 23BEC1359 |

**Submitted to:** Dr. G Lakshmi Priya

---

## 🎯 Objective

To implement a Static CMOS Full Adder and obtain the respective truth table and performance analysis values, then compare them with Approximate Full Adder (LCAFA3 & LCAFA4) values.

## 📖 Theory

### Static CMOS Full Adder
A full adder is a combinational logic circuit that adds three 1-bit binary numbers. It includes the carry-in, making it useful for multi-bit binary addition (8-bit or 16-bit applications). It has 3 inputs and produces **Sum** and **Carry** as outputs.

### Approximate Full Adder
An approximate full adder intentionally sacrifices some accuracy to gain improvements in:
- ⚡ **Power consumption**
- 🚀 **Speed (lower delay)**
- 📐 **Area (fewer transistors)**

In modern applications like image processing, machine learning, IoT, and signal processing, perfect accuracy isn't always necessary. Using simpler, faster, or lower-power hardware can save significant resources while keeping errors within acceptable margins.

---

## 🔬 Digital Assignments

### DA-1: Static CMOS Full Adder
- Circuit design and truth table verification
- Circuit schematic implementation
- Output waveform simulation
- Delay and power analysis

**Key observations:**
- Optimized XOR gates for reduced delay
- Compact carry logic with no redundant inverters
- Validated output waveforms matching expected truth table

### DA-2: Approximate Full Adder Design
- **LCAFA3** — Low Complexity Approximate Full Adder (variant 3)
- **LCAFA4** — Low Complexity Approximate Full Adder (variant 4)
- Circuit design, truth tables, and simulation waveforms for both variants

### DA-3: Performance Analysis
- Power and delay measurement of LCAFA3 & LCAFA4
- Comparative study with Static CMOS Full Adder

---

## 📊 Key Findings

| Parameter | Static CMOS FA | LCAFA3 | LCAFA4 |
|-----------|---------------|--------|--------|
| **Power** | Higher | Significantly Lower | Significantly Lower |
| **Accuracy** | 100% Accurate | Approximate | Approximate |
| **Transistor Count** | More | Fewer | Fewer |
| **Delay** | Higher | Lower | Lower |

### Conclusions

1. **Power Consumption:** LCAFA3 and LCAFA4 consume exponentially less power than the Static CMOS design.
2. **Accuracy:** Static CMOS design is the most accurate compared to LCAFA3 & LCAFA4.
3. **Applications:**
   - **Static CMOS FA** → Accuracy-critical systems (microprocessors, microcontrollers)
   - **LCAFA3 & LCAFA4** → Error-tolerant applications (image processing, ML, IoT)

---

## 📂 Repository Structure

```
├── docs/
│   ├── reference_paper.pdf        # Research paper on approximate full adders in CMOS
│   ├── vlsi_report.pdf            # VLSI implementation report with schematics & analysis
│   └── vlsi_presentation.pdf      # Detailed presentation covering DA1, DA2, DA3
└── README.md                      # This file
```

## 📄 References

- Research on approximate full adders in CMOS technology
- Low Complexity Approximate Full Adder designs (LCAFA3, LCAFA4)
- Performance metrics: Power consumption, Propagation delay, PSNR, SSIM, Error Distance (ED), Error Rate (ER)

## 📝 License

This project is part of academic coursework at VIT University.
