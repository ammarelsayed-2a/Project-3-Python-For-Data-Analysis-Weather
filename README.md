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
12. Key Insights

---

## ❓ 15 Analytical Questions

### Q1 — Find all unique Wind Speed values
Find all distinct wind speed measurements recorded in the dataset.

### Q2 — How many times was weather exactly 'Clear'?
Count the total occurrences of clear weather conditions.

### Q3 — How many times was Wind Speed exactly 4 km/h?
Count records where wind speed equals 4 km/h precisely.

### Q4 — Find all missing (null) values in the data
Identify and count all empty cells across all columns.

### Q5 — Rename 'Weather' column to 'Weather_Condition'
Clean up column naming for clarity and avoid ambiguity.

### Q6 — What is the mean Visibility?
Calculate the average visibility across all hourly readings.

### Q7 — What is the standard deviation of Pressure?
Measure how much atmospheric pressure fluctuates in this dataset.

### Q8 — What is the variance of Relative Humidity?
Quantify the spread of humidity values throughout the year.

### Q9 — Find all instances where Snow was recorded
Filter and display all records with snow conditions.

### Q10 — Wind Speed > 24 AND Visibility = 25
Find records meeting BOTH conditions simultaneously.

### Q11 — Mean value of each column per Weather Condition
Group data by weather condition and calculate averages for all metrics.

### Q12 — Min and Max values per Weather Condition
Find extreme values (lowest and highest) for each weather type.

### Q13 — All records where Weather Condition is 'Fog'
Display all foggy weather observations in the dataset.

### Q14 — Weather is 'Clear' OR Visibility > 40
Find records satisfying either condition (using OR operator).

### Q15 — Complex filtering: (Clear AND Humidity > 50) OR Visibility > 40
⚠️ **Operator Precedence:** Demonstrates the importance of parentheses in conditional logic.  
Find records that are either:
- Clear weather AND relative humidity exceeds 50%, OR
- Visibility is above 40 km

---

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
