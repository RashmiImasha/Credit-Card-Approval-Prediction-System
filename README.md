# Credit Card Approval Prediction System 💳

- A Machine Learning-based system designed to predict credit card approval by analyzing applicant demographic, financial, and behavioral data. 
- This project focuses on handling real-world challenges such as high-dimensional data, missing values, and class imbalance.

---

## 📌 Project Overview

Financial institutions must evaluate thousands of credit card applications efficiently while minimizing risk. Manual decision-making is slow and inconsistent.

This project builds an **end-to-end ML pipeline** that:
- Processes large-scale applicant and credit history data
- Engineers meaningful features
- Handles class imbalance
- Trains classification models to predict credit approval risk

---

## ⚙️ Machine Learning Pipeline

```mermaid
graph TD
A[Application Data + Credit Data] --> B[Data Cleaning]
B --> C[Feature Engineering]
C --> D[Normalization & Scaling]
D --> E[Outlier Removal (IQR)]
E --> F[Encoding (OneHot)]
F --> G[Merge Datasets]
G --> H[Target Variable Creation]
H --> I[Feature Selection]
I --> J[Train-Test Split]
J --> K[SMOTE (Imbalance Handling)]
K --> L[Model Training]
L --> M[Evaluation]
```
