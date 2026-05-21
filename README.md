# Machine_Learning-Project

# 📊 Marketing Revenue Prediction using Machine Learning

## 🚀 Project Overview
This project focuses on predicting revenue generated from marketing campaigns using Machine Learning techniques. The objective is to analyze marketing performance data and identify key factors influencing revenue generation.

A Random Forest Regression model is used to learn relationships between features such as budget, clicks, conversions, ROI, discount levels, and customer engagement metrics.

---
## Dataset Link

[Dataset Link](https://www.kaggle.com/datasets/imranalishahh/marketing-and-product-performance-dataset)

## 📂 Dataset Information

| Feature | Description |
|--------|------------|
| Total Records | 10000 |
| Total Features | 16 |
| Target Variable | Revenue_Generated |
| Missing Values | None |

---

## 🔀 Train-Test Split

| Dataset Type | Samples |
|-------------|--------|
| Training Set | 8000 (80%) |
| Testing Set | 2000 (20%) |
| Total Dataset | 10000 |

---

## ⚙️ Technologies Used
- Python 🐍  
- Google Colab  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🤖 Machine Learning Model
- Random Forest Regressor

---

## 📈 Model Performance

| Metric | Value |
|--------|------|
| Mean Squared Error | 818624596.26 |
| R2 Score | -0.0039 |

---

## 📊 Feature Importance Analysis

| Feature | Importance Level |
|--------|------------------|
| Budget | High |
| Clicks | High |
| Conversions | High |
| ROI | Medium |
| Discount Level | Medium |

---

## 📊 Key Insights
- Marketing Budget strongly impacts revenue generation  
- Clicks and Conversions are major performance indicators  
- ROI and Discounts also influence revenue outcomes  
- Relationships in data are nonlinear  

---

## 📁 Project Structure

Marketing-ML-Project
├── marketing_project.ipynb
├── marketing_dataset.csv
├── report.pdf
├── README.md
└── images/
└── actual_vs_predicted.png
