<div align="center">

# ⚡ MSPM0-CORE HARDWARE

**High-Performance ARM Cortex-M0+ PCB Platform**

[![KiCad Version](https://img.shields.io/badge/KiCad-v10.0-226BA5?style=for-the-badge&logo=kicad&logoColor=white)](https://kicad.org)[cite: 1]
[![MCU](https://img.shields.io/badge/MCU-TI_MSPM0G3507-CC0000?style=for-the-badge&logo=texas-instruments&logoColor=white)](#)[cite: 1]
[![Hardware Status](https://img.shields.io/badge/Status-Prototype_v1.0-FF8C00?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-CERN--OHL--P-008080?style=for-the-badge)](LICENSE)

---

</div>

> [!NOTE]
> **Project Overview**
> **MSPM0-Core** is an open-source, production-ready hardware development platform designed around the **Texas Instruments MSPM0G3507SPTR** microcontroller. Engineered in **KiCad 10.0**, this 2-layer layout optimizes high-frequency power decoupling and signal integrity in a compact form factor.

---

## 🎨 Board Specifications

| Feature | Engineering Parameter | Fabrication Detail |
| :--- | :--- | :--- |
| 🟢 **Substrate** | standard FR4 Core | **1.6mm Thickness** |
| 🔵 **Layer Stackup** | 2-Layer Layout (`Top` / `Bottom`)[cite: 1] | **0.035mm Outer Copper (1 oz)**[cite: 1] |
| 🟡 **Surface Finish** | Lead-Free HASL[cite: 1] | **RoHS Compliant** |
| 🟣 **Mechanical** | Dual Grounded Pad Holes[cite: 1] | **2x 3.2mm M3 Screws (`MH1`, `MH2`)**[cite: 1] |
| 🔴 **Design Tool** | KiCad EDA Workstation[cite: 1] | **`pcbnew` Generator v10.0**[cite: 1] |

---

## 🔌 Hardware Architecture & BOM

> [!IMPORTANT]
> Ensure all active voltage sources do not exceed `3.6V` max rating on power rails during bring-up.

```diff
+ COMPONENT SUMMARY (Core Layout)
+ ---------------------------------------------------------------------
! [U1]  MSPM0G3507SPTR   : ARM Cortex-M0+ Main Microcontroller[cite: 1]
+ [C12] 470nF 0603       : High-Frequency Decoupling Capacitor[cite: 1]
+ [C3]  10uF 0805        : Bulk Power Rail Filtering Capacitor[cite: 1]
- [MH1] M3 Grounded Hole : Structural Mount & Chassis Ground[cite: 1]
- [MH2] M3 Grounded Hole : Structural Mount & Chassis Ground[cite: 1]
