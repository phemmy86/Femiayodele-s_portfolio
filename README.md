# Project 1:  Income Statement Analysis Using Power BI
# [Income Statement Analysis](https://app.powerbi.com/view?r=eyJrIjoiNDViZTRiODQtMmFkNC00ZWViLTgzZTYtOWZmMDIzZGVkODQyIiwidCI6ImJhMTMwZWNhLTMwMzAtNDhlMS05MDg5LWM5NzkyOTNhZWI3MCIsImMiOjh9)

### Project Overview
An income statement is a financial statement that shows the company's income and expenditures. It also shows whether a company is making profit or loss for a given period. The income statement, along with balance sheet and cash flow statement, helps organization understand the financial health of your business.

### The Component of Income Statement for this Analysis

The components of the income statement include: Revenue; Cost of Good Sold; Gross Profit, Expenses, EBIT; Finance Costs; Net Income Before Tax; Tax; and Net Income as shown below.

<img width="227" alt="image" src="https://github.com/user-attachments/assets/040786c5-1509-49ce-a1c7-43c29602f8e0">

The income statement includes various categories for reporting and analysis, comparing the current year against the previous year, and highlighting the percentage change for each category, as shown below

<img width="632" alt="image" src="https://github.com/user-attachments/assets/9c5222b0-55e4-4875-bcdf-265f2a87cde4">



# Project 2: Forthbridge Loan Disbursement Analysis
# [Loan Disbursement Analysis](https://app.powerbi.com/view?r=eyJrIjoiZjAwN2UxMzQtZjMwMS00ZWE1LWFiZmItODBjMGE5NTU5ZjQyIiwidCI6ImJhMTMwZWNhLTMwMzAtNDhlMS05MDg5LWM5NzkyOTNhZWI3MCIsImMiOjh9)

### Project Overview
This project focuses on a comprehensive analysis of loan disbursements over the past six months, evaluating the performance across different branches and account officers. Key areas of analysis include:

1. Branch Performance: Assessment of loan disbursement trends across various branches, identifying high-performing and underperforming locations.

2. Account Officer Performance: Evaluation of individual account officers based on their loan disbursement volumes, highlighting top performers and areas needing improvement.

3. Portfolio At Risk (PAR): Analysis of loans with a Portfolio At Risk (PAR) status of 30 days and above, identifying trends in delayed repayments and potential risk factors.

4. Invalid Loans: Identification and analysis of loans with incomplete or missing master data, which may affect the accuracy and reliability of loan records.


### The Loan Disbursement for the Last Six Months 
Below report show the analysis of loan disbursements over the past six months, evaluating the performance across different branches, different loan products and account officers.

<img width="590" alt="image" src="https://github.com/user-attachments/assets/3e14377b-2704-46d9-97da-08bba11b76dd">

### The Loan Disbursement for the Last Month
The report below provides an analysis of last month's loan disbursements, detailing the total amount disbursed and the number of loans issued, broken down by loan product and branch.

<img width="586" alt="image" src="https://github.com/user-attachments/assets/51911660-6255-40e6-8675-67b2da23374e">

### Portfolio At Risk (PAR)
Portfolio At Risk (PAR): Analysis of loans with a Portfolio At Risk (PAR) status of 30 days and above, identifying trends in delayed repayments and potential risk factors.

<img width="551" alt="image" src="https://github.com/user-attachments/assets/a044f679-0ad1-4394-a9e9-ba64a856edd6">

### Invalid Loans:
The report below shows the identification and analysis of loans with incomplete or missing master data, which may affect the accuracy and reliability of loan records.

<img width="556" alt="image" src="https://github.com/user-attachments/assets/33fbc477-6666-4c72-a95c-c05d67965fa0">

In conclusion: The objective of the is project is to provide actionable insights for optimizing loan disbursement strategies, improving branch and officer performance, reducing risk, and enhancing data integrity in the loan portfolio.


# Project 3: Connect SQL Server DB to Oracle SQL Developer (Data Migration from SQL Server to Oracle SQL Developer)

# [Data Migration from SQL Server to Oracle SQL Developer](https://drive.google.com/file/d/1TaGgkRDUBP-4x6gbVp8W-mY9J_g47aM9/view?usp=sharing)

### Project Overview: Data Migration from SQL Server to Oracle SQL Developer
The Data Migration from SQL Server to Oracle SQL Developer project was initiated to ensure a seamless and efficient transfer of data from a legacy SQL Server database to an Oracle SQL Developer environment. This migration was critical for enhancing the organization's database management capabilities, ensuring scalability, improving performance, and aligning with the strategic IT infrastructure upgrade.

Objectives:
1. Data Integrity: Ensure the accurate and complete migration of all data with zero loss or corruption.
2. Performance Optimization: Improve query performance and data retrieval speeds by leveraging Oracle SQL Developer’s advanced features.
3. System Integration: Ensure the migrated database seamlessly integrates with existing applications and systems.

Connecting an SQL Server database to Oracle SQL Developer involves setting up a connection within Oracle SQL Developer to your SQL Server instance. Here’s a step-by-step guide:
1.	Download Oracle SQL Developer: If you don't already have Oracle SQL Developer installed, download it from (https://www.oracle.com/database/sqldeveloper/technologies/download/)

![image](https://github.com/user-attachments/assets/0def62d0-cf68-4852-bc19-e1bb1fc9c07a)

2.	Install the jTDS JDBC Driver: To connect to SQL Server from Oracle SQL Developer, you will need the jTDS JDBC driver.
o	Download the jTDS driver from SourceForge.

![image](https://github.com/user-attachments/assets/6af6ec9a-804b-4343-9c0a-d77771a82855)

o	Extract the downloaded file. The main file you need is jtds-1.3.1.jar or a similar version.

![image](https://github.com/user-attachments/assets/a3451da3-8a5c-4f42-9358-8637b84de83e)

3.	Add the jTDS Driver to SQL Developer:
o	Open Oracle SQL Developer.
o	Go to Tools -> Preferences
o	In the Preferences window, navigate to Database -> Third Party JDBC Drivers.

![image](https://github.com/user-attachments/assets/f99d8c12-449e-4db4-bf4c-09f41f4e163d)

o	Click the Add Entry button and select the jtds-1.3.1.jar file you downloaded and extracted earlier.

![image](https://github.com/user-attachments/assets/d01b5b51-327d-4083-8ec0-3b051341de84)

Note: I have already added it, but if you are following the steps, yours will be empty

![image](https://github.com/user-attachments/assets/94cd73b9-6db2-439a-9a4c-f36797af8ab7)

o	Click OK to add the driver.

4.	Create a New Connection in Oracle SQL Developer:
o	In Oracle SQL Developer, go to the Connections tab on the left-hand side.
o	Click the green + (plus) icon to create a new database connection.
o	In the New / Select Database Connection window, do the following:

![image](https://github.com/user-attachments/assets/6b5daf36-c89f-4aac-b9ae-e3e56a50f154)

	Connection Name: Enter a name for your connection (e.g., SQLServerConnection).

	Connection Type: Choose SQL Server from the drop-down list.

![image](https://github.com/user-attachments/assets/26a058bc-b396-4e37-bc42-c96c3bb412bd)

	Hostname: Enter the hostname or IP address of your SQL Server instance. (Default : localhost)

	Port: Enter the port number on which your SQL Server is running (default is 1433).

	Username: Enter your SQL Server username.

	Password: Enter your SQL Server password.

Note: You will obtain the username and password from the SQL Server database. Also, ensure that you have created user logins and have successfully logged in.


![image](https://github.com/user-attachments/assets/de21f0d9-5b1e-4186-a74c-a8b5cc70d6e3)

Enter the same credentials as it shown below 

![image](https://github.com/user-attachments/assets/b3be2627-e335-487c-a937-bd7af1e837c6)

Once you have entered your credentials correctly, click on "Retrieve Database." If the connection is successful, the database will automatically appear in the box beside the button. You can then use the drop-down menu to view other databases.

![image](https://github.com/user-attachments/assets/028473f9-df50-4190-88c4-b21b18c63a5c)

5.	Test and Save the Connection:
   
o	Click the Test button to verify that the connection parameters are correct and the connection to SQL Server is successful.
o	If the test is successful, 
o	click on the connect button,
o	Click Save to save the connection.

<img width="461" alt="image" src="https://github.com/user-attachments/assets/56797b68-e659-4a94-b44e-e9ddfbf3be9f">

Compare the databases in both Oracle SQL Developer and SQL Server.

Note: If there is an error, double-check your connection parameters and ensure that your SQL Server is accessible.
Challenges: (Port 1433)

Allow Remote Connections:

•	Open SQL Server Management Studio (SSMS).

•	Right-click on the server’s name in Object Explorer and select "Properties".

•	Go to the "Connections" tab and make sure "Allow remote connections to this server" is checked.

Verify TCP/IP is Enabled:

•	In SQL Server Configuration Manager, expand "SQL Server Network Configuration" and select "Protocols for [YourInstance]".

•	Ensure that the TCP/IP protocol is enabled.

Check Firewall Settings

1.	Allow SQL Server Port in Firewall:
   
o	Open Windows Firewall with Advanced Security.

o	Add an inbound rule for TCP port 1433 (default port for SQL Server).

By following these steps, you will be able to connect to your SQL Server database to Oracle SQL Developer, allowing you to manage and query your SQL Server database using the Oracle SQL Developer interface.



# Project 4: Bank ATM Transaction Analysis Across Some States in Nigeria

# [Bank ATM Transaction Analysis](https://app.powerbi.com/view?r=eyJrIjoiZTM4YWZmODAtZDk3ZC00M2Q4LTg5ZTctNDExZTRkZDdjODMzIiwidCI6ImJhMTMwZWNhLTMwMzAtNDhlMS05MDg5LWM5NzkyOTNhZWI3MCIsImMiOjh9)

### Project Overview
The Bank ATM Transaction Analysis project was undertaken to gain comprehensive insights into customer behavior, transaction patterns, and ATM usage across five key states in Nigeria. The analysis aimed to enhance customer experience, optimize ATM deployment, and improve operational efficiency for the bank.

Objectives:
1. Customer Behavior Insights: Understand customer transaction patterns and preferences across different states.
2. ATM Usage Optimization: Identify high and low-performing ATMs to ensure optimal distribution and availability.
3. Operational Efficiency: Improve ATM service levels and reduce downtime by analyzing transaction data and customer feedback.

### Home Page
The Home page provides a detailed breakdown of the total transaction amount and monthly totals, utilization rate and its monthly breakdown, transaction count, and the monthly count of utilization rate, among other key metrics.

<img width="536" alt="image" src="https://github.com/user-attachments/assets/fdff0bd9-3730-4c10-99dd-446e3202390b">

### The Overview Page
The overview provides a summary of the average transaction duration across various transaction types, along with a daily transaction trend analysis showing that customers typically use ATMs between 6:00 AM and 7:00 PM. It also presents the monthly trends in transaction amount and count, as well as the average transaction amount across different transaction types.

<img width="542" alt="image" src="https://github.com/user-attachments/assets/c7beefc6-31b8-49fd-ba30-a46a26931462">

### Demographic Report
The demographic report page presents the distribution of transactions by demographic factors such as occupation and transaction type. It also details transaction counts by customer age group and transaction type, along with the average time customers spend on ATM transactions.

<img width="539" alt="image" src="https://github.com/user-attachments/assets/b4f0fd2a-5645-4172-bda3-f5df176afcaa">



# Project 5: Retail Sales Analysis SQL Project

## Project Overview
Project Title: Retail Sales Analysis
Database: retail_sales_analysis_project
Tool: PostgreSQL Database

This project aims to showcase SQL skills and techniques commonly utilized by data analysts to explore, clean, and analyze retail sales data. It involves setting up a retail sales database, conducting exploratory data analysis (EDA), and using SQL queries to answer targeted business questions. This project is perfect for beginners in data analysis who wish to establish a strong foundation in SQL.

## Objectives
1. Set up a retail sales database: Create and populate a retail sales database with the provided sales data.
2. Data Cleaning: Identify and remove any records with missing or null values.
3. Exploratory Data Analysis (EDA): Perform basic exploratory data analysis to understand the dataset.
4. Business Analysis: Use SQL to answer specific business questions and derive insights from the sales data.

# Project Structure
##  1. Database Setup
- **Database Creation**: The project starts by creating a database named `retail_sales_analysis_project`.
- **Schema Creation**: A database owner called Schema is created named `sales`
- **Table Creation**: A table named `retail_sales` is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.

```sql
---SQL Retails Sales Analysis
---create database
create database retail_sales_analysis_project;

--create schema
create schema sales;

---create table
create table sales.retail_sales(
	transactions_id int primary key,
	sale_date date,
	sale_time time,
	customer_id	int,
	gender	varchar,
	age int,
	category varchar (20),
	quantiy int,
	price_per_unit float,
	cogs float,
	total_sale float
);
```
### 2. Data Exploration & Cleaning

- **Record Count**: Determine the total number of records in the dataset.
- **Customer Count**: Find out how many unique customers are in the dataset.
- **Category Count**: Identify all unique product categories in the dataset.
- **Null Value Check**: Check for any null values in the dataset and delete records with missing data.

```sql
SELECT COUNT(*) FROM retail_sales;
SELECT COUNT(DISTINCT customer_id) FROM retail_sales;
SELECT DISTINCT category FROM retail_sales;

SELECT * FROM retail_sales
WHERE 
    sale_date IS NULL OR sale_time IS NULL OR customer_id IS NULL OR 
    gender IS NULL OR age IS NULL OR category IS NULL OR 
    quantity IS NULL OR price_per_unit IS NULL OR cogs IS NULL;

DELETE FROM retail_sales
WHERE 
    sale_date IS NULL OR sale_time IS NULL OR customer_id IS NULL OR 
    gender IS NULL OR age IS NULL OR category IS NULL OR 
    quantity IS NULL OR price_per_unit IS NULL OR cogs IS NULL;
```
### 3. Data Analysis & Findings

-- Data Analysis & Business Key Problems & Answers

1. **Write a SQL query to retrieve all columns for sales made on '2022-11-05**:
   
```sql
SELECT *
FROM retail_sales
WHERE sale_date = '2022-11-05';
```
<img width="748" alt="image" src="https://github.com/user-attachments/assets/04787024-ffb9-4e12-9c8f-6208ec27b427">

2. **Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022**:
```sql
select * 
from sales.retail_sales
where category = 'Clothing'
AND quantiy >= 4 
	AND sale_date BETWEEN '2022-11-01' AND '2022-11-30';
```
Alternatively

```sql
SELECT  *
FROM sales.retail_sales
WHERE category = 'Clothing'
	AND TO_CHAR(sale_date, 'YYYY-MM') = '2022-11'
    AND quantiy >= 4
```
<img width="778" alt="image" src="https://github.com/user-attachments/assets/9a13dd79-2f6e-4302-a1a0-aefb8bb9c1c0">

3. **Write a SQL query to calculate the total sales (total_sale) for each category.**:

```sql
SELECT category, sum(total_sale) as Total_Sales
from sales.retail_sales
group by category
order by 2 desc
```
Alternatively
```sql
SELECT 
    category,
    SUM(total_sale) as net_sale,
    COUNT(*) as total_orders
FROM sales.retail_sales
GROUP BY 1
```
<img width="803" alt="image" src="https://github.com/user-attachments/assets/cd25fa12-5318-4a05-9284-18f193cd0aec">

4. **Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.**:
```sql
select avg(age)
	from sales.retail_sales
where category = 'Beauty'
```
Alternatively
```sql
SELECT
    ROUND(AVG(age), 2) as Avg_Age
FROM sales.retail_sales
WHERE category = 'Beauty'
```
<img width="808" alt="image" src="https://github.com/user-attachments/assets/edf3a4b1-c1a9-4df1-a3eb-a9ba939751e1">

5. **Write a SQL query to find all transactions where the total_sale is greater than 1000.**:
```sql
SELECT * FROM retail_sales
WHERE total_sale > 1000
```
<img width="812" alt="image" src="https://github.com/user-attachments/assets/91cbc1c0-a034-43c9-97e2-803a04035f98">

6. **Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.**:
```sql
select category, gender, count(transactions_id)
from sales.retail_sales
group by gender, category
order by 1
```
Alternatively
```sql
SELECT 
    category,gender,
    COUNT(*) as total_trans
FROM sales.retail_sales
GROUP BY category,gender
ORDER BY 1
```
<img width="809" alt="image" src="https://github.com/user-attachments/assets/ff2097ad-8e30-4730-8f6f-affa250ea8d4">

7. **Write a SQL query to calculate the average sale for each month. Find out best selling month in each year**:
```sql
SELECT year,month,avg_sale
FROM 
( SELECT 
    EXTRACT(YEAR FROM sale_date) as year,
    EXTRACT(MONTH FROM sale_date) as month,
    AVG(total_sale) as avg_sale,
    RANK() OVER(PARTITION BY EXTRACT(YEAR FROM sale_date) ORDER BY AVG(total_sale) DESC) as rank
FROM sales.retail_sales
GROUP BY 1, 2
) as t1
WHERE rank = 1
```
<img width="803" alt="image" src="https://github.com/user-attachments/assets/05c0d744-8fdb-4113-858b-d2ec29fe8a9b">

8. **Write a SQL query to find the top 5 customers based on the highest total sales **:
```sql
select customer_id, sum(total_sale) as Total_Sales
from sales.retail_sales
group by customer_id
order by 2 desc
limit 5
```
Alternatively
```sql
SELECT customer_id,
    SUM(total_sale) as total_sales
FROM sales.retail_sales
GROUP BY 1
ORDER BY 2 DESC
LIMIT 5
```
<img width="806" alt="image" src="https://github.com/user-attachments/assets/7c818522-0c55-4aa6-ac85-344bfb76e707">

9. **Write a SQL query to find the number of unique customers who purchased items from each category.**:
```sql
select category, COUNT(DISTINCT customer_id) as Total_Customer
	from sales.retail_sales
group by category
ORDER BY 2 DESC
```
<img width="810" alt="image" src="https://github.com/user-attachments/assets/f9732411-824c-4b19-907a-72264a3a1312">

10. **Write a SQL query to create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17)**:
```sql
WITH hourly_sale
AS
(
SELECT *,
    CASE
        WHEN EXTRACT(HOUR FROM sale_time) < 12 THEN 'Morning'
        WHEN EXTRACT(HOUR FROM sale_time) BETWEEN 12 AND 17 THEN 'Afternoon'
        ELSE 'Evening'
    END as shift
FROM sales.retail_sales
)
SELECT 
    shift,
    COUNT(*) as total_orders    
FROM hourly_sale
GROUP BY shift
```
<img width="808" alt="image" src="https://github.com/user-attachments/assets/258942ae-6c03-48b4-8f07-5a4da58158d4">

## Findings

- **Customer Demographics**: The dataset includes customers from various age groups, with sales distributed across different categories such as Clothing and Beauty.
- **High-Value Transactions**: Several transactions had a total sale amount greater than 1000, indicating premium purchases.
- **Sales Trends**: Monthly analysis shows variations in sales, helping identify peak seasons.
- **Customer Insights**: The analysis identifies the top-spending customers and the most popular product categories.

## Reports

- **Sales Summary**: A detailed report summarizing total sales, customer demographics, and category performance.
- **Trend Analysis**: Insights into sales trends across different months and shifts.
- **Customer Insights**: Reports on top customers and unique customer counts per category.

## Conclusion

This project serves as a comprehensive introduction to SQL for data analysts, covering database setup, data cleaning, exploratory data analysis, and business-driven SQL queries. The findings from this project can help drive business decisions by understanding sales patterns, customer behavior, and product performance.

# Project 6: Hospital Emergency Room Visits Dashboard

# [Hospital Emergency Room Visits](https://app.powerbi.com/reportEmbed?reportId=ca5194c1-ed2e-4cfc-b97b-db0faeb25a81&autoAuth=true&ctid=ba130eca-3030-48e1-9089-c979293aeb70)

## Project Overview
Project Title: Hospital Emergency Room Visits
Data Source: Microsoft SQL Server
Tool: Microsoft Power BI

This Power BI project delivers a dynamic and interactive dashboard designed to support hospitals in monitoring and improving emergency room (ER) operations. The dashboard provides a comprehensive overview of ER visits, enabling healthcare administrators to:

- Analyze key performance metrics such as patient wait times, visit volumes, and admission rates
-Identify peak hours and high-demand periods for better staff allocation
- Track patient outcomes and revisit rates to assess care quality
- Detect trends and patterns in emergency cases over time
- Make data-driven decisions to enhance efficiency and patient satisfaction

By consolidating critical ER data into a single, user-friendly interface, this dashboard empowers hospital management to uncover actionable insights, optimize resource utilization, and ultimately improve the quality of emergency care services.

## Overview Page

![Image](https://github.com/user-attachments/assets/90e7d07c-7277-4b19-af0f-07e2bb63e1a5)

# Number of Patients
- The dashboard indicates that 5,000 patients visited the Emergency Room during the selected month (2020).
- This is a significant increase of 897.5% compared to the previous month, suggesting a surge in ER visits. This could be due to a seasonal trend, public health issue, or special events influencing hospital visits.

# Average Wait Time
- The average wait time for patients in the ER is 35.47 minutes.
- There's been a 2% improvement in wait time compared to the previous month.
This might reflect better operational efficiency, more staffing, or process optimizations in triage and treatment.

# Average Satisfaction
- Patient satisfaction score is 5.0, rated on a scale presumably out of 5.
- The score has improved by 6% since the last month, indicating that changes implemented recently might be positively impacting patient experience.

- # **Satisfaction is further broken down by:**
    - **Race:** Pacific Islanders have the highest average score (5.3), while Native American/Alaska Native and "Two or More Races" have the lowest (4.8).
    - Filters are available to analyze satisfaction by Age Range, Gender, and Race.

# Visits by Gender
- The dashboard shows gender-based visit trends over the week:
  - **Male:** 2,523 visits
  - **Female:** 2,355 visits
  - While both genders follow similar patterns, there is a slight dominance in male visits
  - Peak days appear to be Tuesdays and Fridays, with fluctuations throughout the week.

# Patients Visits by Day and Time
- A heatmap visual shows the volume of visits by day of week and hour of day.
- Monday is the busiest day, and 11:00 PM is the busiest time.
- The darkest shades (higher visit counts) appear between 4 PM to midnight on weekdays.
- Sunday early mornings and weekday mornings are relatively quieter.
- This insight can help with resource planning and staff allocation.

# Average Wait Time by Department
- This bar chart compares wait times across departments:
     - Neurology has the longest average wait time (37 mins), indicating a possible backlog or staff/resource shortage.
     - Physiotherapy, Cardiology, Orthopedics, and unidentified patients ("None") all average 36 mins.
     - Gastroenterology and General Practice are at 35 mins.
     - Renal department has the shortest average wait time (34 mins), possibly indicating a smoother triage process or lower patient volume.

 
## Summary Page

![Image](https://github.com/user-attachments/assets/c2aa334e-edda-4cfc-88d8-380a3d7f9044)


## Columns Explained
1. ### Patient_ID
- A unique identifier for each patient visit (e.g., 100-04-3993).
- Indicates multiple visits by different patients.

2. ### Year / Month
- Displays the year and month of each emergency room visit.
- Helps in analyzing seasonal trends or time-based spikes in ER usage.

3. ### Full Name
- Pseudonym or masked name of the patient for privacy.
- Not relevant for analytics but useful for reference in private/internal reports.

4. ### Gender
- Indicates if the patient is Male (M) or Female (F).
- Enables gender-based trend analysis (e.g., are women waiting longer?).

5. ### Race
- Ethnic identification (e.g., White, African American, Pacific Islander, Asian).
- This data helps track healthcare equity or satisfaction trends across racial groups.

6. ### Age / Age Range
- Numerical age and categorized age groups (e.g., Youth, Adult, Senior).
- Useful for identifying patterns in ER visits by age brackets.

7. ### Department
- The ER department the patient visited (e.g., General Practice, Neurology, Orthopedics).
- Helps assess department workloads, bottlenecks, or specialties with high traffic.

8. ### Satisfaction Score
- Patient-reported satisfaction on a likely scale of 0–10.
- A score of 10 suggests excellent experience, while 0 suggests poor.
  
9. ### Wait Time
- The number of minutes the patient waited before being seen.
- Critical for operational performance analysis and improving patient experience.

## Insights You Can Derive
### Performance per Department
E.g., some departments like General Practice show repeated entries with both low and high wait times — indicating inconsistent performance or varying demand.

### Wait Time Disparities
Seniors and patients in some departments (like Neurology) tend to wait longer (e.g., 60 mins, 55 mins), suggesting potential under-capacity or triage issues.

### Satisfaction vs. Wait Time
You can compare satisfaction scores against wait times. For example:

 - Patient_ID 102-04-8249 had 1 min wait and a satisfaction score of 11, indicating strong satisfaction.
 - Patient_ID 100-17-5953 had 60 min wait and a satisfaction score of 6 — still moderate satisfaction, possibly due to care quality.

### Race-Based or Age-Based Satisfaction Trends
The data allows filtering for race/age to evaluate disparities in treatment or patient experience.

# Project 7: Reducing Reporting Bottlenecks in Finance
# Leveraging Modern Data Solutions for Enhanced Efficiency and Strategic Insights

## Business Use Case: Streamlining Financial Reporting for Better Compliance and Efficiency

## Client Profile
A mid-sized financial services provider—such as a microfinance bank, fintech company, investment firm, or insurance organization—is grappling with increasing data complexity, rising regulatory demands, and inefficient manual reporting processes.

These challenges hinder performance, slow decision-making, and increase compliance risks. To remain competitive and meet regulatory expectations, the institution needs to modernize its data infrastructure by:

- Integrating fragmented systems
- Automating data consolidation and reporting
- Enabling real-time, insight-driven decision-making across the business

## Current Situation
- Multiple Data Silos: Data resides in Excel/CSV, SQL Server, SharePoint folder, ERP, and Core Banking platforms, making integration difficult.
- Manual Reporting: Teams consolidate data manually, increasing the risk of errors and delays.
- Disjointed Systems: Separate tools for ETL, reporting, and visualization reduce collaboration and transparency.
- Inconsistent KPIs: Different departments use their own metrics, leading to conflicting reports and misaligned decisions.

## Key Challenges
- Data Fragmentation: Lack of a unified data platform limits visibility and control.
- No Real-Time Insights: Inability to generate real-time or self-service reports impacts decision-making.
- Inefficiency: Reporting is time-consuming, requiring hours or days of manual effort.
- Regulatory Risk: Difficulty meeting evolving requirements (e.g., IFRS 9, Basel III, CBN Guidelines) due to slow and error-prone processes.
- Rising Costs: High operational burden from repeated manual tasks and data reconciliation.

## Business Impact
This situation leads to:
- Delayed financial reporting and compliance issues
- Limited agility in responding to regulatory or business changes
- High cost-to-serve due to inefficiencies
- Poor decision-making due to inconsistent or outdated data

## Opportunity
By adopting a unified analytics platform like Microsoft Fabric, the institution can:
- Integrate all data sources into a single platform (OneLake)
- Automate data ingestion, transformation, and reporting
- Enable real-time dashboards and self-service BI with Power BI
- Standardize KPIs across departments
- Meet regulatory requirements faster and more accurately

## Overview of the Project Architecture
<img width="1322" height="743" alt="Screenshot 2025-08-02 211111" src="https://github.com/user-attachments/assets/4bee071f-0a27-4c06-8841-5100574e9d08" />

The architecture illustrates an end-to-end enterprise data warehouse and reporting solution using Microsoft Fabric. It ingests data from structured and unstructured sources (CSV, SQL, APIs, SharePoint, JSON) through pipelines, Eventstream, and Dataflow Gen2 into the Bronze layer. The Silver layer processes data via Lakehouse and Fabric Notebooks using PySpark or Scala. The Gold layer stores refined data in the Fabric Data Warehouse for analytics. Power BI connects directly to the warehouse for reporting and dashboards. Eventhouse supports real-time data via KQL queries and dashboards. Microsoft Purview and OneLake unify governance and storage across the platform for business insights and decision-making.

## Project Implementation

## Customer_to_Data_WH_Pipeline
<img width="1486" height="898" alt="Screenshot 2025-08-02 214326" src="https://github.com/user-attachments/assets/800d47a9-56b6-4323-bec8-a5a3c732600d" />

The pipeline “Customer_to_Data_WH_Pipeline” performs an incremental load of customer data from a SharePoint folder to Microsoft Fabric Data Warehouse. Here's a summary:
- Dataflow activity reads customer data from SharePoint.
- Two Lookup activities retrieve the old and new watermark values (typically timestamps) to identify new or changed records.
- The Copy Data activity loads only the delta (incremental data) from SharePoint into Fabric Data Warehouse using the watermark values as filters.
- After loading, a stored procedure (Update_Customer_WaterMark SP) updates the watermark value for the next run.
- The pipeline ensures efficient incremental data loading and historical tracking.
- 
# Here is the customer data in the data warehouse
<img width="1851" height="908" alt="Screenshot 2025-08-02 222414" src="https://github.com/user-attachments/assets/cef9ec6c-33b1-43cd-850f-8ba3ae0c2538" />

## Transaction_Pipeline
<img width="1485" height="827" alt="Screenshot 2025-08-02 214749" src="https://github.com/user-attachments/assets/c0f7fb93-d7aa-4b90-9396-f9ddfcdf9387" />

The Transaction_Pipeline enables dynamic, incremental data loading from SQL Server (Snapnet_FSI database) to the target system. Here's the summary:
- Lookup Activity (Get Base Tables) retrieves a list of source tables (e.g., Loan, Transaction) with schema details.
- A ForEach activity (Loop Table) iterates over these tables.
- Inside the loop, the Copy Data activity (onprem to EDW):
    - Dynamically sets the source schema and table name using @item().Schema and @item().Table.
   - Transfers Loan data from 2020 to date and Transaction data incrementally.
- Ideal for scalable ETL processes across multiple SQL Server tables.

# Here is the data (Loan & Financial transaction) in the Data Warehouse
<img width="1831" height="741" alt="Screenshot 2025-08-02 221852" src="https://github.com/user-attachments/assets/1c7d0634-9787-42bb-a9de-514974619c66" />
<img width="1842" height="901" alt="Screenshot 2025-08-02 222145" src="https://github.com/user-attachments/assets/74b51d02-3fdf-4d34-a6d3-aa7326eb3a91" />

## Fabric_Event_Financial_Data_Source_Nb
<img width="1492" height="871" alt="Screenshot 2025-08-02 220951" src="https://github.com/user-attachments/assets/f649550a-d2b6-43a9-bb1d-5a29529a3a93" />

The attached notebook demonstrates a workflow for extracting financial data via an API, transforming it, and storing it in a lakehouse. The notebook begins with an exploration of available data items, including tables like Financial_Transaction and Loan_trans_2023-2025, suggesting a financial analytics context.

The user,imports libraries such as pandas and uses notebookutils.credentials to securely retrieve an API key from Azure Key Vault. A function, get_data_from_api, is defined to fetch financial data from the API endpoint api.api.tiles.io/v2/markets/stock/financial, using a ticker symbol as input. Although incomplete, the function outlines the API call structure.

The notebook's purpose appears to be pulling financial data (e.g., stock metrics), processing it, and saving it as a table in the lakehouse (e.g., structured_financial_report). This aligns with common data engineering tasks in financial analytics, emphasizing secure API access and lakehouse integration for further analysis. The execution timestamps indicate active development.

## Enterprise Reporting Using Power BI 

Power BI connects directly to the data warehouse to create reports and dashboards that help business users make informed decisions.

# Financial Report

<img width="1417" height="790" alt="Screenshot 2025-08-02 223714" src="https://github.com/user-attachments/assets/7b8c98fc-e364-4d2f-8134-94e4ea71a691" />

This financial report highlights strong growth, with total revenue at $3.06B (↑6.5%) and net profit at $1.47B (↑8.2%). Key takeaways:
- Profitability Improved: Gross profit rose to $1.42B (↑11.35%), with a gross profit ratio of 46.51% (↑4.8%), indicating better cost management.
- Subsidiary Performance:
     - Apple leads in revenue ($1.52B) but saw a decline in gross profit ratio (-13.89%).
   - Google grew strongly ($1.2B revenue, ↑17% gross profit).
   - Tesla struggled with a lower gross profit ratio (21.1%) due to higher expenses.
- Efficiency Gains: Net margin improved to 48.03% (↑1.5%), showing better earnings retention.
- Key Risks: Rising total expenses (↑7.2%) and negative account receivable (-$57M) suggest tighter cash flow management is needed.
Action: Focus on cost control (especially Tesla), leverage Google’s growth, and optimize receivables.

# Loan Performance Report
<img width="1423" height="792" alt="Screenshot 2025-08-02 224537" src="https://github.com/user-attachments/assets/822aad5a-457d-46ce-845c-4fde6c5e3ac2" />

This report analyzes a $5.13B loan portfolio, with $2.22B outstanding and 10K active loans. Key insights:
- Risk Exposure: 1,478 delinquent loans (14% of active loans) and 744 defaults require monitoring.
- Channel Performance: Mobile (ATM/WBC) disbursed $1.2B, but also had higher delinquencies. USSD/API channels showed lower risk.
- Customer Segments: Retail dominated (46% of loans), but delinquency rates were high (9.15%). Corporate/VIP loans were smaller but more stable.
- Sector Focus: General sector (56%) and commerce (14%) drove most loans, while oil/gas and real estate were smaller.
Action: Tighten retail underwriting, optimize mobile channel risk, and diversify sector exposure.

<img width="1415" height="782" alt="Screenshot 2025-08-02 224824" src="https://github.com/user-attachments/assets/7c502d5c-71d2-4411-b09c-0b932a4cf29f" />

# Bank Transaction Report Summary

<img width="1418" height="797" alt="Screenshot 2025-08-02 225106" src="https://github.com/user-attachments/assets/2f16046b-bc8e-45e6-a894-382416869cfd" />

This report analyzes 15K transactions totaling $6.96M, with a 91.9% success rate. Key highlights:
- Net Flow: Positive $995K (credits: $2.2M, debits: $1.2M).
- Recent Activity: $75.27M processed in the last 7 days (21 transactions).
- Customer Segments: Retail dominated ($547K), while Corporate and VIP showed lower volumes.
- Channels: Mobile/ATM led in volume, but USSD/API had higher reliability.
- Risks: 3.3% failure rate and pending/reverted transactions need review.
- Currency Mix: NGN (local) and USD were primary, with CAD/GBP minor.
Action: Optimize mobile channel reliability, monitor failed transactions, and focus on retail/corporate growth.

<img width="1427" height="783" alt="Screenshot 2025-08-02 225405" src="https://github.com/user-attachments/assets/1f60bd4f-badc-4274-be5d-3fc3a7f2e9d3" />

This report provides a detailed analysis of 28K transactions, with $6.96M YTD volume (down 55% MoM). Key insights:
- Performance: Average transaction size is $232, with largest credit/debit at $5.03K/$2.11K.
- Risks: 502 high-risk transactions detected (4.89% anomaly rate), alongside 914 failed and 888 reversed transactions needing review.
- Customer Activity: Retail dominates transactions (e.g., Bruce Gutierrez, Charles Thompson), while corporate/business segments show lower volumes.
- Data Gaps: Missing balance data for some entries (e.g., Josu Sullivan) requires validation.
Action: Investigate MoM decline, address high-risk/failed transactions, and verify incomplete records. (Note: Anomaly detection and channel-specific analysis would enhance insights.)

## Conclusion

Microsoft Fabric empowers financial institutions to modernize their data landscape by:
- Unifying fragmented data sources into a single, scalable platform
- Enabling real-time insights and self-service analytics
- Automating manual processes for faster decision-making
- Ensuring compliance with built-in governance and security
- Reducing operational costs with an all-in-one SaaS solution

With Microsoft Fabric, your organization is better equipped to drive smarter decisions, stay compliant, and remain competitive in today’s fast-paced financial ecosystem.


