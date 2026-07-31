# 👥 HR Analytics Dashboard

> End-to-End HR Analytics Project using Python

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-darkblue)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightgrey)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-green)
![Dashboard](https://img.shields.io/badge/Dashboard-HR%20Analytics-red)

---

# 📌 Project Overview

Employee attrition is one of the biggest challenges for organizations because replacing employees is costly and time-consuming.

This project analyzes the IBM HR Analytics dataset to identify factors related to employee turnover and provide actionable business recommendations through Exploratory Data Analysis (EDA) and an Executive Dashboard.

---

# 🎯 Business Problem

The HR department wants to answer several important questions:

- Which employees are most likely to resign?
- Does overtime increase attrition?
- Which job roles have the highest turnover?
- Does salary affect employee retention?
- Which age groups require more HR attention?

---

# 🎯 Project Objectives

- Perform data cleaning and feature engineering
- Explore employee demographics
- Analyze employee attrition
- Identify important HR trends
- Build an Executive HR Dashboard
- Generate business insights and recommendations

---

# 📂 Dataset

**Dataset : IBM HR Analytics Employee Attrition**

- Employees : **1,470**
- Features : **35**
- Target Variable : **Attrition**

---

# 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- GitHub

---

# 🔄 Project Workflow

```
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Business Insights
        ↓
Executive Dashboard
```

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- No missing values
- No duplicate records
- Removed non-informative columns
  - EmployeeCount
  - EmployeeNumber
  - StandardHours
  - Over18
- Created Age Group
- Created Income Level
- Created Tenure Group

---

# ⚙ Feature Engineering

New business-oriented features:

| Feature | Description |
|----------|-------------|
| AgeGroup | Employee age categories |
| IncomeLevel | Low / Medium / High income |
| TenureGroup | Years at company categories |

---

# 📊 Exploratory Data Analysis

The analysis includes:

- Employee Age Distribution
- Monthly Income Distribution
- Attrition Distribution
- Attrition by Department
- Attrition by Job Role
- Attrition by Age Group
- Attrition by Income Level
- Attrition by Overtime
- Correlation Analysis

---

# 📈 Executive Dashboard

> Executive HR Dashboard

<p align="center">

<img src="dashboard.png" width="95%">

</p>

---

# 💡 Business Insights

### 1. Overtime employees have significantly higher attrition rates.

Employees who frequently work overtime are much more likely to leave the company.

---

### 2. Certain Job Roles experience the highest employee turnover.

HR should prioritize retention strategies for these positions.

---

### 3. Younger employees show higher attrition.

Employees in younger age groups tend to leave more frequently than senior employees.

---

### 4. Lower-income employees are more likely to resign.

Compensation appears to influence employee retention.

---

### 5. Long-tenure employees demonstrate stronger loyalty.

Employees with longer service periods generally have much lower attrition.

---

# 📌 Business Recommendations

Based on the analysis, HR should consider:

- Reduce excessive overtime
- Improve onboarding programs
- Review compensation for lower-income employees
- Create career development plans
- Increase employee engagement initiatives
- Strengthen retention strategies for high-risk job roles

---

# 📁 Repository Structure

```
HR-Analytics-Dashboard/
│
├── data/
│   ├── data_IBM.csv
│
├── dashboard.png
│
├── HR_Analytics.ipynb
│
└── README.md
```

---

# 📊 Key KPIs

| KPI | Value |
|------|------:|
| Employees | 1,470 |
| Attrition | 237 |
| Attrition Rate | 16.12% |
| Average Age | 36.9 Years |
| Average Monthly Income | $6,503 |
| Average Tenure | 7 Years |

---

# 🚀 Future Improvements

- Interactive Power BI Dashboard
- Tableau Dashboard
- Machine Learning Attrition Prediction
- SHAP Feature Importance
- Employee Risk Scoring

---

# 👩 Author

**Tiara Azahra Wika Putri**

Master of Mathematics

Aspiring Data Analyst

GitHub:
https://github.com/azahratawp-ctrl
