# Muhammad Huzaifa Khan Ghory
### Mechanical Engineer | CFD & FEA Specialist | METU Student

Welcome to my engineering portfolio. I specialize in **Computational Fluid Dynamics (CFD)**, **Acoustics**, and **Non-Destructive Testing (NDT)**. My work focuses on bridging theoretical analysis with practical simulation to solve complex mechanical problems.

## 🛠 Skills & Tools

### 🌊 Analysis & Simulation
![MATLAB](https://img.shields.io/badge/MATLAB-R2023b-orange?logo=mathworks&style=for-the-badge) &nbsp;
![Ansys](https://img.shields.io/badge/Ansys-Simulation-FFB114?logo=ansys&style=for-the-badge&logoColor=black) &nbsp;
![SimScale](https://img.shields.io/badge/SimScale-Cloud_CFD-004C97?style=for-the-badge) <br><br>

![OpenFOAM](https://img.shields.io/badge/OpenFOAM-CFD-44CC11?style=for-the-badge) &nbsp;
![ElmerFEM](https://img.shields.io/badge/ElmerFEM-FEA-black?style=for-the-badge) &nbsp;
![ParaView](https://img.shields.io/badge/ParaView-Data_Viz-FF6600?style=for-the-badge) &nbsp;
![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python&style=for-the-badge)

### ⚙️ Design & CAD
![SolidWorks](https://img.shields.io/badge/SolidWorks-CAD-cB2027?logo=solidworks&style=for-the-badge&logoColor=white) &nbsp;
![Fusion 360](https://img.shields.io/badge/Autodesk-Fusion_360-F57826?logo=autodesk&style=for-the-badge&logoColor=white)

### 📝 Documentation
![LaTeX](https://img.shields.io/badge/LaTeX-Overleaf-47A141?logo=latex&style=for-the-badge)

## 📂 Featured Projects

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Responsive Grid */
  gap: 20px;
  margin-top: 20px;
}
.project-card {
  position: relative;
  height: 250px; /* Fixed height for uniformity */
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  text-decoration: none !important; /* Removes default underline */
}
.project-image {
  width: 100%;
  height: 100%;
  object-fit: cover; /* Ensures image covers area without stretching */
  display: block;
  transition: transform 0.3s ease;
}
.project-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.8); /* Dark see-through background */
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  opacity: 0; /* Hidden by default */
  transition: opacity 0.3s ease;
  padding: 20px;
  text-align: center;
}
/* HOVER EFFECTS */
.project-card:hover .project-overlay {
  opacity: 1; /* Show text on hover */
}
.project-card:hover .project-image {
  transform: scale(1.1); /* Zoom image slightly */
}
.project-title {
  font-size: 1.2rem;
  font-weight: bold;
  margin-bottom: 10px;
  color: #fff;
}
.project-tags {
  font-size: 0.8rem;
  background: #007bff;
  padding: 2px 8px;
  border-radius: 4px;
  margin-top: 5px;
}
</style>

<div class="project-grid">

  <a href="heat-exchanger" class="project-card">
    <img src="thumb_heat.png" alt="CFD Heat Exchanger" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Heat Exchanger CFD</div>
      <p>Optimization of fluid domain using SimScale & MATLAB.</p>
      <span class="project-tags">View Report (PDF)</span>
    </div>
  </a>

  <a href="ect-probe" class="project-card">
    <img src="thumb_probe.png" alt="ECT Probe" class="project-image">
    <div class="project-overlay">
      <div class="project-title">ECT Probe Design</div>
      <p>Custom coil probe for detecting surface flaws.</p>
      <span class="project-tags">View Report (PDF)</span>
    </div>
  </a>

  <a href="acoustics" class="project-card">
    <img src="thumb_acoustic.png" alt="Acoustics" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Acoustic Bubble Detection</div>
      <p>Numerical modeling of ultrasonic transducers.</p>
      <span class="project-tags">View Report (PDF)</span>
    </div>
  </a>

  <a href="structure-design" class="project-card">
    <img src="thumb_load.png" alt="Load Structure" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Load Bearing Structure</div>
      <p>Design, fabrication, and testing with minimal resources.</p>
      <span class="project-tags">View Report (PDF)</span>
    </div>
  </a>

  <a href="gearbox" class="project-card">
    <img src="thumb_gear.png" alt="Gearbox" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Gearbox Design</div>
      <p>ISO standard gearbox design with MATLAB analysis.</p>
      <span class="project-tags">View Report (PDF)</span>
    </div>
  </a>

</div>

## 📂 Featured Projects

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin-top: 20px;
}
.project-card {
  position: relative;
  height: 250px;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  text-decoration: none !important;
  color: inherit; /* Inherit text color */
}
.project-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.3s ease;
}
.project-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.85); /* Slightly darker for better text contrast */
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: opacity 0.3s ease;
  padding: 20px; 
  box-sizing: border-box; /* 🟢 FIXES TEXT CUTOFF */
  text-align: center;
}
/* HOVER EFFECTS */
.project-card:hover .project-overlay {
  opacity: 1;
}
.project-card:hover .project-image {
  transform: scale(1.1);
}
.project-title {
  font-size: 1.4rem;
  font-weight: bold;
  margin-bottom: 10px;
  color: #fff;
}
.project-desc {
  font-size: 0.95rem;
  margin-bottom: 15px;
  line-height: 1.4;
}
/* NEW "VIEW DETAILS" TEXT STYLE (No Button) */
.project-link-text {
  font-size: 0.9rem;
  font-weight: bold;
  color: #4db8ff; /* Light blue text */
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-top: 5px;
}
</style>

<div class="project-grid">

  <a href="heat-exchanger" class="project-card">
    <img src="thumb_heat.png" alt="CFD Heat Exchanger" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Heat Exchanger CFD</div>
      <p class="project-desc">Optimization of fluid domain using SimScale & MATLAB.</p>
      <div class="project-link-text">View Details &rarr;</div>
    </div>
  </a>

  <a href="ect-probe" class="project-card">
    <img src="thumb_probe.png" alt="ECT Probe" class="project-image">
    <div class="project-overlay">
      <div class="project-title">ECT Probe Design</div>
      <p class="project-desc">Custom coil probe for detecting surface flaws.</p>
      <div class="project-link-text">View Details &rarr;</div>
    </div>
  </a>

  <a href="acoustics" class="project-card">
    <img src="thumb_acoustic.png" alt="Acoustics" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Acoustic Bubble Detection</div>
      <p class="project-desc">Numerical modeling of ultrasonic transducers.</p>
      <div class="project-link-text">View Details &rarr;</div>
    </div>
  </a>

  <a href="structure-design" class="project-card">
    <img src="thumb_load.png" alt="Load Structure" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Load Bearing Structure</div>
      <p class="project-desc">Design, fabrication, and testing with minimal resources.</p>
      <div class="project-link-text">View Details &rarr;</div>
    </div>
  </a>

  <a href="gearbox" class="project-card">
    <img src="thumb_gear.png" alt="Gearbox" class="project-image">
    <div class="project-overlay">
      <div class="project-title">Gearbox Design</div>
      <p class="project-desc">ISO standard gearbox design with MATLAB analysis.</p>
      <div class="project-link-text">View Details &rarr;</div>
    </div>
  </a>

</div>

## 📚 Education
**Middle East Technical University (METU)**
* *Current Student*
* Focus: Computational Fluid Dynamics using OpenFOAM, Simscale, Acoustic Analysis

## 📫 Contact
* [LinkedIn](https://www.linkedin.com/in/muhammad-huzaifa-khan-ghory/)
* huzaifa.ghory@gmail.com
