# Linear Regression from Scratch – Housing Dataset

## Overview
This repository contains a Jupyter Notebook implementation of **linear regression**, including data preprocessing, exploratory data analysis (EDA), outlier detection, visualization, and model construction using the Housing dataset.

The project focuses on understanding the complete linear regression workflow and data preparation steps rather than relying entirely on high-level machine learning libraries.

---

## Repository Structure

├── AS-05_Huseyn_.ipynb
├── HousingData.csv
└── README.md

## Dataset Information
- **Dataset:** Housing Dataset
- **Target Variable:** `MEDV` (Median value of owner-occupied homes)
- Missing values are handled by removing incomplete rows.
- Outliers are detected and filtered using the **Interquartile Range (IQR)** method.

---

## Methodology
The notebook follows these main steps:

1. **Data Loading and Inspection**
   - Reading the dataset
   - Checking data types and missing values

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Feature inspection
   - Correlation analysis

3. **Outlier Detection and Removal**
   - IQR-based method applied to numerical features

4. **Data Visualization**
   - Correlation heatmaps
   - Feature relationships

5. **Linear Regression Implementation**
   - Step-by-step implementation
   - Model understanding and evaluation

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Veynorex/Linear-Regression-From-Scratch.git


3. Open the notebook (if you are using vscode, then open with vscode, it has its own jupyter notebook extension)
   ```bash
   jupyter notebook LinearRegression.ipynb

## Important Note

⚠️ **Train–Test Split Not Applied**

This implementation focuses on understanding the mechanics of linear regression, data preprocessing, and exploratory data analysis.  
For simplicity and educational purposes, the model is trained on the **entire dataset**, and **no train–test split is performed**.

As a result:
- Evaluation metrics may be **optimistic**
- The emphasis is on **conceptual clarity rather than generalization**

