# Global Superstore Analysis

### Table of Content
- [Introduction](#introduction)
- [Problem statement](#problem-statement)
- [Skills Demonstrated](#skills-dmonstrated)
- [Data Source](#data-source)
- [Tool](#tool)
- [Data Transformation](#data-transformation)
- [Results and Findings](#Results-and-Findings)

### Introduction

This data analysis provides an insight into Global Superstore sales.  Global Superstore is a global online retailer based in New York, boasting a broad product catalog and aiming to be a one-stop-shop for its customers. Global The superstore’s clientele, hailing from 147
different countries, can browse through an endless offering with more than 10,000 products. This large selection comprises three main categories: office supplies (e.g., staples), furniture (e.g., chairs), and
technology (e.g., smartphones).

![global project dashbord](https://github.com/user-attachments/assets/519f2108-873d-4ba2-98e7-f426c6be89f8)


### Problem Statement
1. a) What are the three countries that generated the highest total profit for Global Superstore in 2014?
b) For each of these three countries, find the three products with the highest total profit. Specifically,
what are the products’ names and the total profit for each product?

2. a) Identify the 3 subcategories with the highest average shipping cost in the United States.
   
3. a) Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African
countries?
b) What factors might be responsible for Nigeria’s poor performance?
 
 4. a) Identify the product subcategory that is the least profitable in Southeast Asia.
b) Is there a specific country in Southeast Asia where Global Superstore should stop offering the
subcategory identified in 

5. a) Which city is the least profitable (in terms of average profit) in the United States?
    b) Why is this city’s average profit so low?

7. a) Which product subcategory has the highest average profit in Australia?

7.a)Who are the most valuable customers and what do they purchase?
   
### Skills Demonstrated

- Data transformation
- Data cleaning
- Visualization
- Filters
  
- ### Data Source

The dataset used for this analysis was provided by the training institution i am training with, **Digitaley Drive**. 
The data contained 3 tables which are;
- Orders
- People
- Returns

### Tool

PowerBI 

This tool was used for the data cleaning, analysis and the creation of the dashboard.

### Data Transformation
 - I downloaded the CSV files and imported them separately into Power Query Editor.
 - The column Postal_code in the orders table contained 80% empty cells and i went ahead to replace them with 0 using the 'replace value option on Power BI
 - In the People table I chaneged the hearder in both columns using First Row as Hearder
 - The columns also contained 99% empty rows using the remove rows option, i filterd rows to remove all  blank rows reducing the rows to 13
 - I removed dupicate order_id in Returns table reducing the row from 1172 to 1173


### Results and Findings
1. 3 countries that generated the highest total profit  in 2014 and the product names of these countries highest total profit products are:
 (a) United States - Canon Image       $25,199.93,  Cisco Smart Phone $7,753.04  motorola smartphone $6983.88
 (b)China - Sharp wireless fax digital $2,894.10, HP copy machine $2,855.13, Samsung smart phone volp $2,672.10
 (c) India - Sauder Classic bookcase traditional $2,903.58 , Apple smart phone with caller ID $2,817.99, Cisco smart phone with caller ID $1,609.38

2. subcategories with the highest average shipping cost in the United States are copiers, machines and tables

3. Nigeria had a total loss of ($-23,219) in 2014 making them the least profitable country in Africa. The high shipping cost and average discount can be seen as  a major factor responsible for  this.

4. Product subcategory that is the least profitable in Southeast Asia is Tables and Global Store should stop offering this sub category in the country Indonesia because it has the lowest sales .

5. City with  the least profit (in terms of average profit) in the United States  is Lancaster 

6. Product subcategory has the highest average profit in Australia is Appliances

7. Most valuable customers and what they purchase are Bill Eplett, Eric Murdock,  Steven  Ward,
They purchase Avery 3-Hole Punch, Bnney&Smith Markers,Water Color
