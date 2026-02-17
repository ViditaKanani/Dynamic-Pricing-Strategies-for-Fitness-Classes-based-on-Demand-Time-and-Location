# Dynamic Pricing Strategy for Fitness Classes

## Project Overview

This project develops a data-driven dynamic pricing strategy for fitness classes.
The objective is to maximize class attendance and revenue by analyzing demand patterns
based on time, capacity, and pricing behavior.

The project leverages historical attendance data (April–June 2018) to:

- Forecast demand
- Estimate pricing impact
- Develop dynamic pricing rules
- Provide business recommendations

---

## Objectives

- Clean and preprocess historical class booking data
- Integrate multi-month datasets
- Perform quality validation
- Conduct exploratory data analysis (EDA)
- Develop a demand forecasting model
- Design a rule-based dynamic pricing algorithm
- Generate business insights and recommendations

---

## Dataset Description

The dataset contains information about:

- Activity Site ID
- Activity Description
- Booking Date
- Booking Start Time
- Maximum Capacity (MaxBookees)
- Number of Bookings
- Price (INR)

Data spans:
- April–May 2018
- June 2018

---

## Data Cleaning & Preprocessing

The following steps were performed:

- Handled missing values (Price imputation)
- Standardized data types using `astype()`
- Converted date and time columns using `pd.to_datetime()`
- Removed duplicate records
- Merged datasets using `pd.merge()`
- Conducted quality checks
- Removed overbooking anomalies

Final dataset:
- 3,271 clean records
- No missing values
- No duplicates
- No negative prices

---

## Data Integration & Quality Assurance

Datasets were merged using `pd.merge()` with an outer join.
Post-merge validation included:

- Missing value verification
- Duplicate detection
- Overbooking anomaly detection
- Structural consistency checks

The final dataset is clean and analysis-ready.

---

## Modeling Approach

The project includes:

- Demand Forecasting using Regression Analysis
- Price Elasticity Interpretation
- Feature Scaling (StandardScaler)
- Dynamic Pricing Rule Design

---

## Dynamic Pricing Strategy

Pricing rules are based on:

- Utilization rate
- Day of week
- Time slot demand
- Capacity constraints

High-demand classes receive premium pricing,
while low-demand classes are discounted to improve occupancy.

---

## Business Impact

The dynamic pricing model aims to:

- Increase revenue per class
- Improve seat utilization
- Reduce underperforming time slots
- Maintain competitive advantage

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Files Included

- Cleaned_Preprocessed_Fitness_Data.csv
- Jupyter Notebook (.ipynb)
- README.md

---

## Future Improvements

- Time-series demand forecasting (ARIMA / Prophet)
- Location-based pricing segmentation
- Machine learning-based elasticity modeling
- Real-time dynamic pricing engine

---

## Author

[Kanani Vidita]

