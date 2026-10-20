# 6 Cylinder Radial Engine - CAD Modelling and Motion Analysis (SolidWorks)
3D CAD model of a radial engine assembly with a SolidWorks Motion Study, developed for BluePrint 2k24-25 at MNNIT Allahabad.

[![SolidWorks](https://img.shields.io/badge/SolidWorks-MODELLING%20AND%20MOTION%20ANALYSIS-%23C71D23?style=for-the-badge&logo=dassaultsystemes&logoColor=white&labelColor=%23111111)](https://www.solidworks.com/)


---

## Overview : 

This project is the complete 3D model of a **6-Cylinder Radial Engine** built in SolidWorks, assembled as a fully mated multi-body assembly and animated using a SolidWorks Motion Analysis to verify that the mechanism moves correctly.

## Competition : 

- **Event Name:** BluePrint 2k24-25, organized by Mechrocosm under the Avishkar Technical Fest, MNNIT Allahabad
- **Category:** 2nd Year
- **Team:** Kuch Bhi👾
- **Result:** 3rd Position
- **Round:** Qualifier (6 Cylinder Radial Engine Design)

---

## CAD Model (Solidworks) : 

The CAD model features an intricate assembly of all primary engine components, including the crankcase, pistons, connecting rods, and valve mechanisms. Each part was individually modeled in SolidWorks and mated with constraints to ensure correct kinematic behavior and accurate mechanical interaction.

<div align="center">
  <img src="Renders/preview.PNG" alt="6 Cylinder Radial Engine Motion preview" width="75%">
  <p> <i>Rendered view of 6 Cyliner Radial Engine assembly.</i></p>
</div>

---

## Motion Analysis :

Motion study set up in SolidWorks Motion Study:

- **Driver:** Rotary motor on Crankshaft Rod.
- **Speed:** 100 RPM
- **Duration:** 10 seconds
- **Output:** Animation (in .mp4 and.gif) in Motion_Analysis folder.

Demo video: `Motion_Analysis/Motion Analysis.mp4`
<div align="center">
  <img src="Motion_Analysis/Motion_Analysis.gif" alt="6 Cylinder Radial Engine Motion Analysis" width="75%">
  <p><i>Motion Analysis of 6 Cyliner Radial Engine assembly.</i></p>
</div>

---

## Bill of Material (BOM) :

<div align="center">
  <table>
    <thead>
      <tr>
        <th align="center">ITEM NO.</th>
        <th align="left">COMPONENT NAME</th>
        <th align="left">FILE TYPE</th>
        <th align="center">QTY.</th>
      </tr>
    </thead>
    <tbody>
      <!-- Chassis Plates & Mounts -->
      <tr><td align="center">1</td><td>Front Side Plate R</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">2</td><td>Front Side Plate L</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">3</td><td>Front Upper Arm Mount</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">4</td><td>Front Shock Brace</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">5</td><td>Assembled Front Lower Arm</td><td><code>.SLDASM</code></td><td align="center">2</td></tr>
      <tr><td align="center">6</td><td>Assembled Front Upper Arm</td><td><code>.SLDASM</code></td><td align="center">2</td></tr>
      <tr><td align="center">7</td><td>Front Lower Arm Brace</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">8</td><td>Front Lower Hinge Pin</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">9</td><td>Front Upper Hinge Pin</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">10</td><td>E-Clip</td><td><code>.SLDPRT</code></td><td align="center">8</td></tr>
      <tr><td align="center">11</td><td>Front Suspension Adjustment Clip</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">12</td><td>Shock Bushing</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">13</td><td>Assembled Shock Absorber</td><td><code>.SLDASM</code></td><td align="center">2</td></tr>
      <tr><td align="center">14</td><td>Assembled Front Hub Carrier L</td><td><code>.SLDASM</code></td><td align="center">1</td></tr>
      <tr><td align="center">15</td><td>Assembled Front Hub Carrier R</td><td><code>.SLDASM</code></td><td align="center">1</td></tr>
      <tr><td align="center">16</td><td>ANSI B18.22.1 - M5-Narrow Washer</td><td><code>.SLDPRT</code></td><td align="center">6</td></tr>
      <tr><td align="center">17</td><td>ISO-4035-M3-N Hex Nut</td><td><code>.SLDPRT</code></td><td align="center">4</td></tr>
      <tr><td align="center">18</td><td>ISO 4762 - M3 × 20 Hex Socket Head Cap Screw</td><td><code>.SLDPRT</code></td><td align="center">10</td></tr>
    </tbody>
  </table>
</div>

| ITEM NO. | COMPONENT NAME | FILE TYPE | QTY. |
| :---: | :--- | :--- | :---: |
| 1 | Base | `.SLDPRT` | 1 |
| 2 | Piller Support | `.SLDPRT` | 1 |
| 3 | Bearing Support | `.SLDPRT` | 1 |
| 4 | Valve Housing | `.SLDPRT` | 1 |
| 5 | Valve | `.SLDPRT` | 1 |
| 6 | Crankcase | `.SLDPRT` | 1 |
| 7 | Sub Assembled Crankshaft | `.SLDASM` | 1 |
|  |    Counter Weight | `.SLDPRT` | 2 |
|  |    Crankshaft Pin | `.SLDPRT` | 1 |
|  |     Crankshaft Rod | `.SLDPRT` | 1 |
| 8 | Crankshaft Valve Crank | `.SLDPRT` | 1 |
| 9 | SKF - 6001 - Full, DE, AC, Full_68 | `.SLDPRT` | 3 |
| 10 | Connecting Rod Hub | `.SLDPRT` | 1 |
| 11 | Crankcase Gasket | `.SLDPRT` | 1 |
| 12 | Crankcase Cover | `.SLDPRT` | 1 |
| 13 | Hub Pin | `.SLDPRT` | 6 |
| 14 | Cylinder Body | `.SLDPRT` | 6 |
| 15 | Cyinder Bolt | `.SLDPRT` | 24 |
| 16 | Cylinder Cover | `.SLDPRT` | 6 |
| 17 | Connecting Rod | `.SLDPRT` | 6 |
| 18 | Sub Assembled Piston | `.SLDASM` | 6 |
|  |    Piston | `.SLDPRT` | 1 |
|  |    Piston Pin | `.SLDPRT` | 1 |
|  |    Piston Ring | `.SLDPRT` | 2 |
| 19 | DIN 1587 - M6 --NNU | `.SLDPRT` | 24 |
| 20 | ISO 4762 M6 x 45 - 45S | `.SLDPRT` | 6 |
| 21 | Flywheel | `.SLDPRT` | 1 |


## Bill of Material (BOM) :

<div align="center">
  <table>
    <thead>
      <tr>
        <th align="center">ITEM NO.</th>
        <th align="left">COMPONENT NAME</th>
        <th align="left">FILE TYPE</th>
        <th align="center">QTY.</th>
      </tr>
    </thead>
    <tbody>
      <!-- Chassis Plates & Mounts -->
      <tr><td align="center">1</td><td>Front Side Plate R</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">2</td><td>Front Side Plate L</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">3</td><td>Front Upper Arm Mount</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">4</td><td>Front Shock Brace</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">5</td><td>Assembled Front Lower Arm</td><td><code>.SLDASM</code></td><td align="center">2</td></tr>
      <tr><td align="center">6</td><td>Assembled Front Upper Arm</td><td><code>.SLDASM</code></td><td align="center">2</td></tr>
      <tr><td align="center">7</td><td>Front Lower Arm Brace</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">8</td><td>Front Lower Hinge Pin</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">9</td><td>Front Upper Hinge Pin</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">10</td><td>E-Clip</td><td><code>.SLDPRT</code></td><td align="center">8</td></tr>
      <tr><td align="center">11</td><td>Front Suspension Adjustment Clip</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">12</td><td>Shock Bushing</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">13</td><td>Assembled Shock Absorber</td><td><code>.SLDASM</code></td><td align="center">2</td></tr>
      <tr><td align="center">14</td><td>Assembled Front Hub Carrier L</td><td><code>.SLDASM</code></td><td align="center">1</td></tr>
      <tr><td align="center">15</td><td>Assembled Front Hub Carrier R</td><td><code>.SLDASM</code></td><td align="center">1</td></tr>
      <tr><td align="center">16</td><td>ANSI B18.22.1 - M5-Narrow Washer</td><td><code>.SLDPRT</code></td><td align="center">6</td></tr>
      <tr><td align="center">17</td><td>ISO-4035-M3-N Hex Nut</td><td><code>.SLDPRT</code></td><td align="center">4</td></tr>
      <tr><td align="center">18</td><td>ISO 4762 - M3 × 20 Hex Socket Head Cap Screw</td><td><code>.SLDPRT</code></td><td align="center">10</td></tr>
    </tbody>
  </table>
</div>
---

## Repository Structure : 

```
Six-Cylinder-Radial-Engine/
├── BOM/                    # Bill of Materials (in .xlsx and pdf)
├── CAD_Files/              # Contains all individual .SLDPRT part files and master .SLDASM file
├── Motion_Analysis         # Contains motion analysis (mp4 and gif)
├── Renders/                # Visual 3D render image of the assembly
└── README.md               # Project documentation page
```

## Credits : 

**Team:** Kuch Bhi👾, BluePrint 2k24-25, Mechrocosm Event, MNNIT Allahabad.

## License :

Shared for educational and portfolio purposes.
