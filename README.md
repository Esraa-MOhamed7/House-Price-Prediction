# 🏡 Predicting House Prices in Melbourne with Regression Modeling

This project showcases a full machine learning pipeline to predict house prices in Melbourne using structured data, feature engineering, and model comparison.  

---

## Workflow Overview

###  Data Audit & Cleaning 
-  Removed duplicates and handled missing values
-  Verified data types and feature distributions
-  Ensured data integrity before modeling

### Exploratory Data Analysis (EDA) 
-  Visualized feature distributions and relationships
-  Identified outliers, trends, and potential target leakage
-  Explored correlations to guide feature selection

### Feature Engineering  
Created new features to enrich the dataset:
-  `TotalRooms` = sum of bedrooms, bathrooms, and living areas
-  `Density` = rooms per land size  
- Validated feature impact using correlation heatmaps and scatter plots

### Encoding & Scaling 
-  Applied One-Hot Encoding for nominal features
-  Used Target Encoding for high-cardinality categoricals
-  Scaled numerical features using StandardScaler for model stability

###  Modeling & Evaluation  
Trained and compared multiple regression models:

| Model                   | R² Score | MSE         |
|------------------------|----------|-------------|
| Linear Regression       | 0.72     | 1,800,000   |
| Random Forest Regressor | 0.83     | 1,200,000   |
| XGBoost Regressor       | 0.86 ✅  |   980,000   |

- Best performance: **XGBoost** with R² = 0.86  
- Metrics used: R² Score, Mean Squared Error (MSE)
