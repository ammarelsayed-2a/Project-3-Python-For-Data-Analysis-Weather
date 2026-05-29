# Project-3-Python-For-Data-Analysis-Weather
End-to-end EDA project on hourly weather data (Canada 2012) | Exploring temperature, visibility, wind, and precipitation patterns using Python, Pandas, Matplotlib &amp; Seaborn

# 🌦️ Exploratory Data Analysis — Weather Dataset

A structured EDA project on hourly weather observations from Canada (2012), completed as part of the **Python for Data Analysis** course.

## 📌 Objective
Explore weather patterns across all seasons, answer 15 analytical questions, and uncover key relationships between temperature, visibility, wind speed, humidity, and pressure.

## 📂 Dataset
- **Source:** Hourly Weather Observations — Canada 2012
- **Records:** 8,784 hourly readings
- **Features:** Date/Time, Temp_C, Dew Point Temp_C, Rel Hum_%, Wind Speed_km/h, Visibility_km, Press_kPa, Weather_Condition

## 🛠️ Tools & Libraries
| Library | Purpose |
|---|---|
| Pandas | Data loading, cleaning, and exploration |
| Matplotlib | Base plotting |
| Seaborn | Statistical visualizations |

## 📊 Analysis Structure
1. Imports & Setup
2. Load Dataset
3. First Look (head / tail)
4. Data Structure & Info
5. Data Quality Check
6. Descriptive Statistics
7. Column Renaming
8. Categorical Exploration
9. Analytical Questions (Q1 → Q15)
10. Visualizations
    - Univariate (Numerical + Categorical)
    - Bivariate (Num vs Num · Num vs Cat · Cat vs Cat)
    - Multivariate
    - Correlation Heatmap
    - Pairplot
11. Key Insights

## 💡 Key Insights
- Temperature and Dew Point are strongly correlated — near-linear relationship
- Fog and Snow produce the lowest visibility values in the dataset
- Winter dominates with extreme conditions; Summer is mostly clear
- Wind speed has minimal effect on visibility despite common assumption
- Pressure is the most stable variable — changes very slowly hour-to-hour
- High humidity consistently appears in foggy and rainy conditions

## 🚀 How to Run
```bash
git clone https://github.com/ammarelsayed-2a/Project-3-Python-For-Data-Analysis-Weather.git
cd Project-3-Python-For-Data-Analysis-Weather
jupyter notebook "Project 3 Weather.ipynb"
```

## 👤 Author
**Ammar Elsayed** — Python for Data Analysis | 2026  
[LinkedIn](https://www.linkedin.com/in/ammar-elsayed-ibrahim)
