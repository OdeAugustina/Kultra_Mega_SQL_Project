---
# Kultra_Mega_SQL_Project

SQL-based analysis of Kultra Mega Stores (KMS) sales data from 2009-2012 using Microsoft SQL Server. The purpose is to gain insights and drive strategic business decisions, and optimize revenue.

---

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

---


### PROJECT OVERVIEW 



Kultra Mega Stores (KMS) deals in office supplies and furniture, supplying individual consumers, small businesses, and large corporate clients across Nigeria. The purpose of this project is to analyze KMS sales data from 2019-2012 from the  Abuja division using Microsoft SQL Server. The aim is to uncover actionable insights and make data-driven decisions that drive Performance, improve shipping costs, and customer relationships.

---

### DATA SOURCES


The source of data used for this analysis is the KMS SQL Case study and OrderBonus rules.csv, and this is an open-source dataset that can be freely downloaded from open-source online sites such as Kaggle or FRED, or any other data repository site.

---

### TOOLS USED


Ms Excel for Data Cleaning [Download Here](https://www.microsoft.com/en-us/microsoft-365/download-office)
 - For Data Collection
 - For Data preprocessing

Microsoft SQL Server [Download here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- Database management
- SQL querying for extraction, analysis, and reporting.

---


### DATA CLEANING AND PREPARATION


In the initial phase of the Data Cleaning and preparations, I perform the following actions;
1. Data Loading and Inspection
2. Handling Missing Variables
3. Data Cleaning and Formatting

---


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


---

### DATA ANALYSIS


I used SQL queries in Microsoft SQL Server to extract, aggregate, and interpret key business metrics from historical order data (2009-2012). The analysis provides an understanding of the sales performance, customer behavior, and overall operational efficiency across the different product categories, regions, customer segments, shipping modes, and shipping methods.
Key findings included: 
- The best-performing products category and top/bottom regions in sales
- Understand Customer Profitability
     - Identify the valuable and least performing customers
- Evaluate the shipping cost and how it relates to the different shipping modes.



#### 1. Which product category had the highest sales?
  

<img width="472" alt="Query 1a" src="https://github.com/user-attachments/assets/3d8f29ed-6216-4e0e-899b-fc4747ab1e09" />



#### 2. What are the Top 3 and Bottom 3 regions in terms of sales?

![Query 2a](https://github.com/user-attachments/assets/3a6d274e-0465-4b67-93bd-c3ece3ddebdd)





![Query 2b](https://github.com/user-attachments/assets/af77d975-41f2-4ede-83f0-a06e9c47124b)



#### 3. What were the total sales of appliances in Ontario?

<img width="365" alt="Query 3a" src="https://github.com/user-attachments/assets/1b99107c-b360-4209-9baa-e3f509355ad6" />



#### 4. Advise the management of KMS on what to do to increase the revenue from the bottom 10 customers


<img width="602" alt="Query 4" src="https://github.com/user-attachments/assets/ef5f55f2-7a46-4b58-a783-14e6af1bbc59" />



#### 5. KMS incurred the most shipping cost using which shipping method?


<img width="514" alt="query 5a" src="https://github.com/user-attachments/assets/e154391d-01c9-4322-a1c4-1ce65c25a4b5" />



#### 6. Who are the most valuable customers, and what products or services do they typically purchase?

![Query 6](https://github.com/user-attachments/assets/3b2f9975-2706-4f33-a0a2-71ebe8402257)



#### 7. Which small business customer had the highest sales?

<img width="479" alt="query 7a" src="https://github.com/user-attachments/assets/0dc22c82-4a90-456c-afc2-9430a8e6d641" />



#### 8. Which Corporate Customer placed the most number of orders in 2009 – 2012?

<img width="494" alt="query8a" src="https://github.com/user-attachments/assets/5855cdb4-3e3a-4bc3-965e-e6b22f815519" />




#### 9. Which consumer customer was the most profi table one?

![Query 9](https://github.com/user-attachments/assets/383d48f9-b233-4246-9314-373b53c79ae0)




#### 10. Which customers returned items, and what segment do they belong to?

![Query 10](https://github.com/user-attachments/assets/120a2d43-4145-464a-b16c-73b675e1c167)




#### 11. If the delivery truck is the most economical but the slowest shipping method, and Express Air is the fastest but the most expensive one, do you think the company appropriately spent shipping costs based on the Order Priority? Explain your answer


![Query 11](https://github.com/user-attachments/assets/c2e99243-7ffc-47b4-8e38-bd3229d9b453)




---



### DATA VISUALIZATION


#### 1. Top-Selling Product Category


<img width="158" alt="Question 1a" src="https://github.com/user-attachments/assets/9d221600-29ac-4166-8509-cb4d13dda84a" />




#### 2.Top 3 & Bottom 3 Sales Regions



![Top3 Bot3](https://github.com/user-attachments/assets/053930ff-9d0a-4e27-9bbe-302820cc41ed)



![Question 2a](https://github.com/user-attachments/assets/3d4dfaaa-93ca-47e8-ba60-e38aa538552c)



![Question 2b](https://github.com/user-attachments/assets/5e0ce0e5-6d69-4289-92fa-44f1625e5f0d)


#### 3.Appliance Sales in Ontario



<img width="116" alt="Question 3a" src="https://github.com/user-attachments/assets/0fa594b6-60d6-4f1e-a860-3625a0598e93" />




#### 4. Bottom 10 Customers


<img width="1301" alt="Question 4" src="https://github.com/user-attachments/assets/70934ab0-5553-45c6-b27b-f81979e04476" />



#### 5. Highest Shipping Cost by Method

<img width="181" alt="question 5a" src="https://github.com/user-attachments/assets/6e3be50e-6b97-4846-890c-b38165779b29" />



#### 6. Most Valuable Customers & Products


![Question 6](https://github.com/user-attachments/assets/a3dfae70-f24c-4f52-832c-1563358a3c4f)



#### 7. Top Small Business Customer by Sales


<img width="164" alt="question 7a" src="https://github.com/user-attachments/assets/fb3c1252-8484-4f24-b6df-5e93fbf4038c" />




#### 8. Corporate Customer With Most Orders (2009–2012)


<img width="161" alt="question 8a" src="https://github.com/user-attachments/assets/39ddceeb-e025-471e-b2b0-9e10f116c1e2" />



#### 9. Most Profitable Consumer Customer


![Question 9](https://github.com/user-attachments/assets/b99576bf-9b59-4364-b115-96135c0322f5)



#### 10. Customers Who Returned Items & Their Segments



![Question 10](https://github.com/user-attachments/assets/1be35c08-328a-43bb-9776-5cca8c33b702)


#### 11. Shipping Efficiency Based on Order Priority



![Question 11](https://github.com/user-attachments/assets/e4b27a36-f466-402b-8909-60ae99688d54)

---


### INSIGHTS


- Technology is the highest performing product category with over $89,061.05 in sales.
- The top-performing regions are West, Ontario, and Prairie, while the bottom-performing regions are Nunavut, Northwest, and Yukon.
- Appliance sales in Ontario are over 3 million, suggesting high demand in that region.
- The bottom 10 customers are Roy Phalen, Laurel Workman, showing negative profit.
- A delivery truck has the highest costs overall compared to the other shipping methods. This shows that shipping cost allocation is inefficient.
- There is no clear pattern between shipping method and order priority, suggesting a disconnect in how the decision is made.
- Some customers, especially from small businesses and Consumer segments, are highly profitable, while others generate low or negative profits
- The majority of the returned products are from Corporate customers, which could indicate dissatisfaction with product quality or service delivery.
  

---

### RECOMMENDATION


- I recommend that the company expand its product offerings and consider reducing its profit margins or production costs for regions with low sales.
- The company should consider giving incentives, start a loyalty program, and, if possible, personalize their service with the opportunity to provide feedback to retain their customers.
- Review the return trend and survey to understand the underlying factor responsible for these recurring issues among the Corporate clients.
- Align shipping methods with order priority- Use Express Air  for urgent orders and and Delivery truck for low-priority shipments to save costs.
- Use Express Air more for delivery since it is more cost-effective than a Delivery truck.
- Conduct a market survey to better understand the region, segments, and customers and use these insights to address and refine marketing and operations.
- The company should launch targeted marketing campaigns in the underperforming regions to increase awareness and drive sales.
- The company should consider ways to reduce its production costs to better serve its customers.
 
  ---
