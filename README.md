# Flight_Delay
This project focuses on predicting flight delays using a real-world dataset containing over 1.7 million records. The goal is to develop a regression model that can estimate the number of minutes a flight will be delayed based on various features such as airline, route, scheduled/actual departure times, and aircraft details.
## 🧠 Problem Type
- **Supervised Learning**
- **Regression Problem**
- **Target Variable:** `DelayMinutes` (continuous)

## 📁 Dataset Overview
The dataset contains 16 columns including:
- Flight information (`FlightID`, `Airline`, `FlightNumber`)
- Timing details (`ScheduledDeparture`, `ActualDeparture`, `ScheduledArrival`, `ActualArrival`)
- Route details (`Origin`, `Destination`, `Distance`)
- Delay information (`DelayMinutes`, `DelayReason`)
- Aircraft details (`AircraftType`, `TailNumber`)
- Flags (`Cancelled`, `Diverted`)

Total Records: **1,747,627**

## 📌 Objective
To build and evaluate a predictive model that can estimate flight delays in minutes, which could help airlines and passengers make better decisions.

## 🔧 Planned Steps
- Exploratory Data Analysis (EDA)
- Handling missing values and feature engineering
- Encoding categorical variables
- Model training using regression algorithms
- Evaluation using metrics like MAE, RMSE, R² Score

## 📦 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook / VS Code
- Git & GitHub

## 🚀 Future Scope
- Integrate weather data
- Convert to classification (e.g., Delayed vs. On-Time)
- Deploy model via Flask or Streamlit

---

**Feel free to fork, contribute or suggest improvements!**
