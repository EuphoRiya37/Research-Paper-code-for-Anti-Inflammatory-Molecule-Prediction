# GraphAISMNet — Anti-Inflammatory Small Molecule Activity Prediction

Graph Neural Network pipeline for predicting anti-inflammatory activity of small
molecules, using molecular graph featurization and a Graph Attention Network (GAT)
architecture.

🔗 **Live demo:** [graphaismnet-app.streamlit.app](https://graphaismnet-app.streamlit.app)
📄 Code accompanying our research paper (see companion repo: `Anti-inflammatory-small-molecule-prediction-Research-Paper`)

## Overview
- Molecular graphs built from SMILES representations
- Compared 4 architectures: GCN, GAT, Graph Transformer, MSMP
- GAT selected as final model (highest AUC) for both random and scaffold splits
- Early stopping via composite score; external validation reported honestly under distributional shift

## Repo contents
- `GCN_AISM_v10_fast.ipynb` — main training/evaluation pipeline
- `figures_v10fast/` — generated result figures

## Tech stack
PyTorch Geometric, RDKit, scikit-learn

## Status
Research code supporting a submitted paper (co-authored, SRMIST, supervised by Dr. Thirumurthy Madhavan).
