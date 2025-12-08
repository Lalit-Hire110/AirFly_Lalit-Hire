# ✈️ AirFly – Airline Delay Analysis & Visualization Project

## 📌 Project Overview

**AirFly** is an end-to-end data analytics and visualization project focused on analyzing airline delays, cancellations, and seasonal trends using a large-scale real-world flight dataset.

The project covers the complete data lifecycle — from raw data ingestion and cleaning to advanced visual exploration and insight-driven reporting.

This project was completed as part of an **internship-style learning experience**, emphasizing structured analysis, feature engineering, visual storytelling, and professional documentation.

---

## 🎯 Objectives

- Analyze airline delay patterns across carriers, routes, airports, and seasons  
- Identify major delay and cancellation causes  
- Discover congestion-prone routes and peak delay periods  
- Create clear, insightful visualizations and dashboards  
- Present findings in a concise, professional manner  

---

## 🛠 Tech Stack

**Data Processing**
- pandas  
- numpy  

**Visualization**
- matplotlib  
- seaborn  
- plotly  
- folium  

**Dashboarding**
- Power BI  

**Documentation**
- Jupyter Notebook  
- GitHub README  

---

## 📊 Dataset

- **Source:** Delayed Flights Dataset – Kaggle  
- **Size:** 1,936,758 rows × 30 columns  

### Dataset Includes
- Airline and airport information  
- Delay durations and delay reasons  
- Cancellation indicators and categories  
- Time-based flight metadata  

This dataset enabled both **macro-level trend analysis** and **fine-grained operational insights**.

---

## ✅ Project Implementation Summary

### 🧩 Milestone 1: Data Foundation & Cleaning

- Loaded and explored large-scale CSV data using pandas  
- Audited schema, data types, memory usage, and null distributions  
- Identified missing value patterns:  
  - Delay-related columns: ~35.6%  
  - Time-related columns: <1%  
- Removed inconsistencies and ensured clean data structure  
- Optimized memory usage for efficient processing  

📘 **Implementation details:**  
`DelaydFlights_data_engineering.ipynb`

---

### ⚙️ Milestone 2: Preprocessing & Feature Engineering

- Handled null values in delay and cancellation columns  
- Converted and standardized datetime fields  
- Engineered new analytical features:
  - Month  
  - Day of week  
  - Hour of departure  
  - Route (Origin → Destination)  
- Created a reusable, preprocessed dataset for analysis and dashboards  

**Deliverables**
- Cleaned dataset  
- Feature dictionary  
- Reproducible preprocessing logic  

---

### 📈 Milestone 3: Visual Exploration & Delay Analysis

- Performed univariate and bivariate analysis to explore:
  - Top airlines and routes  
  - Flight distribution by time, day, month, and airport  

- Built diverse visualizations:
  - Bar charts  
  - Histograms  
  - Boxplots  
  - Line plots  

- Analyzed delay causes across:
  - Airlines  
  - Airports  
  - Time of day  

- Compared carrier, weather, and NAS delays to identify dominant factors  

📊 **Outcome:**  
Over **8 high-quality analytical visuals** with clear interpretations.

---

### 🗺️ Milestone 4: Route, Cancellation & Seasonal Insights

- Identified top 10 busiest origin–destination routes  
- Built delay heatmaps by airport and route  
- Used geographic maps to visualize:
  - Busiest airports  
  - Average delay intensity  

- Analyzed cancellation trends:
  - Monthly and seasonal patterns  
  - Breakdown by carrier, weather, security, and NAS  

- Highlighted increased delays and cancellations during:
  - Winter months  
  - Peak travel periods  

---

### 📊 Milestone 5: Reporting & Dashboarding

- Integrated all visuals into a cohesive analytical narrative  
- Developed an interactive **Power BI dashboard** for exploratory analysis  
- Ensured all plots followed best practices:
  - Clear titles  
  - Proper labels and legends  
  - Insight-focused design  

- Compiled findings into a structured README for project presentation  

---

## 📌 Key Insights

- Certain airlines and routes consistently contribute to the highest delay volumes  
- Weather and NAS delays dominate during peak and winter travel months  
- Specific airports act as systemic bottlenecks, increasing downstream delays  
- Cancellations show strong seasonal behavior, especially during extreme weather periods  

---

## 📂 Repository Structure

```bash
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── DelaydFlights_data_engineering.ipynb
├── visuals/
├── dashboard/
│   └── PowerBI_Report.pbix
└── README.md
