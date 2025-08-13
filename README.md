
# Metro SHAP Analysis

This repository contains code, sample data, and notebooks for metro ridership analysis using SHAP (SHapley Additive exPlanations) and machine learning models such as XGBoost. It also includes clustering analysis based on spatial features and SHAP values.

## 📂 Project Structure
- `Model_comparison.ipynb` — Notebook for model training and performance comparison.
- `kmean.ipynb` — Notebook for clustering analysis (spatial + SHAP-based).
- `xgboostshap.ipynb` — Notebook for XGBoost model training, SHAP value calculation, and visualization.
- `sample_3000.csv` — A randomly sampled dataset (3,000 rows) without missing values for demonstration.
- `.gitignore` — Files and directories ignored by Git.
- `LICENSE` — MIT License for this repository.
- `README.md` — Project description and usage instructions.

## 🚀 Features
- Data preprocessing and cleaning.
- XGBoost regression model with hyperparameter tuning.
- SHAP value computation for global and local interpretability.
- Visualization of SHAP main effects and feature importance.
- Clustering analysis of metro stations based on:
  - Average ridership and spatial coordinates.
  - Average SHAP values.

## 🛠️ Requirements
Install dependencies:
```bash
pip install pandas numpy scikit-learn xgboost shap matplotlib statsmodels

