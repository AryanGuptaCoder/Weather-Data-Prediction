# 🌦 Weather Data Analysis and Temperature Prediction using Machine Learning

## 📌 Project Overview

This project analyzes historical weather data and predicts future temperature using Machine Learning regression algorithms. Historical weather parameters such as humidity, pressure, wind speed, month, and day are used to estimate temperature.

---

## 🎯 Objectives

- Analyze historical weather data.
- Perform exploratory data analysis.
- Train regression models.
- Predict future temperatures.
- Compare model performance.

---

## 📂 Dataset

Dataset:
Daily Climate Time Series Data

Source:
https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data

Dataset Features:

- Date
- Mean Temperature
- Humidity
- Wind Speed
- Mean Pressure

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

---

## 📂 Project Structure

Weather-Data-Prediction/

├── Weather_Prediction.ipynb
├── README.md
├── requirements.txt
├──weather/├── DailyDelhiClimateTrain.csv
|          ├── DailyDelhiClimateTest.csv
├── weather_model.pkl
└── graphs/

---

## 🤖 Machine Learning Algorithms

- Linear Regression
- Random Forest Regression

---

## 📊 Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Workflow

Dataset

↓

Data Cleaning

↓

EDA

↓

Feature Engineering

↓

Train/Test Split

↓

Model Training

↓

Prediction

↓

Evaluation

↓

Save Model

---

## ▶️ How to Run

1. Clone the repository.

2. Install required libraries:

pip install -r requirements.txt

3. Download the Kaggle dataset.

4. Open Weather_Prediction.ipynb.

5. Run all notebook cells.

6. Save the model:

joblib.dump(model, "weather_model.pkl")

---

## 📊 Results

Random Forest Regression produced better prediction performance than Linear Regression for this dataset.

---

## 🚀 Future Scope

- LSTM for time-series forecasting.
- Real-time weather API integration.
- Web application deployment.
- Rainfall prediction.
- Humidity prediction.

---

## 👨‍💻 Author

Aryan Gupta
