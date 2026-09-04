# Insurance Charges Prediction (Scikit-Learn)

A Machine Learning project focused on Exploratory Data Analysis (EDA) and predicting personal medical insurance costs using traditional regression algorithms.

## Project Overview
This project builds a baseline machine learning model to estimate medical insurance charges based on demographic and lifestyle features (such as age, BMI, smoking status, etc.). It demonstrates the complete data science pipeline from data exploration to model evaluation.

## Pipeline Steps
1. **Exploratory Data Analysis (EDA):** 
   - Inspected dataset structure (`info()`, `describe()`).
   - Visualized feature distributions and relationships using `Seaborn` (Histograms, Pairplots, and Correlation Heatmaps).
   - Analyzed key cost drivers (e.g., impact of smoking and age on charges).
2. **Data Preprocessing:**
   - Converted categorical variables into numerical format using One-Hot Encoding (`pd.get_dummies`).
   - Split the data into training and testing sets (`train_test_split`).
3. **Modeling & Evaluation:**
   - Trained a **Linear Regression** model using **Scikit-Learn**.
   - Evaluated model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and $R^2$ Score.
   - Visualized predicted vs. actual values with scatter plots.

## Tech Stack
- **Python**
- **Scikit-Learn** (Linear Regression, Metrics)
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
