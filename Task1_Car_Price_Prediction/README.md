# 🚗 Task 1: Car Price Prediction  
Oasis Infobyte Internship (OIBSIP)

This project builds a Machine Learning model to predict the **selling price of used cars** based on features such as the car model year, present price, fuel type, transmission, owner, and more.

---

## 📌 Objective
To develop a prediction system using **Random Forest Regressor** that estimates the price of a car based on its features.

---

## 📂 Dataset Information

The dataset contains the following columns:

- **Car_Name** – Name of the car  
- **Year** – Purchase year  
- **Selling_Price** – The price at which the car can be sold  
- **Present_Price** – Price of the car when it was new  
- **Driven_kms** – Kilometers driven  
- **Fuel_Type** – Petrol/Diesel/CNG  
- **Selling_type** – Dealer/Individual  
- **Transmission** – Automatic/Manual  
- **Owner** – Number of owners previously  

---

## 🧠 Steps Performed

### ✔ 1. Data Loading  
Read the CSV file using Pandas.

### ✔ 2. Data Cleaning & Encoding  
Converted categorical columns into numerical values:
- Fuel_Type  
- Selling_type  
- Transmission  

### ✔ 3. Feature Selection  
Separated input features **X** and target **y (Selling_Price)**.

### ✔ 4. Train-Test Split  
Split data into:
- 80% training  
- 20% testing  

### ✔ 5. Model Training  
Used **RandomForestRegressor**.

### ✔ 6. Model Evaluation  
Measured accuracy using **R2 Score**.

### ✔ 7. Price Prediction  
Tested the model with user-defined input values.

Example output:
