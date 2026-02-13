# Food Delivery Demand & Operational Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on a food delivery dataset to understand demand patterns, operational trends, and delivery performance characteristics.

The objective is to analyze order behavior, delivery time distribution, and operational factors influencing food delivery services.

---

## Dataset

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/jayjoshi37/daily-food-delivery-orders-and-delivery-time

The dataset contains 2,600+ food delivery order records with the following features:

- Order ID
- Order Date
- Customer Age
- Restaurant Type
- Order Value
- Delivery Distance (km)
- Delivery Time (minutes)
- Payment Method
- Delivery Partner Rating
- Order Status

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Analysis Performed

### Data Cleaning
- Checked for missing values
- Removed duplicates
- Converted date columns to datetime format

### Exploratory Data Analysis
- Distribution of delivery times
- Distance vs delivery time relationship
- Restaurant type impact on delivery duration
- Payment method distribution
- Orders by day of the week
- Orders by hour of the day
- Correlation heatmap of numerical features

---

## Key Insights

- Delivery times follow a relatively stable distribution across orders.
- Weak correlation observed between delivery distance and delivery time.
- Payment methods are evenly distributed, indicating balanced digital adoption.
- Restaurant types show moderate variation in median delivery time.
- Demand patterns show variation across weekdays and weekends.

---

## Observations

The dataset shows weak predictive relationships between numerical features and delivery time, suggesting that external operational factors (e.g., traffic, weather, rider allocation) may significantly influence delivery performance.

---

## Conclusion

This project demonstrates strong exploratory data analysis techniques and business-oriented interpretation of operational data.

It highlights the importance of understanding feature relationships before building predictive models and showcases data-driven insight extraction for real-world delivery systems.

---
