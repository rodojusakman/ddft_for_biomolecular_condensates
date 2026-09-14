# Dynamical Density Functional Theory Framework for Non-Equilibrium Phase Behavior of Biomolecular Condensates


# DDFT for Biomolecular Condensates

A computational tools implementing **Dynamical Density Functional Theory (DDFT)** to model the non-equilibrium phase separation, spatial organization, and assembly dynamics of biomolecular condensates.

Here is the step-by-step instruction for setting up and running the workflow.

---

## Environment Setup

Use one of the following methods to set up a working environment for `ddft_for_biomolecular_condensates`.

### Conda Environment

The workflow requires specific scientific computing (NumPy, SciPy, PyTorch) and numerical solver for PDE (FiPy) tools, which can be acquired via the Anaconda/Miniconda package manager.


After Anaconda or Miniconda is installed on your machine, create and activate the environment:

```bash
conda env create -f envs/ddft.yml
conda activate ddft
pip install -e .
```

# Code Provenance
The free energy model used in this project is derived from  originally developed by Y.-H. Lin: https://github.com/laphysique/Protein_RPA
A Finite Volume PDE Solver Using Python (Fipy): https://github.com/usnistgov/fipy

# Authors and Contributors
Current development is carried out in the Zerze research group at the University of Houston.
