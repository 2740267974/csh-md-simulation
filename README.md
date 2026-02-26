# Molecular Dynamics Simulation of Ca(OH)₂ Adsorption on C–S–H

## Overview

This project investigates the adsorption behavior of calcium hydroxide (Ca(OH)₂) on Calcium Silicate Hydrate (C–S–H) using Molecular Dynamics (MD) simulations.

The study aims to understand how structural parameters of C–S–H and environmental conditions (e.g., temperature) influence ion diffusion, adsorption mechanisms, and interfacial interactions in cement hydration systems.

Supervisor: A/Prof. Kai Li  
Institution: Hunan University  
Duration: 09/2024 – Present

## Research Objectives

- Construct a realistic C–S–H model based on the Tobermorite structure
- Control key structural parameters: Ca/Si ratio, bridging oxygen ratio, interlayer spacing
- Build a Ca(OH)₂ aqueous solution model and assemble the interface system
- Run MD simulations in LAMMPS to study adsorption and diffusion behavior
- Analyze results using MSD, RDF, and density profiles

## Methodology

Model construction:
- Built C–S–H structure in Materials Studio (Tobermorite-based)
- Tuned Ca/Si ratio and bridging oxygen distribution
- Exported structure as LAMMPS-readable data files

Simulation:
- Performed MD simulations with LAMMPS
- Used periodic boundary conditions and temperature-controlled ensembles (NVT/NPT)

Post-processing:
- Mean Square Displacement (MSD) for diffusion analysis
- Radial Distribution Function (RDF) for coordination analysis
- Density profiles to observe ion enrichment near the C–S–H surface
- Data processing and plotting with Python

## Key Findings (Summary)

- Temperature significantly influences Ca²⁺ diffusion behavior
- C–S–H structural parameters affect adsorption intensity near the interface
- RDF peaks indicate strong Ca–O coordination interactions
- Density profiles show ion accumulation close to the C–S–H surface

## Project Structure

csh-md-simulation/
- input/    LAMMPS input scripts and structure data files
- output/   Simulation outputs (log, density, RDF, dumps)
- analysis/ Python scripts for MSD/RDF plotting and analysis
- figures/  Generated plots
- README.md

## Tools and Software

- Materials Studio
- LAMMPS
- Python (NumPy, Matplotlib)
- OVITO (visualization)

## Research Significance

Understanding Ca(OH)₂ adsorption on C–S–H helps explain cement hydration mechanisms and supports microstructure-property analysis for durability improvement.

## License

For technical demonstration and academic presentation purposes only.
