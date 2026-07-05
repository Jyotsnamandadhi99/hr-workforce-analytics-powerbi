# DAX Measures

## Overview

This document describes the DAX measures created for the HR Workforce Analytics Dashboard.

---

## Total Employees

**Purpose**

Returns the total number of employees in the dataset.

Total Employees = 
COUNTROWS(HR_Dataset)

---

## Active Employees

**Purpose**

Counts employees who are currently active.

Active Employees = 
CALCULATE(
    COUNTROWS(HR_Dataset),
    HR_Dataset[Termd]=0
)

---

## Terminated Employees

**Purpose**

Counts employees who have left the organization.

Terminated Employees = 
CALCULATE(
    COUNTROWS(HR_Dataset),
    HR_Dataset[Termd]=1
)

---

## Attrition Rate

**Purpose**

Calculates the percentage of terminated employees relative to the total workforce.

Attrition Rate = 
DIVIDE(
    [Terminated Employees],
    [Total Employees]
)

---

## Average Salary

**Purpose**

Calculates the average employee salary.

Average Salary = 
FORMAT(
    AVERAGE(HR_Dataset[Salary]),
    "$#,##0"
)

---

## Average Age

**Purpose**

Calculates the average employee age.

Average Age = 
AVERAGE(HR_Dataset[Age])

---

## Average Engagement

**Purpose**

Calculates the average employee engagement survey score.

Average Engagement = 
AVERAGE(HR_Dataset[EngagementSurvey])

---

## Average Satisfaction

**Purpose**

Calculates the average employee satisfaction score.

Average Satisfaction = 
AVERAGE(HR_Dataset[EmpSatisfaction])

---

## Average Absences

**Purpose**

Calculates the average number of employee absences.

Average Absences = 
AVERAGE(HR_Dataset[Absences])

---

## Average Days Late

**Purpose**

Calculates the average number of late arrivals during the last 30 days.

Average Days Late = 
AVERAGE(HR_Dataset[DaysLateLast30])