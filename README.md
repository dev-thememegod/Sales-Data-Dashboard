# Sales Data Dashboard - Power BI

This project is a sales data dashboard created using Power BI. It provides insights into sales performance across different regions, quarters, product categories, and more.

## Features
- Interactive Filters: Filter by region and quarter.
- KPIs: Display total sales, average sales per transaction, and sales growth percentage.
- Visualizations: Pie charts, bar charts, and line charts to visualize sales data trends.

## Setup Instructions
1. Clone the Repository:
   ```sh
   git clone https://github.com/yourusername/Sales-Data-Dashboard.git
2. Open SalesDataDashboard.pbix in Power BI Desktop.

##Data Cleaning and Preparation
The dataset used for this dashboard includes the following columns:
Order Date, Customer ID, Product Category, Product Sub Category, Region, Sales Amount, and Quantity.

##Handling Missing Values:
Order Date: Replaced with a earliest. (e.g., 01/01/1900).
Customer ID: Replaced with "Unknown".
Product Category/Sub Category: Replaced with "Unspecified".
Region: Replaced with "Unspecified".
Sales Amount: Replaced with 0.
Quantity: Replaced with 0.

##DAX Functions/Measures

Total Sales = SUM('Sales Data'[Sales Amount])

Avg Sales per Transaction = [Total Sales] / COUNT('Sales Data'[Sales Amount])

##Visuals

![Main Dashboard](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash.PNG?raw=true)
![Quater 1 Filter](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash1.PNG?raw=true)
![Quater 2 Filter](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash%202.PNG?raw=true)
![Region](https://github.com/dev-thememegod/Sales-Data-Dashboard/blob/main/dash%203.PNG?raw=true)

##Technologies Used
Power BI
DAX
Excel (for data preparation)

<h2>License</h2>

This project is licensed under the MIT License - see the LICENSE.md file for details.




