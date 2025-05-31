# [HR Analytics Dashboard using Power BI 🔗](https://drive.google.com/file/d/1h30yQ-tukzdef7TLYNqnkKJKS_5BZZmr/view?usp=sharing)

## 🎯 Objective

The objective of this project is to identify the key factors driving employee attrition and provide actionable insights to improve workforce retention within an organization.

This dashboard enables the HR team to analyze employee attrition patterns using interactive visuals and KPIs.

Throughout this project, I had the opportunity to:

- Dive deep into HR data to uncover meaningful trends.
- Build interactive dashboards using Power BI visuals.
- Deliver data-driven insights for strategic decision-making.

---

## 🔄 Steps Followed


### 1. **Data Gathering**
- Imported raw CSV data into Power BI.
- Used Power Query Editor for cleaning and preprocessing.

### 2. **Data Cleaning**
- Removed empty columns, duplicates, and fixed errors.
- Replaced invalid values and standardized column naming.
- Ensured proper data types using auto-detect features.

### 3. **Data Processing**
- Created a new column `AttritionCount` using conditional logic:  
  `IF Attrition = 'Yes' THEN 1 ELSE 0`.
- Built DAX measures like:  
  `Attrition Rate = SUM([AttritionCount]) / SUM([EmployeeCount]) * 100`.

### 4. **Data Analysis**
- Created visualizations including bar charts, KPIs, pie charts, and tables.
- Used slicers and filters for interactive exploration.

---

## ❓ Dashboard Answers the Following Questions

- What is the total employee count?
- What is the average age and salary of employees?
- What is the attrition count among men and women?
- How many years have employees worked in the company?
- Which department has the most employees?
- What is the gender distribution?
- Which education field has the most employees?
- Which business travel type is most frequent?

---

## 📊 Visuals & Features

- Calculated fields for attrition rate and active employees
- Matrix tables for job satisfaction analysis
- Donut, pie, and bar charts for clear comparison
- KPIs and slicers for dynamic filtering
- Field-specific filters (e.g., education)

---

## 🧠 Key Insights

1. **Total Employees:** 1470, showing strong organizational growth.
2. **Attrition Count:** 237 employees left; 150 males and 87 females.
3. **Departmental Attrition:** R&D has the highest attrition (56.13%).
4. **Education Field Impact:** Life Sciences had the highest attrition.
5. **Job Role Affected:** Sales department had the most attrition.
6. **Education-wise Attrition:** High school grads had the highest rate (18.24%).
7. **Age Group Impact:** Age group 25-34 had the most attrition (112 employees).

---

## 📁 Files

- `HR_Analytics_Dashboard.pbix` – Main Power BI Dashboard  
- 📷 **Dashboard Preview**:

![HR Analytics dashboard](https://github.com/vishal-56/HR-Analytics-Dashboard-using-Power-BI/blob/main/HR%20Analytics%20dashboard.pdf)

---

## 📌 How to Use

1. Clone/download the repository
2. Open `.pbix` file using Power BI Desktop
3. Explore visuals and apply filters as needed

---


<!-- Commit on 2025-05-25T10:00:00 -->
<!-- Commit on 2025-05-30T10:00:00 -->
