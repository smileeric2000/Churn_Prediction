# 📊 Customer Churn Prediction with XGBoost

This project aims to predict customer churn using machine learning techniques, specifically **XGBoost**. The goal is to identify customers likely to leave a service, allowing for proactive retention strategies.

---

## 🧱 Project Overview

The project follows a standard end-to-end machine learning pipeline:

1. **Data Cleaning** – Handled missing values, removed inconsistencies.
2. **Exploratory Data Analysis (EDA)** – Explored distributions, correlations, and key patterns.
3. **Feature Engineering** – Converted categorical variables, normalized numerical features.
4. **Class Imbalance Handling** – Applied techniques like SMOTE to improve recall on minority class.
5. **Modeling** – Trained and tuned an XGBoost classifier for best performance.
6. **Evaluation** – Assessed using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.

---

## 🔧 Tech Stack

- **Language**: Python 3.x  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, imbalanced-learn

---



## 📂 Project Structure

| Directory/File            | Description                                               |
|---------------------------|-----------------------------------------------------------|
| **data/**                 | Cleaned dataset                                            |
| **notebooks/**            | EDA and modeling Jupyter notebooks                         |
| **models/**               | XGBoost model                                              |
| **README.md**             | Project overview and instructions                          |

---
