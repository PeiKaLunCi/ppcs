# Polynomial Preconditioner for Compressed Sensing

This repository reproduces the experiments in
[Accelerating Convergence of Proximal Methods for Compressed Sensing using
Polynomials with Application to MRI](https://arxiv.org/abs/2204.10252).

Written by Siddharth Srinivasan. Please post an issue on the repository
page if there is a problem.

## Installation.

Run the following commands in sequence to run the experiments.

1. `conda update -n base -c defaults conda`
2. `make conda`
3. `conda activate ppcs`
4. `make pip`

## Data.

For most experiments, the corresponding data are located in the `data`
folder.
For the `mrf3d` experiment, please run `bash download_data.sh` in the
`data/mrf3d` folder to download the data.

## Run experiments.

- All experiments are in the form `demo_*.py`.
- An experiment can be performed by running, for example, `python3 demo_brain.py`.
- The respective Jupyter notebooks can be used to generate images.
- The Jupyter notebooks must be started after running Step 3 above.
- Additionally, LaTeX is required to render equations in the plots.

## Uninstall.

To uninstall, run the following commands:

1. `conda activate`
2. `make clean`

## Packages used:

- [SigPy](https://github.com/mikgroup/sigpy) [![DOI](https://zenodo.org/badge/139635485.svg)](https://zenodo.org/badge/latestdoi/139635485)
- [SymPy](https://github.com/sympy/sympy) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5558034.svg)](https://doi.org/10.5281/zenodo.5558034)
- [Chebyshev](https://github.com/mlazaric/Chebyshev) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5831845.svg)](https://doi.org/10.5281/zenodo.5831845)

## DOI
[![DOI](https://zenodo.org/badge/452385092.svg)](https://zenodo.org/badge/latestdoi/452385092)
