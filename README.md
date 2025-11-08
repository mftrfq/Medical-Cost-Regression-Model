# Medical Cost Regression Model

## 📖 Overview
This project develops a **regression model** to predict individual **medical insurance costs** based on various demographic and lifestyle features such as age, BMI, smoking status, and region.  
The notebook demonstrates the complete machine learning workflow — from data preprocessing, exploratory data analysis (EDA), and feature encoding to model evaluation and deployment preparation.

---

## 🧩 Workflow Summary

### 1. Data Preparation
- Dataset: *Medical Cost Personal Dataset*  
- Features include:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, and `charges` (target)
- Tasks performed:
  - Handle missing or inconsistent values  
  - Encode categorical variables (`LabelEncoder` / `OneHotEncoder`)  
  - Feature scaling (if applicable)  

### 2. Exploratory Data Analysis (EDA)
- Analyze feature distribution
- Correlation heatmap to detect relationships between predictors and medical charges  
- Key observations:
  - Smokers show the highest increase in medical costs  
  - BMI and age have strong positive correlations with insurance charges  

### 3. Modeling
Multiple regression models were trained and compared:
- **Linear Regression**  
- **Ridge Regression**  
- **Lasso Regression**  
- **Random Forest Regressor**    

### 4. Model Evaluation Example
Each model was evaluated using:
- **R² (Coefficient of Determination)**  
- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  
