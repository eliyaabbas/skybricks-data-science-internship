# 📊 Task 1: Customer Churn Data Preparation & EDA

## 📝 Overview
This repository contains the solution for **Task 1: Customer Churn Data Preparation**, part of the SkyBricks Data Science Internship. The primary objective is to clean, prepare, and analyze the Telco customer churn dataset to uncover insights about customer retention and the factors that lead to churn.

## 📁 Files in this Task
* **`WA_Fn-UseC_-Telco-Customer-Churn.csv`**: The original raw dataset containing 7,043 rows and 21 columns detailing customer demographics, account information, and churn status.
* **`CustomerChurn_EDA.ipynb`**: The Jupyter Notebook containing the end-to-end data cleaning, preprocessing, and Exploratory Data Analysis (EDA) pipeline.
* **`CustomerChurn_Cleaned_Task1_Final.csv`**: The fully cleaned and processed dataset ready for predictive modeling.

## 🎯 Objectives Achieved
1. **Data Cleaning**: 
   - Handled missing values (e.g., in `TotalCharges`).
   - Converted data types appropriately for analysis.
2. **Feature Engineering**: 
   - Created specialized features like `Tenure Buckets` and `Monthly Spend Groups`.
3. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions and correlations using Seaborn (`pairplots`, `heatmaps`, `countplots`).
   - Extracted key insights into which features most strongly impact customer churn.

## 🚀 How to Run
1. Ensure you have Python installed with the necessary libraries (`pandas`, `matplotlib`, `seaborn`, `numpy`).
2. Open `CustomerChurn_EDA.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to reproduce the data cleaning and EDA steps.

## 📈 Key Insights
* The analysis highlights specific customer segments with higher churn rates.
* Offers actionable recommendations for retention strategies, such as targeted promotions for high-risk demographics.
