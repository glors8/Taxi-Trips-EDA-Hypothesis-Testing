# 🚕 Chicago Taxi Trips – Exploratory Data Analysis & Hypothesis Testing

## 📁 Project Summary

In this bootcamp project, you analyze real-world taxi trip data from **Chicago**, focusing on company performance, popular drop-off areas, and trip durations under different weather conditions.

The project is divided into two main parts:
1. **Exploratory Data Analysis (EDA)** of trip counts by taxi companies and neighborhoods
2. **Hypothesis Testing** regarding trip duration affected by weather on rainy Saturdays

---

## 🔍 Objectives

### Part 1: Exploratory Data Analysis (EDA)

Datasets:
- `/datasets/project_sql_result_01.csv`: Number of trips per taxi company on Nov 15–16, 2017.
- `/datasets/project_sql_result_04.csv`: Average number of trips per neighborhood in Nov 2017.

Tasks:
- Import and inspect the datasets
- Validate and clean data types
- Identify top 10 drop-off neighborhoods
- Visualize:
  - Number of trips per company
  - Top 10 neighborhoods by trip completions
- Interpret insights from the charts

---

### Part 2: Hypothesis Testing

Dataset:
- `/datasets/project_sql_result_07.csv`: Trip data from the Loop to O'Hare Airport

The hypothesis test:

> "The average trip duration from the Loop to O'Hare changes on rainy Saturdays."

Tasks:
- Define null and alternative hypotheses
- Choose an appropriate significance level (alpha)
- Select and justify a statistical test
- Analyze and interpret results

---

## 🧠 Tools & Techniques

- Python (pandas, matplotlib, seaborn, scipy)
- Data cleaning and aggregation
- Bar charts and histograms
- Statistical hypothesis testing (e.g., t-test)

---

## 📦 Dataset Features

### `project_sql_result_01.csv`
- `company_name`: Taxi company name  
- `trips_amount`: Number of trips per company (Nov 15–16, 2017)

### `project_sql_result_04.csv`
- `dropoff_location_name`: Chicago neighborhoods  
- `average_trips`: Avg. trips ending in each neighborhood (Nov 2017)

### `project_sql_result_07.csv`
- `start_ts`: Trip start datetime  
- `weather_conditions`: Weather at trip start  
- `duration_seconds`: Trip duration in seconds

---

## ✅ Project Outcome

The project helps answer:
- Which taxi companies and neighborhoods have the most traffic?
- Are weather conditions affecting trip durations to O’Hare Airport?
- Can data-driven insights help improve transport efficiency?

