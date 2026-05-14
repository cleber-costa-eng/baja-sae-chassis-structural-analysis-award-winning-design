# baja-sae-chassis-structural-analysis-designFinite Element Analysis (FEA) and Structural Validation of a Baja SAE Chassis

# Finite Element Analysis (FEA) and Structural Validation of a Baja SAE Chassis

This repository contains the technical development and structural validation for my **Final Graduation Project (TCC)** in Mechanical Engineering at UFSCar. The project focuses on advanced simulation techniques to ensure the reliability and safety of an off-road vehicle.

## 🛠 Project Overview

The objective was to perform a complete structural audit and optimization of a Baja SAE roll cage. By integrating field-acquired data with advanced simulation software, I was able to predict fatigue life and validate the chassis under extreme operational conditions.

### Key Technical Contributions:
* **Real-World Load Acquisition:** Utilized proprietary telemetry software from the UFSCar Baja Team to capture dynamic loads during field tests, ensuring that the boundary conditions for the FEA were based on actual physical data.
* **Structural Optimization:** Conducted iterative simulations to balance the trade-off between weight reduction and structural stiffness.
* **Academic Excellence:** Developed at the Federal University of São Carlos (UFSCar), one of Brazil's leading engineering institutions.

## 📊 Engineering Methodology

### 1. Meshing Strategy & Global Model
A critical part of this study was the meshing strategy. I implemented a hybrid approach to maximize results accuracy while maintaining computational efficiency across the entire frame.

<p align="center">
  <img src="images/malha.png" width="60%" />
  <br><em>Figure 1: Global mesh of the Baja SAE vehicle frame.</em>
</p>

<p align="center">
  <img src="images/mesh%20quality%20hex.png" width="45%" />
  <img src="images/mesh%20quality%20tet.png" width="45%" />
  <br><em>Figure 2: Detailed view: High-quality Hexahedral mesh for structural tubes vs. Tetrahedral mesh for complex nodes.</em>
</p>

* **Hexahedral Meshing:** Applied to regular geometries to provide superior stress gradient resolution.
* **Numerical Convergence:** A mesh independence test was performed to ensure that the results were independent of the element size, a crucial step for professional FEA validation.

### 2. Fatigue Life & Durability Analysis
After establishing a high-quality mesh and applying field-tested loads, I focused on the fatigue life of critical components like the wheel hub (cubo) and steering knuckle (manga).

<p align="center">
  <img src="images/vida%20cubo%20otimizado.png" width="45%" />
  <img src="images/vida%20manga%20overall%20otim.png" width="45%" />
  <br><em>Figure 3: Fatigue life prediction showing safety factors and durability cycles after topology optimization.</em>
</p>

## 💻 Tech Stack
* **CAE/FEA:** Ansys Mechanical, SolidWorks Simulation.
* **CAD:** SolidWorks.
* **Data Acquisition:** Custom proprietary software (UFSCar Baja Team).

---
*Note: This project was developed as my Final Graduation Thesis at the Federal University of São Carlos (UFSCar).*
