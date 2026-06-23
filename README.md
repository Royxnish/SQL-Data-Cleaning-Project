# Layoffs Data Cleaning and Exploratory Data Analysis using SQL

## Overview

This project focuses on cleaning and analyzing a real-world layoffs dataset using MySQL. The objective was to improve data quality through preprocessing techniques and perform exploratory data analysis (EDA) to identify meaningful trends across companies, industries, countries, and time periods.

The project demonstrates practical SQL skills including data cleaning, data transformation, aggregation, window functions, Common Table Expressions (CTEs), and trend analysis.

---

## Objectives

* Remove duplicate records
* Handle missing and inconsistent values
* Standardize text and date formats
* Improve overall data quality
* Perform exploratory data analysis on the cleaned dataset
* Generate business insights from layoffs data

---

## Technologies Used

* SQL
* MySQL
* MySQL Workbench
* Git & GitHub

---

## Dataset

The dataset contains records of company layoffs across multiple industries and countries.

### Key Attributes

* Company
* Industry
* Location
* Country
* Total Laid Off
* Percentage Laid Off
* Date
* Stage
* Funds Raised (Millions)

---

## Data Cleaning Process

The following data cleaning operations were performed:

* Removed duplicate records using window functions
* Standardized company and industry names
* Trimmed unnecessary whitespace
* Converted date values into a consistent format
* Handled NULL and missing values
* Validated and corrected inconsistent records

---

## Exploratory Data Analysis

The cleaned dataset was analyzed to identify patterns and trends.

### Analysis Performed

* Companies with the highest layoffs
* Countries with the highest layoffs
* Industry-wise layoffs
* Stage-wise layoffs
* Year-wise layoffs
* Monthly layoffs trends
* Companies with complete workforce reductions (100% layoffs)
* Rolling cumulative layoffs over time

### SQL Concepts Applied

* Aggregate Functions
* GROUP BY
* ORDER BY
* Window Functions
* DENSE_RANK()
* Common Table Expressions (CTEs)
* Date Functions
* String Functions

---

## Project Workflow

1. Imported the raw layoffs dataset into MySQL.
2. Created staging tables for cleaning operations.
3. Removed duplicate records.
4. Standardized text and date formats.
5. Handled missing and inconsistent values.
6. Performed exploratory data analysis.
7. Generated business insights from the cleaned dataset.

---

## Key Findings

* Several technology companies recorded significant workforce reductions.
* Layoffs were concentrated during specific periods across multiple industries.
* Certain countries experienced substantially higher layoffs than others.
* Multiple startups reported complete workforce reductions despite having raised significant funding.
* Layoff activity varied considerably across funding stages and industries.

---

## How to Run

1. Import the dataset into MySQL.
2. Execute the data cleaning SQL script.
3. Run the exploratory data analysis queries.
4. Review the outputs and insights generated from the cleaned dataset.

---

## Future Enhancements

* Build interactive dashboards using Power BI or Tableau.
* Automate data cleaning workflows using stored procedures.
* Integrate Python for advanced analytics and visualization.
* Perform predictive analysis on layoff trends.

---

## Repository Structure

```text
layoffs.csv
Portfolio Project - Data Cleaning.sql
Portfolio Project - EDA.sql
README.md
```
