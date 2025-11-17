# HR Employee Attrition Analysis (End-to-End Data Analytics Project)

# Dataset: IBM HR Analytics Employee Attrition Dataset
# Tools Used: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook, Power BI

![Dashboard Preview](dashboard.png)


## Project Overview

Employee attrition is one of the most costly challenges for modern organizations. High turnover negatively impacts productivity, recruitment expenses, team morale, and long-term performance.
In this project, I performed a full end-to-end HR analytics workflow, using the IBM HR Analytics dataset to uncover hidden drivers of workforce attrition, identify high-risk employee groups, and provide data-driven recommendations for retention strategy.



## Analytics Approach

1️⃣ Data Loading & Initial Exploration

- Loaded HR dataset into a Jupyter Notebook
- Reviewed structure, columns, data types
- Checked for missing values & anomalies
- Verified class imbalance in target variable (Attrition)


2️⃣ Data Cleaning

Cleaning included:

✔ Fixing incorrect data types
✔ Standardizing categorical values
✔ Removing duplicates
✔ Handling inconsistencies in fields such as department, marital status, job role
✔ Creating clean and analysis-ready DataFrame

This ensures reliable analysis and prevents misleading insights.


3️⃣ Feature Engineering

- Created meaningful new variables to improve analysis
Feature engineering gives HR actionable segments instead of raw data.



4️⃣ Exploratory Data Analysis (EDA)

- Performed in-depth analysis answering key business questions:

🔹 Attrition Rate Overview
🔹 Univariate & Bivariate Analysis

- Analyzed relationships between attrition and employee key drivers.

🔹 Key Visuals (Python)
- Attrition by Age Group
- Attrition by Department
- Income vs Attrition
- Overtime vs Attrition
- Tenure Curve (Years at Company vs Attrition)
- Correlation Heatmap (Numerical Features)


5️⃣ Power BI Dashboard

An interactive dashboard was created including:
- KPI Cards → Total Employees, Attrition Count, Attrition Rate
- Filters/Slicers → Department, Role, Age Group
Charts:
- Attrition by Job Role
- Attrition by Age Group
- Salary Distribution
- Tenure vs Attrition
The dashboard allows HR managers to drill down into high-risk groups instantly.


## Key Insights 

1️⃣ High-Risk Roles

Roles with the highest attrition include:
- Sales Representatives
- Laboratory Technicians
- HR staff
- Research Scientists
Reason: High stress, competitive job market, workload imbalance.


2️⃣ High-Risk Age Groups

Highest attrition was observed in:
- Younger employees (18–30)
- Motivated by better pay and growth opportunities.
- Mid-career employees (31–40) showed moderate risk.
- Older employees (45+) showed very low attrition.


3️⃣ High-Risk Salary Bands

Employees earning below the median salary showed much higher attrition.
Low-income employees often leave due to:
- Salary dissatisfaction
- Better external offers
- Higher financial pressure


4️⃣ Overtime Strongly Predicts Attrition

Employees regularly working overtime leave at significantly higher rates. This suggests:
- Burnout risk
- Staffing shortages
- Poor work-life balance


5️⃣ Tenure Curve Reveals Attrition Pattern

Attrition is highest for:
- Employees in their first 2 years
- Employees with 7–10 years of tenure
- Low risk beyond 10 years.
This pattern helps shape onboarding and career development programs.



## Project Structure 

HR_Attrition_Analysis/
├── data/
│   └── HR_employee_attrition.csv
|   └── hr_cleaned.csv
|   └── employees_with_risk_score.csv
├── notebooks/
│   └── 01_data_cleaning.ipynb
|   └── 02_eda.ipynb
|   └── 03_modelling.ipynb
├── dashboard/
│   └── HR_Attrition_Dashboard.pbix
├── images/
│   └── dashboard.png
├── Report/
|   └──Insight.md
|   └── HR_Attrition_Dashboard.pdf
│   
└── README.md




## Conclusion

This project demonstrates a full end-to-end HR analytics workflow showing:
- Business understanding
- Data cleaning and feature engineering
- Insight-driven EDA
- Visualization and storytelling
- Dashboard building
- It highlights strong analytics capabilities and a clear understanding of real business challenges.