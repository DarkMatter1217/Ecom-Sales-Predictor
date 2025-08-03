# Amazon Sales Data Analysis

## Overview

This project analyzes and explores a large Amazon Sales dataset, focusing on understanding sales performance, order statuses, product details, shipment statuses, and other key business insights. The analysis is performed in a Jupyter notebook using pandas, seaborn, and matplotlib for data exploration and visualization.

## Features

- **Dataset Loading \& Cleaning**:
Loads sales data (`Amazon Sale Report.csv`) with attention to potential column type mismatches and missing values.
- **Comprehensive Data Exploration**:
    - Overview of columns, missing data, and value counts.
    - Unique value counts and sample values for every column.
    - Column-wise breakdown into new user-friendly names and cleaned formats.
- **Data Transformation**:
    - Renaming columns for clarity and ease of use (e.g., `Order ID` → `order_ID`).
    - Date formatting and extraction of time features.
    - Creation of derived variables like month names, log transformations, promotion flags, and customer type flags.
- **Descriptive Statistics**:
    - Summary statistics for numerical and categorical features.
    - Distribution and frequency statistics for sales amount, quantity, cities, states, product categories, etc.
    - Detailed analysis of cancellation, fulfillment, and shipment statuses.
- **Visualization**:
    - Utilizes seaborn and matplotlib for clear, aesthetic visuals.
    - Plots to inspect sales trends, product performance, etc.
- **Prepared for Further Analytics \& Modeling**:
    - Cleaned dataframe (`df`) ready for business intelligence or further modeling tasks.


## Data Dictionary (Main Columns)

| Column | Description |
| :-- | :-- |
| order_ID | Unique order identifier |
| date | Order date (YYYY-MM-DD) |
| ship_status | Status (Shipped, Cancelled, Delivered, etc.) |
| fullfilment | Fulfillment channel (Amazon/Merchant) |
| service_level | Shipping speed (Standard/Expedited) |
| style | Product style code |
| sku | Stock Keeping Unit |
| product_category | Product category/segment |
| size | Product size |
| asin | Amazon Standard Identification Number |
| courier_ship_status | Shipment courier status |
| order_quantity | Quantity ordered |
| order_amount | Net order value (INR) |
| city | Shipping city |
| state | Shipping state |
| zip | Shipping postal code |
| promotion | Applied promotions |
| customer_type | B2B or B2C |
| month | Month of order |

_Note: There may be other columns not listed depending on further transformations in the notebook._

## Requirements

- Python 3.x
- Jupyter Notebook or compatible environment
- pandas, numpy, seaborn, matplotlib


## How to Use

1. **Clone or Download** this repository.
2. **Place the CSV file** (`Amazon Sale Report.csv`) in the same directory as the notebook.
3. **Open** `Amazon_DS.ipynb` with Jupyter Notebook.
4. **Run all cells** step by step for full data exploration and analysis.
5. Customize or extend the analysis as per your business or academic needs.

## Notable Insights from the Data

- Over 128,000+ sales records spanning across 90 days.
- Rich diversity in product categories, sizes, fulfillment channels, and cities.
- Analysis reveals trends in sales volume, value, and cancellations.
- Ready for downstream modeling or business dashboarding.


## Credits

- Data analysis and notebook by [Your Name/Team].
- Data provided via Amazon Seller Account exports.


