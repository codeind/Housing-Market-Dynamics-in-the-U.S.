### 📘 Project Description

Housing Market Dynamics in the U.S.: Trends, Predictive Analytics, and Forecasting Insights Using Zillow Data
Graduate Research Project – Creative Component | Iowa State University

This project presents a comprehensive analysis of the U.S. housing market using Zillow’s Home Value Index (ZHVI) dataset. With over two decades of monthly housing price data across 900+ U.S. metro areas, the study explores the evolution of housing prices, market volatility, seasonal behaviors, and post-pandemic recovery patterns. It further employs advanced machine learning models to predict future housing values and classify regional market types.

The project was conducted in fulfillment of the Creative Component requirement for the Master of Science in Information Systems at Iowa State University and integrates a full data analytics pipeline — from data engineering and exploratory analysis to predictive modeling and interactive visualization.

### 🎯 Key Objectives
Analyze historical housing price patterns and trends across metro regions.
Examine the impact of volatility, growth rates, and COVID-19 on housing dynamics.
Build interactive Tableau dashboards for geographical and temporal insights.
Forecast future housing prices using time series and regression models.
Identify speculative or unstable housing markets using clustering and anomaly detection.

### 🔧 Technologies & Tools
. Python: Data preprocessing, machine learning, forecasting, anomaly detection
. Tableau: 8 dashboard visualizations for trend analysis and storytelling
. Prophet (by Meta): Time series forecasting
. Scikit-learn: Random Forest regression, KMeans clustering, Isolation Forest
. Pandas/Matplotlib/Seaborn: Data exploration and feature engineering
. Zillow Research ZHVI Dataset: Core dataset for analysis and modeling

### 📊 Project Workflow

##### 1. Data Preprocessing & Engineering
Reshaped Zillow ZHVI data to long format
Cleaned missing values and normalized features
Engineered lag features, rolling averages, and date components

##### 2. Descriptive Analysis – Tableau Dashboards
. Time Series Price Trends
![Time Series Trend Analysis](https://github.com/user-attachments/assets/86a2a308-e5c4-4818-aa65-0c9844e33dfc)

. Year-over-Year (YoY) & CAGR Growth Rates
![Year over Year   CAGR Growth](https://github.com/user-attachments/assets/89efbb58-10e7-405a-b913-2a0eae53e327)

. Geospatial Heatmaps by City and State
![Geospatial Map (3)](https://github.com/user-attachments/assets/7b81e2e8-4d64-40df-9b60-60b709d1a3f3)
![Geospatial Map (2)](https://github.com/user-attachments/assets/c66440d4-d1bb-44e0-9bba-f338f8cf6c94)

. Volatility Analysis (Standard Deviation)
![Volatility Analysis](https://github.com/user-attachments/assets/4c092d76-1e48-4c7f-a913-966cf3f21d75)

. Monthly Seasonality Trends
![Monthly Trend Comparison (1)](https://github.com/user-attachments/assets/403069de-d3ca-4a18-847c-956c8baff7da)

. COVID-19 Recovery Growth Metrics
![Post Covid Recovery](https://github.com/user-attachments/assets/15b54f53-0b45-4296-993f-d950d0dd1b86)


##### 3. Predictive Analytics – Python Models
. Prophet Forecasting: Generated 24-month forecasts for metro areas
![image](https://github.com/user-attachments/assets/66d8bb4d-e95c-435f-a764-d1acb487eba6)

. Random Forest Regression: Achieved R² = 0.87 for ZHVI predictions
. KMeans Clustering: Segmented markets into 4 behavioral types (e.g., stable, speculative)
![image](https://github.com/user-attachments/assets/37a969d9-7f69-4d8e-89dc-e94cac5ce255)

. Anomaly Detection: Combined Z-score and Isolation Forest to flag risky metros
![image](https://github.com/user-attachments/assets/c62c95f8-3d2d-416d-a409-020f235403fd)


### 🔍 Notable Insights
Austin, TX showed 100%+ growth in 10 years, indicating speculative behavior
Des Moines, IA exhibited strong stability with 4.5% CAGR and low volatility
Seasonal price peaks consistently occurred between May–July across metros
Ottumwa, IA saw 46% post-COVID recovery in ZHVI, one of the highest nationwide
Clustering and anomaly detection highlighted markets vulnerable to correction or investor overreach

### 📄 Deliverables
📘 Final Research Report (PDF)
📈 Tableau Workbook with 8 visual dashboards
📊 Python Jupyter Notebooks (Prophet, RF, Clustering, Anomaly Detection)
📂 Cleaned & reshaped ZHVI dataset (.csv)

### 🧠 Academic Context
This project demonstrates how advanced analytics and predictive modeling can support evidence-based decision-making in real estate. By blending traditional trend analysis with modern machine learning tools, the study provides a framework for understanding and forecasting housing market behavior — valuable to urban planners, investors, data scientists, and policy-makers.

