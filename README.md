🧠 Employee Attrition Analysis – Biliv-Augmenta
This Power BI project analyzes employee attrition at Biliv-Augmenta to uncover the key factors contributing to turnover and provide data-driven insights to improve employee retention.

📊 Project Objective:
To help Biliv-Augmenta understand patterns behind employee attrition by analyzing employee demographics, performance, satisfaction, and HR records. This enables the company to develop effective strategies for talent retention.

🛠️ Tools Used:
Power BI – for data modeling, visualization, and dashboard creation
Power Query – for data cleaning and transformation
DAX (Data Analysis Expressions) – for calculating key metrics like attrition rate
Data Model View – for creating relationships between fact and dimension tables

📁 Data Model
The dataset consists of multiple dimension and fact tables including:
DimEmployee
FactPerformanceRating
DimEducationLevel
DimSatisfiedLevel
DimRatingLevel
DimDate

CalMeasures (calculated measures):
These were connected using Power BI’s Model View to establish one-to-many relationships and maintain data integrity for accurate analysis.
🔍 Key Calculated Measure
Attrition Rate (DAX formula):
%AttritionDate = DIVIDE([InActiveEmployeesDate], [TotalEmployeesDate])
This metric provides the percentage of employees who left the organization over a specific time period.

📌 Insights Discovered:
Employees with low job and environment satisfaction were more likely to leave.
Distance from home had a mild correlation with attrition.
Certain departments showed significantly higher attrition rates.
Manager ratings and training opportunities had a noticeable impact on retention.

📷 Screenshots
