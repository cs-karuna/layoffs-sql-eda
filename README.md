# Layoffs SQL EDA

This repository contains my SQL-based Exploratory Data Analysis (EDA) on a dataset of global company layoffs. The goal was to uncover trends such as:

- Top companies and industries with the highest layoffs
- Percentage-based layoffs over time
- Year-wise and stage-wise analysis
- Rolling monthly trends using window functions

## Tools Used
- MySQL
- SQL Workbench / DBeaver
- Power BI (optional)

## Dataset
Layoffs data sourced from [source] (if public).

## Features
- Use of GROUP BY, ORDER BY, WINDOW functions (DENSE_RANK, SUM OVER)
- Time-series analysis using substring on date
- Company and yearly ranking logic

## How to Use
- Open the `eda_queries.sql` file in any SQL editor.
- Run queries step by step to explore the data.
