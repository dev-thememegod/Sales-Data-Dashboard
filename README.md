# Sales Data Dashboard - Power BI

This project is a sales data dashboard created using Power BI. It provides insights into sales performance across different regions, quarters, product categories, and more.

<h2>## Features</h2>
- Interactive Filters: Filter by region and quarter.
- KPIs: Display total sales, average sales per transaction, and sales growth percentage.
- Visualizations: Pie charts, bar charts, and line charts to visualize sales data trends.

<h2>## Setup Instructions</h2>
1. Clone the Repository:
   ```sh
   git clone https://github.com/yourusername/Sales-Data-Dashboard.git
2. Open SalesDataDashboard.pbix in Power BI Desktop.

<h2>##Data Cleaning and Preparation</h2>
The dataset used for this dashboard includes the following columns:
Order Date, Customer ID, Product Category, Product Sub Category, Region, Sales Amount, and Quantity.

<h2>##Handling Missing Values</h2>
Order Date: Replaced with a earliest. (e.g., 01/01/1900).
Customer ID: Replaced with "Unknown".
Product Category/Sub Category: Replaced with "Unspecified".
Region: Replaced with "Unspecified".
Sales Amount: Replaced with 0.
Quantity: Replaced with 0.

<h2>##DAX Functions/Measures</h2>

1. Total Sales = SUM('Sales Data'[Sales Amount])

2. Avg Sales per Transaction = [Total Sales] / COUNT('Sales Data'[Sales Amount])

<h2>##Visuals</h2>

![Main Dashboard](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash.PNG?raw=true)
![Quater 1 Filter](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash1.PNG?raw=true)
![Quater 2 Filter](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash%202.PNG?raw=true)
![Region](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash%203.PNG?raw=true)

<h2>##Technologies Used</h2>
Power BI
DAX
Excel (for data preparation)

<h2>License</h2>

This project is licensed under the MIT License - see the LICENSE.md file for details.




