[← Back to Portfolio](./)

# Design & Manufacturing of a Load Bearing Structure

![Structure Load Test](thumb_structure.png)
*Figure 1: The final fabricated structure undergoing stress testing.*

## 🎯 Objective
To design and fabricate a load-bearing structure capable of supporting a specific weight while minimizing the structure's own mass. The project required strict adherence to material constraints and geometric limitations.

## ⚙️ Technical Details
* **CAD:** SOLIDWORKS, Siemens NX 11
* **Fabrication:** Laser Cutting, Bending, Manual Assembly
* **Material:** Aluminum Sheet (Al 6061)
* **Optimization:** Topology Optimization for weight reduction

## 🧠 The Challenge
The primary constraint was the **Strength-to-Weight Ratio**. We had a limited amount of material and had to support a dynamic load without buckling. The challenge was identifying the "zero-force members" in the truss design and removing them to save weight without compromising structural integrity.

## 🔬 Methodology
1.  **Conceptual Design:** Sketched multiple truss configurations (Warren vs. Pratt truss).
2.  **FEA Analysis:** Used SolidWorks Simulation to identify high-stress concentration areas and potential buckling points.
3.  **Refinement:** Removed material from low-stress areas (creating "cutouts") to reduce the total mass by 25%.
4.  **Fabrication:** Generated DXF files for laser cutting and assembled the interlocking parts.

## 📊 Results
* **Load Capacity:** Successfully held 200% of the design load.
* **Final Weight:** 15% lighter than the initial baseline design.
* **Failure Mode:** Predicted buckling occurred exactly as simulated in FEA, validating the model.

### Visuals
![FEA Stress Analysis](thumb_structure_fea.png)
*Figure 2: Von Mises stress distribution analysis showing critical load paths.*

---

### 📥 Downloads
[**📄 Download Full Project Report (PDF)**](Design_and_Manufacturing_of_a_Load_Bearing_Structure.pdf)
