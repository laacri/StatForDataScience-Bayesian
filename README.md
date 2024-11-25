# StatForDataScience-Bayesian

This repository hosts the final project material for the course Statistical Methods In Data Science II. The course focuses on Bayesian inference techniques for approximation of unknown parameters of interest, that provide a valuable tool in addressing a variety of tasks including regression and classification.

The project consists in the development and test of Bayesian models to perform regression. The parameters are estimated through Gibbs sampling and Monte Carlo Markov Chains, assessing convergence with appropriate diagnostics, then compared with the results of a frequentist model and finally the best performing model is chosen.

The datased used is publicly available on Kaggle at this [link].

This repository contains the files:

- `CPU_benchmark.csv`: the dataset;
- `model_1.txt`, `model_2.txt`, `model_3.txt`: JAGS models;
- `SDS II Final Project.Rmd` main file;
- `SDS II Final Project.Rmd` rendered version of the main file;
- `seagreen3_style.css` custom style for the rendered document.

[link]: https://www.kaggle.com/datasets/alanjo/cpu-benchmarks