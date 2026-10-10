# thesis-repository
Code implementation and numerical experiments for my MSc thesis, testing different image reconstruction approaches for a deblurring task.

This repository contains the code and experiments developed for my thesis titled **"From Analytical Regularisation to Learned Priors: A Spectrum of Approaches to Image Deblurring"**, completed for **Laurea Magistrale in Matematica, Università degli Studi di Ferrara**.

All the code is provided as Jupyter Notebooks, pre-loaded with execution outputs that correspond to the results reported and discussed in the thesis.

## Overview & Requirements
### Dataset Preparation
Before running any analysis or model notebooks, **you must first execute the `prepare_UrbanDataset.ipynb` notebook**.

* **Urban Images Dataset:** Running `prepare_UrbanDataset.ipynb` downloads the urban image dataset and automatically generates and saves the dataset splits required by all other notebooks.
* **Randomness & Reproducibility Note:** Due to random seed assignments during data splitting/initialisation, executing `prepare_UrbanDataset.ipynb` again may produce dataset splits that differ slightly from the pre-computed outputs shown in the saved notebooks.
* **Medical Images:** The repository includes the two specific medical images selected for the experiments analysed in the thesis. However, the codebase is modularly designed so that alternative images can easily be substituted and evaluated.

## Hardware & Execution Environment
The original code and outputs were executed using Python 3 environments employing hosted GPU accelerators (NVIDIA Tesla T4 and NVIDIA A100) and high-RAM system instances.

## Getting Started
```bash
git clone https://github.com/IreneCarra21/thesis-repository.git
cd thesis-repository
