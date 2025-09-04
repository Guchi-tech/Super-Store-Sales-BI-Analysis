### Executive_Summary.md

# Executive Summary – Super Store Sales BI Analysis

## Table of Contents
1. [Introduction](#introduction)
    - [Background](#background)
    - [Data Source](#data-source)
    - [Data Description](#data-description)
2. [BI Solution Overview](#bi-solution-overview)
    - [KPI Requirements](#kpi-requirements)
    - [Methodology](#methodology)
3. [Key Findings](#key-findings)
    - [Marketing Analysis](#marketing-analysis)
    - [Product Analysis](#product-analysis)
    - [Geographical Analysis](#geographical-analysis)
    - [Budget Analysis](#budget-analysis)
    - [Profit Analysis](#profit-analysis)
    - [Sales Analysis](#sales-analysis)
4. [Limitations and Recommendations](#limitations-and-recommendations)

---

## Introduction

### Background
In today’s competitive environment, data-driven decision-making is essential. Business Intelligence (BI) tools help organizations uncover insights from data, enabling strategies that improve efficiency and growth. This project uses the US Superstore dataset to analyze sales performance, profit drivers, and market dynamics through interactive Power BI dashboards.

### Data Source
- Dataset: [US Store Sales (Kaggle)](https://www.kaggle.com/datasets/dsfelix/us-stores-sales)
- Period: January 2010 – January 2011
- Size: 4,249 rows, 20 columns

### Data Description
Key columns include:
- **State**: Location of transactions
- **Profit & Margin**: Profitability measures
- **Sales & COGS**: Sales amount and cost of goods
- **Marketing**: Marketing expenditure
- **Product & Product Type**: Product details
- **Date**: Transaction date

---

## BI Solution Overview

### KPI Requirements
The dashboards were designed to answer business questions such as:
- ROI by state and product
- Best-selling products
- Sales performance across locations
- Budget vs Actual performance
- Profitability trends
- Sales trends over time

### Methodology
1. **Data Sourcing** – Collected dataset from Kaggle
2. **Data Cleaning & Transformation** – Ensured data quality and consistency
3. **Data Modeling** – Created a star schema for efficient analysis
4. **Dashboard Development** – Built interactive Power BI dashboards with slicers and visuals

---

## Key Findings

### Marketing Analysis
- ROI for the period: **5.13**, indicating strong profitability
- Illinois had the highest ROI despite New York having the highest marketing spend
- States with losses: Missouri, New Mexico, Nevada

### Product Analysis
- Best-selling product: **Columbian Coffee**, Sales = **$117K**
- Lowest-selling product: **Regular Espresso**
- Tea sub-category achieved the highest ROI

### Geographical Analysis
- California and Utah had the highest customer retention (92.31%)
- Massachusetts had the lowest retention (46.51%)
- Top performing states: California, New York, Illinois
- Least performing: New Mexico

### Budget Analysis
- Significant variances between actual and budgeted sales across locations
- Some days exceeded budgeted cumulative sales; others underperformed

### Profit Analysis
- Tea sub-category delivered the highest ROI
- Espresso was the weakest-performing category
- Profit margins varied significantly across states

### Sales Analysis
- Highest daily sales: **Jan 1, 2011**
- Lowest daily sales: **Jan 11, 2010**
- Small markets contributed more to total revenue than expected

---

## Limitations and Recommendations

### Limitations
- Data limited to January 2010 and January 2011 only
- Some data inconsistencies required cleaning

### Recommendations
- Improve marketing in underperforming states
- Expand operations in top states like California and New York
- Promote best-selling products like Columbian Coffee
- Increase tea product count to boost ROI
- Replicate successful strategies from top-performing markets

---

---