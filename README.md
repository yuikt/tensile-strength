# Tensile Test Simulation using FEniCS (Dolfin) and Sfepy

This repository was created as part of my personal practice exploring **Finite Element Method (FEM)** analysis workflows with FEniCS and Sfepy. The script demonstrates to test a simple tensile strength using 2D linear elasticity.
  
It calculates **maximum displacement** and **von Mises stress** for each specimen based on experimental data.

- `tensile_data.csv` stores demo data for five specimens.
- Creates a 2D rectangular mesh for each specimen (length × thickness).
- Defines material properties using isotropic linear elasticity.
- Computes:
  - Maximum nodal displacement.
  - Maximum von Mises stress.


## **To install FEniCS**
Open terminal and run as follows:
1. Create a new Conda environment with FEniCS called fenics-env.
    `conda create -n fenics-env -c conda-forge fenics`

2. Activate the environment
    `conda activate fenics-env`

3.Verify installation
Run Python and test:
`import dolfin
print(dolfin.__version__)`

