# U.S. Pollution Analysis (2006–2010) – Power BI Dashboard

## 📌 Problem
Air pollution is one of the biggest environmental challenges, affecting both health and climate.  
The U.S. Pollution dataset (2006–2010) contained thousands of rows of data across four pollutants:
- Carbon Monoxide (CO)
- Ozone (O3)
- Sulphur Dioxide (SO2)
- Nitrogen Dioxide (NO2)

The dataset was large and complex, making it difficult to understand at first glance.  
The challenge: **How can we transform this raw dataset into clear, interactive insights?**

---

## 💡 Solution & Features
I built a multi-page **Power BI Dashboard** with the following features:

- **Interactive Overview Page**  
  - Slicers for State, City, County  
  - Filled map of U.S. states showing pollutant spread  
  - Quarter-wise bifurcation of pollutants  
  - **Page Navigation buttons** → Overview links directly to pollutant-specific pages (CO, O3, SO2, NO2)

- **Pollutant-Specific Pages (CO, O3, SO2, NO2)**  
  - KPI Cards showing 1st max hour, max value, and pollutant units  
  - Top 10 states with highest pollutants  
  - Tables with conditional formatting (highest = red, lowest = green)  
  - Line charts showing AQI trends from 2006–2010  
  - Highlighting the city with the highest pollutant levels  

- **Sync Slicers**  
  - Date-based filtering across all pollutant pages  
  - Makes comparison easier between states and time periods  

---

## 📊 Key Insights
- **Mexicali** recorded the highest CO and O3 levels.  
- **Oklahoma** showed alarming spikes for SO2 and NO2.  
- Seasonal and yearly trends revealed persistent pollution levels across states between 2006–2010.  

---

## 🚀 Tools Used
- **Power BI Desktop**  
- Data cleaning (null → 0 replacement)  
- Interactive visuals (Maps, Slicers, KPI Cards, Line/Bar Charts, Conditional Formatting)  

---

## 📂 Files in this Repository
- [US Pollution Dashboard (PBIX)]https://drive.google.com/file/d/1v9JEsNi8K0fA4sXe6saC88ut2hZxVLnO/view?usp=sharing – Download the interactive Power BI file (open in Power BI Desktop).  

---


