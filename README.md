# Predicting Happiness (Regression Analysis)

This project was completed as part of **UCLA’s CS M148: Introduction to Data Science** course (Fall 2025).  
It explores how economic prosperity relates to national happiness scores using regression modeling.

## Objective
Build and evaluate **Least Absolute Deviation (LAD / L1)** and **Least Squares (LS / L2)** regression models to predict 
happiness scores from **log GDP per capita** using data from the *World Happiness Report*.

## Methods
- Data cleaning and preprocessing with **pandas** and **numpy**  
- Model training with **scikit-learn**  
- Performance evaluation using **RMSE**, **MAE**, **MAD**, and **R²**  
- Visualization of residuals and fitted relationships with **matplotlib** and **seaborn**

## Results
- Dataset includes **150+ countries**  
- **LAD model** outperformed **LS model** in robustness to outliers  
- Achieved **R² ≈ 0.65** and **r ≈ 0.80**, indicating strong correlation between GDP and happiness  
- Visualizations reveal a clear upward trend linking economic prosperity and subjective well-being

## Tools
Python · pandas · numpy · scikit-learn · matplotlib 


