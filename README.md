# Supply Chain Demand Forecasting & Inventory Optimization

##  Project Overview

This project focuses on analyzing historical sales and supply chain data to forecast product demand and support inventory management decisions.

The project follows a complete data analytics and machine learning workflow:

**Data Cleaning → Exploratory Data Analysis → Feature Engineering → Demand Forecasting → Inventory Optimization → Business Recommendations**

The goal is to help businesses understand demand patterns, identify important factors affecting demand, forecast future demand, and determine appropriate inventory levels.

---

##  Problem Statement

Businesses need to maintain enough inventory to meet customer demand while avoiding excessive stock that increases holding costs.

This project aims to:

- Analyze historical product demand
- Identify demand patterns across products, categories, and regions
- Analyze factors such as price, discount, promotion, and competitor pricing
- Forecast product demand using machine learning
- Calculate inventory metrics such as Safety Stock, Reorder Point, and EOQ


## 📊 Dataset

The project uses a synthetic supply chain dataset containing approximately 500 records.

### Important Columns

| Column | Description |
|---|---|
| Date | Date of the sales record |
| Store_ID | Store identifier |
| Product_ID | Product identifier |
| Category | Product category |
| Region | Sales region |
| Inventory_Level | Current inventory level |
| Units_Sold | Number of units sold |
| Units_Ordered | Number of units ordered |
| Price | Product price |
| Discount | Discount percentage |
| Promotion | Promotion indicator |
| Weather_Condition | Weather condition |
| Competitor_Pricing | Competitor's product price |
| Seasonality | Seasonal factor |
| Epidemic | External event indicator |
| Demand | Product demand |

> **Note:** The dataset used in this project is synthetic and was created for learning and portfolio purposes.

## 🔍 Exploratory Data Analysis

The following analysis was performed:

- Category-wise demand analysis
- Region-wise demand analysis
- Product demand analysis
- Price analysis
- Discount analysis
- Promotion vs demand analysis
- Competitor pricing analysis
- Demand variability analysis


### Visualizations

- Bar charts
- Pie charts
- Line charts
- Scatter plots
- Box plots

Example analysis questions:

- Which category has the highest demand?
- Which region generates the highest demand?
- Which category has the highest maximum discount?
- How does product price compare with competitor pricing?
- Does promotion affect demand?
- How does demand change over time?

---

## 🧹 Data Cleaning

The dataset was checked and cleaned for:

- Missing values
- Duplicate records
- Incorrect data types
- Numerical and categorical inconsistencies

Different missing-value strategies were used depending on the column.

Examples:

- Numerical values → median where appropriate
- Categorical values → mode
- Discount → handled based on promotion status

---

##  Feature Engineering

Features were created to improve demand forecasting.

### Time-based Features

- Month
- Day of week

### Lag Features

- Lag 1
- Lag 7

These features help the model understand previous demand patterns.

##  Demand Forecasting

Machine learning models were used to predict product demand.

### Models

- Random Forest Regressor

### Target Variable

Demand
