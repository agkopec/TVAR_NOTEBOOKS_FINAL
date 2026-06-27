# NEURAL NETWORK-BASED ESTIMATION OF TIME-DEPENDENT PARAMETERS IN AR(p) PROCESSES

This repository contains Jupyter notebooks accompanying the manuscript *Neural Network-Based Estimation of Time-Dependent Parameters in AR(p) Processes*.

The repository includes three notebooks covering the following experiments:

- synthetic data with Gaussian noise ([`01_GAUSS_SYNTHETIC.ipynb`](01_GAUSS_SYNTHETIC.ipynb))
- synthetic data with Laplace noise ([`02_LAPLACE_SYNTHETIC_GRID.ipynb`](02_LAPLACE_SYNTHETIC_GRID.ipynb))
- real-data experiments using electricity spot prices ([`03_REAL_DATA.ipynb`](03_REAL_DATA.ipynb)).

The real-data experiments use the following Kaggle dataset:

https://www.kaggle.com/datasets/arashnic/electricity-spot-price

## Abstract

We investigate a forecasting framework based on a simple discrete-time dynamic model with coefficients varying in time. The parameters of the model are recovered within a deep learning framework, which makes it possible to retain a transparent parametric structure while simultaneously accounting for complex and nonstationary patterns in the observed phenomenon.

Our analysis covers two specifications of the noise process. Besides the standard Gaussian setting, we also consider Laplace-distributed noise, which can offer a more adequate description in the presence of heavier tails and sharper local fluctuations.

The results illustrate that a relatively simple model, when combined with time-dependent parameter estimation, can serve as a mathematically tractable and practically flexible tool for forecasting complex dynamics under different noise assumptions.
