# California Housing: Linear vs Logistic Regression

This project explores the California Housing dataset using machine learning models to predict and classify median house values.

## Overview
The analysis compares:
- **Linear Regression** — predicting continuous house values  
- **Logistic Regression** and **Random Forest** — classifying homes as *High* or *Low* value  

## Methods
- Data exploration with visualizations (correlation heatmap, scatter plot, map plot)  
- Feature scaling and model training  
- Model evaluation with **MAE**, **RMSE**, **R²**, **Accuracy**, **Precision**, **Recall**, and **ROC-AUC**

## Key Findings
- **Median Income (MedInc)** is the strongest factor affecting house value.  
- **Location** (latitude & longitude) also has a clear impact — coastal areas are most expensive.  
- **Random Forest** achieved the highest accuracy and recall.

## Tools
Python • scikit-learn • pandas • matplotlib • seaborn

---

*Jupyter Notebook: `California_Housing_Analysis.ipynb`*

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/ml-california-housing.git
   cd ml-california-housing
