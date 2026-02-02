# Fluent Coronary Bifurcation Batch Simulations

This repository contains scripts to run automated ANSYS Fluent simulations
of coronary artery bifurcation flow across a sweep of Reynolds numbers.

## Contents
- `run_bifurcation.sh` – Bash script to batch-run Fluent simulations
- `bifurcation_template.jou` – Fluent journal template
- `coronary_extracted_vessel.msh.h5` – Mesh file (if included)

## Requirements
- ANSYS Fluent (3D, double precision)
- Git Bash (Windows)
- Python (for velocity calculation)
- VS Code or equivalent editor

## Usage
1. Place mesh file in the repository root
2. Edit Reynolds number list in `run_bifurcation.sh`
3. Run:
   ```bash
   ./run_bifurcation.sh
