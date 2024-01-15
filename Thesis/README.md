# Important

The notebook _main.ipynb_ contains the setup functions, in which the necessary files are created. If the binary files molecule representations or shuffles are deleted, the other notebooks will not work until _main.ipynb_ is run first.

Additionally, for the dummy datasets, the files _dummy_krr.ipynb_ and _rotated_dummy_krr.ipynb_ contain the shuffle creation functions. If the dummy shuffles are deleted, the other dummy notebooks will not work until the two above are run.

## Notebooks

Below is provided an overview of the Jupyter Notebooks used in the thesis

- **main.ipynb:** Contains the setup for all the necessary files for the molecular data, as well as Kernel Ridge Regression for both molecular datasets. Please run this first.

- **gpr.ipynb:** Gaussian Process Regression for the benzene and porphyrin datasets. Found in folder _GPR_

- **mtgpr.ipynb:** Multitask Gaussian Process Regression for benzene and porphyrin datasets. Found in folder _GPR_

- **dummy_krr.ipynb:** Kernel Ridge Regression for the dummy data, as well as the shuffling creation of the dummy data. Please run this before other dummy data notebooks. Found in folder _Dummy Data_

- **rotated_dummy_krr.ipynb:** Kernel Ridge Regression for the rotated dummy dataset, as well as the shuffling creation of the rotated dummy data. Please run this before other rotated dummy data notebooks. Found in folder _Dummy Data_

- **dummy_gpr.ipynb:** Gaussian Process Regression for the dummy dataset. Found in folder _Dummy Data_

- **rotated_dummy_gpr.ipynb:** Gaussian Process Regression for the rotated dummy dataset. Found in folder _Dummy Data_

- **dummy_mtgpr.ipynb:** Multitask Gaussian Process Regression for the dummy dataset. Found in folder _Dummy Data_

- **rotated_dummy_mtgpr.ipynb:** Multitask Gaussian Process Regression for the rotated dummy dataset. Found in folder _Dummy Data_

- **hypertuning.ipynb:** Hyperparameter tuning for the benzene dataset. Porphyrine dataset was too small to present any meaningful results.

- **dummy_hyperparam_training.ipynb:** Hyperparameter tuning for the dummy datasets.

## Thesis Structure

The code for this thesis has the following directory structure:

```bash
├───Benzene files_tdm
├───Binaries
├───Dummy Data
│ └───Dummy Shuffles
├───Final Plots
│ ├───Benzene Dataset
│ ├───Dummy Dataset
│ └───Porphyrin Dataset
├───GPR
├───InitialData
├───Molecular Shuffles
├───POR
└───POR_files
```

### Description of directories

- **Benzene files_tdm:** Contains the molecule representations for the benzene dataset.

- **Binaries:** Contains the binary files used as input data.

- **Dummy Data:** Contains all the files necessary for the dummy data experiments.

- **Final Plots:** Contains the final plots of the thesis, which can also be found in the respective Jupyter notebooks. It includes subdirectories for different datasets, namely "Benzene Dataset," "Dummy Dataset," and "Porphyrin Dataset."

- **GPR:** Contains the GPR and MTGPR files for the molecular datasets.

- **InitialData:** Contains the initial data given for the benzene dataset.

- **Molecular Shuffles:** Contains the shuffle files for the two molecular datasets.

- **POR:** Contains the initial data given for the porphyrin dataset.

- **POR_files:** Contains the molecule representations for the porphyrin dataset.
