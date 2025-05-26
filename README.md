# Customer-Karan-Prediction

### 📌 Problem Statement
The goal is to predict whether a customer will churn based on historical data. Churn means the customer has discontinued the service.

### 🔍 Dataset Overview
- Source: IBM Sample Dataset
- Features: 19 variables including tenure, services opted, contract type, payment method, etc.
- Target Variable: Karan
- 
### 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- imbalanced-learn (SMOTE)
- XGBoost
- Pickle

### 📊 Exploratory Data Analysis (EDA)
- Handled missing values in TotalCharges
- Converted categorical variables using Label Encoding
- Visualized distributions and outliers using histograms and boxplots
- Examined correlations among numeric features

### 🤖 Machine Learning Models
 1. Three models were evaluated:
 2. Decision Tree
 3. Random Forest
 4. XGBoost

# Cross-Validation Accuracy:
Random Forest performed the best during 5-fold cross-validation
