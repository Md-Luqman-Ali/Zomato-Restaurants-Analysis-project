# Zomato Restaurant Analytics | SQL, Power BI, Tableau & Excel

An end-to-end restaurant analytics project exploring restaurant distribution, opening trends, customer ratings, pricing, cuisines and service availability using multiple data tools.

## Project Overview

This project brings together SQL-based data analysis and dashboard development. It includes work with MySQL, Power BI, Tableau and Microsoft Excel to explore restaurant-related data and organize business questions into analytical views.

## Business Objectives

- Analyze restaurant counts by city and country.
- Explore restaurant opening trends by year, quarter and month.
- Group restaurants by average rating.
- Analyze restaurant price-range categories.
- Examine table-booking and online-delivery availability.
- Explore cuisines, cities and restaurant performance.
- Build calendar and country lookup dimensions.

## Tools and Technologies

| Area | Tools |
|---|---|
| Database and querying | MySQL |
| Business intelligence | Power BI |
| Data visualization | Tableau |
| Spreadsheet analysis | Microsoft Excel |
| Data preparation | SQL transformations |

## Repository Contents

The project assets are stored in `Zomato-Restaurants-Analysis-project/`.

- `SQL scripts .sql` — date transformations, grouping, joins, rating and price analysis, and cuisine extraction.
- `data dump.sql` — SQL data dump.
- `Zomato Objectives.txt` — original analytical objectives.
- `zomato data.xlsx` — source workbook.
- `zomato reataurants analysis in Excel.xlsx` — Excel analysis workbook.
- `Zomato restaurants analysis dashboard in Power BI.pbix` — Power BI dashboard.
- `Zomato Restaurants analysis Tableau.twbx` — Tableau workbook.
- `Screenshot 2025-09-15 182302.png` — dashboard screenshot.

## Analytical Workflow

1. Review the source data and business questions.
2. Prepare date fields and derive calendar attributes.
3. Use SQL joins and aggregations to explore restaurant distribution.
4. Group records by rating and price categories.
5. Examine service attributes such as online delivery and table booking.
6. Develop dashboard views using Power BI, Tableau and Excel.

## SQL Concepts Demonstrated

- `SELECT`, `UPDATE`, `ALTER TABLE`
- Date and calendar transformations
- `CASE` expressions
- `INNER JOIN`
- `GROUP BY` and aggregate functions
- String extraction using `SUBSTRING_INDEX`
- Ranking and filtering with `ORDER BY` and `LIMIT`

## Dashboard Preview

![Zomato project screenshot](Zomato-Restaurants-Analysis-project/Screenshot%202025-09-15%20182302.png)

## Validation Notes

The SQL scripts are part of the original project and should be reviewed before being treated as production-ready. Some financial-month mapping and percentage calculations require correction and validation. Results should be recomputed against the source data before publishing numerical business conclusions.

## Future Improvements

- Add a documented, reproducible data-cleaning workflow.
- Validate KPI formulas and financial-calendar logic.
- Add a data dictionary and dashboard navigation guide.
- Document key findings with verified values.
- Add screenshots for the Power BI, Tableau and Excel views.

## Author

**Md Luqman Ali**

[GitHub](https://github.com/Md-Luqman-Ali) · [LinkedIn](https://www.linkedin.com/in/mdluqmanali/) · [YouTube](https://youtube.com/@thecodingkaro)
