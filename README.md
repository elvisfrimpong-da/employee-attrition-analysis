# 🧠 Employee Attrition Analysis – Biliv-Augmenta
This Power BI project analyzes employee attrition at Biliv-Augmenta to uncover the key factors contributing to turnover and provide data-driven insights to improve employee retention. This repository houses key files and documentation for Employee Attrition Analysis . You can find the comprehensive report and in-depth documentation on Medium here.

##  📊 Problem Statement
This project aims to analyze employee attrition at Biliv-Augmenta to uncover the key factors driving turnover. Using Microsoft Power BI, the analysis explores employee data to identify trends, patterns, and insights that will help:
- Understand reasons behind employee resignations or exits
- Develop data-driven strategies to improve retention
- Inform HR and management decisions for employee satisfaction
- Support the creation of effective employee engagement programs.

## 🛠️ Tools Used
- Power BI – for data modeling, visualization, and dashboard creation
- Power Query – for data cleaning and transformation
- DAX (Data Analysis Expressions) – for calculating key metrics like attrition rate
- Data Model View – for creating relationships between the fact and dimension tables

## 📁 Data Model
The dataset consists of multiple dimension and fact tables, including:
- DimEmployee
- FactPerformanceRating
- DimEducationLevel
- DimSatisfiedLevel
- DimRatingLevel
- DimDate

## CalMeasures (calculated measures)
- These were connected using Power BI’s Model View to establish one-to-many relationships and maintain data integrity for accurate analysis.

### 🔍 Key Calculated Measure
- Attrition Rate (DAX formula):
%AttritionDate = DIVIDE([InActiveEmployeesDate], [TotalEmployeesDate]).
This metric provides the percentage of employees who left the organization over a specific time period.

## 🔍 Key Insights
The analysis revealed several important insights into employee demographics and attrition at Biliv-Augmenta:<br>
Total Employees Analyzed: 1,470<br>
Inactive Employees (Attrition): 237<br>
Active Employees: 1,233<br>
Overall Attrition Rate: 16.1%

- 👨‍💼 Active Employees by Department<br>
Technology: 828<br>
Sales: 354<br>
Human Resources: 51

- 👥 Employee Age Distribution<br>
Youngest Employee: 18 years<br>
Oldest Employee: 51 years

- Age Groups<br>
<20 years: 81 employees<br>
20–29 years: 874 employees<br>
30–39 years: 289 employees<br>
40–49 years: 219 employees<br>
50+ years: 7 employees

- 💍 Marital Status Breakdown<br>
Married: 624 (42.45%)<br>
Single: 549 (37.35%)<br>
Divorced: 297 (20.20%)<br>

These insights help management better understand the workforce composition and areas where targeted retention strategies may be most effective.

## 📖 Read the Full Story on Medium  
[Uncovering the Hidden Drivers of Employee Turnover: A Data Analyst’s Guide to Retention Strategy](https://medium.com/@elvisfrimpong.da/uncovering-the-hidden-drivers-of-employee-turnover-a-data-analysts-guide-to-retention-strategy-9929d1dcd931)


### 👉 Scroll down to view the dashboard and explore insights on employee turnover, satisfaction, and performance.
![Screenshot 2025-06-11 230927](https://github.com/user-attachments/assets/7125c6b1-0a2f-4cb0-ab83-5622d4509be6)


-Let's Connect On 
[LinkedIn](https://www.linkedin.com/in/elvisfrimpong)
