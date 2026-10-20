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
      <tr><td align="center">1</td><td>Base</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">2</td><td>Piller Support</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">3</td><td>Bearing Support</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">4</td><td>Valve Housing</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">5</td><td>Valve</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">6</td><td>Crankcase</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">7</td><td>Sub Assembled Crankshaft</td><td><code>.SLDASM</code></td><td align="center">1</td></tr>
      <tr><td align="center"></td><td>&nbsp;&nbsp;&nbsp;&nbsp;  Counter Weight</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center"></td><td>&nbsp;&nbsp;&nbsp;&nbsp;  Crankshaft Pin</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center"></td><td>&nbsp;&nbsp;&nbsp;&nbsp;  Crankshaft Rod</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">8</td><td>Crankshaft Valve Crank</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">9</td><td>SKF - 6001 - Full, DE, AC, Full_68</td><td><code>.SLDPRT</code></td><td align="center">3</td></tr>
      <tr><td align="center">10</td><td>Connecting Rod Hub</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">11</td><td>Crankcase Gasket</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">12</td><td>Crankcase Cover</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center">13</td><td>Hub Pin</td><td><code>.SLDPRT</code></td><td align="center">6</td></tr>
      <tr><td align="center">14</td><td>Cylinder Body</td><td><code>.SLDPRT</code></td><td align="center">6</td></tr>
      <tr><td align="center">15</td><td>Cyinder Bolt</td><td><code>.SLDPRT</code></td><td align="center">24</td></tr>
      <tr><td align="center">16</td><td>Cylinder Cover</td><td><code>.SLDPRT</code></td><td align="center">6</td></tr>
      <tr><td align="center">17</td><td>Connecting Rod</td><td><code>.SLDPRT</code></td><td align="center">6</td></tr>
      <tr><td align="center">18</td><td>Sub Assembled Piston</td><td><code>.SLDASM</code></td><td align="center">6</td></tr>
      <tr><td align="center"></td><td>&nbsp;&nbsp;&nbsp;&nbsp;  Piston</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center"></td><td>&nbsp;&nbsp;&nbsp;&nbsp;  Piston Pin</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
      <tr><td align="center"></td><td>&nbsp;&nbsp;&nbsp;&nbsp;  Piston Ring</td><td><code>.SLDPRT</code></td><td align="center">2</td></tr>
      <tr><td align="center">19</td><td>DIN 1587 - M6 --NNU</td><td><code>.SLDPRT</code></td><td align="center">24</td></tr>
      <tr><td align="center">20</td><td>ISO 4762 M6 x 45 - 45S</td><td><code>.SLDPRT</code></td><td align="center">6</td></tr>
      <tr><td align="center">21</td><td>Flywheel</td><td><code>.SLDPRT</code></td><td align="center">1</td></tr>
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
