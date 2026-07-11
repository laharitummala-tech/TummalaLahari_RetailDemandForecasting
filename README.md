# Retail Demand Forecasting

## Project Overview

This project predicts Walmart weekly sales using machine learning techniques. Historical sales, promotions, holidays, store information, and economic indicators were used to build a forecasting model.

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Hyperparameter Tuning (Optuna)
- Time Series Validation
- Model Explainability (SHAP)
- Robustness Testing

---

## Dataset

The project uses:
- train.csv
- features.csv
- stores.csv

---

## Models

- Linear Regression
- Random Forest
- XGBoost
- XGBoost (Optuna Tuned)

---

## Final Model

The final model selected is **XGBoost (Optuna)**.

Performance:
- Validation MAE: **1209.71**
- Validation RMSE: **2536.66**
- Validation WMAE: **1250.61**
- Validation R²: **0.987**

---

## Repository Structure

```
data
notebook
process_doc
README.md
requirements.txt
```

---

## Files

- `TummalaLahari_RetailDemandForecasting.ipynb` – Complete implementation
- `Retail_Demand_Forecasting_Process_Flow.pdf` – Detailed workflow documentation

---

## Author

**Tummala Lahari**
