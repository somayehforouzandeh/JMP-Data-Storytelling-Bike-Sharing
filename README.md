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

* Explore bike-sharing demand patterns
* Compare Registered and Casual user behavior
* Analyze seasonal and weekly demand patterns
* Compare working and non-working day demand
* Examine the impact of weather conditions
* Investigate the relationship between demand and environmental factors
* Apply regression analysis
* Communicate insights through data storytelling

---

## 🔍 Key Analytical Questions

* How do Registered and Casual users behave differently?
* How does demand change across seasons?
* What patterns appear throughout the week?
* Does demand differ between working and non-working days?
* How do weather conditions influence demand?
* Which environmental factor has the strongest relationship with demand?

---

# 📊 Visual Analysis

## 👥 User Type Distribution

![User Type Distribution](Screenshots/User%20Type%20Distribution.png)

The distribution of demand reveals two distinct user profiles. Registered users account for a larger and more stable share of system usage, while Casual users show more variable behavior.

---

## 🌦️ Seasonal Demand by User Type

![Seasonal Demand by User Type](Screenshots/Seasonal%20Demand%20by%20User%20Type.png)

Demand increases during warmer seasons for both user groups. The response is stronger among Casual users, while Registered users remain comparatively active across seasons.

---

## 📅 Working Day vs. Non-Working Day Demand

![Working Day vs. Non-Working Day Demand](Screenshots/Working%20Day%20vs.%20Non-Working%20Day%20Demand.png)

Casual users are more active on non-working days, while Registered users show stronger demand on working days.

---

## 📈 Weekly Demand Pattern of Registered Users

![Weekly Demand Pattern of Registered Users](Screenshots/Weekly%20Demand%20Pattern%20of%20Registered%20Users.png)

Registered users show stronger demand during the middle of the working week, reflecting routine and commuting-oriented usage.

---

## 📈 Weekly Demand Pattern of Casual Users

![Weekly Demand Pattern of Casual Users](Screenshots/Weekly%20Demand%20Pattern%20of%20Casual%20Users.png)

Casual users show stronger demand around the beginning and end of the week, reflecting more flexible and leisure-oriented usage patterns.

---

## 🌦️ Weather Condition and User Demand

![Weather Condition and User Demand](Screenshots/Weather%20Condition%20and%20User%20Demand.png)

Both user groups prefer favorable weather conditions. Casual users show greater sensitivity to less comfortable conditions, while Registered users are more resilient.

---

## 🌡️ Temperature and Bike-Sharing Demand

![Temperature and Bike-Sharing Demand](Screenshots/Temperature%20and%20Bike-Sharing%20Demand.png)

Demand generally increases as temperatures become more favorable for cycling. Temperature is one of the strongest environmental drivers analyzed.

---

## 💧 Humidity and Bike-Sharing Demand

![Humidity and Bike-Sharing Demand](Screenshots/Humidity%20and%20Bike-Sharing%20Demand.png)

Higher humidity is associated with lower bike-sharing usage, particularly among Casual users.

---

## 💨 Wind Speed and Bike-Sharing Demand

![Wind Speed and Bike-Sharing Demand](Screenshots/Wind%20Speed%20and%20Bike-Sharing%20Demand.png)

Demand generally decreases as wind speed increases. However, wind speed has a weaker relationship with demand than temperature and humidity.

---

## 🌍 Environmental Drivers of Bike-Sharing Demand

![Environmental Drivers of Bike-Sharing Demand](Screenshots/Environmental%20Drivers%20of%20Bike-Sharing%20Demand.png)

Temperature shows the strongest relationship with demand, followed by humidity. Wind speed demonstrates the weakest relationship among the environmental variables analyzed.

---

## 📊 Regression Analysis: Temperature vs. Demand

![Regression Analysis Temperature vs Demand](Screenshots/Regression%20Analysis%20Temperature%20vs%20Demand.png)

Regression analysis provides statistical support for the relationship between temperature and bike-sharing demand.

---

## 📊 Regression Analysis: Humidity vs. Demand

![Regression Analysis Humidity vs Demand](Screenshots/Regression%20Analysis%20Humidity%20vs%20Demand.png)

Humidity also shows a meaningful relationship with demand, although its explanatory power is lower than that of temperature.

---

# 📈 Statistical Analysis

Regression analysis was used to evaluate the relationship between bike-sharing demand and selected environmental variables.

| Environmental Factor |    R² | Approx. Variation Explained |
| -------------------- | ----: | --------------------------: |
| Temperature          | 0.211 |                       21.1% |
| Humidity             | 0.120 |                       12.0% |
| Wind Speed           | 0.008 |                        0.8% |

> **Key Insight:** Temperature is the strongest environmental driver of bike-sharing demand among the variables analyzed.

The moderate R² values indicate that bike-sharing demand is influenced by multiple factors rather than a single environmental variable.

---

# 📌 Key Insights

### 👥 User Behavior

Registered users generally demonstrate more stable and routine-oriented usage patterns, while Casual users show greater sensitivity to seasonality and environmental conditions.

### 📅 Time and Seasonality

Bike-sharing demand varies across seasons, days of the week, and working versus non-working days.

### 🌦️ Environmental Factors

Temperature demonstrates the strongest relationship with bike-sharing demand among the environmental variables analyzed.

Humidity also shows a meaningful relationship with demand, while wind speed demonstrates a comparatively weak relationship.

---

# 🛠️ Tools & Methods

## Tool

* **JMP**

## Methods

* Exploratory Data Analysis (EDA)
* Data Visualization
* Comparative Analysis
* Regression Analysis
* Statistical Interpretation
* Data Storytelling

---

# 📄 Reports

### 🇬🇧 English Report

📄 [Data Storytelling with JMP](Report/Data_Storytelling_with_JMP.pdf)

### 🇮🇷 Persian Report

📄 [گزارش Data Storytelling با JMP](Report/Data-Storytelling-with-JMP-FA.pdf)

---

# 📂 Project Structure

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
│   ├── Environmental Drivers of Bike-Sharing Demand.png
│   ├── Humidity and Bike-Sharing Demand.png
│   ├── Regression Analysis Humidity vs Demand.png
│   ├── Regression Analysis Temperature vs Demand.png
│   ├── Seasonal Demand by User Type.png
│   ├── Temperature and Bike-Sharing Demand.png
│   ├── User Type Distribution.png
│   ├── Weather Condition and User Demand.png
│   ├── Weekly Demand Pattern of Registered Users.png
│   ├── Weekly Demand Pattern of Casual Users.png
│   ├── Wind Speed and Bike-Sharing Demand.png
│   └── Working Day vs. Non-Working Day Demand.png
│
└── README.md
```

---

# 💡 Final Insight

> **Data becomes more powerful when analysis is transformed into a story.**

This project demonstrates how visualization and statistical analysis can work together to reveal behavioral patterns, identify environmental drivers, and transform raw data into meaningful insights.

---

## 👩‍💻 Author

**Somayeh Forouzandeh**

Industrial Engineer | Business Intelligence | Data Analytics

---

⭐ Explore the visualizations and analytical reports to discover the key insights from this bike-sharing demand analysis.
