# HR-Attrition-Insights-Decision-Support-Dashboard
Interactive Power BI dashboard analyzing employee attrition patterns with DAX-driven KPIs, reducing HR reporting time by 94% and enabling data-driven retention strategies.
# Employee Attrition Analysis & Reporting Dashboard

## 📌 Project Overview
This project presents an **interactive Power BI dashboard** designed to help HR executives analyze and monitor employee attrition patterns.  
The dashboard centralizes attrition-related KPIs, enabling quick identification of high-risk employee segments and data-driven retention strategies.

---

## 🎯 Objectives
- Provide HR with a **clear, visual overview** of attrition trends by department, job role, age group, and education field.
- Automate HR reporting to **reduce manual analysis time** and improve decision-making efficiency.
- Highlight **critical attrition drivers** to support proactive employee retention initiatives.

---

## 🛠 Tools & Technologies
- **Power BI** – Data modeling, dashboard creation, and visualization.
- **DAX (Data Analysis Expressions)** – Custom measures for KPIs:
  - `Total Attrition = SUM('HR data'[Attrition Count])`
  - `Attrition Rate = SUM('HR data'[Attrition Count]) / SUM('HR data'[Emp no])`
  - `Active Employees = SUM('HR data'[Employee Count]) - [Total Attrition]`
- **Excel** – Data cleaning and preparation.

---

## 📊 Key Insights from the Dashboard
- **Overall Attrition Rate:** 16%
- **Highest Turnover Segment:** Sales Executives with poor work-life balance scores.
- **Departmental Trends:** R&D department experience significantly higher attrition than others.
- **Age & Education Factors:** Younger employees from age 25-34 and Life Sciences education fields have higher attrition rates.

---

## ⏱ Business Impact
- **Reduced reporting time** from approximately **4 hours** of manual Excel analysis to **under 30 minutes** with automated visual insights.
- Improved HR’s ability to detect at-risk employee groups and implement targeted retention strategies.

---

## 📷 Dashboard Preview  
![Dashboard Screenshot](https://github.com/ksweta01/HR-Attrition-Insights-Decision-Support-Dashboard/blob/main/Attrition%20Analysis.png)

---

## 📂 Dataset
- **Data:** [HR Data](https://github.com/ksweta01/HR-Attrition-Insights-Decision-Support-Dashboard/blob/main/HR%20Data.xlsx)
- **Size:** 1470 rows × 41 columns.

---

## 👩‍💻 Author
**[Your Name]**  
- GitHub: [[github.com/ksweta01](https://github.com/ksweta01)]  
- LinkedIn: [[linkedin.com/in/kumari-sweta-85b4432a7/](https://www.linkedin.com/in/kumari-sweta-85b4432a7/)]

---
