# Car Price Prediction using Machine Learning

This project aims to predict **car prices** based on various features such as brand, year, mileage, fuel type, transmission, and other specifications using **machine learning models**.  
It demonstrates a full **data science workflow** — from data preprocessing and visualization to model building, evaluation, and prediction.

---

## Project Overview

In today’s used car market, determining the right selling price is challenging due to numerous influencing factors.  
This notebook analyzes car datasets and builds predictive models to estimate prices accurately.

### Key Objectives
- Clean and preprocess the dataset for missing and inconsistent values.  
- Perform **exploratory data analysis (EDA)** to find insights and relationships.  
- Build and compare multiple ML models (e.g., Linear Regression, Random Forest, XGBoost).  
- Evaluate performance using metrics like **R² score**, **RMSE**, and **MAE**.  
- Predict car prices for new data entries.

---

## Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Visualization
  - `scikit-learn` – ML modeling
  - `xgboost` – Advanced ML algorithm (if used)
  - `joblib` – Model saving/loading

---

## Workflow

1. **Data Import & Cleaning**
   - Handle missing values, duplicates, and outliers.
   - Convert categorical variables into numerical using label/one-hot encoding.

2. **Exploratory Data Analysis**
   - Visualize price distribution.
   - Correlation heatmaps.
   - Feature importance.

3. **Model Building**
   - Split data into training and testing sets.
   - Train models like:
     - Linear Regression  
     - Decision Tree / Random Forest  
     - XGBoost (optional)

4. **Model Evaluation**
   - Compare models using:
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)
     - R² Score

5. **Prediction**
   - Predict car prices for sample or unseen data.

---

## Results

| Model | R² Score |
|--------|-----------|
| Linear Regression | 0.64 | 


---

## 🧠 Insights
- Year of manufacture and mileage are key factors influencing price.
- Certain brands retain higher resale value.
- Engine power and fuel type significantly affect pricing trends.

---


