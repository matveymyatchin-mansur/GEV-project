# Computational Ground-Effect Vehicle project (Project outline)

## Phase 0 - Project setup (COMPLETED)
* [X] Set up Git/GitHub repository with clear folder structure.  
* [X] Configure VS Code for Python, LaTeX, and Git workflows.  
* [X] Establish logging system (Markdown notes, notebooks, or CSV logs).  
* [X] Create initial README and LaTeX report skeleton.  

## Phase 1 - Airfoil GE analysis
* [X] Write an abstract section.  
* [X] Perform literature study on GEVs.
- Descritpion: Perfomr literature study on current state research concerning GEVs.
- Source: [literature_study.tex](latex/sections/literature_study.tex)
* [X] Methodology
- Source: [methodology.tex](latex/sections/methodology.tex)
### [] Airfoil selection  
- Description: Selecting appropriate airfoils for testing (eg: DHMTU, NACA, Horton)
- Source: [airfoil_selection.tex](latex/sections/airfoil_selection.tex)
- LaTeX label: 'sec:airfoil-selection'
* [] Establish baseline aerodynamic performance outside ground effect.  
* [] Perform parametric sweeps over angle of attack, Reynolds number, and height-to-chord ratio.  
* [] Use reduced-order tools (e.g., XFOIL) for rapid comparison.  
* [] Run CFD cases (OpenFOAM) for selected operating points.  
* [] Extract lift, drag, and pitching moment coefficients and pressure distributions.  
* [] Identify sensitivity to modeling assumptions and ground proximity.  

## Phase 2 - Reduced-order mechanical vehicle
* [] Define a simplified GEV configuration (wing, tail/control surface, fuselage mass).  
* [] Assign geometric parameters, center of gravity, and inertial properties.  
* [] Integrate airfoil aerodynamic data into a vehicle-level force and moment model.  
* [] Solve force and pitching-moment equilibrium to determine trim conditions.  
* [] Identify trim envelopes and no-trim regions across height and speed.  

## Phase 3 - Static stability analysis
* [] Evaluate static margin and pitching-moment slope as a function of height.  
* [] Assess sensitivity of trim to small height and angle-of-attack perturbations.  
* [] Compare stability behavior in strong ground effect versus free-flight conditions.  
* [] Identify mechanisms leading to loss of controllability outside ground effect.  

## Phase 4 - Transition & control strategy study
* [] Select one or two mechanically realistic transition strategies.  
* [] Examples include variable-incidence surfaces, control surface authority mapping, or CG shifts.  
* [] Quantify required control inputs to maintain trim during ground-effect exit.  
* [] Assess feasibility and limitations of each strategy.  

## Phase 5 - High-fidelity validation
* [] Select representative configurations and operating points for detailed CFD.  
* [] Refine meshes and boundary conditions for higher accuracy.  
* [] Compare high-fidelity results with reduced-order predictions.  

## Phase 6 - Documentation
* [] Consolidate results into a structured LaTeX report.  
* [] Clearly document assumptions, limitations, and future work.  
* [] Prepare figures and plots suitable for academic review.  
* [] Finalize GitHub repository as a public or private portfolio artifact.  