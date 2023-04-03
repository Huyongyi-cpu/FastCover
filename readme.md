# README 

Code for the paper :

_FastCover: Graph Reversed Attention Framework for Maximum Coverage Problem

## Important Python Libraries
- igraph=0.9.1
- torch=1.8.1
- dgl=0.6.0 (based on the CUDA version)
- furl=2.0.0
- timeout-decorator=0.5.0

## Instructions

### File Organization

- `data/graphs/`: Some small graphs for training and test
- `model/`: Loss functions and GNN layers (implemented in `dgl`)
- `experiments/`: Training and evaluation launchers.
- `baselines/`: Heuristic algorithms for 

### Graph Reversed Attention Network (GRAT)

To train a GRAT solving k-dDSP, run the demo `experiments/train_models.py`.

To evaluate the model, run `exeriments/evaluate_models.py`
