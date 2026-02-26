# Molecular Dynamics Simulation of Ca(OH)₂ Adsorption on C–S–H

## Overview

This project investigates the adsorption and diffusion behavior of calcium hydroxide (Ca(OH)₂) on Calcium Silicate Hydrate (C–S–H) using Molecular Dynamics (MD) simulations.

The objective is to quantify how structural characteristics of C–S–H and environmental parameters (e.g., temperature) influence interfacial interactions, ion mobility, and adsorption mechanisms in cement hydration systems.

Supervisor: A/Prof. Kai Li  
Institution: Hunan University  
Duration: 09/2024 – Present

---

## Research Objectives

- Construct a physically representative C–S–H model based on the Tobermorite structure
- Control key structural parameters including Ca/Si ratio, bridging oxygen ratio, and interlayer spacing
- Develop a Ca(OH)₂ aqueous solution model and assemble the interfacial simulation system
- Perform MD simulations in LAMMPS to evaluate adsorption and diffusion behavior
- Conduct quantitative analysis using MSD, RDF, and density distribution profiles

---

## Methodology

### Model Construction
- Built a Tobermorite-based C–S–H structure using Materials Studio
- Tuned Ca/Si ratio and bridging oxygen distribution
- Exported the structure as LAMMPS-compatible data files

### Simulation
- Performed MD simulations using LAMMPS
- Applied periodic boundary conditions
- Employed temperature-controlled ensembles (NVT)
- Analyzed temperature-dependent diffusion behavior

### Post-processing
- Mean Square Displacement (MSD) for diffusion coefficient estimation
- Radial Distribution Function (RDF) for coordination and local structural analysis
- Density profiles to evaluate ion enrichment near the C–S–H interface
- Data processing and visualization using Python (NumPy, Matplotlib)

---

## Key Findings (Summary)

- Temperature significantly influences Ca²⁺ diffusion dynamics
- Structural parameters of C–S–H affect interfacial adsorption intensity
- RDF analysis reveals strong Ca–O coordination interactions
- Density profiles indicate ion accumulation near the C–S–H surface region

---

## Project Structure

csh-md-simulation/
- Input/    LAMMPS input scripts and structure data files
- Output/   Processed simulation outputs (MSD, density profiles)
- analysis/ Python scripts for MSD/RDF plotting and analysis
- figures/  Generated plots
- README.md

---

## Tools and Software

- Materials Studio
- LAMMPS
- Python (NumPy, Matplotlib)
- OVITO (visualization)

---

## Research Significance

Understanding Ca(OH)₂ adsorption on C–S–H contributes to the fundamental interpretation of cement hydration mechanisms and supports microstructure–property correlation analysis for durability and performance optimization.

---

## License

This repository is provided for academic demonstration and research presentation purposes.
