# Kultra_Mega_SQL_Project
SQL-based analysis of Kultra Mega Stores (KMS) sales data from 2009-2012 using Microsoft SQL Server. The purpose is to gain insights and drive strategic business decisions, and optimize revenue.

## PROJECT TITLE: KMS SALES ANALYSIS

[PROJECT OVERVIEW](#project-overview)

[DATA SOURCES](#data-sources)

[TOOLS USED](#tools-used)

[DATA CLEANING AND PREPARATION](#data-cleaning-and-preparation)

[EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)

[DATA ANALYSIS](#data-analysis)

[DATA VISUALIZATION](#data-visualization)

[INSIGHTS](#insights)

[RECOMMENDATION](#recommendation)


### PROJECT OVERVIEW 

Kultra Mega Stores (KMS) deals in office supplies and furniture, supplying individual consumers, small businesses, and large corporate clients across Nigeria. The purpose of this project is to analyze KMS sales data from 2019-2012 from the  Abuja division using Microsoft SQL Server. The aim is to uncover actionable insights and make data-driven decisions that drive Performance, improve shipping costs, and customer relationships.

### DATA SOURCES
The source of data used for this analysis is the KMS SQL Case study and OrderBonus rules.csv, and this is an open-source dataset that can be freely downloaded from open-source online sites such as Kaggle or FRED, or any other data repository site.

### TOOLS USED
Ms Excel for Data Cleaning [Download Here](https://www.microsoft.com/en-us/microsoft-365/download-office)
 - For Data Collection
 - For Data preprocessing

Microsoft SQL Server [Download here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- Database management
- SQL querying for extraction, analysis, and reporting.
- 
### DATA CLEANING AND PREPARATION
In the initial phase of the Data Cleaning and preparations, I perform the following actions;
1. Data Loading and Inspection
2. Handling Missing Variables
3. Data Cleaning and Formatting


### EXPLORATORY DATA ANALYSIS
The objective of this analysis is to explore, summarize key patterns and trends in the KMS data by answering the following important questions:
1. Which product category had the highest sales?
2. What are the Top 3 and Bottom 3 regions in terms of sales?
3. What were the total sales of appliances in Ontario?
4. Advise the management of KMS on what to do to increase the revenue from the bottom 10 customers
5. KMS incurred the most shipping cost using which shipping method?
6. Who are the most valuable customers, and what products or services do they typically purchase?
7. Which small business customer had the highest sales?
8. Which Corporate Customer placed the most number of orders in 2009 – 2012?
9. Which consumer customer was the most profitable one?
10. Which customer returned items, and what segment do they belong to?
11. If the delivery truck is the most economical but the slowest shipping method, and Express Air is the fastest but the most expensive one, do you think the company appropriately spent shipping costs based on the Order Priority? Explain your answer




### DATA ANALYSIS
I used SQL queries in Microsoft SQL Server to extract, aggregate, and interpret key business metrics from historical order data (2009-2012). The analysis provides an understanding of the sales performance, customer behavior, and overall operational efficiency across the different product categories, regions, customer segments, shipping modes, and shipping methods.
Key findings included: 
- The best-performing products category and top/bottom regions in sales
- Understand Customer Profitability
     - Identify the valuable and least performing customers
- Evaluate the shipping cost and how it relates to the different shipping modes.

```1. Which Product category had the highest Sales
Select Product_Category,  Max(Sales) As Max_Sales From dbo.[KMS Sql Case Study]
Group by Product_Category
Order by Max_Sales desc```

```%Female High Salary = DIVIDE([Female_HighSalary_Count],[Total_Male_Female])```

```%Female Low Salary = DIVIDE([Female_LowSalary_Count],[Total_Male_Female])```

```%Male Above Average = Divide([No of Males Rated Above Average],[Total_Male_Female])```

```%Male High Salary = DIVIDE([Male_HighSalary_Count],[Total_Male_Female])```

```%Male Low Salary = DIVIDE([Male_LowSalary_Count],[Total_Male_Female])```

```Average Salary by Gender = AVERAGE('Palmoria Group emp-data'[Salary])```

```Total Pay = 'Palmoria Group emp-data'[Salary] + 'Palmoria Group emp-data'[Bonus Amount]```

### DATA VISUALIZATION
After cleaning and creating New columns in Power Query, I applied the changes and used the Report Review for data visualization. Several expressions and functions were created to achieve the desired KPIs or metrics, providing a clear and actionable visual for informed decision-making. Some of the visuals are:
- Gender Distribution
- Salary Distribution
- Gender Per Gap and Performance rating
- Salary band and Bonus Distribution







### INSIGHTS
- The organization's gender is nearly balanced with 49.1 % Male, 46.6% Female, and 4.3% undisclosed. However, a department like Engineering, Legal, and Operations has lower female representation.
- Males earn more on average than females.
- The gender gap is significant in the Human Resources and Support departments.
- Abuja shows the widest salary distribution between males and females across the regions
- About 654 (69%) earn less than the $90000 minimum salary benchmark which indicates a lack of compliance.
- Palmoria paid over $2.2 million in bonuses, with Kaduna receiving the largest share
- The total amount paid by the company exceeded $71.9 million


### RECOMMENDATION
While there are some gender pay gaps within Palmoria Group, especially in departments like HR, Legal, and Support, the data shows that the situation may not be as severe as the media suggests. The disparities aren't widespread, but they do exist and deserve attention.

That said, the company needs to take clear steps toward fairness. We recommend focusing on closing salary gaps in the affected departments and making sure female employees are fairly compensated, especially when they have similar roles and performance to their male colleagues.

Additionally, a significant number of employees earn below the $90,000 minimum wage benchmark. Addressing this will not only help Palmoria stay compliant but also improve employee satisfaction and reputation
