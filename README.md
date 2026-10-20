# chemml-journey

I'm a synthetic organic chemist (PhD in total synthesis) learning Python, cheminformatics, and machine learning. This repository documents that work, one notebook at a time.

The notebooks start with Python and RDKit basics and build towards machine learning on molecular data. Every example uses public molecules from PubChem, ChEMBL, published papers, or textbooks.

## Notebooks

| # | Notebook | Topics |
|---|---|---|
| 01 | [First molecules](01_first_molecules.ipynb) | SMILES parsing, drawing structures, molecular formula, average and exact mass |

## Setup

The notebooks run in a conda environment named `chemml`:

```bash
conda activate chemml
jupyter lab
```

Main packages: [RDKit](https://www.rdkit.org/) and [matplotlib](https://matplotlib.org/).
