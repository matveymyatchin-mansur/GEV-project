# Computational Ground-Effect Vehicle Stability Study

## Overview
A ground-effect vehicle (GEV) is an aircraft designed to operate in close proximity to the ground, capitalising on a phenomenon -- the so-called ground effect -- that results in a significant increase in lift and a  reduction in induced drag. Despite their potential efficiency advantages, GEVs present significant challenges in airfoil selection and trim behavior, particularly when transitioning between ground-effect and free-flight conditions.\\

This study investigates the aerodynamic characteristics of selected airfoil profiles in ground effect, with the objective of identifying configurations suitable for mechanically stable GEV operation. Building upon preliminary airfoil investigations conducted during a prior academic project, **five** representative airfoils are selected and evaluated using a combination of reduced-order aerodynamic analysis and computational fluid dynamics (CFD) simulations. Parametric variations in angle of attack, Reynolds number, and height-to-chord ratio are considered to assess lift, drag, and pitching moment behavior.\\

---

## Project Objectives
- Quantify airfoil performance in ground effect under varying modeling assumptions.  
- Compare conventional airfoils with ground-effect-optimized profiles.  
- Develop a system-level mechanical model of a GEV.  
- Analyze trim conditions and static stability across height-to-chord ratios.  
- Investigate mechanically realistic strategies for maintaining controllability outside ground effect.  

---

## Methodology Overview

### 1. Airfoil-Level Ground Effect Analysis
- Multi-fidelity aerodynamic analysis of selected airfoil profiles
- Parametric sweeps over:
  - Angle of attack
  - Height-to-chord ratio (h/c)
  - Reynolds number
- Evaluation of lift, drag, and pitching moment sensitivity
- CFD simulations conducted using **OpenFOAM**
- Validation against reduced-order methods (e.g. XFOIL) outside ground effect

### 2. System-Level Mechanical Modeling
- Reduced-order mechanical model representing a WIG-type vehicle
- Force and moment equilibrium analysis
- Identification of trim points and no-trim regions
- Evaluation of control authority and sensitivity to height variation

### 3. Stability and Transition Analysis
- Static stability margin assessment across operating regimes
- Investigation of mechanically driven transition strategies, such as:
  - Variable incidence surfaces
  - Control surface authority mapping
  - Stability-oriented geometric design choices

---

## Tools & Technologies
- **CAD:** Potentially Ansys (to be determined later)
- **CFD:** OpenFOAM  
- **Numerical Analysis:** Python (NumPy, SciPy, pandas, Matplotlib)  
- **Reduced-Order Aerodynamics:** XFOIL/Ansys (to be determined later)  
- **Documentation:** LaTeX  
- **Version Control:** Github  

---

## Project Status
**Status:** Ongoing  

Current focus:
- Refine literature study (fix reference placements)
- Refine methodology
- Start writing the "Simulation" section:
    ->  Gather geometric data on selected airfoils

---

## Notes
  
Results and conclusions are expected to evolve as modeling fidelity increases.

---

## Author
Matvey Myatchin

Independent Engineering Project
