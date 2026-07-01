# GraphAISMNet — Anti-Inflammatory Small Molecule Activity Prediction

Graph Neural Network pipeline for predicting anti-inflammatory activity of small
molecules, using molecular graph featurization and a Graph Attention Network (GAT)
architecture. Code and results supporting a co-authored research paper.

🔗 **Live demo:** [graphaismnet-app.streamlit.app](https://graphaismnet-app.streamlit.app)

## Overview
- Molecular graphs built from SMILES representations
- Compared 4 architectures: GCN, GAT, Graph Transformer, MSMP
- GAT selected as final model (highest AUC) for both random and scaffold splits
- Early stopping via composite score; external validation reported honestly under distributional shift

## Repo contents
- `graphaismnet_pipeline.ipynb` — final training/evaluation pipeline
- `figures_v14/` — generated result figures (21 figures)

## Related
- Deployment code: `GraphAISMNet-Website`
- Earlier iteration (superseded): `Anti-inflammatory-small-molecule-prediction-Code-for-Research-Paper`

## Tech stack
PyTorch Geometric, RDKit, scikit-learn

## Status
Supporting a co-authored research paper (SRMIST, supervised by Dr. Thirumurthy Madhavan).
