# Customer Churn Analysis

## Project Overview
This project analyzes customer churn for a fictional telco company using Python. The goal is to identify key patterns, trends, and actionable insights to help reduce churn and improve customer retention.

The analysis includes:
- Exploratory Data Analysis (EDA)
- Data Cleaning and Feature Engineering
- Churn patterns by contract type, tenure, and payment method
- Visualizations for key metrics
- Data-driven insights with actionable recommendations

---

## Dataset
- Source: IBM Telco Customer Churn dataset
- Format: Excel (.xlsx)
- Records: 7043 customers
- Features: 33 columns including customer demographics, account information, services subscribed, charges, and churn information.

Key columns:
- `CustomerID`: Unique customer identifier
- `Gender`, `Senior Citizen`, `Partner`, `Dependents`
- `Tenure Months`, `Contract`, `Payment Method`
- `Monthly Charge`, `Total Charges`
- `Churn Label` / `Churn Value`

---

## Tools & Libraries
- Python 3.x
- Pandas & NumPy
- Matplotlib & Seaborn for visualization
- Jupyter Notebook for analysis and documentation

---

## Analysis Steps

1. **Data Loading & Initial Inspection**  
   - Loaded Excel dataset into Pandas DataFrame
   - Checked for nulls and data types

2. **Data Cleaning & Feature Engineering**  
   - Converted `Total Charges` to numeric and handled missing values
   - Created binary `churn_flag` from `Churn Label`
   - Created tenure groups for analysis

3. **Exploratory Data Analysis (EDA)**  
   - Calculated overall churn rate
   - Visualized churn by contract type, tenure group, and monthly charges
   - Analyzed payment method impact on churn

## 4. Insights & Recommendations

- **'Month-to-month' contract customers** show highest churn: 42.71%  
  **Action:**  
  Introduce loyalty incentives or longer-term plans

- **Customers in tenure group '0-1 yr'** have highest churn risk: 47.68%  
  **Action:**  
  Target first-year customers with onboarding campaigns

- **Average monthly charges for churned customers:** $74.44  
  **Average monthly charges for retained customers:** $61.27  
  **Action:**  
  Offer flexible payment options for high-paying customers

- **Long-tenure customers (4+ yr)** are most stable with churn rate 9.51%  
  **Action:**  
  Reward loyalty through special offers or upselling

- **Customers using 'Electronic check' payment method** have highest churn: 45.29%  
  **Action:**  
  Simplify or incentivize preferred payment methods


---

## Key Visualizations
- Bar charts: Churn by Contract Type and Tenure Group  
- Box plots: Monthly Charges vs Churn  
- Summary statistics: Average charges, churn percentages

---

## Conclusion
This project highlights:
- Use of Python libraries for data analysis and visualization  
- Exploration of customer churn through EDA and feature engineering  
- Derivation of actionable insights from customer data  
- Clear visual storytelling through charts and summaries


---

## How to Run
1. Clone the repository  
2. Ensure Python 3.x is installed  
3. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn

