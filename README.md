# Kernel Based Molecular Machine Learning for Vector Valued Properties

This repository contains my bachleor thesis conducted at Jacobs University. In this project, I focused on kernel based regression models, specifically on the prediction of the Transition Dipole Moment - a vectorial property of molecules.

## Overview

The primary objective of this work was to evaluate the performance of multivariate models in predicting Transition Dipole Moment in comparison to other kernel-based models. To achieve this, I concentrated on three regression models: Kernel Ridge Regression, Gaussian Process Regression, and Multitask Gaussian Process Regression.

## Technologies and notions learned and used

- KRR
- Gaussian Processes, Probability Theory
- GPR
- MT-GPR
- scikitlearn
- GPytorch
- Custom Hyperparameter Tuning
- Evaluation using Validation set (MAE minimization)
- Learning curves with random shuffling
- Plotting log scaled data with matplotlib
- QML Library for molecular data

## Data Limitations

Unfortunately, the original datasets  and theirs shuffles utilized for this research are not included in this repository due to their substantial size. However, these can be recreated by running the ``main.ipynb`` notebook again. More detailed instructions in the ``Thesis`` folder and the actual notebook. This experiment was ran on two datasets, one containing a Benzene trajectory with 768 molecues, and one a Porphyrin trajectory with 151 molecules.

## Validation with Dummy Dataset

To ensure the robustness of the implemented algorithms, a dummy dataset was also tested. This synthetic dataset comprises 3000 observations generated from a linear combination of trigonometric and exponential functions. It was later presented that the molecular datasets had oversights, hence this test dataset.



## Repository Structure

Found in the next folder.
