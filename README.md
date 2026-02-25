# Student Academic & Behavioral Analysis – Power BI Dashboard

## Project Overview

This project analyzes student academic performance, attendance patterns, and behavioral trends using Microsoft Power BI.

The dashboard consolidates multi-source data into an interactive analytical solution that helps identify performance gaps, subject-level strengths and weaknesses, and the relationship between attendance, behavior, and academic outcomes.

The project demonstrates strong capabilities in **data modeling, DAX calculations, dashboard design, and insight generation**.

---

## Dataset Description

The solution integrates multiple structured datasets sourced from Google Sheets / Excel:

* **Students** – StudentID, Name, Class, Section, Gender
* **Scores** – Subject-wise exam scores, maximum score, term
* **Attendance** – Attendance percentage and daily status
* **Behavior** – Categorized behavior records

All datasets are relationally connected using **StudentID**.

---

## Data Modeling

* Implemented a **star-schema data model**
* Students table serves as the primary dimension table
* Scores, Attendance, and Behavior function as fact tables
* Established one-to-many relationships
* Applied data cleaning:

  * Standardized column naming
  * Corrected data types
  * Handled missing values

---

## Key DAX Measures

Developed dynamic DAX measures to support KPI tracking and segmentation:

* Total Students
* Total Score
* Total Max Score
* Average Score
* Percentage Score
* Attendance %
* Behavior Count
* Performance Category (High / Medium / Low using SWITCH logic)

All measures dynamically respond to slicer selections.

---

## Dashboard Components

### KPI Indicators

* Total Students
* Average Score
* Percentage Score
* Attendance %
* Performance Category

### Visualizations

* **Bar Chart** – Average Score by Subject and Class
* **Line Chart** – Term-wise Performance Trend
* **Donut Chart** – Behavior Distribution
* **Performance Table** – Student-level analysis with conditional formatting

### Interactivity

* Slicers: Class, Section, Subject, Term
* Dynamic cross-filtering
* Conditional formatting to highlight performance categories

---

## Key Insights

* Strong positive correlation observed between attendance and academic performance
* Certain subjects consistently show lower scoring averages
* Medium-performing students display higher behavioral variability
* Academic trends fluctuate across terms

---

## Tools & Technologies

* Microsoft Power BI Desktop
* DAX (Data Analysis Expressions)
* Excel / Google Sheets
* Data Modeling (Star Schema)

---

## Deliverables

* Student_Performance_Dashboard.pbix
* Project documentation

---

## Conclusion

This project showcases the ability to transform raw educational data into a structured analytical model and interactive dashboard.

It reflects practical expertise in data modeling, KPI development, and insight-driven reporting — aligned with real-world Business Intelligence use cases.

---

## Author

Rajvi Trivedi
Data Analyst | Business Analyst

---
