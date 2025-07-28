# Econometrics Academy Project Workspace

This repository contains hands-on implementations of econometric models from the [Econometrics Academy](https://sites.google.com/site/econometricsacademy/econometrics-models) course series.

The goal is to apply each model using real or simulated data in Jupyter Notebooks, reinforcing theoretical concepts with practical code.

---

## 🔍 Project Scope

This workspace covers implementations of the following econometric model categories:

- Linear Regression
- Binary Choice Models
- Panel Data Models
- Instrumental Variables
- Time Series Models
- Simultaneous Equations
- Limited Dependent Variable Models

Each model is organized in a separate notebook under the `notebooks/` directory.

---

## 🗂️ Repository Structure
econometrics/
├── notebooks/              # Jupyter notebooks by model category
│   ├── 01_linear_regression.ipynb
│   ├── 02_logit_probit.ipynb
│   ├── 03_panel_data.ipynb
│   └── …
├── data/                   # Datasets used in the models (not tracked in Git)
├── src/                    # Optional: helper Python scripts
├── environment.yml         # Conda environment to reproduce the setup
├── .gitignore
└── README.md

---

## 📦 Setup Instructions

To reproduce the environment:

```bash
conda env create -f environment.yml
conda activate econ_env