## **📝 Data Analyst Tech Chanllenge - Oil & Gas Production Analysis**

### **📌 Overview**
Welcome to the **Data Analyst Tech Challenge**! Your objective is develop reports and visuals that tell a story with data. You will be performing various tasks of **data wrangling, querying, and analysis** using your preferred tools of choice such as (**SQL, python, or BI**).

This challenge will assess your ability to **perform exaploratory data analysis, understand requirements, and create visually compelling reports and visuals** while maintaining high-quality, structured, and reusable code.

This project focuses on analyzing oil and gas well data from the US Dept of Interior, Bureau of Ocean Energy Management. It includes identifying top-producing wells, mapping their performance, forecasting future production, evaluating operator trends, and assessing drilling efficiency.

---

## **💂️ Project Source Data**
[OgorA field definitions](https://www.data.boem.gov/Main/HtmlPage.aspx?page=ogorA)
```
📆 boem
 ├📄 Borehole.csv           # Well Header data file
 ├📄 ogora2010delimit.zip   # 2010 Monthly Production
 ├📄 ogora2011delimit.zip   # 2011 Monthly Production
 ├📄 ogora2012delimit.zip   # 2012 Monthly Production
 ├📄 ogora2013delimit.zip   # 2013 Monthly Production
 ├📄 ogora2014delimit.zip   # 2014 Monthly Production
 ├📄 ogora2015delimit.zip   # 2015 Monthly Production
 ├📄 ogora2016delimit.zip   # 2016 Monthly Production
 ├📄 ogora2017delimit.zip   # 2017 Monthly Production
 ├📄 ogora2018delimit.zip   # 2018 Monthly Production
 ├📄 ogora2019delimit.zip   # 2019 Monthly Production
 ├📄 ogora2020delimit.zip   # 2020 Monthly Production
 ├📄 ogora2021delimit.zip   # 2021 Monthly Production
 ├📄 ogora2022delimit.zip   # 2022 Monthly Production
 ├📄 ogora2023delimit.zip   # 2023 Monthly Production
 ├📄 ogora2024delimit.zip   # 2024 Monthly Production
 ├📄 ogora2025delimit.zip   # 2025 Monthly Production
```

---

## 📌 Project Objectives

- Identify top-producing wells over the past year
- Visualize well and operator performance
- Forecast future production
- Compare regional trends over five years
- Analyze drilling speed by operator
- Hint: Well Header can be joined to Monthly Production based on API Well Number

---

## ✅ Requirements

### 🔷 Top Producing Wells & Forecasting

1. **Identify Top Wells**
   - Determine the top 20 producing wells based on total production in the last 1 year.

2. **Map Production**
   - Generate a map showing the top 20 wells from step 1:
     - 📍 Point size = total production  
     - 🎨 Point color = `BH Total MD (feet)`

3. **Forecast Future Production**
   - Forecast the next 2 years of production for the top 20 wells from step 1 using historical data.
   - Present results with a time-series visualization.

---

### 🔷 Operator & Regional Trends

4. **Top Operators (Annual)**
   - Create a visual showing the top producing operators for the last 5 years in the Gulf of America.

5. **Monthly Drilling Activity**
   - Visualize the number of wells drilled per month in the last 5 years:
     - Based on **Spud Date**
     - Grouped by **operator** and **region**

6. **Regional Annual Production**
   - Compare total production by region over the last 5 years.

7. **Seasonal Trends**
   - Analyze and summarize the impact of **seasonality** on **monthly production** by region.

---

### 🔷 Drilling Efficiency Analysis

8. **Calculate Drilling Rates**
   - Using:
     - `Spud Date`
     - `Total Depth Date`
     - `BH Total MD (feet)`
   - Compute the average drilling rate (feet/day) for each well drilled in the last 5 years.

9. **Top Drilling Operators**
   - Identify the top 10 operators with the fastest average drilling rates.

---

## 📂 Deliverables

- 📊 Visualizations (maps, time-series, bar/line charts)
- 📁 Summary tables and insights
- 📈 Forecast plots
- 🧠 Written analysis for trends and recommendations

---

## 📝 Notes

- Ensure consistency in timeframes and regions.
- Include data cleaning, preprocessing, and validation steps in documentation.
- Clearly indicate any assumptions or limitations.

---

## 🛠️ Tools Suggested

- Python (Pandas, Matplotlib, Seaborn, Plotly)
- SQL (if working from a database)
- Jupyter Notebooks
- GIS tools (for mapping, e.g., Folium or GeoPandas)

---

## 📧 Contact

For questions or collaboration inquiries, feel free to reach out.
