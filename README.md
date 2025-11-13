# California Housing: Linear vs Logistic Regression

This project analyzes the California Housing dataset using different machine learning models to predict and classify median house values.

## Overview
The goal of this analysis is to:
- Predict median house value using **Linear Regression**
- Classify homes as *High Value* or *Low Value* using **Logistic Regression** and **Random Forest**
- Compare model performance, interpret feature importance, and visualize key relationships.

## Models Used
- Linear Regression  
- Logistic Regression  
- Random Forest Classifier  

## Methods
- Data exploration and visualization (correlation heatmaps, scatter plots, map-style plots)  
- Feature scaling and model training  
- Evaluation using metrics such as **MAE**, **RMSE**, **R²**, **Accuracy**, **Precision**, **Recall**, and **ROC-AUC**

## Key Insights
- **Median Income (MedInc)** is the strongest predictor of house value.  
- **Location** (Latitude and Longitude) also has a major influence — coastal areas tend to have higher house prices.  
- The **Random Forest** model achieved the highest overall accuracy.

## Tools and Libraries
- Python  
- scikit-learn  
- pandas  
- matplotlib  
- seaborn  

## File
- `California_Housing_Analysis.ipynb` — Jupyter Notebook with full code, explanations, and visualizations.

---

*Created as part of a Machine Learning assignment exploring regression and classification models.*
