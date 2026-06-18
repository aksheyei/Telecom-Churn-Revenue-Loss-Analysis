# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

Customer churn is a critical challenge in the telecommunications industry, directly affecting revenue and profitability. This project analyzes customer churn patterns using Python to identify the factors influencing customer attrition, quantify revenue loss, and generate actionable business recommendations.

The project follows a complete data analytics workflow, including data cleaning, exploratory data analysis, statistical testing, and business insight generation.

---

## 🎯 Business Problem

The telecom company is experiencing customer attrition, resulting in revenue loss. The objectives of this analysis are:

- Identify major drivers of customer churn.
- Quantify revenue loss due to churn.
- Understand customer segments with higher churn risk.
- Provide actionable recommendations to improve customer retention.

---

## 📂 Dataset Overview

The dataset contains telecom customer information, including:

- Customer Demographics
- Service Subscriptions
- Internet Services
- Contract Information
- Payment Methods
- Churn Status
- Churn Categories
- Churn Reasons
- Revenue Metrics

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

---

## 🔧 Data Cleaning & Transformation

The following preprocessing steps were performed:

- Removed unnecessary columns.
- Identified and handled missing values.
- Replaced internet-related null values for customers without internet service.
- Replaced missing churn categories and churn reasons for non-churned customers.
- Created a binary churn indicator.
- Created customer age group categories.
- Created tenure categories.

---

## 📊 Exploratory Data Analysis

Customer churn was analyzed across multiple dimensions:

### Customer Attributes

- Gender
- Age Group
- Tenure Category

### Service Attributes

- Internet Type
- Contract Type
- Offer Type
- Payment Method

### Churn Attributes

- Churn Category
- Churn Reason

### Revenue Analysis

Revenue loss was analyzed across:

- Churn Categories
- Churn Reasons
- Contract Types
- Internet Types

---

## 📈 Statistical Analysis

### Chi-Square Test

The following relationships were tested:

1. Contract Type vs Customer Churn
2. Internet Type vs Customer Churn
3. Tenure Category vs Customer Churn

### ANOVA Test

ANOVA was performed to determine whether revenue loss differs significantly across churn categories.

---

## 🔍 Key Findings

- Customer churn is influenced by contract structure.
- Certain internet service types exhibit higher churn rates.
- Customer tenure is associated with churn likelihood.
- Revenue loss varies across churn categories.
- Competitor-related reasons contribute significantly to churn.
- Customer dissatisfaction is a major contributor to attrition.

---

## 💡 Business Recommendations

### 1. Target High-Risk Customers

Develop proactive retention campaigns for customers with higher churn probability.

### 2. Improve Customer Loyalty

Introduce loyalty programs and rewards for long-tenure customers.

### 3. Enhance Competitive Positioning

Address competitor-related churn through improved pricing and service offerings.

### 4. Optimize Contract Offerings

Review contract structures to improve customer retention.

### 5. Monitor Customer Satisfaction

Implement early-warning systems to identify dissatisfied customers before they churn.

---

## 📋 Project Workflow

```text
Raw Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Statistical Testing
    │
    ▼
Revenue Loss Analysis
    │
    ▼
Business Insights
    │
    ▼
Recommendations
```

## 📊 Dashboard Preview

### Customer Churn Dashboard

Add your Power BI screenshots below:

```markdown
![Dashboard Overview](images/dashboard_overview.png)

![Revenue Analysis](images/revenue_analysis.png)

![Churn Drivers](images/churn_drivers.png)
```

---

## 📁 Repository Structure

```text
Telecom-Customer-Churn-Analysis/
│
├── data/
│   └── telecom_churn_cleaned.xlsx
│
├── notebooks/
│   └── Telecom_Customer_Churn_Analysis.ipynb
│
├── dashboard/
│   └── Telecom_Churn_Dashboard.pbix
│
├── images/
│   ├── dashboard_overview.png
│   ├── revenue_analysis.png
│   └── churn_drivers.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Statistical Hypothesis Testing
- Revenue Analytics
- Business Intelligence
- Data Visualization
- Customer Segmentation
- Power BI Dashboard Development
- Business Problem Solving

---

## 📌 Results

This project successfully identified key churn drivers, quantified revenue loss, and generated actionable recommendations that can help telecom organizations improve customer retention and reduce revenue leakage.

---

## 👨‍💻 Author

**Akshay**

Aspiring Data Analyst | Python | SQL | Power BI | Statistics

If you found this project useful, feel free to ⭐ the repository.
