# Generated-Data

## Project 1: Physics-Guided Deep Generative Model for New Ligand Discovery

This project leverages a physics-aware variant of the MolGAN framework (PhyMolGAN) for discovering novel ligands. The model integrates structural data with or without physics-based descriptors derived from the **PDBbind** dataset.

### Dataset

The datasets are organized by PDBbind version and presence of Without physics-based features:

- **PDBbind v19**
  - With physics features: **samples**
  - Without physics features: **5 samples**

- **PDBbind v2020**
  - With physics features: **samples**
  - Without physics features: **samples**

Each sample includes structural, molecular, and optionally physics-guided descriptors used in training or evaluating the model.

### Each subdirectory contains:
  - Generated ligand files in `.sdf.gz` format for various force fields (`add`, `gna`, `pkt`, `uff`)
  - Source ligand and receptor structures (`src.sdf.gz`)
  - File naming follows the pattern:  
    `DEMO_pdbbindtest_<ID>_lig_gen_fit_<ff>.sdf.gz`

