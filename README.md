Kernel Based Molecular Machine Learning for Vector Valued Properties was my thesis at Jacobs University. The idea is to determine whether multivariate models perform better at predicting the Transition Dipole Moment ( physical, vectorial property of molecules) than other kernel-based models. This specific work is focused on three regression models: Kernel Ridge Regression, Gaussian Process Regression, and Multitask Gaussian Process Regression.
Unfortunately the datasets used are not present in this repository, as they vastly exceed the size limit ( 151 observations of porphyrin molecules and 768 observations of benzene molecules in their DFTB form).

However, to double check the implementation of the algorithms, I have created a dummy dataset of 3000 observations sampled from a linear combination of trigonometric and exponential functions.