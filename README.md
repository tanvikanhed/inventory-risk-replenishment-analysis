# Inventory Risk & Replenishment Prioritization Analysis

## Project Overview
This project analyzes retail inventory and sales data to identify store–product combinations with potentially low inventory coverage. It uses Python-based data analysis and rule-based prioritization to support inventory review and replenishment decisions.

## Objectives
- Analyze retail inventory, sales, and demand forecast data.
- Estimate inventory coverage using historical average sales.
- Classify store–product combinations into high, medium, and low review priorities.
- Compare average actual sales with average demand forecasts.
- Provide actionable recommendations for inventory monitoring.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Methodology
1. Loaded and inspected the dataset.
2. Checked missing values, duplicate records, and data types.
3. Calculated average sales for each store–product combination.
4. Estimated inventory coverage in days.
5. Applied illustrative rule-based priority thresholds:
   - High: less than 3 days of estimated coverage
   - Medium: 3 to less than 7 days
   - Low: 7 days or more
6. Compared average actual sales with average demand forecasts.
7. Exported a prioritized review list and project report.

## Key Deliverables
- `Inventory_Risk_Analysis.ipynb` — analysis code and visualizations
- `replenishment_priority_list.csv` — prioritized store–product review list
- `Inventory_Risk_Project_Report.txt` — project summary and recommendations
- `retail_store_inventory.csv` — input dataset

## Business Recommendations
- Review combinations with low estimated inventory coverage first.
- Consider supplier lead times and recent sales before placing orders.
- Monitor inventory levels and demand changes regularly.
- Investigate large differences between actual sales and demand forecasts.

## Limitations
- The dataset is synthetic and does not represent a real retailer.
- Priority thresholds are illustrative assumptions, not universal business rules.
- Inventory coverage is based on historical averages and does not guarantee stockout predictions.
- Forecast gaps are descriptive comparisons, not formal forecast-accuracy measurements.

## Data Source
Retail Store Inventory Forecasting Dataset, sourced from Kaggle. Please refer to the original dataset page and its license before redistributing the data.

## Disclaimer
This is an educational data analytics project demonstrating data cleaning, exploratory analysis, KPI calculation, visualization, and rule-based inventory prioritization.
