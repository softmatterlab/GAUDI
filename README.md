# GAUDI
By Mirja Granfors, Jesús Pineda, Blanca Zufiria Gerbolés, Joana B. Pereira, Carlo Manzo, and Giovanni Volpe.

GAUDI is an unsupervised geometric deep learning framework for analyzing complex graph-structured data. GAUDI's hourglass architecture, with multiple hierarchical pooling and upsampling steps, maps graphs into a structured latent space, capturing their underlying parameters.

This repository contains an implementation of GAUDI, introduced in [Global graph features unveiled by unsupervised deep learning](http://iopscience.iop.org/article/10.1088/2632-2153/ae8d7f).

The `data` folder contains the Single-Molecule Localization Microscopy (SMLM) simulations and the script used to generate the Vicsek model simulations.

## Getting started

An example of how GAUDI is trained on Watts-Strogatz small-world graphs can be found here:

[Training GAUDI on Watts-Strogatz Small-World Graphs](GAUDI_Watts_Strogatz.ipynb)

To run the example, first download or clone this GitHub repository, then run the notebook from within the repository folder.

Running the example takes about **5 minutes** on a standard laptop.

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


# Citation

If you use GAUDI in your project, please cite us:
<http://iopscience.iop.org/article/10.1088/2632-2153/ae8d7f>
```
"Global graph features unveiled by unsupervised deep learning"
Mirja Granfors, Jesús Pineda, Blanca Zufiria-Gerbolés, Joana B. Pereira, Carlo Manzo and Giovanni Volpe
Machine Learning: Science and Technology (2026).
```
