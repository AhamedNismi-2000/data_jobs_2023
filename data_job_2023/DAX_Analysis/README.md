# 📊 Job Market Data Analysis Portfolio  
**Excel · Power Query · Power Pivot · DAX · Interactive Dashboards**

---

## 👋 Overview
This repository contains a collection of **Excel-based job market analyses** demonstrating **end-to-end data analytics skills** — from data cleaning and modeling to advanced DAX calculations and interactive visualizations.

All analyses are built using **Microsoft Excel**, leveraging **Power Query** for ETL, **Power Pivot** for data modeling, and **DAX** for explicit measures and advanced filter control.  
The dashboards are designed to mirror **real-world BI and Data Analyst workflows**.

---

## 🛠 Core Skills Demonstrated
- Data Cleaning & Transformation (ETL)
- Power Query (Advanced)
- Power Pivot Data Modeling
- DAX Explicit Measures
- CROSSFILTER for complex relationships
- Pivot Tables & Pivot Charts
- Interactive Slicers (Country, Job Title, Skills)
- Analytical thinking & data storytelling

---

## 📅 Analysis 1: Job Posting Trends by Day of the Week (2023)

### Objective
Analyze how **job posting volume varies by weekday** to understand recruiter posting behavior.

### Methodology
- Cleaned and prepared global job posting data using **Power Query**
- Aggregated job counts by weekday using **Pivot Tables**
- Visualized trends using a **Column Chart**

### Visualization Design
- **Chart Type:** Column Chart  
- **X-Axis:** Day of the Week (Monday–Sunday)  
- **Y-Axis:** Job Posting Count  

### Dashboard Preview
<p align="center">
  <img src="../assets/job_count_by_weekday.png" width="1200">
</p>

---

## 🌎 Analysis 2: Median Salary Comparison – US vs Non-US vs Global

### Objective
Compare **median salary levels across regions** to identify global compensation differences.

### Methodology
- Cleaned and standardized salary and country data using **Power Query**
- Built a **Power Pivot data model**
- Created DAX measures for:
  - US Median Salary
  - Non-US Median Salary
  - Global Median Salary
- Enabled dynamic filtering using a **Country slicer**

### Visualization Design
- **Chart Type:** Stacked Column Chart  
- **X-Axis:** Salary Category (US, Non-US, Global)  
- **Y-Axis:** Median Salary
-  **Slicer:** Country   

### Dashboard Preview
<p align="center">
  <img src="../assets/median_salary_comparison.png" width="1200">
</p>

---

## 🧠 Analysis 3: Skill Complexity vs Median Salary

### Objective
Understand how **skill complexity (skills per job)** relates to **median salary**, with cross-country comparison.

### Methodology
- Prepared job and skill datasets using **Power Query**
- Modeled relationships using **Power Pivot**
- Created explicit DAX measures:
  - Skill Count  
  - Job Count  
  - Skills per Job  
- Enabled **Country slicer** for regional analysis

### Visualization Design
- **Chart Type:** Scatter Plot  
- **X-Axis:** Median Salary  
- **Y-Axis:** Skills per Job  
- **Slicer:** Country  

### Dashboard Preview
<p align="center">
  <img src="../assets/skills_vs_salary.png" width="1200">
</p>

---

## 🔗 Analysis 4: Skill Type vs Salary & Demand (DAX CROSSFILTER)

### Objective
Analyze **median salary and demand by skill type**, resolving data model filter-direction limitations.

### The Challenge
The relationship between the **skills table** and **salary table** did not allow salary values to be filtered correctly by skill.

### The Solution
Used **DAX `CROSSFILTER`** inside explicit measures to temporarily control filter direction, enabling:
- Correct salary aggregation by skill
- Accurate skill demand calculation
- Reliable analysis without modifying the physical data model

### Visualization Design
- **Chart Type:** Combo Chart (Column + Line)  
- **X-Axis:** Skills  
- **Primary Y-Axis:** Median Salary  
- **Secondary Y-Axis:** Skill Count  
- **Slicers:** Country, Job Title  

### Dashboard Preview
<p align="center">
  <img src="../assets/skill_type_salary_combo.png" width="1200">
</p>

---

## 🎛 Interactivity Across Dashboards
- Country slicers for regional insights
- Job Title slicers for role-based analysis
- Dynamic updates across all visuals
- BI-style, self-service analytical experience

---

## 📌 Why This Portfolio Matters
This repository demonstrates my ability to:
- Build **robust analytical models** using Power Pivot
- Apply **advanced DAX techniques** to solve real modeling problems
- Design **clear, interactive dashboards** for decision-makers
- Translate complex data into **business-ready insights**

These are core competencies expected from a **Data Analyst / BI Analyst**.

---

## 🚀 How to Use
1. Download and open the Excel workbook
2. Navigate to dashboard or pivot chart sheets
3. Use slicers to filter by country, job title, or skill
4. Explore insights interactively
