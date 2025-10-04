# Wine Quality Prediction using Random Forest

This project uses a Random Forest classifier to predict the quality of wine as either **high quality** or **ordinary quality** based on various physicochemical properties.

## Overview

- Dataset consists of chemical features like acidity, sugar, pH, sulphates, alcohol, etc.
- Target variable: wine quality, converted into binary classes (high vs ordinary).
- Exploratory Data Analysis (EDA) performed to understand feature distributions and correlations.
- Model training includes baseline Random Forest and hyperparameter tuning with GridSearchCV.
- Performance evaluation with accuracy and ROC-AUC scores.
- Visualization of ROC curves for baseline and tuned models.

## Features

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

## Tools and Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Results

- Tuned model accuracy: ~91.56%
- Tuned model ROC-AUC: ~0.93
