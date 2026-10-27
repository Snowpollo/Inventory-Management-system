# Inventory Management & Stock Control System

## Project Overview

An Excel-based inventory management solution designed to help businesses track stock movements, monitor inventory levels, calculate stock value, and identify products that need restocking.

The project combines Excel formulas, structured tables, PivotTables, PivotCharts, conditional formatting, and a dashboard to turn inventory transactions into useful business insights.

## Business Problem

Poor inventory tracking can lead to stock shortages, excess inventory, and difficulty determining how much capital is tied up in products. This project provides a structured way to monitor stock levels and support restocking decisions.

## Tools & Skills

- Microsoft Excel
- Excel Tables and structured references
- XLOOKUP
- SUMIFS
- IF and COUNTIF
- PivotTables and PivotCharts
- Conditional formatting
- Inventory data analysis
- Dashboard design and KPI reporting

## Workbook Structure

### 1. Products
Stores product information, including product IDs, names, categories, supplier IDs, unit costs, and reorder levels.

### 2. StockMovements
Records purchases, sales, and stock adjustments, including transaction dates, product IDs, movement types, and quantities.

### 3. InventorySummary
Calculates stock on hand, inventory value, and stock status for each product. Products are classified as In Stock, Reorder, or Out of Stock.

### 4. Dashboard
Summarizes inventory performance using KPI cards, charts, and a reorder alert table.

## Key Metrics

The workbook was tested after recording an additional sale of five Wireless Mouse units.

| Metric | Result |
|---|---:|
| Total Products | 12 |
| Total Units in Stock | 158 |
| Total Inventory Value | ₦3,562,500 |
| Products to Reorder | 5 |
| Out-of-Stock Products | 0 |
| Products In Stock | 7 |

*These results reflect the workbook at the time of testing and will change as inventory transactions are added.*

## Dashboard Visualizations

- **Inventory Value by Category:** Compares the value of inventory across product categories.
- **Stock on Hand by Product:** Compares available stock quantities across products.
- **Reorder Alert Table:** Identifies products whose current stock has reached or fallen below their configured reorder thresholds.

## Key Insights

- Five products are currently flagged for reordering.
- No products are classified as Out of Stock.
- Inventory value can be compared across categories to understand where inventory capital is concentrated.
- Recording a new sale updates the relevant stock calculations and dashboard KPIs.
- PivotCharts can be refreshed to reflect updated inventory data.

## Testing & Validation

The workbook was tested by adding a sale of five Wireless Mouse units.

The test confirmed that:
- Wireless Mouse stock decreased from 28 to 23 units.
- Total stock decreased from 163 to 158 units.
- Inventory value decreased from ₦3,605,000 to ₦3,562,500.
- Dashboard KPIs reflected the updated figures.
- PivotCharts displayed updated information after being refreshed.

## Project Outcome

This project demonstrates how Excel can be used to build a practical inventory monitoring and reporting solution. It showcases skills in data organization, lookup formulas, conditional aggregation, stock monitoring, inventory valuation, and dashboard reporting.

## Author

**Excel Specialist Portfolio Project**

Built with Microsoft Excel.

