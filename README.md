# Food Trend Analysis – Somalia 🇸🇴

## Project Overview

This project focuses on analyzing historical food price trends in Somalia using the World Food Programme (WFP) food-price dataset. The analysis explores how food prices have changed over time and how prices differ across markets and regions.

The project uses Exploratory Data Analysis (EDA) to identify historical price patterns, regional differences, and market trends, providing insights into Somalia's food market.

## Problem Statement

How have food prices changed over time, and how do prices differ across markets and regions?

This analysis aims to help readers explore long-term food price patterns while understanding the limitations of the available data.

## Dataset

The project uses the World Food Programme (WFP) food-price dataset.

**Dataset details:**
- Total records: 26,083
- Time period: 1995–2023
- Regions: 19
- Administrative areas: 44
- Markets: 46
- Dataset file: `wfp_food_price_som.csv`

**Key fields include:**
- Date
- Region / Admin area
- Market
- Commodity
- Unit
- Currency
- Price
- USD Price

## Methodology

The analysis was conducted using Python and Pandas.

Key analytical steps included:

1. Data inspection and understanding the dataset structure.
2. Checking missing values and duplicate records.
3. Reviewing data types and identifying data-quality issues.
4. Calculating descriptive statistics.
5. Exploring market and regional price patterns.
6. Reviewing missing USD-price values and currency-related limitations.
7. Building visual summaries and KPI comparisons using Power BI.

## Key Findings

- The dataset contains 26,083 records across 19 regions, 44 administrative areas, and 46 markets.
- The original dataset contains missing USD-price values.
- Among the available USD-price values reported in the analysis, the mean is approximately $91.35 and the median is approximately $12.22.
- The difference between the mean and median indicates a strongly right-skewed distribution.
- Food price analysis requires careful interpretation of currency and price-unit context.

## Business Impact

This project provides a structured view of historical food-price data and a dashboard concept for comparing trends and markets.

As this is a portfolio analysis, no external business decision or measured financial impact is claimed.

The findings can support further investigation into food market conditions and historical price trends in Somalia.

## Tools & Technologies

- Python
- Pandas
- Excel
- Jupyter Notebook
- Power BI

## Project Files

| File | Description |
|---|---|
| `Wfp_Som_food_price.ipynb` | Data analysis notebook |
| `wfp_food_price_som.csv` | WFP food-price dataset |

## Project Gallery

The project includes dashboard visualizations presenting food-price analysis and key performance indicators.

## Author

**Abdimalik Hassan**

Data Analyst

GitHub: [AbdimalikHassan-Dataanalyst](https://github.com/AbdimalikHassan-Dataanalyst)

Portfolio: [View My Portfolio](https://abdimalikabdi.byethost24.com/projects)

---

*This project was developed for educational and portfolio purposes, focusing on understanding historical food-price trends in Somalia.*
