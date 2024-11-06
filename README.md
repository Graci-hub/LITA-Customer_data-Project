# Overview
### This report analyzes customer data from a subscription service to identify different customer segments, assess engagement levels, and understand revenue contributions. The report provides steps for data preparation and analysis using Excel for data cleaning, SQL for data segmentation and metrics calculation, and Power BI for visualizing insights.
### Tools Used
- Excel: Used for initial Data cleaning, preparation, and formula-based calculations.
- SQL ( Structured Query Language): Used for Querying and grouping data to analyze metrics by customer segments.
- Power BI: Used for Creating dashboards and charts for a visual representation of key insights.
### Key Metrics
- Subscription Duration: Number of days a subscription lasted.
- Churn Rate: Percentage of Customers who canceled their subscriptions.
- Customer Segments: Based on Subscription type, churn status, and engagemet level.
- Revenue Contribution: Total revenue generated by each customer.
- Average Subscription Duration: Average duration a customer stays subscribed.
## Dataset and structures
The dataset include the following columns:
- Customer ID: This is the unique identifier for each customer
- Customer Name: Name of the customer
- Subscription Type: Type of subscription chosen by the customer (e.g., Basic, Standard, Premium).
- Subscripton Start: Date the subscription started.
- Subscription End: Date the subscription ended.
- Canceled: Indicator of whether the subscription was canceled (True/ False)
- Revenue: Total revenue generated from the customer’s subscription.
- Duration: Duration of the subscription (calculated as days or months between Subscription Start and Subscription End).
## Data Preparation and Cleaning (EXCEL)
- Removing Duplicates: I ensured that there's no duplicate records by filtering out duplicate Customer ID entries.
- Adding calculated Columns:
  1. Duration: Calculated as the difference between Subscription Start and Subscription End.
- Formulas and Functions: During the analysis, Excel’s powerful functions were used extensively to calculate key sales metrics and derive actionable insights from the data. By leveraging these formulas, I was able to perform complex calculations quickly and efficiently. Some of the functions used are: COUNT(), COUNTIF(), AVERAGEIF(), etc
## SQL(Structured Query Language): Data Querying
### Metrics to Track
- Total Number of Customers from each Region
- Most popular subscription type by number of customers
- Customers who canceled their subscripton within 6 months
- Average subscription Duration for all customers
- Customers with subscriptions longer than 12 months
- Total Revenue by Subscription type
- Top 3 Regions Subscription Cancellations
- Total Number of Active and Canceled Subscription
## Queries: 
Below are some of the Metrics that were Queried
- Average Subscription Duration for all customers: Average duration highlights how long customers typically stay subscribed, which can indicate customer satisfaction and value.
  [Average subscription.txt](https://github.com/user-attachments/files/17649176/Average.subscription.txt)

- Total Revenue by Subscription: Calculating each customer’s revenue provides insight into high-value customers.
  [Total revenue by subscription.txt](https://github.com/user-attachments/files/17649254/Total.revenue.by.subscription.txt)
  
- Top 3 Regions by Subscription cancellations
[top 3 region.txt](https://github.com/user-attachments/files/17649274/top.3.region.txt)

 - Total number of Active and Canceled Subscription
   [active and canceled.txt](https://github.com/user-attachments/files/17649307/active.and.canceled.txt)

- Most popular subscription by number of Customers
 [most popular.txt](https://github.com/user-attachments/files/17649328/most.popular.txt)

## Query Attachment from SQL Server
- [SQLQuery3.txt](https://github.com/user-attachments/files/17648172/SQLQuery3.txt)

## POWER BI (Visualization)







