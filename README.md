** Sales Performance Dashboard – Power BI Project**

What the Report is About

This Power BI report analyzes sales performance across different regions, customers, and product lines. 

The dashboard provides insights into:

Sales trends over time

Product performance

Country- and city-wise sales

Profitability (Sales vs. Cost)

Regional performance based on office locations

It helps business users make decisions related to sales strategy, marketing, and customer engagement.

Data Source Details

The data used in this report includes the following fields:
| Column Name        | Description                                 |
| ------------------ | ------------------------------------------- |
| `orderdate`        | Date when the order was placed              |
| `ordernumber`      | Unique identifier for the order             |
| `productName`      | Name of the product sold                    |
| `productLine`      | Category the product belongs to             |
| `customerName`     | Name of the customer                        |
| `customer_city`    | City of the customer                        |
| `customer_country` | Country of the customer                     |
| `office_city`      | Location of the office handling the order   |
| `office_country`   | Country where the office is located         |
| `buyPrice`         | Purchase price of the product               |
| `priceEach`        | Selling price per unit                      |
| `QuantityOrdered`  | Number of units sold                        |
| `sales_value`      | Total sales value (priceEach × quantity)    |
| `cost_of_sales`    | Total cost for the order                    |
| `office_grouped`   | Grouped office regions (e.g., Asia, Europe) |
