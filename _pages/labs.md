---
title: "Lab Challenges"
layout: collection
permalink: /labs/
collection: labs
entries_layout: list
layout: default
---

# 🧪 Cyber Shujaa Data Lab Challenges

As part of the **Cyber Shujaa Data & AI track**, I've worked on various lab challenges in **data wrangling**, **exploratory data analysis (EDA)**, and **data visualization using Power BI**. Below are summaries of each challenge and what I learned from them.

---

## 🧹 1. Data Wrangling: Sales Dataset

### 🎯 Objective
Clean a raw sales dataset with missing values, inconsistent formatting, and duplicates to prepare it for analysis.

### 🛠️ Tools Used
- Python (Pandas)
- OpenRefine
- Microsoft Excel

### 💻 Tasks Completed
- Removed duplicate records
- Standardized inconsistent date formats
- Filled in missing revenue data with group averages
- Renamed columns for readability

### ✅ Results
- A clean dataset with 10,000+ valid entries
- Ready for analysis or visualization in Power BI and Python

### 🧠 Key Learnings
- Efficient use of `.fillna()`, `.drop_duplicates()`, and `.apply()` in Pandas
- Regex for cleaning text columns
- Data profiling using `pandas-profiling`

---

## 📊 2. Exploratory Data Analysis (EDA): Hospital Dataset

### 🎯 Objective
Analyze and visualize hospital admissions data to uncover insights into patient demographics, diagnoses, and care outcomes.

### 🛠️ Tools Used
- Python (Jupyter Notebook, Pandas, Seaborn, Matplotlib)
- Excel (for quick summary stats)

### 🔍 Analysis Performed
- Univariate and bivariate analysis (histograms, bar plots, boxplots)
- Correlation heatmap to identify relationships
- Grouped averages by diagnosis and age group
- Outlier detection using IQR method

### ✅ Insights
- Most admissions were emergency cases for patients aged 60+
- High correlation between age and length of stay
- Common diagnoses included Hypertension, Diabetes, and Pneumonia

### 🧠 Key Learnings
- Visualizing distributions and relationships is crucial for understanding data
- Cleaning before EDA reduces misleading patterns
- Summarizing findings improves communication in reports and dashboards

---

## 📈 3. Power BI: Hotel Dashboard

### 🎯 Objective
Create an interactive Power BI dashboard to summarize and present key hotel booking metrics.

### 🛠️ Tools Used
- Microsoft Power BI Desktop
- Cleaned hospital dataset (CSV)

### 📊 Dashboard Features
- Slicers for gender, age group, and admission type
- KPIs: Total Admissions, Average Length of Stay, Diagnosis Counts
- Charts: Line chart for trends, bar charts for top diagnoses, donut charts for gender distribution
- DAX formulas for calculating aggregates and filters

### 🧠 Key Learnings
- Importance of consistent formatting for Power BI imports
- DAX for custom calculated fields and measures
- Dashboard layout and color choices enhance interpretability

---

## 📁 Files (If You’re Cloning the Repo)
- `data-wrangling-sales.py` – Python script for cleaning sales data  
- `eda-hospital.ipynb` – Jupyter notebook for EDA  
- `hospital-dashboard.pbix` – Power BI dashboard  
- `hospital.csv` – Original dataset  
- `cleaned_sales.csv` – Cleaned version of sales dataset

---

## 🙌 Summary

These labs helped me gain hands-on experience with:
- **Real-world data cleaning**
- **Insight extraction through EDA**
- **Visual storytelling using dashboards**

I’m now more confident working with messy datasets, communicating insights, and using visualization tools to support data-driven decision-making.

