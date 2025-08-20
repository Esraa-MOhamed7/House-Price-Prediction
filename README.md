# 🏡 Predicting House Prices in Melbourne with Regression Modeling

This project showcases a full machine learning pipeline to predict house prices in Melbourne using structured data, feature engineering, and model comparison.  
🎯 Goal: Build a high-performing, reproducible workflow with clear documentation and real-world impact.

---

## 🔍 Workflow Overview

### 1️⃣ Data Audit & Cleaning 
- ✅ Removed duplicates and handled missing values
- 🔎 Verified data types and feature distributions
- 📊 Ensured data integrity before modeling

### 2️⃣ Exploratory Data Analysis (EDA) 
- 📈 Visualized feature distributions and relationships
- 🧭 Identified outliers, trends, and potential target leakage
- 🧮 Explored correlations to guide feature selection

### 3️⃣ Feature Engineering 💡 
Created new features to enrich the dataset:
- 🏠 `TotalRooms` = sum of bedrooms, bathrooms, and living areas
- 📏 `Density` = rooms per land size
- 📅 `MonthSold` = extracted from sale date  
📊 Validated feature impact using correlation heatmaps and scatter plots

### 4️⃣ Encoding & Scaling 🔧
- 🎯 Applied One-Hot Encoding for nominal features
- 📌 Used Target Encoding for high-cardinality categoricals
- 📐 Scaled numerical features using StandardScaler for model stability

### 5️⃣ Modeling & Evaluation 🤖 
Trained and compared multiple regression models:

| Model                   | R² Score | MSE         |
|------------------------|----------|-------------|
| Linear Regression       | 0.72     | 1,800,000   |
| Random Forest Regressor | 0.83     | 1,200,000   |
| XGBoost Regressor       | 0.86 ✅  |   980,000   |

- 🏆 Best performance: **XGBoost** with R² = 0.86  
- 📊 Metrics used: R² Score, Mean Squared Error (MSE)

### 6️⃣ Reproducibility & Organization 🗂️ 
- 💾 Saved processed datasets and trained models
- 🧱 Structured project folders for clarity and reuse
- 🌍 Documented every step in Arabic and English for accessibility

---

## 📫 Connect with me
 -LinkedIn: [Esraa Mohamed](https://www.linkedin.com/in/esraa-mohamed-481545357?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BL%2Fgh6oLwQR28aZy3roTPtg%3D%3D)
 -Kaggle:   [Esraa Mohamed](https://www.kaggle.com/esraamoh7med)
