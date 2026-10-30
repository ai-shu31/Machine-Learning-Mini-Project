# 🌍 Air Quality Data Analysis and CO Prediction

## 📌 Project Overview

This project focuses on analyzing air quality data and understanding the concentration of Carbon Monoxide (CO) in the atmosphere.

The project uses Python-based data analysis and visualization techniques to explore air quality measurements, identify missing values, understand pollutant distributions, and examine how CO concentration changes over time.

It also prepares the dataset for **next-hour CO concentration prediction** by creating a target variable using the CO measurement from the following hour.

## 🎯 Objectives

- Analyze air quality measurements using Python.
- Identify and handle missing and invalid data.
- Explore the statistical characteristics of CO concentration.
- Visualize pollutant distributions and temporal trends.
- Prepare the dataset for time-based prediction.
- Understand the relationship between air quality measurements and CO concentration.

## 📊 Dataset

The project uses an Air Quality dataset containing hourly air quality measurements.

The dataset includes information such as:

| Feature | Description |
|---|---|
| Date | Date of the measurement |
| Time | Time of the measurement |
| CO(GT) | Ground-truth Carbon Monoxide concentration |
| PT08.S1(CO) | Sensor response associated with CO |
| NMHC(GT) | Ground-truth Non-Methane Hydrocarbons |
| C6H6(GT) | Benzene concentration |
| PT08.S2(NMHC) | Sensor response associated with NMHC |
| NOx(GT) | Ground-truth Nitrogen Oxides |
| NO2(GT) | Ground-truth Nitrogen Dioxide |
| PT08.S3(NOx) | Sensor response associated with NOx |
| PT08.S4(NO2) | Sensor response associated with NO2 |
| PT08.S5(O3) | Sensor response associated with Ozone |
| T | Temperature |
| RH | Relative Humidity |
| AH | Absolute Humidity |

The dataset uses `-200` as a missing-value marker in measurement columns. These values are replaced with `NaN` during data cleaning.

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization

## 🔍 Project Workflow

### 1. Data Loading

- Uploaded the dataset into Google Colab.
- Loaded the Excel file using Pandas.
- Examined the dataset dimensions and structure.

### 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand the dataset.

- Displayed column names and data types.
- Examined the first five records.
- Generated descriptive statistical
