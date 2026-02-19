# 📊 HR Analytics Dashboard | Employee Attrition Analysis

This project is an interactive **HR Analytics Dashboard** built using **Microsoft Power BI** to analyze employee attrition trends, workforce demographics, and key HR performance metrics.

The goal of this project is to simulate how data analysts support HR teams by transforming raw employee data into actionable insights using data modeling, DAX calculations, and visualization techniques.

---

## 📌 Project Objective

To analyze employee attrition patterns and identify key factors influencing workforce turnover, including:

- Age group distribution  
- Salary slabs  
- Job roles  
- Education background  
- Years at company  
- Department and gender trends  

---

## 🔎 Dataset Overview

The dataset represents an HR employee database containing demographic details, compensation information, job roles, and attrition status.

Each record corresponds to one employee and includes attributes such as:

- Employee demographics  
- Compensation data  
- Department and job role  
- Tenure (years at company)  
- Attrition flag  

---

## 🛠 Technical Implementation

### 1️⃣ Data Preparation

- Cleaned and transformed raw HR data using Power Query  
- Standardized column formats and handled missing values  
- Created calculated columns for salary slabs and tenure grouping  

### 2️⃣ Data Modeling

- Built relationships between tables where applicable  
- Designed a structured data model for accurate KPI calculations  

### 3️⃣ DAX Measures Created

- Total Employees  
- Attrition Count  
- Attrition Rate (%)  
- Average Age  
- Average Salary  
- Average Years at Company  

Example DAX formula:

```DAX
Attrition Rate =
DIVIDE([Attrition Count], [Total Employees], 0)

```
## 📊 Dashboard Features

- Executive KPI summary cards  
- Attrition by Education (Donut Chart)  
- Attrition by Age Group (Column Chart)  
- Attrition by Salary Slab (Bar Chart)  
- Attrition by Years at Company (Trend Analysis)  
- Attrition by Job Role (Bar Chart & Heatmap Table)  
- Gender Distribution Analysis  
- Department-level filtering (HR, R&D, Sales)  
- Interactive slicers for dynamic exploration  

---

## 📈 Key Insights

- Overall Attrition Rate: **16.1%**  
- Highest attrition observed in **26–35 age group**  
- Employees in lower salary slabs show higher turnover  
- Attrition decreases as tenure increases  
- Certain job roles show concentrated attrition risk  

---

## 🧠 Skills Demonstrated

- Data Analysis  
- HR Analytics  
- Power BI Dashboard Development  
- DAX Calculations  
- Data Modeling  
- Power Query  
- KPI Development  
- Workforce Analytics  
- Business Intelligence  

---

## 📁 Files Included

- HR_Analytics_Dashboard.pbix –( https://github.com/SAKhan2121/-HR-Analytics-Dashboard-Employee-Attrition-Analysis/blob/main/3rd%20HR%20DASHBOARD.pbix) Power BI dashboard file  
- Dashboard_Screenshot.png – Dashboard preview  
- README.md – Project documentation  

---

## 📌 Business Impact

This dashboard enables HR teams to:

- Identify high-risk attrition segments  
- Improve employee retention strategies  
- Support workforce planning decisions  
- Monitor key HR performance metrics  

---

## 👤 Author

**Suhail Ahmed Khan**  
Data Analyst | Power BI | SQL | Business Intelligence


