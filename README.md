# Introduction

This repository contains the python code needed to reproduce the paper
[Connectome-Mediated Prediction of Future Tau-PET Burden in Alzheimer’s Disease](https://fortunepublish.com/articles/10.26502.jbb.2642-91280065.pdf).

## Installation

All the python requirements can be installed via:

```
$ conda env create --name brain --file=brain.yml
$ conda activate brain
$ jupyter-lab /notebooks
```

## Notebooks
### 1.Load_and_save_data.ipynb
    - Loads the data and save useful pickle files.

### 2.NDM_model.ipynb
    - Runs NDM model to predict Δτ over time

### 3. Linear
    - Runs linear model to predict  Δτ

### 4. Constant
    - Runs constant model to predict Δτ

### 5. Other_plots
    - Creates R2 plots

## Questions

For questions about this repository, contact prof. Ashish Raj at ashish dot raj @ ucsf.edu or PabloDamasceno at pm.me
