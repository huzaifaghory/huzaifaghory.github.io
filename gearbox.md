[← Back to Portfolio](./)

# Design of a Two-Stage Reduction Gearbox

![Gearbox Assembly](images/thumb_gearbox.png)
*Figure 1: 3D Assembly of the gearbox showing input, intermediate, and output shafts.*

## 🎯 Objective
To design a two-stage spur gear reduction unit to specific input power and speed requirements, strictly adhering to ISO 6336 standards for durability and safety.

## ⚙️ Technical Details
* **Design Standards:** ISO 6336 (Capacity of Spur Gears), DIN 743 (Shafts).
* **Tools:** MATLAB (Iterative Calculations), SolidWorks (CAD & Assembly).
* **Components:** Spur Gears, Deep Groove Ball Bearings, Keyways, Housing.

## 🧠 The Challenge
The primary challenge was balancing the **volume/weight** of the gearbox against the required **safety factor**. A smaller gearbox is cheaper but runs hotter and risks tooth failure. I had to iteratively calculate the module and face width to ensure the gears would withstand both pitting (surface fatigue) and bending stress.

## 🔬 Methodology
1.  **Parameter Selection:** Selected material (Case-hardened Steel 18CrNiMo7-6) for high surface hardness.
2.  **Mathematical Modeling:** Wrote a **MATLAB script** to automate the iteration of the Lewis Bending Equation and Hertzian Contact Stress formulas. This allowed me to optimize the gear module ($m$) quickly.
3.  **Shaft Design:** Calculated shear, bending, and torsion diagrams to determine the minimum shaft diameters at critical steps (bearing seats, gear seats).
4.  **Bearing Selection:** Selected SKF bearings based on calculated radial and axial loads for a target life of 10,000 hours.

## 📊 Results
* **Safety Factor:** Achieved a contact safety factor of 1.2 and bending safety factor of 1.5.
* **Compactness:** Reduced the overall housing volume by 12% compared to the initial manual calculation.
* **Documentation:** Produced a complete set of engineering drawings (Bill of Materials, Section Views, Tolerancing).

### Visuals
![Detailed Engineering Drawing](images/thumb_gearbox_dwg.png)
*Figure 2: Section view showing bearing arrangements and oil seal placements.*

---

### 📥 Downloads
[**📄 Download Full Project Report (PDF)**](project_pdfs/Design_of_a_Gearbox_Project.pdf)
