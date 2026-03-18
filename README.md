# 🚗 Car Mortgage Value Prediction

---

## 📌 Project Overview

The **Car Mortgage Value Prediction** project focuses on estimating the value of used cars for loan/mortgage purposes using machine learning techniques.

In the financial ecosystem, banks and lending institutions often provide loans against vehicles. Accurately determining the resale or mortgage value of a car is critical for minimizing risk and ensuring fair loan disbursement. This project leverages historical used car data to build a predictive model that estimates vehicle value based on various features.

The dataset includes attributes such as car brand, manufacturing year, fuel type, kilometers driven, and transmission type. By analyzing these factors, the model provides a data-driven approach to vehicle valuation.

---

## 📊 Data Dictionary

The dataset contains multiple features describing used cars:

| Column Name   | Description                      |
| ------------- | -------------------------------- |
| Car_Name      | Name/model of the car            |
| Year          | Manufacturing year               |
| Selling_Price | Target variable (price in lakhs) |
| Present_Price | Original showroom price          |
| Kms_Driven    | Distance driven by the car       |
| Fuel_Type     | Petrol / Diesel / CNG            |
| Seller_Type   | Dealer or Individual             |
| Transmission  | Manual or Automatic              |
| Owner         | Number of previous owners        |

---

## 🔍 Exploratory Data Analysis (EDA) Insights

* **Age of Car:** Older cars have significantly lower resale value
* **Kms Driven:** Higher usage reduces vehicle price
* **Fuel Type:** Diesel cars tend to retain higher value compared to petrol
* **Transmission:** Automatic cars often have slightly higher resale value
* **Owner Count:** Fewer previous owners increase trust and price

---

## 🤖 Model Development

This is a **regression problem**, where the goal is to predict the monetary value of a car.

### Models Used:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### ⚙️ Pipeline:

* Data cleaning and preprocessing
* Encoding categorical variables
* Feature selection
* Model training and evaluation

---

## 📈 Model Performance

* Random Forest Regressor achieved the best performance
* Improved prediction accuracy by capturing non-linear relationships

### Evaluation Metrics:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

---

## 💡 Key Impact

### 📌 Real-World Value:

* Helps banks determine **car mortgage value**
* Assists buyers/sellers in fair price estimation
* Useful for **vehicle loan risk assessment**

### 📌 Technical Value:

* Demonstrates regression modeling
* Real-world dataset handling
* Feature importance analysis

---

## 🧠 Conclusion

The Car Mortgage Value Prediction project highlights the practical application of machine learning in the automotive and financial sectors. By leveraging structured data and regression models, the system provides accurate and scalable solutions for vehicle valuation, supporting better decision-making in loan processing and resale markets.

---
