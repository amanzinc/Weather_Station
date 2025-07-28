
# Weather Station PCB

This repository contains the design files and documentation for a **basic PCB** that integrates multiple environmental sensors and a solid-state relay, all controlled via an **ESP32 development board**.

## 📦 Components Integrated

* **DFRobot Gravity: PM2.5 Air Quality Sensor**
* **O₂ (Oxygen) Sensor**
* **SO₂ (Sulfur Dioxide) Sensor**
* **NO₂ (Nitrogen Dioxide) Sensor**
* **Solid-State Relay (SSR)**
* **ESP32 Development Board**

## 🛠️ Current Status

* ✅ Footprints created for all components
* ✅ Initial layout drafted in **KiCAD**
* 🧐 Currently verifying mechanical dimensions and clearances

## 📝 To-Do

* [ ] Complete PCB **routing**
* [ ] Improve **part file organization** for better reusability
* [ ] Add **Bill of Materials (BoM)**
* [ ] Document **sensor pinouts and power requirements**
* [ ] Test assembled PCB and update results

## 📁 Project Structure

```bash
project-root/
├── kicad_files/           # KiCAD project files
├── footprints/            # Custom footprints and symbols
├── datasheets/            # Sensor and component datasheets
├── images/                # Renders or screenshots of layout
├── docs/                  # Additional documentation
└── README.md              # This file
```

## 🤝 Contributions

Feel free to fork the repo and submit pull requests to help improve design replicability and documentation clarity.


