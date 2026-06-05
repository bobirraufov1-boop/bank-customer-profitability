# Bank Customer Profitability Analysis

A full end-to-end data analytics project built on a 30-table banking database.

## Methods
- SQL Server — database design & KPI queries
- Python (Faker, pyodbc) — synthetic data generation (1,000 customers, 5,000+ transactions)
- Power BI — dashboard with DAX measures

## Key Findings
- Top 30% of customers generate ~70% of total profit
- Namangan branch outperforms Tashkent despite being a smaller city
- Savings accounts drive the highest revenue across all account types
- High-value customers are 103x more profitable than low-value customers

## Files
- `Bank.sql` — database schema + KPI queries
- `Bank_data_generation.ipynb` — Python data generation script
- `Bank_Visuals.pdf` — Power BI dashboard export

## KPI Queries
1. Customer Profitability Score — ranks all customers by estimated profit
2. Pareto Analysis — proves top 20% generate 70% of profit
3. Profit by Branch — identifies best and worst performing branches
4. Customer Segment Analysis — compares High/Medium/Low value segments
