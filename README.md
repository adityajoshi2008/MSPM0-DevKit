# ⚡ MSPM0-Core

🌐 **ARM Cortex-M0+ • KiCad 10.0 • Open Source • PCB Hardware**

*Design. Route. Fabricate.*  
An open-source hardware breakout board engineered around the **Texas Instruments MSPM0G3507SPTR** microcontroller[cite: 1].

<p align="left">
  <img src="https://img.shields.io/badge/KiCad-v10.0-226BA5?style=flat-square&logo=kicad&logoColor=white" alt="KiCad">[cite: 1]
  <img src="https://img.shields.io/badge/MCU-TI__MSPM0G3507-CC0000?style=flat-square&logo=texas-instruments&logoColor=white" alt="MCU">[cite: 1]
  <img src="https://img.shields.io/badge/Layers-2--Layer-green?style=flat-square" alt="Layers">[cite: 1]
  <img src="https://img.shields.io/badge/Substrate-FR4-orange?style=flat-square" alt="FR4">[cite: 1]
  <img src="https://img.shields.io/badge/Status-Prototype__v1.0-FF8C00?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/License-CERN--OHL--P-008080?style=flat-square" alt="License">
</p>

<p align="left">
  <a href="https://kicanvas.org/?file=https://raw.githubusercontent.com/your-username/mspm0-core/main/hardware/mspm0-core.kicad_pcb">
    <img src="https://img.shields.io/badge/🎨_OPEN_WEB_PCB_VIEWER-2ea44f?style=for-the-badge&color=2ea44f" alt="Web Viewer">
  </a>
  <a href="https://your-username.github.io/mspm0-core/ibom.html">
    <img src="https://img.shields.io/badge/🔍_OPEN_INTERACTIVE_BOM-0366d6?style=for-the-badge&color=0366d6" alt="iBOM">
  </a>
</p>

---

### 🧭 Navigate

🚀 [Overview](#-overview) • 📐 [Board Specifications](#-board-specifications) • 🔌 [Hardware Architecture & BOM](#-hardware-architecture--bom) • 🚀 [Quick Start](#-quick-start) • 👏 [Credits & End Notes](#-credits--end-notes)

---

## 🚀 Overview

> **MSPM0-Core** is an open-source, production-ready hardware development platform designed around the **Texas Instruments MSPM0G3507SPTR** microcontroller[cite: 1]. Engineered using **KiCad 10.0** (`pcbnew` engine)[cite: 1], this 2-layer layout optimizes high-frequency power decoupling and signal integrity in a compact form factor[cite: 1].

---

## 📐 Board Specifications

| Feature | Engineering Parameter | Fabrication Detail |
| :--- | :--- | :--- |
| 🟢 **Substrate** | Standard FR4 Core[cite: 1] | **1.6mm Board Thickness**[cite: 1] |
| 🔵 **Layer Stackup** | 2-Layer Layout (`Top` / `Bottom`)[cite: 1] | **0.035mm Outer Copper (1 oz)**[cite: 1] |
| 🟡 **Surface Finish** | Lead-Free HASL[cite: 1] | **RoHS Compliant** |
| 🟣 **Mechanical** | Dual Grounded Pad Holes[cite: 1] | **2x 3.2mm M3 Screws (`MH1`, `MH2`)**[cite: 1] |
| 🔴 **Design Tool** | KiCad EDA Workstation[cite: 1] | **`pcbnew` Generator v10.0**[cite: 1] |

---

## 🔌 Hardware Architecture & BOM

> [!IMPORTANT]
> Ensure all active voltage sources do not exceed `3.6V` maximum rating on power rails during initial bring-up.

```diff
+ COMPONENT SUMMARY (Core Layout)
+ ---------------------------------------------------------------------
! [U1]  MSPM0G3507SPTR   : ARM Cortex-M0+ Main Microcontroller[cite: 1]
+ [C12] 470nF 0603       : High-Frequency Decoupling Capacitor[cite: 1]
+ [C3]  10uF 0805        : Bulk Power Rail Filtering Capacitor[cite: 1]
- [MH1] M3 Grounded Hole : Structural Mount & Chassis Ground[cite: 1]
- [MH2] M3 Grounded Hole : Structural Mount & Chassis Ground[cite: 1]
```

---

## 🚀 Quick Start

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/mspm0-core.git](https://github.com/your-username/mspm0-core.git)
   cd mspm0-core
   ```

2. **Open in KiCad:**
   Launch **KiCad 10.0**[cite: 1] and open the PCB layout directly:
   ```text
   hardware/mspm0-core.kicad_pcb[cite: 1]
   ```

---

## 👏 Credits & End Notes

### 👤 Author & Design Lead
* **Aditya Joshi**  
  *ECE Semiconductor*  
  **The NorthCap University**

---

### 🛠️ Hardware Ecosystem & Acknowledgments
* **Microcontroller Platform:** Texas Instruments (**MSPM0 Series**)[cite: 1]
* **EDA Tooling:** [KiCad EDA Suite](https://kicad.org) (v10.0 PCB Engine)[cite: 1]
* **Web Viewers:** [KiCanvas Engine](https://kicanvas.org) & [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom)

---

<div align="center">

**Distributed under the CERN Open Hardware Licence Version 2 (CERN-OHL-P)**  
*Crafted with precision for the Open-Source Semiconductor & Hardware Community.*

</div>
