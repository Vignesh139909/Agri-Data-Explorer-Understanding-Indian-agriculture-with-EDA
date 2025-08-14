# AgriData Explorer: Understanding Indian Agriculture with EDA

## 📌 Project Overview
**AgriData Explorer** is a data analysis and visualization project focused on understanding crop production, yields, and farming areas across India. Using **Python**, **SQL**, and **Power BI**, the project integrates district-level agricultural data from the ICRISAT dataset to provide actionable insights for **farmers**, **policymakers**, and **researchers**.

The goal is to enable stakeholders to make data-driven decisions by exploring historical and regional agricultural performance.

---

## 🎯 Problem Statement
India's agricultural sector is vital to the economy, yet agricultural data remains **complex, fragmented, and difficult to access**. This project creates an **interactive data visualization platform** that:
- Integrates state and district-level data.
- Offers insights into crop production, yields, and cultivation areas.
- Helps stakeholders identify **trends, gaps, and disparities**.
- Supports decision-making for crop optimization, resource allocation, and research.

---

## 💼 Business Use Cases

### **Farmers**
- Analyze historical crop performance to choose optimal crops per season.
- Identify productivity gaps and improve practices like irrigation and soil health.

### **Policymakers**
- Detect low-productivity regions for targeted subsidies or resources.
- Track fluctuating yields to improve crop insurance and risk policies.

### **Researchers**
- Study the impact of climate, soil, and irrigation on yields.
- Identify opportunities for innovation (e.g., high-yielding varieties).

---

## 🛠️ Approach

### **1. Data Collection & Cleaning**
- Data from **ICRISAT-District Level Data** and official reports.
- Standardized units, handled missing values, ensured consistency.

### **2. Exploratory Data Analysis (EDA)**
- Identified top-performing states & districts for major crops.
- Analyzed trends over 50 years for rice, wheat, sugarcane, and more.
- Compared crop yields across regions.

### **3. Visualization**
- Built **Python-based** EDA plots (matplotlib, seaborn, plotly).
- Developed **Power BI dashboards** with interactive filters and KPIs.
- Created **geospatial maps**, time-series graphs, and comparative charts.

### **4. Advanced Analytics**
- Machine learning models for:
  - Yield forecasting.
  - Best cultivation area prediction.
  - Crop diversification recommendations.

---

## 📊 Key EDA Insights
Some of the analyses performed:
- **Top 7 Rice Producing States** (bar plot).
- **Top 5 Wheat Producing States** & % share (bar + pie chart).
- **Oilseed & Sunflower Production Leaders**.
- **50-year trends** in sugarcane, millet, and sorghum production.
- **Rice vs. Wheat yield comparison**.
- **District-level deep dives** (e.g., Rice in West Bengal, Wheat in UP).
- Impact of cultivated area on production for major crops.

---

## 📂 Dataset Details
**Source:** ICRISAT-District Level Data

### Main Fields:
- **Identifiers**: District Code, State Code, District Name, State Name, Year.
- **Major Crops**: Rice, Wheat, Maize, Sugarcane, Cotton, Oilseeds, Soybean, Groundnut, Sunflower, etc.
- **Metrics per Crop**:
  - Area Cultivated (1000 ha)
  - Production (1000 tons)
  - Yield (kg/ha)
- **Other Fields**: Fruits, Vegetables, Potatoes, Onions, Fodder cultivation data.

---

## 📌 SQL-Based Analysis Examples
1. Year-wise trend of rice production for top 3 states.
2. Top 5 districts by wheat yield growth over last 5 years.
3. States with highest 5-year growth in oilseed production.
4. District-wise area vs. production correlation.
5. Yearly cotton production in top 5 cotton states.
6. Highest groundnut production districts in 2020.
7. Annual average maize yield per state.
8. Total oilseed cultivation area per state.
9. Highest rice yield districts.
10. 10-year wheat vs. rice production comparison for top 5 states.

---

## 📊 Power BI Dashboard Features
- **Interactive Filters**: Crop type, year, state, district.
- **Geospatial Heatmaps** for crop yields.
- **Trend & Comparative Charts**.
- **KPI Indicators** for production targets.
- **Dynamic Titles** that adapt to slicer selections.

---

## 📦 Deliverables
- **Python Scripts**: Data cleaning, EDA, and SQL integration.
- **SQL Database**: Structured and normalized agricultural dataset.
- **Power BI Reports**: Interactive dashboards & insights.
- **Documentation**: Project process, challenges, and learnings.

---

## 📈 Evaluation Metrics
- Data visualization clarity & accuracy.
- Dashboard speed & responsiveness.
- Completeness of dataset.
- User engagement & satisfaction.

---

## 🖥️ Tech Stack
- **Programming**: Python (pandas, matplotlib, seaborn, plotly)
- **Database**: MySQL / SQL
- **Visualization**: Power BI
- **Data Source**: ICRISAT-District Level Data

---

## 🚀 How to Run the Project

### **1. Python EDA**
```bash
pip install pandas numpy matplotlib seaborn plotly mysql-connector-python
jupyter notebook agri.ipynb

---

