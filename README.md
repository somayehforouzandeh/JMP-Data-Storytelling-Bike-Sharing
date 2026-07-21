# 📊 Data Storytelling with JMP

<p align="center">
  <img src="Assets/JMP-Data-Storytelling-Banner.png" alt="Data Storytelling with JMP - Bike-Sharing Demand Analysis">
</p>

<h3 align="center">
  Bike-Sharing Demand Analysis through Visualization, Statistical Analysis, and Data Storytelling
</h3>

---

## 📌 Project Overview

This project presents a visual and statistical analysis of bike-sharing demand using **JMP**.

The analysis explores how user type, seasonality, weekly patterns, working days, weather conditions, and environmental factors influence bike-sharing demand.

The project follows a **data storytelling approach**, transforming analytical results into a clear and meaningful narrative.

---

## 🎯 Objectives

- Explore bike-sharing demand patterns
- Compare Registered and Casual user behavior
- Analyze seasonal and weekly demand patterns
- Compare working and non-working day demand
- Examine the impact of weather conditions
- Investigate the relationship between demand and environmental factors
- Apply regression analysis
- Communicate insights through data storytelling

---

## 🔍 Key Analytical Questions

- How do Registered and Casual users behave differently?
- How does demand change across seasons?
- What patterns appear throughout the week?
- Does demand differ between working and non-working days?
- How do weather conditions influence demand?
- Which environmental factor has the strongest relationship with demand?

---

## 📈 Key Insights

### 👥 User Behavior

Registered users generally demonstrate more stable and routine-oriented usage patterns, while Casual users show greater sensitivity to seasonality and environmental conditions.

### 📅 Time and Seasonality

Bike-sharing demand varies across seasons, days of the week, and working versus non-working days.

### 🌦️ Environmental Factors

Temperature demonstrates the strongest relationship with bike-sharing demand among the environmental variables analyzed.

Humidity also shows a meaningful relationship with demand, while wind speed demonstrates a comparatively weak relationship.

---

## 📊 Statistical Analysis

Regression analysis was used to evaluate the relationship between bike-sharing demand and selected environmental variables.

| Environmental Factor | R² | Approx. Variation Explained |
|---|---:|---:|
| Temperature | 0.211 | 21.1% |
| Humidity | 0.120 | 12.0% |
| Wind Speed | 0.008 | 0.8% |

> **Key Insight:** Temperature is the strongest environmental driver of bike-sharing demand among the variables analyzed.

The moderate R² values also indicate that bike-sharing demand is influenced by multiple factors rather than a single environmental variable.

---

## 🖼️ Visual Analysis

The project includes visualizations covering:

- User Type Distribution
- Seasonal Demand by User Type
- Working Day vs. Non-Working Day Demand
- Weekly Demand Patterns by User Type
- Weather Condition and User Demand
- Temperature and Bike-Sharing Demand
- Humidity and Bike-Sharing Demand
- Wind Speed and Bike-Sharing Demand
- Environmental Drivers of Bike-Sharing Demand
- Regression Analysis of Environmental Variables

📁 Explore the visual outputs in the [`Screenshots`](Screenshots) folder.

---

## 📄 Reports

### 🇬🇧 English Report

📄 [Data Storytelling with JMP](Report/Data_Storytelling_with_JMP.pdf)

### 🇮🇷 Persian Report

📄 [گزارش Data Storytelling با JMP](Report/Data-Storytelling-with-JMP-FA.pdf)

---

## 🛠️ Tools & Methods

### Tool

- **JMP**

### Methods

- Exploratory Data Analysis (EDA)
- Data Visualization
- Comparative Analysis
- Regression Analysis
- Statistical Interpretation
- Data Storytelling

---

## 📂 Project Structure

```text
JMP-Data-Storytelling-Bike-Sharing/
│
├── Assets/
│   └── JMP-Data-Storytelling-Banner.png
│
├── Data/
│
├── JMP-Analysis/
│
├── Report/
│   ├── README.md
│   ├── Data_Storytelling_with_JMP.pdf
│   └── Data-Storytelling-with-JMP-FA.pdf
│
├── Screenshots/
│
└── README.md
