# 🚖 PREDICTING TAXI FARE

This project is based on the **NYC Yellow Taxi Trip Data** and aims to predict the fare amount of a taxi ride. The model is built using **Linear Regression** implemented with **PySpark** in a Python environment.

## 📊 Dataset

Dataset source:  
[NYC Yellow Taxi Trip Data – Kaggle](https://www.kaggle.com/datasets/elemento/nyc-yellow-taxi-trip-data)

## 🛠️ Technologies Used

- Python
- Apache Spark (PySpark)

## 🔁 Project Workflow

1. **Exploratory Data Analysis (EDA)**:
   - Identify missing values, duplicates and outliers (e.g., negative distances or durations).
2. **Feature Engineering**:
   - Extract time-based features (day of week, hour, month) from the pickup datetime.
3. **Data Preparation**:
   - Assemble features using `VectorAssembler`.
   - Split the dataset into training and testing sets.
4. **Model Training**:
   - Train a `LinearRegression` model from `pyspark.ml.regression`.
   - Evaluate using metrics like RMSE, MAE, and R².

## 📥 Relevant Features

- Month, Day of week, hour of day
- Pickup longitude & latitude
- Dropoff longitude & latitude
- Passenger count
- Trip distance
- RateCodeID

## 📈 Example Metrics

- RMSE: *to be filled after training*
- MAE: *to be filled after training*
- R²: *to be filled after training*
