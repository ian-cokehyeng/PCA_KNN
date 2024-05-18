# Comparing Preprocessing Methods for KNN Classification

A quick demonstration of common preprocessing techniques applied to the `Biomechanical features of orthopedic patients` for binary class prediction using the `KNeighborsClassifier`. Original feature values were processed using dimensionality reduction (PCA), scaling (StandardScaler), both, or none. All techniques influence how distance is measured which is crucial for algorithms such as KNN. GridsearchCV was applied for determining the optimal model for each preprocessing pipeline and the resulting test accuracy was used to evaluate and compare.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

## Installation

To install this project, follow these steps:

```bash
conda env create -f environment.yml -n custom_env_name
```

This command will create a new Conda environment that includes the dependencies needed for the project.

## Usage

To use this project, follow these steps:

```bash
conda activate <env_name>
jupyter notebook
```

Replace `<env_name>` with the name of the Conda environment specified above. This will activate the environment and start Jupyter Notebook, where you can open and run the notebook file.

## Contributors

The following individuals have contributed to this project:

- Ian CoKehyeng
