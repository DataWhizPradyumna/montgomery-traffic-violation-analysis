# 🚦 Montgomery County Traffic Violation Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-111?style=flat&logo=lightgbm&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

> 📍 A data-driven exploration of over 2 million traffic stops in Montgomery County (2012–2024), revealing enforcement patterns, accident risks, and demographic trends through machine learning and visual storytelling.

---

## 📌 Overview

This project analyzes historical traffic violation records to identify patterns across **time**, **location**, and **demographics**, with the goal of informing public policy, improving road safety, and promoting equitable enforcement.

---

## 🎯 Objectives

- 📍 Map violation hotspots across the county  
- ⏰ Discover time-based violation trends  
- 🧑‍🤝‍🧑 Explore demographic insights by race and gender  
- 🧠 Predict accident and arrest likelihoods using ML models  
- 📊 Deliver dashboards and maps for public consumption

---

## 🧾 Dataset Summary

| 📂 Attribute       | 📄 Description |
|-------------------|----------------|
| Records           | 2,000,127      |
| Time Span         | 2012 – 2024    |
| Features          | 40+ Columns    |
| Key Fields        | Date, Time, Race, Gender, Location, Charge |

📌 **Source:** [Data.gov - Montgomery County Traffic Stops](https://www.data.gov/)

---

## 📁 Project Structure

montgomery-traffic-analysis/
├── data/ # Sample/cleaned data
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── scripts/ # Python scripts
├── visualizations/ # Maps, charts, screenshots
├── report/ # Final project report (.docx or .pdf)
├── requirements.txt # Python libraries
└── README.md


---

## 🔍 Methodology

🔹 **Data Cleaning**: Removed duplicates, standardized timestamps, encoded categoricals 
   ![Missing Values](https://github.com/DataWhizPradyumna/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.49.47%E2%80%AFPM.png)
🔹 **EDA**: Heatmaps, bar plots, demographic slices  
🔹 **Modeling**:  
- 🟧 `RandomForestClassifier`: Predicts accidents based on violation context  
- 🟩 `LightGBM`: Forecasts arrest probability  
🔹 **Mapping**: Folium used to visualize spatial trends  
🔹 **Dashboards**: Tableau for dynamic public-facing visuals

---

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy)
![Seaborn](https://img.shields.io/badge/-Seaborn-4C4C4C?style=flat)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat)
![Folium](https://img.shields.io/badge/-Folium-008000?style=flat)
![LightGBM](https://img.shields.io/badge/-LightGBM-111?style=flat)
![Scikit-learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=flat)
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)

---

## 📊 Key Insights

- 🚧 **Southern Montgomery** shows higher accident-prone zones  
- 🌃 **Arrests peak** during early morning weekend hours  
- 📉 **Citations decreased** from 56% to 29% over time, while warnings increased  
- ⚖️ Disparities in stop outcomes observed by race and gender

---

## 📸 Visuals

### 📍 Violation Distribution by Traffic
![Violation Time](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.51.24%E2%80%AFPM.png)

### 🚨 Monthly Traffic Stops (2012-2024)
![Accident Chart](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.51.57%E2%80%AFPM.png)

### 📈 Search Rate by Race and Time of Day
![Violation Types](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.52.25%E2%80%AFPM.png)

### 👥 Violation Types with Highest Accident Rates
![Gender Split](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.52.58%E2%80%AFPM.png)

### 🌍 Top 5| Pre-Crash Predictors of Accident Risk
![Hotspot Map](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.53.40%E2%80%AFPM.png)

### 🚔 Folium plot of Accidents
![Citation vs Arrest](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.54.19%E2%80%AFPM.png)

### 📉 Top 5 Most Important Features for Arrest Prediction
![Citations Decline](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.54.54%E2%80%AFPM.png)

### 📊 Arrest Rate by Day of Week
![Arrests Timing](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.55.23%E2%80%AFPM.png)

### ⚖️ Arrest Rate by Day of Week and Hour
![Race-Based Analysis](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%204.55.55%E2%80%AFPM.png)

### 💡 Violation by Race Type
![RF Feature Importance](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.00.12%E2%80%AFPM.png)

### 🎯 Violation Types by Gender
![LGBM Accuracy](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.01.09%E2%80%AFPM.png)

### 🛣️ Demogrphics with warning violations
![Location Frequency](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.02.14%E2%80%AFPM.png)

### 📆 Heatmap of Violation types by Race
![Daily Patterns](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.09.34%E2%80%AFPM.png)

### 🕒 Warning and citation by time of day
![Hourly Density](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.10.11%E2%80%AFPM.png)

### 🚗 ESERO violations by Time and Race
![Vehicle Type](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.10.54%E2%80%AFPM.png)

### 👮 Traffic Violation by hour of Day
![Sub-agency](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.11.39%E2%80%AFPM.png)

### 📋 Distribution of Violation type by Day of Week
![Top Charges](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.12.13%E2%80%AFPM.png)

### 🔢 Distribution of Violation type by Hour and Day
![Violation Count](https://github.com/DataWhizShiva/montgomery-traffic-violation-analysis/blob/main/Visualizations/Screenshot%202025-05-20%20at%205.12.43%E2%80%AFPM.png)

## 🧠 Author

- **Shiva Sai Pradyumna E**  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/shiva-sai-e-685956174)  
  📧 shivasaie1315@gmail.com

## 📘 References

Dataset:[Data.gov - Montgomery County Traffic Stops](https://www.data.gov/)

## 💡 Final Thought

> “Turning raw traffic data into smarter, safer streets — one prediction at a time.”


**Tags:**  
#DataScience #MachineLearning #TrafficAnalysis #Python #LightGBM #Tableau #Pandas


