# Employee_Attrition_Analysis_Using_Power_BI

## Overview

The HR Analytics Dashboard is an interactive Power BI project designed to analyze workforce data and provide insights into employee attrition, demographics, education, job satisfaction, and age distribution.

The project uses SQL Server for data cleaning and transformation and Power BI for visualization, helping HR teams make data-driven decisions.

---

## Dashboard Preview

The dashboard includes:

- Total Employees
- Active Employees
- Employee Attrition
- Attrition Rate
- Average Employee Age
- Department-wise Attrition
- Education Field-wise Attrition
- Employee Distribution by Age Group
- Attrition Rate by Gender and Age Group
- Job Satisfaction Rating by Job Role

---

## Project Features

- Data Cleaning using SQL
- Duplicate Data Removal
- Attrition Calculation
- Interactive Power BI Dashboard
- Department Analysis
- Education Analysis
- Gender-based Attrition
- Age Group Analysis
- Job Satisfaction Matrix

---

## Dataset

The dataset contains employee information such as:

- Employee ID
- Age
- Gender
- Department
- Education Field
- Job Role
- Attrition Status
- Job Satisfaction
- Business Travel
- Marital Status
- Monthly Income
- Years at Company
- Performance Rating
- and other HR-related attributes.

---

## Technologies Used

- Power BI Desktop
- Microsoft SQL Server
- SQL
- Microsoft Excel (optional for preprocessing)

---

## Data Cleaning Steps

The SQL script performs:

1. Added `attrition_value` column
   - Yes = 1
   - No = 0

2. Removed unnecessary columns.

3. Checked duplicate employee records.

4. Removed duplicate rows.

5. Prepared cleaned data for Power BI visualization.

---

## Dashboard KPIs

- Total Employees
- Active Employees
- Attrition Count
- Attrition Rate
- Average Age

---

## Visualizations

- Department-wise Attrition (Pie Chart)
- Education Field Attrition (Bar Chart)
- Employee Distribution by Age Group
- Attrition Rate by Gender
- Job Satisfaction Rating Matrix

---

## Project Structure

```
HR-Analytics-Dashboard/
│
├── HR_Analytics.sql
├── HR Analytics dashboard.pdf
├── README.md
└── requirements.txt
```

---

## How to Run

1. Import the HR dataset into SQL Server.
2. Execute the SQL script (`HR_Analytics.sql`).
3. Import the cleaned data into Power BI.
4. Build or open the dashboard.
5. Refresh the visuals.

---

## Future Improvements

- Predict employee attrition using Machine Learning.
- Add dynamic drill-through reports.
- Department-level KPI pages.
- Employee retention forecasting.
- Real-time database connectivity.

---

## Author
Raviteja Kola

