# HR-Analytics-Dashboard
Interactive HR Analytics Dashboard built with Power BI, Power Query and DAX.
# HR Analytics Dashboard

## Overview

This project presents an interactive HR Analytics Dashboard built in Power BI to analyze employee demographics, workforce distribution, promotion eligibility, employee retention, performance ratings, and job satisfaction.

The objective of the dashboard is to provide HR teams and managers with actionable insights to support workforce planning and decision-making.

---

## Dashboard Preview

### Home Page

![Home Dashboard](home-dashboard.png)

### Detail Page

![Detail Dashboard](detail-dashboard.png)

---

## Business Objectives

The dashboard was designed to answer the following questions:

* How many employees are currently active?
* What is the gender distribution of the workforce?
* Which employees are due for promotion?
* Which employees are potential layoff candidates?
* How are employees distributed across job levels?
* How does employee satisfaction vary across the organization?
* Which departments present higher workforce risk?

---

## Data Preparation

The dataset was cleaned and transformed using Power Query.

Key transformations included:

* Splitting and restructuring imported data
* Creating promotion eligibility categories
* Creating retrenchment status categories
* Grouping employees by service years
* Categorizing employee distance from workplace
* Merging employee information tables
* Creating custom calculated fields

---

## DAX Measures

Several DAX measures were created to support KPI calculations:

* Total Employees
* Male Employees
* Female Employees
* Due for Promotion
* Lay Off Candidates
* Active Employees
* High Performance Employees
* Low Performance Employees
* Percentage KPIs

Blank values were handled using conditional DAX logic to improve dashboard usability.

---

## Tools Used

* Power BI Desktop
* Power Query
* DAX
* Data Modeling
* Data Visualization

---

## Key Insights

* Total Workforce: 1,470 employees
* Male Employees: 60%
* Female Employees: 40%
* Employees Due for Promotion: 72
* Lay Off Candidates: 117
* Active Employees: 1,353
* High Performance Employees: 84.6%

---

## Project Structure

```text
HR-Analytics-Dashboard/
│
├── HR_Analytics.pbix
├── home-dashboard.png
├── detail-dashboard.png
└── README.md
```

---

## Author

Marc Pluvins Gil
