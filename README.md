# Global Remote Work & Salary Analytics Dashboard

<img width="1357" height="736" alt="image" src="https://github.com/user-attachments/assets/41974f66-010e-49cb-82e7-662d8825e6b0" />

## Project Overview

This project analyzes global salary trends in the data industry using Power BI.

The dashboard helps answer key business questions:

- Which job roles have the highest salaries?
- How does experience level impact salary?
- How have salaries changed over time?
- What is the distribution of remote, hybrid, and onsite jobs?

---

## Tools Used

- Power BI
- Power Query
- DAX
- CSV Dataset
- GitHub

---

## Dataset

Data Source:
Data Science Salaries Dataset (Kaggle)

The dataset contains information about:

- Job Titles
- Salary (USD)
- Experience Levels
- Employment Type
- Remote Work Ratio
- Company Location
- Work Year

---

## Data Preparation

Data cleaning was performed using Power Query:

- Verified data types
- Created Work Mode column
- Removed inconsistencies
- Prepared dataset for analysis

Example transformation:

0 = Onsite

50 = Hybrid

100 = Remote

---

## DAX Measures

### Average Salary

```DAX
Average Salary =
AVERAGE(ds_salaries[salary_in_usd])
```

### Total Employees

```DAX
Total Employees =
COUNTROWS(ds_salaries)
```

### Maximum Salary

```DAX
Max Salary =
MAX(ds_salaries[salary_in_usd])
```

### Minimum Salary

```DAX
Min Salary =
MIN(ds_salaries[salary_in_usd])
```

---

## Dashboard Features

### KPI Cards

- Average Salary
- Total Employees
- Maximum Salary
- Minimum Salary

### Interactive Analysis

- Salary by Experience Level
- Top Paying Job Titles
- Year Filtering
- Work Mode Filtering

### Slicers

- Work Year
- Experience Level
- Work Mode

---

## Key Insights

### Experience Impacts Salary

Executive-level professionals earn the highest salaries while entry-level professionals earn the lowest.

### Salary Growth Over Time

Average salaries increased between 2020 and 2022.

### Highest Paying Roles

Top paying roles identified:

1. Data Analytics Lead
2. Principal Data Engineer
3. Financial Data Analyst

---

## Dashboard Preview

(Add screenshots here)

---

## Author

Saim Shaikh

Aspiring Data Analyst focused on SQL, Python, Power BI, and Business Intelligence.
