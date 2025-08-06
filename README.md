<img width="1343" height="767" alt="image" src="https://github.com/user-attachments/assets/20721db9-cbe1-4391-b1d0-f2dc7d30dc99" />

# Income, Spending, and Saving Overview by Demographic Group

## 📌 Table of Contents

1. [Dataset Description](#dataset-description)
2. [Dashboard Structure](#dashboard-structure)
3. [Key Takeaways & Recommendations for Individuals](#key-takeaways--recommendations-for-individuals)
4. [✅ Recommendations by Structure](#-recommendations-by-structure)
5. [Tools Used](#tools-used)
6. [File](#file)

---

This Tableau dashboard provides a comprehensive analysis of personal financial behavior based on demographic factors such as age and occupation. The goal is to uncover trends in income, spending, and saving patterns to offer actionable insights for individuals.

## Dataset Description

**Financial Literacy Dataset** is a synthetic personal finance dataset that simulates key financial behaviors such as income, spending, saving habits, and potential savings.

* **Size**: 20,000 rows and 27 columns
* **Data Quality**: No missing or duplicate values

The dataset can be categorized into four major feature groups:

1. **Demographics & Personal Info**: `Income`, `Age`, `Dependents`, `Occupation`, `City_Tier`
2. **Annual Spending Categories**: `Rent`, `Loan_Repayment`, `Insurance`, `Groceries`, `Transport`, `Eating_out`, `Entertainment`, `Utilities`, `Education`, `Miscellaneous`
3. **Saving Details**: `Desired_Savings_Percentage`, `Desired_Savings`, `Disposable_Income`
4. **Potential Saving Opportunities**: Derived fields estimating how much one could save per category

**Data Source & Simulation**:

* Synthetic data generation based on real-world distributions
* Based on **Bureau of Labor Statistics (BLS.gov)** public data (Reference: Spending by age range, 2023)
* Used CSV data (`financial-literacy-data.csv`) as cleaned mock base and XLSX (`reference-person-age-ranges-2023.xlsx`) as distribution reference

**Analysis Goals**:

* Uncover financial trends across 20,000 individuals
* Understand differences between demographic groups
* Help individuals benchmark their habits against similar groups
* Provide insights for financial institutions to personalize product segmentation

## Dashboard Structure

The dashboard is divided into four analytical sections:

### 1. **KPI Overview**

Provides a high-level summary of key financial metrics across the dataset:

* **Average Income**: \$74,503.05
* **Average Expenditure**: \$66,196.25
* **Average Saving**: \$8,306.81
* **Sample Size**: 20,000 individuals
* **Average Age**: 41

### 2. **Analysis by Age Group**

Visualizations include:

* Financial distribution by age
* Expense breakdown by age group
* Total spending distribution by age group

**Insights:**

* Middle-aged groups (36-55) tend to have the highest expenditures.
* Younger age groups (18-25) save significantly less.
* Transportation and insurance dominate expenses across all ages.

### 3. **Analysis by Occupation**

Visualizations include:

* Spending structure by occupation
* Financial distribution (income, expenditure, saving) by occupation

**Insights:**

* **Self-employed** individuals have slightly higher savings than others.
* **Students** spend the least but also save the least.
* Spending habits differ, but savings capacity seems consistent in proportion.

### 4. **Saving-Spending-Income Relationship**

A scatter plot explores the correlation among total spending, income, and saving.

**Insights:**

* Positive correlation between income and savings, but not perfectly linear.
* Individuals with higher total spending don't always have higher savings.
* Highlights the importance of spending discipline regardless of income level.

## Key Takeaways & Recommendations for Individuals

* If you belong to younger age groups or student status, consider building saving habits earlier.
* Use spending categories to identify over-expenditure habits, such as shopping or entertainment.
* Visualize your own income/saving pattern against the dataset to self-evaluate.
* Apply budgeting tools to reduce non-essential spending and increase long-term savings.

---

## ✅ Recommendations by Structure

### 1. KPI Overview

💡 *Interpretation*: Provides a snapshot of overall financial health.

**Recommendation:**

* Use the KPI values to benchmark your personal finance.
* If your income is above average but saving is below \$8,306/year, consider reviewing your expense structure.

### 2. Analysis by Age Group

💡 *Interpretation*: Identifies financial trends across different life stages.

**Recommendation:**

* Individuals aged **18–25**: Start building saving habits early, even if income is low. Use budgeting apps to monitor expenses.
* Age **36–55**: Highest spending group — review large recurring expenses (e.g., transport, insurance) and cut unnecessary costs.
* For all age groups: Periodically review your savings-to-income ratio and adjust discretionary spending.

### 3. Analysis by Occupation

💡 *Interpretation*: Spending and saving behaviors differ by job roles.

**Recommendation:**

* **Students**: Track every expense and reduce non-essential spending like takeout or shopping.
* **Self-employed**: Take advantage of flexible income to set monthly saving targets. Use tools like cash flow forecasting.
* **Professionals & Retired**: Focus on maintaining a stable saving plan and preparing for unexpected costs.

### 4. Saving-Spending-Income Relationship

💡 *Interpretation*: Spending more doesn’t always mean saving less — discipline is key.

**Recommendation:**

* Avoid lifestyle inflation — as income grows, avoid letting expenses grow equally.
* Use the visual correlation to self-assess whether you fall into the “high-spending–low-saving” zone.
* Automate your savings (e.g., 20% of income monthly) to prioritize future financial security.

---

## Tools Used

* **Tableau** for dashboard design and data visualization
* **Calculated Fields** in Tableau to derive new insights from raw data

## File

* `spending_overview_dashboard.twbx` (Tableau packaged workbook)

---


