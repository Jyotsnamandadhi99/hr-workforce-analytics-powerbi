# Data Cleaning

## Overview

The HR-Dataset was imported into Power BI using Power Query for data preparation before building the HR Workforce Analytics Dashboard.

The objective of this phase was to validate the dataset, correct data types, identify missing values, and ensure the data was ready for analysis.

---

## Dataset Information

- **Dataset:** HR-Dataset
- **Tool Used:** Power BI Power Query Editor
- **Total Records:** 311
- **Total Columns:** 35

---

## Data Cleaning Steps

### 1. Imported Dataset

- Imported the Excel dataset into Power BI.
- Selected the employee data worksheet.
- Opened the dataset in Power Query Editor for transformation.

---

### 2. Data Profiling

Enabled Power Query data profiling features:

- Column Quality
- Column Distribution
- Column Profile

This was done to inspect data completeness, uniqueness, and data quality before making transformations.

---

### 3. Data Type Validation

Reviewed the data type of every column and verified that each field was assigned the appropriate data type.

Examples include:

| Column | Data Type |
|---------|-----------|
| Employee_Name | Text |
| EmpID | Whole Number |
| Salary | Whole Number |
| DOB | Date |
| DateofHire | Date |
| DateofTermination | Date |
| LastPerformanceReview_Date | Date |
| EngagementSurvey | Decimal Number |
| EmpSatisfaction | Whole Number |
| Absences | Whole Number |

---

### 4. Missing Value Analysis

The dataset was inspected for null or empty values.

#### DateofTermination

- Null values were found.
- These represent employees who are currently active.
- No changes were made because these values have business significance.

#### ManagerID

- Null values were identified.
- These likely correspond to employees at the top of the organizational hierarchy who do not report to another manager.
- No changes were made.

No other significant missing values requiring correction were identified.

---

### 5. Duplicate Validation

Employee uniqueness was verified using the **Employee_Name** field.

Results:

- Total Records: **311**
- Distinct Employee Names: **311**
- Unique Employee Names: **311**

No duplicate employee records were found.

---

### 6. New Column Created

#### Age

A new **Age** column was created using the employee's Date of Birth (DOB).

To maintain consistent analysis across the project, a fixed reference date of **31 December 2018** was used instead of the current system date.

This ensures that age-related calculations remain reproducible regardless of when the dashboard is opened.

---

## Data Cleaning Summary

| Task | Status |
|------|--------|
| Dataset Imported | Completed |
| Data Profiling | Completed |
| Data Types Verified | Completed |
| Missing Values Reviewed | Completed |
| Duplicate Records Checked | Completed |
| Age Column Created | Completed |

---

## Outcome

The dataset is now clean, validated, and ready for data modeling and DAX calculations.

The next phase of the project will focus on building the data model, creating calculated columns and measures, and designing the interactive HR Workforce Analytics Dashboard.