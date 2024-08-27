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

