# 🧠 Employee Attrition Analyzer – Machine Learning Project

### 📍 Open-Ended Machine Learning Lab Project

**Student Name:** RAJA ABDUL RAFAY
**Roll No:** 22F-BSAI-93
**University:** Dawood University of Engineering & Technology

## 📘 Project Overview

This Machine Learning project predicts whether an employee will leave the company (**Attrition: Yes/No**) using HR analytics data.  
It includes **Data Preprocessing, Visualization, Feature Engineering, Model Training, Evaluation, and Model Saving**.

This project fulfills the requirements of an **Open-Ended ML Lab** by implementing:

✔ Multiple ML Models  
✔ Data Preprocessing  
✔ SMOTE for Imbalanced Data  
✔ Model Comparison & Evaluation  
✔ Visual Insights  

---

## 📂 Dataset

**Dataset Title:** IBM HR Analytics Employee Attrition & Performance  
**Source:** Kaggle  
Dataset Link: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset  

| Attribute | Details |
|----------|-----------|
| Total Records | 1470 |
| Target Column | Attrition (Yes/No) |
| Features | Employee Work Data, Salary, Environment, Job Role, Performance |

## 🧹 Data Preprocessing Steps

- Dropped non-useful column: `EmployeeNumber`
- Converted Target to numeric: Yes → 1, No → 0
- One-Hot Encoding for categorical columns
- Train-Test Split: 80% Training, 20% Testing
- Handled imbalance using **SMOTE**
- Scaled features using **StandardScaler**


## 📊 Exploratory Data Analysis (EDA)

Performed the following analysis:

- Dataset Shape & Basic Info
- Missing Values Check
- Numerical vs Categorical Data Summary
- Attrition Distribution
- Correlation Heatmap
- Age Distribution vs Attrition

---

## 🤖 Machine Learning Models Used

Trained and evaluated three classification models:

| Model | Status |
|--------|----------|
| Logistic Regression | ✅ Trained & Evaluated |
| Decision Tree Classifier | ✅ Trained & Evaluated |
| Random Forest Classifier | ✅ Trained & Evaluated |

> Among all, **Random Forest** performed the best and was selected as the final model.


## 📈 Model Evaluation Metrics

- Accuracy Score  
- Precision, Recall & F1-Score  
- Confusion Matrix  
- ROC-AUC Score  
- ROC Curve Comparison  

Also includes visual plots for:

✅ Confusion Matrix for all models  
✅ ROC Curve Comparison  
✅ Feature Importance Bar Graph  


## 🔥 Feature Importance (Random Forest)

Top 15 features affecting employee attrition were visualized to understand major influencing factors.


## 💾 Model Saving

Saved the best model and scaler for future predictions:


