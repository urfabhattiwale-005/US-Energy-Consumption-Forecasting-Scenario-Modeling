# US-Energy-Consumption-Forecasting-Scenario-Modeling
Time series analysis project on electricity consumption data using Python. Includes data cleaning, EDA, trend and seasonal analysis, ARIMA and Prophet forecasting, and scenario-based modeling to simulate future demand variations. Provides insights for energy planning and decision-making.

Objectives
-Analyze electricity consumption trends
-Identify seasonal patterns
-Build forecasting models (ARIMA & Prophet)
-Perform scenario-based analysis (high/low demand)

📂 Dataset

Name: Household Power Consumption Dataset
Source: Kaggle

Features Used:
Date, Time,Global Active Power,Voltage, Intensity,Sub-metering values

--> Tools & Technologies
Python,Pandas,NumPy,Matplotlib & Seaborn,Statsmodels (ARIMA),Prophet

--> Exploratory Data Analysis

Trend Analysis 📈:
-Rolling Mean (12 months)
-Year-wise Consumption
-Monthly Seasonality
-Distribution Analysis

--> Models Used
🔹 ARIMA
-Used for short-term forecasting
-Captures trend and temporal dependencies

🔹 Prophet
-Captures seasonality and long-term trends
-Provides interpretable forecasts

🔹Scenario-Based Modeling
Baseline Forecast
High Demand (+10%)
Low Demand (-10%)
Helps simulate real-world variations in energy consumption.

--> Results & Insights

Consumption shows a stable trend with minor fluctuations
Seasonal patterns observed across months
ARIMA provides reliable short-term forecasts
Prophet captures long-term trend and seasonality effectively
Scenario modeling helps in demand planning


📁 Project Structure
├── data/
│   └── power_consumption.csv
├── notebooks/
│   └── analysis.ipynb
├── plots/
├── report/
│   └── final_report.pdf
└── README.md


Conclusion

This project demonstrates the use of time series analysis and forecasting techniques to derive meaningful insights from energy consumption data and support future planning.


Author

Urfa Ilyas Bhattiwale
