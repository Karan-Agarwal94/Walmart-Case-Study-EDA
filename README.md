# Walmart Black Friday Customer Spending Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blueviolet)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-teal)
![Statistics](https://img.shields.io/badge/Statistics-CLT%20%26%20CI-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Project Overview

This project analyzes **Walmart Black Friday sales data** to understand **customer spending behavior** across different demographic segments such as **gender, marital status, and age groups**.

Given the **highly skewed nature of retail transaction data**, the analysis leverages **statistical inference techniques**, specifically:

- **Central Limit Theorem (CLT)**
- **Confidence Intervals (90%, 95%, 99%)**

to make **reliable, population-level business conclusions**.

---

## Business Objectives

The project answers key business questions such as:

- Do **male and female customers** differ in average spending?
- Does **marital status** significantly affect purchase behavior?
- Are spending patterns consistent across **different age groups**?
- How can Walmart use **confidence intervals** instead of point estimates for better decision-making?

---

## Key Concepts Used

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Univariate & Bivariate Analysis
- Outlier Detection (Business-aware handling)
- Central Limit Theorem (CLT)
- Sampling Distributions
- Confidence Interval Estimation
- Business Interpretation of Statistical Results

---

## Dataset Information

- **Total Transactions:** ~550,000+
- **Unique Customers:** ~5,900
- **Features:** 10 columns
- **Target Variable:** `Purchase` (transaction amount)

### Key Features:
- Gender  
- Age Group  
- Marital Status  
- City Category  
- Occupation  
- Product Category  
- Purchase Amount  

> The dataset is pre-cleaned with **no missing values**, making it ideal for statistical analysis.

---

## Analysis Performed

### Exploratory Data Analysis
- Distribution analysis of purchase amounts
- Right-skewed spending behavior confirmed
- High-value purchases retained as **genuine business signals**

### Bivariate Analysis
- Gender vs Purchase
- Marital Status vs Purchase
- Age Group vs Purchase

### Statistical Inference (CLT)
- Sampling distributions created for different sample sizes
- Normality of sample means observed despite skewed raw data

### Confidence Interval Analysis
- Confidence intervals computed for:
  - Male vs Female customers
  - Married vs Unmarried customers
  - All Age Groups
- Confidence levels used: **90%, 95%, 99%**

---

## Key Insights

### 🔹 Gender
- Male customers show **statistically higher average spending**
- Confidence intervals **do not overlap**
- Difference is **statistically significant but modest**

### 🔹 Marital Status
- Confidence intervals **overlap substantially**
- Marital status alone is **not a strong spending differentiator**

### 🔹 Age Groups
- Average spending is **largely consistent across age groups**
- Older age segments show **slightly higher upper bounds**
- Indicates premium purchase tendencies rather than higher averages

---

##  Business Recommendations

- ❌ Avoid aggressive **demographic-only targeting**
- ✅ Focus on **behavioral signals** (basket size, frequency, product categories)
- 📈 Use **confidence intervals instead of single averages** for forecasting
- 🎯 Combine demographics with purchasing behavior for smarter segmentation

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy (Statistical Analysis)**

---

## 📁 Repository Structure

```text
├── data/
│   └── walmart_data.txt
├── notebooks/
│   └── Walmart_Black_Friday_Analysis.ipynb
├── reports/
│   └── Walmart_Business_Case.pdf
├── README.md
├── .gitignore
├── LICENSE

Author

Karan Agarwal
🎓 MSc AI/ML — Scaler Neoversity
💼 Aspiring Data Analyst / Data Scientist

🔗 GitHub: https://github.com/Karan-Agarwal94
🔗 LinkedIn: https://www.linkedin.com/in/karan-agarwal-jain94

⭐ Final Note

This project emphasizes statistical thinking over surface-level metrics, showcasing how real-world business decisions should be backed by distribution-aware, uncertainty-conscious analysis.

If you found this project useful, feel free to ⭐ the repository!