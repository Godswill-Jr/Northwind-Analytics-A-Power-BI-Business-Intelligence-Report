# Power-BI-Capstsone-Project
This project was completed as part of my Power BI Capstone with The Data Immersed (TDI). The goal was to analyze Northwind Traders’ sales data and transform it into actionable business insights through a series of interactive dashboards.


### Data Sources
The dataset used for this analysis was provided as part of the Northwind Traders sample database.
It contains seven (7) related tables used to build the data model:

Table Name	Description
Categories	Contains information about product categories.
Customers	Stores details about customer names, contact information, and locations.
Employees	Lists sales representatives and staff data.
Order_Details	Contains transactional data — product quantity, unit price, and discounts.
Orders	Records each order with order dates, shipped dates, and customer IDs.
Products	Provides product-level details including product name, category, and pricing.
Shippers	Contains information on shipping companies and delivery services.

These tables were connected through primary and foreign key relationships to create a Star Schema Model in Power BI.

### Tools Used
- **Microsoft Power BI** -  Data modeling, visualization, and reporting [Download Here](https://www.microsoft.com/en-us/download/details.aspx?id=58494) 
- **DAX (Data Analysis Expressions)** – Custom measures and KPIs  

### Objectives
- Analyze company performance using key metrics (Revenue, Units Sold, and Profit).  
- Identify high-performing products, customers, and employees.  
- Assess operational efficiency by evaluating shipping time and methods.  
- Provide insights that support data-driven business decisions.

## Dashboard
### 1. Sales Overview Dashboard
- **Revenue:** $1.35M  
- **Units Sold:** 51K  
- **Estimated Profit:** $406K  
- **Insights:**  
  - Monthly revenue trends show consistent growth after mid-year.  
  - Top-performing employee: *Margaret Peacock* ($250K in revenue).  
  - Average shipping time: *8.49 days*, with *United Package* as the most used shipper.
 
  ### 2. Customer & Operations Insights Dashboard
- **Top Categories:** Beverages, Dairy Products, and Meat & Poultry.  
- **Key Customers:** Horst Kloss, Jose Pavarotti, and Roland Mendel.  
- **Shipper Contribution:** United Package handled **42% of total shipments**.

  ## Key Insights
- Revenue and profit grew by over **50% YoY**, showing strong business performance.  
- Employee and product-level breakdowns revealed strategic areas for focus and incentives.  
- Operational efficiency can improve by optimizing shipper allocation for high-demand regions.


## Skills Demonstrated
- Data Modeling (Star Schema Design)  
- DAX Calculations (Revenue, Profit, YOY Growth etc.)  
- Power BI Visualization and Report Design  
- Time Intelligence (Monthly and Yearly Trend Analysis)  
- Data Storytelling and Dashboard Design

## Limitations  
While the analysis provided valuable insights, it’s important to note that the dataset only includes transactions starting from **July 2013**.  
As a result, comparisons and trend analyses before this date could not be performed, which slightly limits the ability to evaluate long-term historical performance.









