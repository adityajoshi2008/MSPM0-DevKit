# ⚡ MSPM0-Core Hardware

Live, browser-based inspection tools and automated build outputs for the MSPM0-Core PCB.

---

## 🕹️ Interactive Web Viewers

| Interactive Tool | Description | Live Link |
| :--- | :--- | :--- |
| 🔍 **Interactive BOM** | Click components to highlight footprints and values on the PCB layout. | [**Open Interactive BOM ➔**](https://your-username.github.io/mspm0-core/ibom.html) |
| 📐 **3D / PCB Web Viewer** | Inspect layers, traces, and components directly in your browser using KiCanvas. | [**Launch Web Viewer ➔**](https://kicanvas.org/?file=https://raw.githubusercontent.com/your-username/mspm0-core/main/hardware/mspm0-core.kicad_pcb) |

---

## ⚙️ Automated Build Status (CI/CD)

![KiCad DRC Check](https://github.com/your-username/mspm0-core/actions/workflows/drc.yml/badge.svg)
![Gerber Build](https://github.com/your-username/mspm0-core/actions/workflows/gerbers.yml/badge.svg)

* **Design Rule Check (DRC):** Automatically runs in GitHub Actions on every commit to verify clearance and trace widths.
* **Auto-Generated Gerbers:** Downloading manual files is unnecessary; production gerber archives are automatically generated on every tag release.

---

## 📦 Quick Downloads

* 📥 [Download Latest Manufacturing Gerbers (.zip)](https://github.com/your-username/mspm0-core/releases/latest)
* 📄 [Download Schematic PDF](https://github.com/your-username/mspm0-core/releases/latest/download/schematic.pdf)
