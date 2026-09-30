# 🚗 Used Vehicle Price Prediction

> Regression project predicting used-vehicle prices from vehicle attributes — EDA, feature engineering and model comparison.

## The Problem
Used-vehicle pricing depends on dozens of interacting factors (age, mileage, brand, fuel type, condition…). This project builds a regression model that estimates a fair price from a vehicle's attributes.

## The Data
Vehicle listings dataset (see `Data/`), with features such as make/model, year, mileage, fuel type, transmission and condition, plus the target: price.

## Approach
1. **EDA** — price distributions by brand, fuel type and age; correlation analysis to find the strongest price drivers; outlier treatment.
2. **Feature engineering** — vehicle age from year, mileage binning, one-hot encoding of categoricals, scaling of numerics.
3. **Modeling** — train/test split, then compared regression models (e.g. Linear Regression, Random Forest, Gradient Boosting) with cross-validation.
4. **Evaluation** — RMSE / MAE and R² on the held-out test set.

## Key Results
- **Best model:** [e.g. Gradient Boosting]
- **Test R²:** [fill in] · **RMSE:** [fill in]
- **Top price drivers:** [e.g. vehicle age, mileage, brand — fill in from your feature importances]

## Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Jupyter

## Project Structure
```
├── Used-Vehicle-Price-Prediction.ipynb   # Full workflow: EDA → modeling → evaluation
└── Data/                                 # Dataset
```

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Used-Vehicle-Price-Prediction.ipynb
```
