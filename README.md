# Capstone-Project-5
Dominos - Predictive Purchase Order System
Problem Statement
Dominos is seeking to optimize its ingredient ordering process by accurately predicting future sales and generating efficient purchase orders. The company faces challenges related to inventory management, such as minimizing ingredient waste due to overstocking and avoiding stockouts that disrupt operations. These inefficiencies not only lead to increased costs but also negatively impact customer satisfaction and overall operational efficiency.
Objectives
•	Accurate Sales Prediction: Develop a accurate predictive model to forecast future sales based on historical sales data and trends.
•	Efficient Ingredient Ordering: Prepare a purchase order system that aligns with predicted sales of Pizzas to ensure an optimal inventory level.
•	Waste Reduction: Minimize ingredient wastage by avoiding overstocking and managing inventory efficiently.
•	Cost Optimization: Reduce costs associated with excess inventory, storage, and expired ingredients.
Project Summary
Step 1: Load the data files (CSV) (Pizza sales and Ingredients) 
Step 2: Read the data files with Pandas  
Step 3: Data pre-processing
•	Data cleaning (Handling missing Data, removing inconsistent and duplicates data)
•	Identified outliers (using IQR method) and removed
•	Exploratory Data Analysis (EDA) to discover patterns, relationships, and anomalies in the data
Step 4: Feature Engineering
•	Add new columns like day of the week, month, year, and holidays
Step 5: Model Selection
•	ARIMA, SARIMA, PROPHET, REGRESSION, and LSTM
•	Identify best fit model based on the evaluation of MAPE results
•	Best fit model SARIMA is utilised to forecast one week sales of Pizzas
Step 6: Prepare ingredients purchase order
•	Predict the quantify of pizza  sales (for a week)
•	Estimated the total ingredients required for the predicted pizza types
•	Prepare the purchase order for ingredients required for one week of pizza sales predictions
