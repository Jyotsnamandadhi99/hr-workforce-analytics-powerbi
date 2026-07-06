# HR Workforce Analytics Dashboard

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success)

![Dashboard Preview](images/Executive%20Overview.png)
---

## Overview

The **HR Workforce Analytics Dashboard** is an end-to-end Power BI project that provides interactive insights into workforce demographics, employee performance, recruitment effectiveness, salary trends, attendance, and attrition.

The project demonstrates the complete analytics workflow—from data cleaning and transformation using Power Query to DAX calculations, dashboard design, and interactive reporting.

---

## Objectives

- Analyze workforce demographics
- Monitor employee attrition
- Evaluate recruitment effectiveness
- Assess employee performance and engagement
- Explore salary distribution
- Identify attendance patterns
- Enable HR decision-making through interactive dashboards

---

## Dataset

**Dataset:** HR-Dataset.xlsx

The dataset contains:

- **311 Employees**
- **35 Features**

Key attributes include:

- Employee Demographics
- Department
- Salary
- Recruitment Source
- Performance Score
- Engagement Survey
- Employee Satisfaction
- Absences
- Employment Status
- Termination Reasons

---

# Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
- Git
- GitHub

---

# Dashboard Pages

## 1.Executive Overview

Provides an overall snapshot of the workforce.

### KPIs

- Total Employees
- Active Employees
- Terminated Employees
- Attrition Rate
- Average Salary
- Average Age
- Average Engagement
- Average Satisfaction

### Visuals

- Employees by Department
- Gender Distribution
- Employment Status
- Recruitment Sources
- Employee Distribution by State

---

## 2.Employee Insights

Focuses on workforce demographics.

### KPIs

- Average Age
- Average Salary
- Average Engagement
- Average Satisfaction

### Visuals

- Age Distribution
- Marital Status
- Race Distribution
- Department Workforce
- Salary Distribution

---

## 3.Performance & Attrition

Analyzes employee performance and turnover.

### KPIs

- Attrition Rate
- Average Performance Score
- Average Absences
- Average Days Late

### Visuals

- Manager Attrition
- Performance Distribution
- Attrition by Department
- Termination Reasons
- Performance vs Satisfaction
- Absence vs Performance

---

# 🖼 Dashboard Preview

## Executive Overview

![Executive Overview](images/Executive%20Overview.png)

---

## Employee Insights

![Employee Insights](images/Employee%20Insights.png)

---

## Performance & Attrition

![Performance & Attrition](images/Performance%20%26%20Attrition.png)

---

# Data Preparation

The dataset was cleaned using **Power Query**.

Performed tasks include:

- Data type validation
- Missing value analysis
- Duplicate verification
- Data profiling
- Age column creation
- Age Group categorization
- Data quality validation

---

# DAX Measures

Key DAX measures include:

- Total Employees
- Active Employees
- Terminated Employees
- Attrition Rate
- Average Salary
- Average Age
- Average Engagement
- Average Satisfaction
- Average Performance Score
- Average Absences
- Average Days Late

---

# Project Structure

```text
hr-workforce-analytics-powerbi/
│
├── dashboard/
│   └── HR_Workforce_Analytics.pbix
│
├── data/
│   ├── raw/
│   │   └── HR-Dataset.xlsx
│   │
│   └── processed/
│
├── documentation/
│   ├── BusinessQuestions.md
│   ├── DashboardLayout.md
│   ├── DataCleaning.md
│   ├── DataDictionary.md
│   ├── DAXMeasures.md
│   ├── EmployeeInsights.md
│   └── PerformanceAttrition.md
│
├── images/
│   ├── Executive Overview.png
│   ├── Employee Insights.png
│   └── Performance & Attrition.png
│
├── LICENSE
├── README.md
├── requirements.md
└── .gitignore
```

---

# Development Progress

### Day 1

- Project initialization
- Repository setup
- Dataset documentation
- Business questions
- Initial README

### Day 2

- Imported dataset into Power BI
- Data profiling
- Missing value validation
- Duplicate verification
- Data type validation
- Age column creation
- Data cleaning documentation

### Day 3

- Created calculated columns
- Developed core DAX measures
- Built Measure table
- Organized KPI calculations

### Day 4

- Designed Executive Overview dashboard
- Created KPI cards
- Added slicers
- Built Executive visuals
- Applied dashboard theme

### Day 5

- Developed Employee Insights dashboard
- Built demographic visualizations
- Added workforce analytics
- Enhanced dashboard formatting

### Day 6

- Developed Performance & Attrition dashboard
- Built HR performance visuals
- Added attrition analysis
- Included performance insights

### Day 7

- Final dashboard polishing
- Layout refinements
- Documentation updates
- GitHub project completion

---

# Future Enhancements

- Publish to Power BI Service
- Row-Level Security (RLS)
- Scheduled data refresh
- Drill-through pages
- Bookmarks & Navigation
- Predictive Attrition Analysis using Machine Learning

---

# Documentation

Detailed project documentation is available in the **documentation/** folder.

Includes:

- Business Questions
- Data Dictionary
- Data Cleaning
- Dashboard Layout
- DAX Measures
- Employee Insights
- Performance & Attrition

---

# Author

**Jyotsna Mandadhi**

Computer Science Engineering Student

Aspiring Data Analyst | Power BI | Python | SQL | Machine Learning

GitHub: https://github.com/JyotsnaMandadhi99

---

## If you found this project useful, consider giving it a Star!
