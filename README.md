🌍 Climate–Agriculture Nexus
Data Analytics & Machine Learning for Climate-Resilient Farming

📌 Project Overview

This project analyzes how climate change is impacting Indian agriculture using historical data from 2000 to 2025.
It combines data analysis, visualization, and machine learning to understand how temperature rise, rainfall decline, groundwater depletion, and extreme weather affect:

🌾 Crop yield

👨‍🌾 Farmer distress

💧 Water security

🌱 Climate resilience

The project also generates future predictions (2026–2035) to support climate-resilient agricultural planning.

📂 Dataset

The dataset (climate_agriculture_dataset.csv) contains 26 years of data with the following key variables:

Category	Variables
Climate	Temperature, Rainfall, Drought Events, Extreme Weather Days
Agriculture	Crop Yield, Crop Diversification, Irrigation Coverage
Environment	Groundwater Level, Soil pH
Socio-Economic	Farmer Income Index, Input Cost Index, Farmer Distress Index
Sustainability	Climate Resilience Index
🔍 Key Insights (2000–2025)

🌡 Temperature increased by 2.7°C

🌧 Rainfall reduced by 230 mm

💧 Groundwater dropped by 6.3 meters

🚨 Farmer distress index increased by 30 points

Strong correlations found:

Temperature vs Crop Yield → 0.986

Temperature vs Farmer Distress → 0.998

Rainfall vs Crop Yield → –0.965

🤖 Machine Learning Models

The following models were trained to predict crop yield and climate outcomes:

Model	Performance
Random Forest	High accuracy
Gradient Boosting	Best Model (R² ≈ 0.987)
Linear Regression	Baseline

The model predicts crop yield, farmer distress, groundwater level, and climate resilience up to 2035.

📊 Feature Importance (Crop Yield)

Top factors affecting crop yield:

Groundwater Level

Irrigation Coverage

Temperature

This shows that water availability is the most critical driver of agricultural productivity.

📈 Future Outlook (2035)

Crop yield expected to stagnate under current climate trends

Water stress and economic pressure on farmers expected to increase

Climate resilience improves slowly but not enough to offset risks

🛠 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Jupyter Notebook

▶ How to Run

Clone this repository

Open Jupyter Notebook

Load the dataset:

import pandas as pd
df = pd.read_csv("climate_agriculture_dataset.csv")


Run the notebook cells to reproduce analysis, models, and charts

🎯 Applications

This project can help:

Climate policy makers

Agricultural planners

Sustainability researchers

Farm support agencies

by providing data-driven insights into climate risks and food security.

👤 Author

Mohammed
Data Analyst | Machine Learning Enthusiast
