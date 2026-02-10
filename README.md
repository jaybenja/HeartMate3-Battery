# Open Source HeartMate 3 Battery Research

> **⚠️ SAFETY NOTICE: RESEARCH ONLY**
> * This repository documents a **work-in-progress investigation**.
> * There is **no working prototype** yet.
> * **DO NOT** attempt to power medical equipment with experimental hardware.
> * We are currently in the **Reverse Engineering & Data Collection** phase.

---

## ❓ The Problem
The current external power system for the HeartMate 3 LVAD relies on proprietary, sealed lead-acid or older Li-ion technology. Users face several challenges:
1.  **Connector Wear:** The battery clips frequently melt or fail at the connection point.
2.  **Form Factor:** The existing batteries are heavy and bulky.
3.  **Charger Lock-in:** The proprietary charger is the only way to recharge, creating a single point of failure.

## 🎯 The Goal
To collaboratively research, document, and design a **modern, open-specification** external battery alternative that is:
* **Lighter:** Using modern high-density Lithium cells (21700 standard).
* **Repairable:** Using off-the-shelf connectors and standard chargers.
* **Transparent:** Documenting the pinout and communication protocols so users understand their own equipment.

## 🚧 Current Research Status
We are currently gathering data on the following components. **Check the [Issues] tab to contribute data.**

### 1. The Connector
* **Status:** *Unidentified.*
* **Goal:** Determine the manufacturer and part number of the 5-pin blade connector.
* **Action:** [Help us identify this part in Issue #1]

### 2. The Cells
* **Status:** *Evaluating candidates.*
* **Goal:** Select 21700 cells that match or exceed the specific discharge curve of the OEM battery.
* **Requirements:** High capacity (>4500mAh) and stable voltage under load.

### 3. The Communication Protocol
* **Status:** *Unknown.*
* **Goal:** Determine if the "Smart" pins use SMBus, I2C, or simple voltage sensing.

---

## 🤝 How to Contribute
We need engineers, designers, and fellow users to help populate this data.
* **Have a dead battery?** We need photos of the internal PCB.
* **Know the connector?** Post in the Issues tab.
* **Have 3D scanning gear?** We need scans of everything.

## 🤝 Support the Research
**I am self-funding this project to help my mother and other patients.**
Building a safe, medical-grade alternative requires expensive hardware validation. I am purchasing used HeartMate 3 controllers for destructive testing and hiring professional engineers for 3D scanning and safety checks.

**If you want to speed up development, you can contribute directly to the R&D fund:**
[![Donate with Square](https://img.shields.io/badge/Donate-Square-3E43BA?style=for-the-badge&logo=square&logoColor=white)](https://square.link/u/YXz3dqBN)

## ⚖️ Disclaimer
This is a research project, not a product. The maintainers are not affiliated with Abbott Laboratories. All trademarks belong to their respective owners.
