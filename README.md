# IJCLab_Bc2JpsiD*

This repository contains scripts and notebooks used for the analysis and classification of the decay process **Bc → J/ψ D\***. The project involves preprocessing, model training, evaluation, and signal extraction.

## 📁 Repository Structure

Here’s a brief overview of the key files in this repository:

### 📊 Jupyter Notebooks
- **D_star.ipynb** – Preselection the D*.
- **Jpsi.ipynb** – Preselection the J/ψ.
- **IMPORTAN.ipynb** – Used Preselections.
- **MODELS.ipynb** – Searching for signal model for normalization channel.
- **NN.ipynb** – BDT - first attempt.
- **NN_Kfold.ipynb / NN_Kfold copy.ipynb / NN_Kfold_.ipynb** – BDT applying.
- **calculations.ipynb** – calculations for number of events and BR.
- **fakedatasets.ipynb** – Generation otoys for testing.
- **mass_sideband.ipynb** – Mass sideband analysis, likely for background modeling.
- **model_searching.ipynb** – Searching for signal model.
- **preselection_K3pi.ipynb / preselection_Kpipi0.ipynb** – Preselection.
- **signal_model.ipynb / supersignalmodel.ipynb** – Signal modeling for fits and classification.
- **main.ipynb / main.py** – superfirst script.

### 📦 Model Files
- **best_kfold_early_stopping_model.json** – JSON structure of the best trained model with early stopping.
- **best_optuna_model.pkl** – Serialized Optuna-optimized model (Pickle format).

## 🧠 Machine Learning Overview

- Models: Neural Networks, Optuna tuning
- Techniques: K-Fold Cross-validation, Early stopping, Signal vs Background classification
- Tools: Scikit-learn, Keras/Tensorflow (assumed from naming), matplotlib, pandas
---
