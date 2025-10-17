# HR Analytics Prediction

Predicting employee attrition using HR analytics and machine learning.  
This project explores HR data, performs feature engineering, and builds predictive models to identify key drivers of attrition.

## Overview

Employee attrition impacts productivity and costs.  
This project uses data analysis and machine learning to predict which employees are likely to leave and why.

**Goal:** Build interpretable, accurate models to support HR decision-making.


## Dataset

- **Source:** [Kaggle – HR Analytics Prediction](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction/data)
- **Records:** 1,470 employees, 35 features  
- **Target Variable:** `Attrition` (Yes / No)

Features include demographics, compensation, satisfaction levels, and work-related details.


## Project Steps

1. **Data Cleaning** – Removed redundant columns and standardized names.  
2. **EDA** – Visualized key factors (Overtime, Job Role, Department, Income).  
3. **Feature Selection** – Used LASSO regression to identify important predictors.  
4. **Modeling** – Compared multiple machine learning models:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  
   - AdaBoost  
   - Support Vector Machine (SVC)  
   - K-Nearest Neighbors (KNN)  
   - Naive Bayes  
   - Stochastic Gradient Descent (SGD Classifier)  
5. **Evaluation** – Measured accuracy, ROC AUC, precision, recall, and F1 score.  

## Key Insights

- **Overtime** strongly increases attrition risk.  
- **Lower income** and **early-career** employees are more likely to leave.  
- **High satisfaction** and **better work-life balance** reduce attrition.  
- **Lack of promotion** and **stagnation** increase turnover risk.

## Tools & Libraries

- Python, pandas, numpy  
- scikit-learn (LASSO, Random Forest, SGDClassifier, etc.)  
- matplotlib, seaborn, plotly  
- Jupyter Notebook / Google Colab
