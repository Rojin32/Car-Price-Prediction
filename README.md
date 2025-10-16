# Car-Price-Prediction

Car Price Prediction using Machine Learning
Project Overview

This project predicts the price of cars based on features such as mileage, engine size, number of seats, year of manufacture, transmission type, and fuel type.
A Linear Regression model was trained and evaluated to understand how these factors influence the price of a car.

 Objectives

Build a regression model to predict car prices.

Analyze feature impact on car price.

Evaluate model performance using R², MSE, and Cross-Validation.

Visualize predictions and residuals to understand model behavior.

 Dataset

File: car_price_data.csv
Rows: 100
Columns:

year – Year of manufacture

mileage – Mileage in km/l

engine_size – Engine capacity in CC

fuel_type – Petrol / Diesel / Electric

transmission – Automatic / Manual

seats – Number of seats

price – Car price in ₹ lakhs (target variable)

🧩 Model Used

Algorithm: LinearRegression()
Libraries: scikit-learn, pandas, numpy, matplotlib


📊 Model Evaluation
Metric	Score
R² Score	0.91
Average Cross-Validation Accuracy	0.87
Mean Squared Error (MSE)	62.0

📈 Visualizations
1️⃣ Actual vs Predicted Car Prices

Shows how close predicted values are to actual ones.
Points near the red line = good predictions.

2️⃣ Residual Plot (Error Distribution)

Checks randomness of prediction errors.
Residuals are centered around 0 → model is unbiased
