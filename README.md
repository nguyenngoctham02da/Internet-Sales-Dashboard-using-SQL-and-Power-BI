# Internet-Sales-Dashboard-using-SQL-and-Power-BI

In this project, I have to build a dashboard to meet the demand from the sales manager. The outline of the project as below:
1. Business requirements

Assume that this is an email from a sales manager:

 _ I hope you are doing well. We need to improve our internet sales reports and want to move from static reports to visual dashboards.
Essentially, we want to focus on how much we have sold of what products, to which clients and how it has been over time.
Seeing as each sales person works on different products and customers it would be beneficial to be able to filter them also.
We measure our numbers against budget so I added that in a spreadsheet so we can compare our value against performance.
The budget is for 2021 and we usually look 2 years back in time when we do analysis of sales._

Then I create a user story as below:
  - Sales managers want to get a DASHBOARD OVERVIEW OF INTERNET SALES can follow better which CUSTOMERS AND PRODUCTS SELL THE BEST. They need a power bi dashboard which UPDATES DATA ONCE A DAY.

  - Sales representatives a detailed OVERVIEW OF INTERNET SALES PER CUSTOMERS can follow up my CUSTOMERS THAT BUY THE MOST and who we can sell to. They need a power bi dashboard which allows me to FILTER DATA FOR EACH CUSTOMER.

  - Sales representatives a detailed OVERVIEW OF INTERNET SALES PER PRODUCT can follow up my PRODUCT THAT BUY THE MOST and who we can sell to. They need a power bi dashboard which allows me to fILTER DATA FOR EACH PRODUCT.

  - Sales manager a dashboard overview of internet sales follow SALES OVER TIME AGAINST BUDGET. They need a power bi dashboard with graphs and KPIS COMPARING against the budget.
    
2. Data description

This is a dataset from Microsoft which is about Internet Sales. It includes dimension and fact tables about sales, customers, products and transactions from 2019 to 2021.

It can be downloaded from: https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms  

3. Data cleaning and extraction using SQL

I use SQL to extract some necessary tables and columns from the data warehouse. You can see the way I extract data from the data warehouse in the .sql script. 

4. Building a dashboard using Power BI

I use Power BI to build a dynamic dashboard about sales overview, customers and product. You can download .pbix and see the dynamic visual dashboard.


