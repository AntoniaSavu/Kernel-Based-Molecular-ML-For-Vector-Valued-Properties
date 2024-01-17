# Kernel Based Molecular Machine Learning for Vector Valued Properties

This repository contains my bachleor thesis conducted at Jacobs University. In this project, I focused on kernel based regression models, with a specific focus on the prediction of the Transition Dipole Moment - a vectorial property of molecules.

## Overview

The primary objective of this work was to evaluate the performance of multivariate models in predicting Transition Dipole Moment in comparison to other kernel-based models. To achieve this, I concentrated on three regression models: Kernel Ridge Regression, Gaussian Process Regression, and Multitask Gaussian Process Regression.

## Technologies and notions learned and used

- KRR
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

Unfortunately, the original datasets utilized for this research are not included in this repository due to their substantial size. The datasets consist of 151 observations of porphyrin molecules and 768 observations of benzene molecules in their DFTB form. The initial files and the molecular representations ( using Coulomb Matrices) could not be added due to their size). These can be further supplied for replication of experiment.

## Validation with Dummy Dataset

To ensure the robustness of the implemented algorithms, a dummy dataset has been provided in this repository. This synthetic dataset comprises 3000 observations generated from a linear combination of trigonometric and exponential functions.



## Repository Structure

Found in the next folder.
