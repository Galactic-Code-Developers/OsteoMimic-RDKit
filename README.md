# OsteoMimic-RDKit

This repository contains the open-source RDKit-based molecular simulation materials supporting the paper:

**Innovative Design and Molecular Simulation of OsteoMimic:  
A Mussel-Inspired Adhesive for Bone Repair Using RDKit**

## Purpose
This repository provides transparent, reproducible computational resources for:
- Catechol-based adhesive monomers and oligomers
- Fe³⁺–catechol coordination motifs
- Molecular descriptor analysis (MW, LogP, TPSA, HBD/HBA)

The repository is intended as a **computational reference**, not as a mechanical, biological, or clinical model.

## Open-Source Framework
All simulations are implemented using **RDKit**, an open-source cheminformatics toolkit
released under a permissive BSD license.

## Repository Structure
```
OsteoMimic-RDKit/
├── molecules/        # SMILES definitions
├── scripts/          # RDKit simulation scripts
├── notebooks/        # Reproducible Jupyter notebooks
├── zenodo/           # Zenodo deposition metadata
├── docs/             # Supplementary documentation
```

## Reproducibility
All structures are generated using ETKDG embedding and optimized with MMFF94.
Parameters are explicitly defined in the scripts to enable independent verification.

## License
This repository is released under the MIT License.
