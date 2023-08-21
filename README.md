# Pizza Sales Dashboard

Welcome to the Pizza Sales Dashboard project! This project aims to analyze and visualize a year's worth of sales data from a fictitious pizza place. The provided dataset includes detailed information about each order, including order dates, times, pizza types, sizes, quantities, prices, and ingredients.

## Project Overview

The main goal of this project is to gain insights into the pizza sales data and create a Power BI Dashboard to visualize these insights in an interactive and meaningful way. The analysis focuses on answering key questions such as customer patterns, popular pizza choices, revenue trends, and menu optimization opportunities.

## Table of Contents

- [Data](#data)
- [Scripts](#scripts)
- [Power BI Dashboard](#power-bi-dashboard)
- [Key Insights](#key-insights)
- [Contribution](#contribution)
- [Contact](#contact)
- [License](#license)

## Data

The raw sales data is located in the `data/` directory. It includes order details, pizza types, sizes, quantities, prices, and ingredients. This data was collected over the course of a year from the fictitious pizza place.

## Scripts

In the `scripts/` directory, you can find any scripts used for data cleaning and transformation. The cleaned and transformed data were used to create the Power BI Dashboard.

```python
# Example data cleaning and transformation script
import pandas as pd

# Load raw data
raw_data = pd.read_csv('data/raw_sales_data.csv')

# Perform data cleaning and transformation
# ...

# Save cleaned data
cleaned_data.to_csv('data/cleaned_sales_data.csv', index=False)
