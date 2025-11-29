# HR Analytics Dashboard 

## Overview

This repository contains a Power BI–based **HR Analytics Dashboard** designed to analyze workforce performance, attrition patterns, satisfaction levels, and demographic trends. The dashboard integrates **Power BI visuals, DAX queries, and HR datasets** to deliver actionable insights for strategic HR decision-making.

---

## Key Features

### **1. Workforce Summary**

* Total Employees
* Active Employees
* Attrition Count
* Attrition Rate (calculated using DAX)
* Average Age

### **2. Attrition Analytics**

* Department-wise attrition
* Age group attrition
* Gender-based attrition
* Education field-wise attrition

### **3. Job Satisfaction Analysis**

Matrix visuals showing satisfaction ratings (1–4) across job roles such as:

* Sales Executive
* Research Scientist
* Manager
* Laboratory Technician
* HR

### **4. Interactive Visuals**

Includes bar charts, matrices, cards, and slicers for easy drill-down and exploration.

---

## DAX Queries Used

The dashboard uses **custom DAX measures** to calculate key HR KPIs.

### 🔹 **Exact DAX Measures Used**

**Attrition Rate**

```
Attrition Rate =
    SUM('HR data'[Attrition Count]) /
    SUM('HR data'[Employee Count])
```

**Active Employees**

```
Active Employees =
    SUM('HR data'[Employee Count]) -
    SUM('HR data'[Attrition Count])

---

## Tools Used

* **Microsoft Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* HR employee dataset (job roles, demographics, attrition, education fields)

---

## Purpose

The goal of this dashboard is to:

* Identify high-risk departments
* Monitor employee satisfaction
* Understand demographic patterns
* Reduce attrition through data-driven insights
* Empower HR teams with real-time analytics

---

## How to Use

1. Download the `.pbix` file.
2. Open in **Power BI Desktop**.
3. Refresh data if needed.
4. Use filters to explore insights by department, gender, education, or age group.

---

## Contact

For improvements or collaboration, feel free to connect or open an issue.
