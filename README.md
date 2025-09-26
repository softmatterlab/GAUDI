# GAUDI
By Mirja Granfors, Jesús Pineda, Blanca Zufiria Gerbolés, Joana B. Pereira, Carlo Manzo, and Giovanni Volpe.

GAUDI is an unsupervised geometric deep learning framework for analyzing complex graph-structured data. GAUDI's hourglass architecture, with multiple hierarchical pooling and upsampling steps, maps graphs into a structured latent space, capturing their underlying parameters.

This repository contains an implementation of GAUDI, introduced in [Global graph features unveiled by unsupervised geometric deep learning](https://arxiv.org/abs/2503.05560v2).

## Getting started

An example of how GAUDI is trained on Watts-Strogatz small-world graphs can be found here:

[Training GAUDI on Watts-Strogatz Small-World Graphs](GAUDI_Watts_Strogatz.ipynb)

## Dependencies

To use this implementation, ensure you have the following dependencies installed:

- `deeplay` (tested with `0.1.3`)
- `torch` (tested with `2.6.0` and `2.7.0`)

You can install them using:

```bash
pip install deeplay
```
```bash
pip install torch
```


### Additional dependencies for the example 

If you also want to run the provided Watts-Strogatz example, you’ll need these extra packages:
- `PyGSP` (tested with `0.5.1`)
- `networkx` (tested with `3.4.2`)
- `torch-geometric`(tested with `2.5.2, 2.6.1`)

You can install them using:

```bash
pip install PyGSP
```
```bash
pip install networkx
```
```bash
pip install torch-geometric
```
