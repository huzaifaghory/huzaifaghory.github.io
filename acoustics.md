# Acoustic Bubble Detection in Fluid Domains

![Acoustic Simulation Field](images/thumb_acoustic.png)
*Figure 1: Harmonic response analysis showing pressure wave propagation through the fluid domain.*

## 🎯 Objective
To develop a numerical model for detecting micro-bubbles in a fluid medium using ultrasonic piezoelectric transducers. The study aimed to correlate the scattering cross-section of bubbles with specific observation frequencies.

## ⚙️ Technical Details
* **Simulation:** ANSYS (Coupled Field Harmonic Response).
* **Analysis:** MATLAB (Signal Processing Toolbox).
* **Physics:** Fluid-Structure Interaction (FSI), Piezoelectricity, Acoustics.
* **Key Variable:** Bubble resonance frequency vs. Transducer frequency.

## 🧠 The Challenge
Detecting small bubbles in hydraulic or medical systems is critical but difficult due to noise and signal attenuation. The main challenge was accurately modeling the **fluid-solid interaction** between the piezoelectric material (the sensor) and the water domain to predict how bubbles of varying sizes would scatter the acoustic waves.

## 🔬 Methodology
1.  **Transducer Modeling:** Modeled the PZT (Lead Zirconate Titanate) sensor in ANSYS, defining piezoelectric properties to convert electrical voltage into mechanical vibration.
2.  **Harmonic Analysis:** Conducted a frequency sweep to identify the resonance frequencies of bubbles ranging from 10µm to 100µm.
3.  **Coupled Field Simulation:** Set up a 2D axisymmetric domain in ANSYS to simulate the propagation of ultrasonic waves and their reflection off the bubble surface.
4.  **Signal Processing:** Exported the acoustic pressure data to MATLAB to calculate the "Target Strength" and scattering cross-section.

## 📊 Results
The simulation established a clear correlation between the bubble radius and the peak scattering frequency (Minnaert resonance).
* **Outcome:** Validated that lower frequencies (kHz range) are more effective for detecting larger bubbles, while MHz frequencies are required for micro-bubbles.
* **Efficiency:** Proposed an optimized frequency band for early detection of cavitation bubbles in hydraulic pumps.

### Visuals
![Scattering Cross Section Graph](images/thumb_acoustic_graph.png)
*Figure 2: MATLAB plot of Scattering Cross-Section vs. Frequency for different bubble sizes.*

---

### 📥 Downloads
[**📄 Download Full Project Report (PDF)**](project_pdfs/Bubble_Detection_in_Fluid_Domain_Using_Ultrasonic_Acoustic_Waves.pdf)
