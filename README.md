Created a weekly credit card dashboard providing real-time visibility to help stakeholders monitor performance and make data-driven decisions.

Descriptio:-
This Credit Card Financial Dashboard, built using Power BI and SQL, provides real-time insights into overall total revenue, transaction amount, transaction count, interest, and customer behavior. It includes interactive filters such as customer income, education, age, and mode of payment, allowing users to easily explore and analyze trends across different customer segments.

Purpose:
The dashboard helps stakeholders monitor weekly and YTD performance, analyze revenue, and transaction trends, and identify key drivers by customer demographics, card type, and geography. These filters enable deeper analysis to understand which customer segments contribute most to performance and where improvements are needed.

Tech-Stack- 
## 🛠️ Tech Stack
- 📊 **Power BI Desktop** – Primary data visualization tool used for building interactive dashboards and reports  
- 🔄 **Power Query** – Used for data extraction, transformation, and cleansing before analysis  
- 🧠 **DAX (Data Analysis Expressions)** – Created calculated measures, KPIs, and dynamic logic for insights and comparisons  
- 🧩 **Data Modeling** – Designed relationships across fact and dimension tables to enable accurate aggregation and cross-filtering  
- 🗄️ **Database: MySQL** – Source system for storing and managing transactional and customer data  
- 💻 **Programming Language: SQL** – Used to query, filter, aggregate, and prepare data from the MySQL database  
- 📁 **File Formats** – `.pbix` for Power BI development and `.png` for dashboard snapshots and previews


4. Data Source
More info on where the data comes from and how it’s structured Example: Source: Kaggle & Google Dataset Search

Business Problem-
The business needed a centralized and real-time view of credit card financial performance. Key metrics like revenue, transaction volume, interest, customer behavior, and week-over-week changes were scattered across raw SQL tables, making it difficult for stakeholders to quickly identify trends, high-performing segments

Goal of the Dashboard
The goal was to build an interactive Power BI dashboard that:
Provides real-time visibility into credit card performance
Tracks weekly and YTD financial metrics
Allows stakeholders to analyze trends by customer demographics, card types, payment modes, and geography
Supports data-driven decision-making without manual analysis

Walkthrough of Key Visuals (Brief)
KPI Cards: Display total revenue, transaction amount, transaction count, interest, activation rate, and delinquency rate
Trend Charts: Show week-over-week and YTD changes in revenue and transactions
Category Breakdown: Revenue and transactions by card type, gender, and customer segments
Geographic View: State-wise contribution to overall transactions
Filters/Slicers: Customer income, education, age, and mode of payment to quickly identify patterns and trends

Business Impact & Key Insights
•	Identified a 28.8% week-over-week revenue increase, supported by growth in transaction amount and volume
•	Found that Visa and Discover cards contribute to 93% of total transactions
•	Observed that TX, NY, and CA drive 68% of total activity
•	Gained visibility into activation (57.5%) and delinquency rates (6.06%) to monitor risk

Dashboard Snapshot-
![Image alt](https://github.com/ShivaniGosavi99/Credit-Card-Customer-Transaction-Analysis-Dashbaord-/blob/5a4edd16594122636c0aca79bb502294f04d14ac/Credit%20card%20Analysis%20Dashbaord%20Snapshot%20.png)



![Image alt](https://github.com/ShivaniGosavi99/Credit-Card-Customer-Transaction-Analysis-Dashbaord-/blob/82bc82350e7847ff21d8ed8bf305246c1774b1bf/Customer%20Analysis%20Snapshot.png)



This dashboard is a reflection of my current project work, where we support customers and merchants using real transactional data. It helps us compare transaction volumes week-over-week, same day, and previous day, identify volume drops, analyze declined transactions, and uncover underlying trends.
Using these insights, we quantify the impact through approval/decline counts and volume comparisons, and work closely with SMEs to recommend corrective actions such as configuration checks, merchant follow-ups, or escalation to improve authorization performance.
