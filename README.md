# Medical Insurance Cost Analysis and Prediction System

## 📌 Project Overview

The **Medical Insurance Cost Analysis and Prediction System** is a data analytics and machine learning project that analyzes medical insurance customer data to understand factors affecting insurance charges and predict future medical insurance costs.

Insurance companies collect large amounts of customer information such as age, gender, BMI, number of children, smoking habits, and region. Manually analyzing these records for premium estimation and risk assessment is difficult and time-consuming. This project automates the analysis process using Exploratory Data Analysis (EDA), Machine Learning models, and Interactive Dashboard Visualization.

The project uses the **Medical Cost Personal Dataset** from Kaggle and applies:

* Exploratory Data Analysis (EDA)
* Linear Regression
* Multiple Linear Regression
* Logistic Regression
* Interactive Dashboard using Plotly

---

# 🎯 Problem Statement

Health insurance companies need accurate methods to estimate insurance premiums and identify high-risk customers.

Incorrect premium estimation can lead to:

* Financial losses for insurance companies
* Unfair premium charges for customers
* Poor risk assessment
* Inefficient policy planning
* Reduced decision-making accuracy

This project develops an automated system that analyzes customer data and predicts insurance costs while identifying customers likely to generate high medical expenses.

---

# 📂 Dataset Information

### Dataset Name

Medical Cost Personal Dataset

### Dataset Source

Kaggle

### Dataset Link

https://www.kaggle.com/datasets/mirichoi0218/insurance

### Dataset Features

| Feature  | Description                  |
| -------- | ---------------------------- |
| age      | Age of customer              |
| sex      | Gender of customer           |
| bmi      | Body Mass Index              |
| children | Number of dependent children |
| smoker   | Smoking status               |
| region   | Residential region           |
| charges  | Medical insurance charges    |

---

# 🎯 Project Objectives

## 1. Data Collection

* Load dataset from Kaggle
* Understand dataset structure
* Explore available features
* Identify independent and dependent variables
* Analyze customer demographics

---

## 2. Data Cleaning & Preprocessing

* Check missing values
* Handle null values
* Remove duplicate records
* Verify data types
* Encode categorical variables
* Prepare data for machine learning

---

## 3. Descriptive Statistics

Calculate:

* Average Age
* Average BMI
* Average Number of Children
* Average Insurance Charges

Analyze:

* Mean
* Median
* Standard Deviation
* Minimum and Maximum Values

---

## 4. Insurance Cost Analysis

Compare insurance charges among:

* Smokers vs Non-Smokers
* Male vs Female Customers
* Different Age Groups
* Different BMI Categories
* Different Regions

Identify high-cost customer segments.

---

## 5. Group-Based Analysis

Perform analysis based on:

* Age vs Charges
* BMI vs Charges
* Children vs Charges
* Region vs Charges
* Gender vs Charges
* Smoking Status vs Charges

---

## 6. Relationship Analysis

Study relationships between:

* Age and Charges
* BMI and Charges
* Children and Charges
* Smoking Status and Charges

Identify the strongest factors influencing insurance premiums.

---

# 📊 Data Visualization

The project includes various visualizations:

### Bar Charts

* Average Charges by Region
* Average Charges by Smoking Status

### Histograms

* Age Distribution
* BMI Distribution
* Charges Distribution

### Scatter Plots

* Age vs Charges
* BMI vs Charges

### Box Plots

* Outlier Detection
* Group Comparisons

### Heatmaps

* Correlation Analysis

### Pie Charts

* Gender Distribution
* Smoker Distribution

---

# ⚠️ Risk Analysis

Customers are classified into:

### Low Cost Customers

Customers with lower insurance expenses.

### Medium Cost Customers

Customers with moderate insurance expenses.

### High Cost Customers

Customers with high medical insurance expenses.

Risk analysis helps identify customers likely to generate higher claims.

---

# 🤖 Machine Learning Models

## 1. Simple Linear Regression

### Objective

Predict insurance charges using age.

### Independent Variable

* age

### Dependent Variable

* charges

### Workflow

* Split data into training and testing sets
* Train Linear Regression model
* Predict insurance charges
* Analyze age impact on premiums

---

## 2. Multiple Linear Regression

### Objective

Predict insurance charges using multiple customer attributes.

### Independent Variables

* age
* bmi
* children
* smoker

### Dependent Variable

* charges

### Workflow

* Encode categorical variables
* Train model
* Predict charges
* Compare with Simple Linear Regression

---

## 3. Logistic Regression

### Objective

Classify customers as:

* Low Cost Customer (0)
* High Cost Customer (1)

### Target Creation

Create a new column:

insurance_category

Based on median insurance charges:

* 0 → Low Cost
* 1 → High Cost

### Independent Variables

* age
* bmi
* children
* smoker

### Dependent Variable

* insurance_category

### Workflow

* Create classification target
* Split dataset
* Train Logistic Regression model
* Predict customer category
* Identify high-risk customers

---

# 📈 Model Evaluation

## Linear Regression Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## Multiple Linear Regression Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## Logistic Regression Metrics

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score
* Classification Report

---

# 📊 Interactive Dashboard

The project includes a Plotly Dashboard for interactive exploration.

## Dashboard Components

### Insurance Analysis

* Charges Distribution
* Age vs Charges
* BMI vs Charges
* Smoker vs Non-Smoker Comparison
* Region-wise Charges
* Gender-wise Charges

### Advanced Analysis

* Correlation Heatmap
* High Cost vs Low Cost Distribution
* Risk Category Analysis

---

## Dashboard Filters

Users can interactively filter data using:

* Age Filter
* Gender Filter
* Region Filter
* Smoker Filter
* Number of Children Filter

Dynamic charts update automatically based on selected filters.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn
* Jupyter Notebook

---

# 📁 Project Structure

```text
Medical-Insurance-Cost-Analysis/
│
├── insurance.csv
├── Medical_Insurance_Analysis.ipynb
├── dashboard.py
├── README.md
│
├── images/
│   ├── age_vs_charges.png
│   ├── bmi_vs_charges.png
│   ├── smoker_analysis.png
│   └── heatmap.png
│
└── reports/
    └── final_report.pdf
```

---

# 🔍 Key Insights Expected

* Smoking significantly increases insurance charges.
* Age positively influences insurance premiums.
* Higher BMI often leads to increased medical expenses.
* Multiple Linear Regression performs better than Simple Linear Regression.
* Logistic Regression effectively identifies high-cost customers.
* Smoking status is one of the strongest predictors of insurance cost.

---

# ✅ Conclusion

The Medical Insurance Cost Analysis and Prediction System provides a complete solution for analyzing customer insurance data, predicting medical insurance charges, and identifying high-risk customers. Through EDA, machine learning models, and dashboard visualization, the project helps insurance companies improve premium estimation, risk assessment, and policy planning while enabling data-driven decision-making.

---

# 👨‍💻 Author

**Mukesh Krishna**

Data Analytics & Machine Learning Project

Medical Insurance Cost Analysis and Prediction System
