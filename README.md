# Loan Prediction & Credit Risk Analysis

## Project Overview
This project is part of the AnalystLab Africa program. The objective is to build an automated Machine Learning pipeline and predictive model to evaluate loan applications, minimize financial default risks, and optimize approval processes for banking institutions.

## Repository Structure
- `Loan_Prediction_Week2.ipynb` : The main Jupyter Notebook containing the full end-to-end workflow (Data Cleaning, Preprocessing, Exploratory Data Analysis, Feature Engineering, and Machine Learning preparation).
- `data/`
  - `train_loan.csv` : The original raw dataset.
  - `final_loan_data.csv` : The final processed and ML-ready dataset.
- `reports/` : Business Understanding and Data Preprocessing reports.
- `images/` : Visualizations (Correlation Heatmap, Feature Importance, Count Plots, etc.).

## Tools & Libraries Used
- **Language:** Python
- **Environment:** Jupyter Notebook / JupyterLab
- **Data Manipulation & Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning & Preprocessing:** Scikit-learn (StandardScaler, RandomForestClassifier, etc.)

## Summary of Steps
1. **Data Cleaning & Preprocessing:** Handled missing values (median/mode imputation), corrected data types, and removed duplicates.
2. **Feature Engineering:** Created `Total_Income` and encoded categorical variables (Label & One-Hot Encoding).
3. **Scaling & Outliers:** Applied `StandardScaler` and treated extreme values using the IQR method.
4. **Feature Selection:** Evaluated feature correlations via a Heatmap and determined predictive power using Random Forest Feature Importance (`Credit_History` identified as the primary driver).
5. **Visualizations:** Generated and analyzed 6 core visual representations of the data.
