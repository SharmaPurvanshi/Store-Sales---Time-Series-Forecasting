# Store-Sales---Time-Series-Forecasting
Kaggle Competetion(Knowledge)

This project focuses on predicting store sales using machine learning techniques, specifically Random Forest and LightGBM. The data is preprocessed and feature engineering is performed to enhance the predictive power of the models. The analysis also includes visualizations to understand sales patterns better.

## Project Overview

1. **Data Preprocessing and Feature Engineering:**
    - Handling missing values.
    - Encoding categorical variables.
    - Merging multiple datasets (stores, transactions, holidays, oil prices).
    - Creating new features from temporal data and external factors.

2. **Exploratory Data Analysis (EDA):**
    - Visualizing sales over time.
    - Analyzing sales by day of the week, month, and store type.
    - Examining the relationship between sales and oil prices.
    - Correlation analysis between numerical features.

3. **Model Training and Evaluation:**
    - Training Random Forest and LightGBM models.
    - Hyperparameter tuning.
    - Evaluating model performance using RMSE and R² metrics.

## Requirements

The project requires the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- lightgbm
