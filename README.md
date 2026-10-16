# Radial Engine - CAD Design and Motion Analysis (SolidWorks)

3D CAD model of a radial engine assembly with a SolidWorks Motion Study, developed for **BluePrint 2k24-25** at MNNIT Allahabad.

[![SolidWorks](https://img.shields.io/badge/CAD-SolidWorks-red)](https://www.solidworks.com/)
[![Motion Study](https://img.shields.io/badge/Analysis-Motion%20Study-blue)](https://www.solidworks.com/)
[![Result](https://img.shields.io/badge/BluePrint%202k24--25-2nd%20Place-gold)](#competition)

---

## Overview

This project is the complete 3D model of a **[N]-cylinder radial engine** built in SolidWorks, assembled as a fully mated multi-body assembly and animated using a SolidWorks Motion Study to verify that the mechanism moves correctly.

## Competition

- **Event:** BluePrint 2k24-25, organized by Mechrocosm under the Avishkar Technical Fest, MNNIT Allahabad
- **Category:** 2nd Year
- **Team:** Kuch Bhi
- **Result:** 2nd Place
- **Round:** Qualifier (radial engine design)

---

## Preview

<img src="Renders/preview.PNG" width="650">

*Rendered view of the complete radial engine assembly.*

<img src="images/motion_study.gif" width="650">

*Motion Study of the engine mechanism.*

---

## What Is Modeled

<!-- Edit this list so it matches your actual assembly -->
- Cylinders with end caps and fasteners
- Pistons
- Flywheel
- Bearings
- Support stand and base plate
- [Add: crankshaft, connecting rods, any other parts]

## Motion Analysis

Motion study set up in SolidWorks Motion Study:

- **Driver:** [rotary motor on crankshaft / flywheel]
- **Speed:** [RPM]
- **Duration:** [seconds]
- **Output:** [animation / piston displacement / velocity plots]

Demo video: `motion_study/radial_engine_motion.mp4`

---

## Repository Structure

```
Radial-Engine_CAD-and-Motion-Analysis_BluePrint-2024/
├── README.md
├── CAD/                  # SolidWorks parts and assembly (Pack and Go)
├── STEP/                 # Neutral-format export for other CAD software
├── motion_study/         # Motion study video
└── images/               # Renders and screenshots
```

## How To Open

1. Download or clone the repository.
2. Open `CAD/[AssemblyName].SLDASM` in SolidWorks ([version]) or later.
3. Open the **Motion Study** tab at the bottom to play the animation.
4. No SolidWorks? Use the files in `STEP/` with any CAD software.

---

## Credits

Team **Kuch Bhi**, BluePrint 2k24-25, Mechrocosm, MNNIT Allahabad.

## License

Shared for educational and portfolio purposes.
