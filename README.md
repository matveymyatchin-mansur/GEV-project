# Computational Ground-Effect Vehicle Stability Analysis

## Overview
This repository contains an ongoing independent engineering project focused on the **computational analysis and mechanical stability assessment of a ground-effect vehicle (WIG) configuration** across operating regimes.

The project investigates how aerodynamic characteristics, trim conditions, and static stability evolve as a vehicle transitions from strong ground effect to non-ground-effect operation. Emphasis is placed on **mechanically driven design and control strategies** that enable stable and controllable behavior across this transition.

The work combines **CFD simulations**, **reduced-order aerodynamic modeling**, and **system-level mechanical analysis**, with a focus on reproducibility, documentation, and engineering rigor.

---

## Project Objectives
- Quantify airfoil performance in ground effect under varying modeling assumptions  
- Compare conventional airfoils with ground-effect-optimized profiles  
- Develop a system-level mechanical model of a WIG-type vehicle  
- Analyze trim conditions and static stability across height-to-chord ratios  
- Investigate mechanically realistic strategies for maintaining controllability outside ground effect  

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
- **CFD:** OpenFOAM  
- **Numerical Analysis:** Python (NumPy, SciPy, pandas, Matplotlib)  
- **Reduced-Order Aerodynamics:** XFOIL  
- **Documentation:** LaTeX  
- **Version Control:** Git / GitHub  

---

## Project Status
**Status:** Ongoing  

Current focus:
- Baseline airfoil simulations outside ground effect  
- Ground-effect CFD case setup and validation  
- Initial reduced-order vehicle modeling  

Future work includes extended stability analysis and evaluation of transition control strategies.

---

## Notes
This repository is structured to emphasize **clarity, reproducibility, and engineering justification**.  
Results and conclusions are expected to evolve as modeling fidelity increases.

---

## Author
Matvey Myathcin
Independent Engineering Project  
