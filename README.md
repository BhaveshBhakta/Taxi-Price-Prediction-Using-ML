# 🚖 Taxi Price Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on building a machine learning pipeline to predict **taxi trip prices** based on multiple real-world factors such as distance, time, weather, traffic conditions, and fare structure. Through robust preprocessing and regression modeling, we aim to generate accurate trip cost predictions to assist ride-hailing services, pricing engines, and transportation analytics.

---

## 🧠 Technical Highlights

* **Dataset**: Contains 1000 real-world taxi trips with 11 features such as:

  * `Trip_Distance_km`, `Passenger_Count`, `Traffic_Conditions`, `Weather`, `Trip_Duration_Minutes`, and various fare components.

* **Preprocessing**:

  * Imputed missing values using **formula-based calculations** and **default statistical methods**
  * Applied **log transformation** for skewed distributions
  * Encoded categorical variables using **LabelEncoder**

* **Feature Selection**:

  * Used **correlation thresholding** to select highly relevant features

* **Models Applied**:

  * Ridge Regression
  * XGBoost Regressor
  * Random Forest Regressor
  * AdaBoost Regressor
  * Gradient Boosting Regressor
  * Bagging Regressor

* **Best Performance**:

  * 📈 **Gradient Boosting Regressor** achieved **R² score of 0.914**

---

## 🎯 Purpose and Applications

* 💸 **Dynamic Fare Estimation** for ride-hailing apps and taxi meters
* 📉 Cost prediction under varying traffic and weather scenarios
* 🧪 Educational reference for **regression modeling**, **feature engineering**, and **data cleaning**
* 🛠️ Basis for building real-time APIs and fare calculators

---

## ⚙️ Installation

 **Clone the repository**

   ```bash
   git clone https://github.com/BhaveshBhakta/Taxi-Price-Prediction-Using-ML.git
   cd axi-Price-Prediction-Using-ML
   ```

---

## 🤝 Collaboration

Contributions are welcome! If you’d like to improve model performance, add new visualizations, or integrate the project with a web interface.
