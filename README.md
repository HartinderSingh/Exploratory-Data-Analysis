# 📊 Exploratiry Data Analytics Project

This project demonstrates SQL-based analysis over  data , focusing on business insights such as customer trends, sales performance, and segmentation. It is designed as a complete **Business Analyst portfolio project** using **T-SQL** and **SQL Server**.

---

## 🏗️ Project Structure

All analysis scripts are organized step-by-step to reflect a real-world data analytics workflow.

| #  | File Name                            | Description |
|----|--------------------------------------|-------------|
| 01 | `01_database_exploration.sql`        | Lists databases, schemas, tables, and column metadata. |
| 02 | `02_dimensions_exploration.sql`      | Explores dimension tables like customers, products, etc. |
| 03 | `03_date_range_exploration.sql`      | Finds min/max dates and timeline coverage. |
| 04 | `04_measures_exploration.sql`        | Understands key KPIs like sales, quantity, discounts. |
| 05 | `05_magnitude_analysis.sql`          | Identifies top sales by customer/product/category. |
| 06 | `06_ranking_analysis.sql`            | Ranks customers/products based on performance. |
| 07 | `07_change_over_time_analysis.sql`   | Tracks sales change over months/years. |
| 08 | `08_cumulative_analysis.sql`         | Adds running totals (e.g. cumulative sales). |
| 09 | `09_performance_analysis.sql`        | Monthly performance evaluation of business metrics. |
| 10 | `10_data_segmentation.sql`           | Segments data by region, category, or other fields. |
| 11 | `11_part_to_whole_analysis.sql`      | Calculates contribution percentage by group. |
| 12 | `12_report_customers.sql`            | Final report on customer-level KPIs. |
| 13 | `13_report_products.sql`             | Final report on product-level KPIs. |

---

## 🗄️ Backup File

- `DataWarehouseAnalytics.bak`: SQL Server database backup file (RESTORE in SSMS to use).

---

## 💡 Features

- Written in **T-SQL** (SQL Server)
- Clean and modular scripts
- Window functions (e.g. `ROW_NUMBER`, `RANK`, `SUM OVER`)
- Advanced use of `GROUP BY`, `DATEPART`, `DATETRUNC`, and `CASE`
---

## 🛠️ How to Use

1. **Restore** the `.bak` file in SQL Server.
2. Run scripts in order to explore and analyze the dataset.
3. Modify queries for specific KPIs or dashboards.
4. Optionally, connect Power BI to the database for visual analytics.


## 👤 Author

**Hartinder Singh**  


---

## 📝 License

This project is for educational use only.
