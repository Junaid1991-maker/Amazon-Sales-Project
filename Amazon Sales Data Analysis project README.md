# Amazon Sales Data Analysis Project

## Overview
This project analyzes Amazon sales transaction data to uncover business insights, optimize operations, and improve customer segmentation. The analysis covers sales trends, geographic performance, product popularity, fulfillment efficiency, and promotional effectiveness.

## Key Features
- **Comprehensive EDA**: Clean and explore order data with visualizations
- **RFM Analysis**: Customer segmentation by Recency, Frequency, Monetary value
- **Geographic Insights**: Identify top-performing states and cities
- **Promotion Impact**: Measure discount effectiveness on order volume and AOV
- **Operational Metrics**: Analyze cancellation rates and fulfillment methods

## Dataset
The `Amazon Sale Report.csv` contains:
- Order details (ID, date, status)
- Product info (SKU, category, size)
- Shipping data (city, state, courier status)
- Financials (amount, promotions)
- Fulfillment method (Amazon/Merchant)

## Key Findings
1. **Sales Distribution**:
   - Top state: Maharashtra (32% of sales)
   - Top category: Motto (28% of revenue)
   - B2C dominates (99.2% of orders)

2. **Promotions**:
   - Drive 4x more orders but reduce AOV by 14%
   - 68% of orders use discounts

3. **Operations**:
   - 6.5% cancellation rate 
   - 68.7% orders use expedited shipping

## How to Use
1. **Requirements**:
   - Python 3.8+
   - Libraries: pandas, numpy, matplotlib, seaborn

2. **Installation**:
   ```bash
   pip install -r requirements.txt

Run Analysis:
jupyter notebook Amazon_Sales_Analysis.ipynb

project/
├── data/
│   └── Amazon Sale Report.csv
├── notebooks/
│   └── Amazon_Sales_Analysis.ipynb
├── outputs/
│   ├── visualizations/
│   └── cleaned_data.csv
└── README.md

