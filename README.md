# Open Source HeartMate 3 Battery Project

> **⚠️ CRITICAL SAFETY WARNING**
> * **DO NOT** use this project for primary life support without clinical oversight.
> * **DO NOT** attempt to charge these custom packs in the official Abbott Universal Battery Charger. It poses a fire risk.
> * **DO NOT** modify the System Controller or internal backup battery.
> * *This repository documents a personal research project to create a user-serviceable alternative to the official 14.4V battery clips.*

---

## 🎯 Project Goal
To design and build a **safe, reliable, and cost-effective** external battery pack for the HeartMate 3 Left Ventricular Assist Device (LVAD). This project aims to solve two common failures of the OEM system:
1.  **Clip Melting:** Replacing worn proprietary contacts with fresh, high-current connectors.
2.  **Charger Reliability:** Enabling the use of standard, smart lithium chargers to prevent thermal stress on batteries.
3.  **Form Factor:** Creating a smaller, lighter solution to improve patient mobility.

## 🛠️ Bill of Materials (BOM)

| Component | Recommendation | Notes |
| :--- | :--- | :--- |
| **Cells** | **Samsung 50E** (21700 Li-Ion) | Must be genuine Grade A. High capacity (5000mAh) and stable chemistry. |
| **Case** | Solderless 4S 21700 Enclosure | Custom 3D print or modified generic case. |
| **BMS** | Passive Balance Lead (5-pin) | Allows individual cell monitoring for safety. |
| **Connector** | Custom 5-Pin Blade | *Currently Reverse Engineering.* |
| **Charger** | Smart Li-Ion Charger | Must support independent channel charging (e.g., XTAR VC4SL). |

## ⚙️ Technical Specifications
* **Nominal Voltage:** 14.4V (4S Configuration)
* **Capacity:** ~5000mAh (72Wh)
* **Max Continuous Discharge:** ~9.8A (Safety margin well above HM3 peak load)

## 📝 Status
* [ ] **Phase 1: Research** - Reverse engineering the connector and voltage protocols.
* [ ] **Phase 2: Design** - Modeling the 4S enclosure and connector interface.
* [ ] **Phase 3: Testing** - Load testing with simulated 3W-10W fluid pump loads.

## ⚖️ Liability Disclaimer
This hardware design is **experimental**. The authors accept **no liability** for device failure, medical complications, or damage to equipment. By using this information, you agree to assume all risks associated with modifying medical power systems.
