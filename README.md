# Introduction

This repository contains a collection of standalone python scripts that may be used to generate simple plots from files of given formats.
The purpose is simply to provide some basic code exposure and scripting help to students who are just learning computational chemistry methods.

As these scripts are generated and made available, this README will be updated to reflect them.

Each script is meant to run without dependencies beyond a standard `conda` installation, and in such cases where a dependency is necessary, 
the script will first check for it and if unable to locate it, will advise the user on method by which it may be installed.

## Visualizers

**PDBtoChemDraw**
- Generates a 2D ChemDraw-style structure from a provided single-molecule PDB.

**SMILEStoChemDraw**
- Generates a 2D ChemDraw-style structure from a provided SMILES string.

## Converters

**MOLtoPDB**
- Generates a PDB from a MOL file, such as from [MolView](https://molview.org)/
- Requires installation of [Chimera](https://www.cgl.ucsf.edu/chimera/)

## Helpful Colab Notebooks
**EasySolventMixturesForMolecularDynamics** [<img src="https://colab.research.google.com/assets/colab-badge.svg">](https://colab.research.google.com/github/markahix/CompChemUtilities/blob/main/HelpfulColabNotebooks/EasySolventMixturesForMolecularDynamics.ipynb)
- Streamlines the creation and use of custom solvent boxes for classical MD setups.  Allows for mixtures of arbitrary number of user-provided molecules.

**Clustering_From_CPPTRAJ** [<img src="https://colab.research.google.com/assets/colab-badge.svg">](https://colab.research.google.com/github/markahix/CompChemUtilities/blob/main/HelpfulColabNotebooks/Clustering_From_CPPTRAJ.ipynb)
- Creates simple scatter plots of 2D data with markers colored by cluster number as provided by CPPTRAJ outputs.  Current version requires Google Drive access.
