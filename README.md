# Molecular-Docking-and-Simulation-Study-of-Target-Drug-Interactions
Mini project on In-silico drug designing 
Project Overview
This repository presents a computational pipeline for molecular docking and molecular dynamics (MD) simulations aimed at studying drug-target interactions. The project focuses on predicting binding affinities, stability, and conformational changes of ligand-protein complexes, providing insights into potential drug candidates.

Objectives
Perform molecular docking to identify potential inhibitors against the selected biological target.
Analyze binding interactions such as hydrogen bonding, hydrophobic contacts, and salt bridges using visualization tools like PyMOL.
Simulate protein-ligand complexes using MD simulations to evaluate their stability and dynamic behavior.
Calculate free energy of binding using MM-PBSA/MM-GBSA methods.
Develop a reproducible workflow for molecular docking and MD simulations using open-source tools.
Workflow and Methodology
1. Molecular Docking
Software Used: AutoDock, AutoDock Vina, PyRx
Procedure:
Protein Preparation: Removal of water molecules, addition of missing hydrogens, and energy minimization.
Ligand Preparation: Optimization of 3D structures, charge assignment, and energy minimization.
Docking Simulation: Defining grid box, running docking experiments, and selecting top poses.
Post-Docking Analysis: Evaluating binding affinities, ligand conformations, and interaction profiles using PyMOL and Chimera.
2. Molecular Dynamics (MD) Simulations
Software Used: GROMACS, AMBER, CHARMM
Procedure:
System Setup: Solvation, ion addition, and energy minimization.
Equilibration: NVT and NPT ensemble simulations.
Production MD Run: Long-scale simulation to analyze system stability.
Trajectory Analysis:
Root Mean Square Deviation (RMSD)
Root Mean Square Fluctuation (RMSF)
Hydrogen bond analysis
Radius of gyration
Solvent-accessible surface area (SASA)
3. Binding Free Energy Calculation
Method: MM-PBSA/MM-GBSA
Purpose: Quantify ligand binding affinity and validate docking results.
Tools and Dependencies
Docking: AutoDock, AutoDock Vina, PyRx
MD Simulations: GROMACS, AMBER, CHARMM
Visualization & Analysis:
PyMOL – Protein-ligand interaction visualization and analysis
Chimera – Advanced structural analysis
VMD – MD trajectory visualization
Analysis & Scripting: Python, R (for statistical analysis and visualization)
Expected Results and Interpretations
Identification of the most promising inhibitors based on docking scores and interaction profiles.
Molecular dynamics simulation results to reveal the stability and flexibility of protein-ligand complexes.
MM-PBSA/MM-GBSA calculations to confirm the binding affinity and predict the most effective drug candidates.
Future Prospects
Experimental validation through in vitro and in vivo studies.
Expansion of ligand library to explore additional potential inhibitors.
Optimization of docking and simulation parameters for increased accuracy.
Machine learning approaches to predict drug-likeness and enhance virtual screening efficiency.
