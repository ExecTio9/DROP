# DROP – Long-Range Aerial Vessel Deployment System

**DROP** (Deployment and Recovery Optimization Platform) is a long-range aerial deployment system developed by SHC for precision payload delivery. It features autonomous altitude-triggered release mechanisms with telemetry and multi-stage deployment capabilities.

---

## 🔧 Features

-  **Tri-redundant altitude-based deployment system**
-  **Dual-band telemetry** (915 & 433 Mhz)
-  **Multi-stage release mechanism** for sequential payload drops
-  Designed for long-duration, autonomous aerial missions

---

## 🗂️ Folder Structure

| Folder       | Purpose                                         |
|--------------|-------------------------------------------------|
| `/firmware`  | Embedded code for main controller               |
| `/hardware`  | Schematics and PCB layout files (KiCad)         |
| `/enclosure` | 3D printable cases or brackets for deployment   |
| `/docs`      | Wiring diagrams, deployment logic, images       |
| `/test`      | Test scripts, validation logs, diagnostics      |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/drop.git
cd drop
```
2. Open the Firmware
Open /firmware/ in PlatformIO or Arduino IDE

Upload firmware to the deployment controller

3. Review Hardware Design
Open /hardware/ in KiCad 7.0 or later

PCB schematics and layout included

# Bill of Materials
-TBD

.....
