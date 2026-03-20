# Credit Card Approval Prediction System 💳

- A Machine Learning-based system designed to predict credit card approval by analyzing applicant demographic, financial, and behavioral data. 
- This project focuses on handling real-world challenges such as high-dimensional data, missing values, and class imbalance.

---

## Project Overview

Financial institutions must evaluate thousands of credit card applications efficiently while minimizing risk. Manual decision-making is slow and inconsistent.

This project builds an **end-to-end ML pipeline** that:
- Processes large-scale applicant and credit history data
- Engineers meaningful features
- Handles class imbalance
- Trains classification models to predict credit approval risk

---

## Machine Learning Pipeline

<img src="MLpipeline.png" height="700">

---

## Tech Stack

Programming : Python
Libraries : Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Imbalanced-learn (SMOTE)
ML Models: Logistic Regression | SVM
Concepts : Machine Learning | Classification | Imbalanced Data Handling | Feature Engineering | Data Preprocessing | Model Evaluation

---

## Key Observations

- Logistic Regression and SVM achieved similar performance **(~63% test accuracy)**, indicating linear separability of selected features
- Improved detection of risky applicants with **recall up to 58%** after applying SMOTE
- Successfully handled extreme **class imbalance using SMOTE**
- **Feature engineering** (age, experience, income scaling) played a critical role in **improving model performance**
- **Reduced dataset dimensionality** from 50+ features to key predictive variables using **correlation analysis**
- Built a complete end-to-end ML pipeline from raw data to prediction
- Models demonstrated consistent performance across training and testing datasets, indicating stable learning

---

## Business Impact

- Enables financial institutions to identify high-risk applicants early, reducing potential credit losses
- Improves decision-making by automating credit approval screening
- Helps prioritize risk detection (high recall), which is critical in fraud/default scenarios
- Reduces manual effort and increases operational efficiency in loan processing

---



