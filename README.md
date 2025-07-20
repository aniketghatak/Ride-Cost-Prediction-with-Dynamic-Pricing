# Ride Cost Prediction with Dynamic Pricing

This project aims to simulate and predict ride costs based on dynamic pricing strategies influenced by demand and supply metrics. Using real-world-like features such as the number of riders, number of drivers, vehicle type, and expected ride duration, a Random Forest Regression model is trained to estimate adjusted ride costs.

---

## 🔍 Overview

Dynamic pricing is a strategy used by ride-sharing platforms to adjust prices based on supply-demand conditions. This project includes:

- Data preprocessing pipeline
- Demand and supply multiplier calculations
- Dynamic cost adjustment
- Exploratory data analysis & visualization
- Predictive modeling using Random Forest Regressor
- Actual vs. predicted cost evaluation
- Interactive user input-based prediction

---

## 📊 Features Engineered

- **Demand Multiplier**: Based on rider count percentiles
- **Supply Multiplier**: Based on driver availability
- **Adjusted Ride Cost**: Calculated by applying multipliers to historical cost

---

## 🛠 Tools & Technologies

- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn (RandomForestRegressor, train_test_split)
- Basic user input handling for predictions

---

## 📈 Visualizations

The project includes:

- Scatter plots with regression lines
- Box plots of ride cost distribution by vehicle type
- Correlation heatmap
- Actual vs. Predicted value comparison
- Donut charts for profitability analysis

---

## 🤖 User Interaction

```python
Users can enter:

- Number of riders
- Number of drivers
- Vehicle type (Economy or Premium)
- Expected ride duration

The model will return the **predicted dynamic ride cost** based on current market conditions.

```

---
