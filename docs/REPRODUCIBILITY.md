# Reproducibility Notes

This repository provides computational materials supporting the molecular
simulations reported in:

"Innovative Design and Molecular Simulation of OsteoMimic:
A Mussel-Inspired Adhesive for Bone Repair Using RDKit"

## Software Environment

- Python ≥ 3.9
- RDKit (open-source, BSD license)
- Jupyter Notebook (for example workflows)

## Molecular Structure Generation

All molecular structures were generated from SMILES definitions using
RDKit's ETKDG embedding protocol. Hydrogen atoms were added explicitly
prior to embedding.

## Geometry Optimization

Embedded structures were optimized using the MMFF94 force field as
implemented in RDKit. Default convergence criteria were used.

## Descriptor Calculation

Physicochemical descriptors reported in the paper, including molecular
weight, LogP, topological polar surface area (TPSA), hydrogen bond donors,
and hydrogen bond acceptors, were computed using standard RDKit descriptor
functions.

## Determinism and Variability

ETKDG embedding includes stochastic elements. While overall structural
features are reproducible, minor geometric variations between runs are
expected. No claims of unique ground-state conformations are made.

## Scope Limitation

The repository is intended as a computational reference for molecular-scale
analysis only. It does not constitute a mechanical, biological, or clinical
performance model.
