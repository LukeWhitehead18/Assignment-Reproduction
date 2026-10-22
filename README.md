# CS 6362 — Assignment 2 Reproduction

This repository contains the PyTorch reproduction code for Assignment 2 of CS 6362: Advanced Machine Learning.

## Notebooks

- `Paper1Implementation-Copy1.ipynb` — Zhang et al., *Understanding Deep Learning Requires Rethinking Generalization* — Figure 1(a–c)
- `Paper2Implementation.ipynb` — Keskar et al., *On Large-Batch Training for Deep Learning: Generalization Gap and Sharp Minima* — Figure 3 (F1, C1, C2)
- `Paper3Implementation.ipynb` — Higgins et al., *β-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework* — Figure 7A/B

## Requirements

The reproductions use Python and PyTorch. Main dependencies include:

- PyTorch
- torchvision
- NumPy
- Matplotlib
- tqdm

A CUDA-capable GPU is recommended.

## Running

Open the corresponding `.ipynb` notebook and run the cells in order. Each notebook downloads or loads the required dataset, trains the models, and generates the reproduced figure.

Due to computational limitations, some experiments use reduced training budgets or experimental grids. These modifications and their effects are documented in the accompanying assignment report.
