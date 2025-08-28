# 🌾 Rainfall Impact on Agricultural Productivity – Power BI Dashboard

## 📌 Project Overview  
This project analyzes the relationship between **rainfall patterns** and **agricultural productivity** across Indian states (1966–2017).  
The goal was to build an **interactive Power BI dashboard** that helps stakeholders understand how rainfall variability affects crop yields and provides **data-driven recommendations** for agricultural planning.

---

## 🎯 Objectives  
- Explore historical **rainfall and crop yield data**  
- Establish **data models and transformations** using Power BI  
- Visualize **rainfall trends, crop yield patterns, and correlations**  
- Provide **strategic insights & recommendations** for better agricultural planning  

---

## 📂 Dataset  
- **File:** `rain-agriculture.csv`  
- **Time Period:** 1966 – 2017  
- **Key Fields:**  
  - `State Name` – Indian states  
  - `Year` – Observation year  
  - `Rainfall (Jun, Jul, Aug, Sep)` – Monsoon rainfall (mm)  
  - `Rice Area (1000 ha)` – Cultivation area under rice  
  - `Crop Yield (Kg/ha)` – Productivity values  

---

## 🔧 Project Workflow  

### 1. Data Exploration & Cleaning
- Imported dataset into Power BI  
- Handled missing values, duplicates, and anomalies  
- Standardized formats for consistency  

### 2. Data Modeling & DAX
- Created calculated measures for:
  - Total & Average Rainfall  
  - Crop Yield (Min, Max, Average)  
- Built time-based aggregations (monthly, yearly)  

### 3. Analysis
- Examined **temporal rainfall trends**  
- Studied correlation between **rainfall & crop yield**  
- Identified **state-wise and seasonal variations**  

### 4. Dashboard Development
Designed an interactive dashboard with:  
- 📈 Line Charts – Rainfall trends (1966–2017)  
- 📊 Bar Charts – Rainfall vs Crop Yield  
- 🔵 Scatter Plots – Rainfall vs Productivity correlation  
- 🗺️ Geographic Maps – Crop yield distribution across states  
- 🎛️ Filters & Slicers – Year, Month, Crop Type, State  

### 5. Insights & Recommendations
- Extracted **key findings** (e.g., rainfall decline in northern states, irrigation-driven yields in Punjab/Haryana)  
- Suggested **strategic recommendations** for crop planning, water management, and policy actions  

---

## 📊 Dashboard Snapshots  

### 🌧️ Rainfall Trends  
<img width="1300" height="726" alt="image" src="https://github.com/user-attachments/assets/5d6b4709-dcf0-4cf7-840c-35203b7fdaba" />

### 🌾 Crop Yield Analysis  
<img width="1304" height="731" alt="image" src="https://github.com/user-attachments/assets/27065abd-6020-4a92-8b19-0a8f8b425c78" />

### 🗺️ Geographic Crop Spread  
<img width="1300" height="725" alt="image" src="https://github.com/user-attachments/assets/aa480790-c300-4fe0-a64f-ba6689e7485c" />

### 📉 Rainfall vs Yield Correlation  
<img width="1302" height="733" alt="image" src="https://github.com/user-attachments/assets/e70f7b91-b753-40f2-aed2-d7e0b63a7c70" />

---

## 🔍 Key Insights  
- Annual rainfall has **declined in northern states** post-2000 with high year-to-year variability  
- Rice yield in **irrigation-dominant states** (Punjab, Haryana) remains stable despite rainfall fluctuations  
- **Eastern states** (Bihar, Odisha, West Bengal) show stronger dependence on rainfall  
- **Wheat & Barley** dominate northern states, while **maize & sorghum** are significant in central/southern states  

---

## 🛠️ Strategic Recommendations  
1. **Crop Planning & Diversification** – Promote drought-tolerant varieties & diversify in high-risk states  
2. **Irrigation & Water Management** – Expand irrigation, adopt micro-irrigation & rainwater harvesting  
3. **Season-specific Actions** – Improve forecast-based advisories & crop insurance linked to rainfall  
4. **Policy & Extension** – Subsidize irrigation equipment, train farmers on adaptive crop planning  

---

## 📌 Tools & Technologies  
- **Power BI** – Data visualization & dashboard creation  
- **DAX** – Calculated measures & aggregations  
- **Dataset** – Rainfall & agriculture data (1966–2017)  

---

## 🚀 How to Use  
1. Clone this repository  
2. Open the `.pbix` file in Power BI Desktop  
3. Use slicers to explore rainfall & crop yield trends by **state, year, and crop type**  

---
