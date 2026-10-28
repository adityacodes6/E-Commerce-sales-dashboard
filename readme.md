# Indian E-Commerce Sales Analysis Dashboard

## Project Overview
This project analyzes Indian e-commerce sales data using **Microsoft Power BI** to understand sales performance, profitability, customer order patterns, and payment preferences.

The interactive dashboard presents key business metrics and visual insights to help identify profitable product categories, popular payment methods, and sub-categories that may require attention.

## Tools & Technologies
- **Microsoft Power BI** – Dashboard development and data visualization
- **Power Query** – Data preparation and transformation
- **DAX** – Calculated measures and KPIs
- **CSV** – Dataset format

## Dataset
The project uses three CSV files from the Indian e-commerce sales dataset:

- `List of Orders.csv` – Order dates, customer names, cities, and states
- `Order Details.csv` – Sales amounts, profits, quantities, categories, sub-categories, and payment modes
- `Sales target.csv` – Sales targets by category and month

**Dataset source:** [E-Commerce Sales Analysis – GitHub](https://github.com/snehagahlot3/ecommerce-sales-analysis)

## Dashboard KPIs

| Metric | Value |
|---|---:|
| Total Sales | 438K |
| Total Profit | 37K |
| Total Orders | 500 |
| Total Quantity Sold | 5,615 |

*Values reflect the current dashboard and may be rounded for display.*

## Key Dashboard Visualizations
- **Profit by Sub-Category:** Compares profitability across product sub-categories.
- **Sales by Payment Mode:** Shows the distribution of sales across payment methods.
- **Sales by Category:** Compares sales performance across product categories.
- **State Filter:** Allows users to explore sales performance for selected states.
- **KPI Cards:** Summarize overall sales, profit, orders, and quantity sold.

## Key Insights
1. **Electronics leads category sales** among the categories displayed in the dashboard.
2. **Cash on Delivery (COD)** contributes approximately 35.45% of sales by payment mode.
3. **Printers is a leading sub-category in profit**, based on the current visualization.
4. **Some sub-categories show negative profit**, highlighting areas that may need further investigation.
5. The dashboard's state filter enables users to explore regional performance and compare results across locations.

## Business Recommendations
- Investigate loss-making sub-categories to understand their costs, pricing, and discount patterns.
- Review the performance of high-profit sub-categories to identify opportunities for growth.
- Analyze payment preferences to better understand customer purchasing behavior.
- Compare state-level results to identify stronger markets and areas for improvement.

## Project Workflow
1. Imported the CSV files into Power BI Desktop.
2. Reviewed the available fields and data structure.
3. Created relationships between relevant tables using the Order ID field.
4. Created DAX measures for total sales, total profit, total orders, and total quantity.
5. Built KPI cards, bar charts, a payment-mode chart, and a state slicer.
6. Formatted the report into an interactive dashboard.

## How to View the Project
1. Download or clone this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. Refresh the data if prompted, ensuring the CSV file paths are correct.
4. Use the state filter and visuals to explore the dashboard.

**Live Dashboard:** Add your Power BI Service or Publish to web link here, if available.

## Author
**Aditya Mungekar**  
Final-Year B.Sc. Data Science Student  
Mumbai, India

- GitHub: [adityacodes6](https://github.com/adityacodes6)
- Portfolio: [Personal Portfolio](https://personal-portfolio-ashen-beta-90.vercel.app/)

---

*This project was created for learning and portfolio development, with a focus on practical business analysis and data visualization using Power BI.*