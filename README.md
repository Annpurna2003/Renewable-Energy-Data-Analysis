# 🌱 Renewable Energy Usage & Cost Savings Analysis

## 📌 Project Overview
This project analyzes **renewable energy adoption, monthly energy usage, and cost savings** across households, regions, countries, and energy sources.  
The dataset contains **1,000 household-level records**, enabling insights into how renewable energy usage varies by geography, energy source, income level, and household characteristics.

A complete **end-to-end analytics pipeline** was built using **AWS, Snowflake, and Power BI**, from data storage to interactive dashboard visualization.

---

## 🏗️ Architecture & Data Pipeline
1. **AWS** – Used for raw data storage (CSV files)
2. **Snowflake** – Data warehousing, transformation, and analytical queries
3. **Power BI** – Interactive dashboards and data visualization

---

## 📊 Dashboard Highlights
The dashboards provide insights such as:
- **Total Monthly Energy Usage (KWH)** by region, country, and energy source  
- **Cost Savings (USD)** by region, country, and energy source  
- Comparison of **Wind, Solar, Hydro, Biomass, and Geothermal** energy sources  
- Identification of regions and countries with the **highest renewable energy impact**

---

## 📁 Dataset Information

- **Total Records:** 1,000 households  
- **Granularity:** Household-level  
- **Time Period:** Multi-year (2024–2026)  

### 🧾 Column Descriptions

| Column Name | Description |
|-------------|------------|
| **Household ID** | Unique identifier for each household |
| **Region** | Geographic region (Asia, Europe, Africa, North America, South America, Australia) |
| **Country** | Country of the household |
| **Energy Source** | Renewable energy type (Wind, Solar, Hydro, Biomass, Geothermal) |
| **Monthly Source KWH** | Monthly renewable energy consumption (KWH) |
| **Year** | Year of record |
| **Household_Size** | Number of household members |
| **Income Level** | Household income category (Low, Medium, High) |
| **Urban_Rural** | Urban or Rural household classification |
| **Adoption Year** | Year renewable energy was adopted |
| **Subsidy_Received** | Government subsidy received (Yes/No) |
| **Cost Savings** | Monthly cost savings from renewable energy usage (USD) |

---

## 🛠 Tools & Technologies Used
- **AWS (S3)** – Cloud storage for raw datasets  
- **Snowflake** – Data warehousing, SQL transformations, analytical querying  
- **Power BI** – Dashboard creation, DAX measures, and visualization  


---

## 📈 Key Insights
- **Wind energy** generates the highest overall usage and cost savings
- Regions with **early adoption years** show greater cumulative benefits
- **Subsidy-supported households** experience higher cost savings
- Urban households consume more energy, while rural households benefit strongly from renewable adoption

---

## 🎯 Use Cases
- Renewable energy adoption analysis  
- Sustainability and climate impact reporting  
- Energy policy and subsidy effectiveness analysis  
- Data Analyst / Business Analyst portfolio project  

---

## 🚀 Future Enhancements
- CO₂ emission reduction analysis  
- Time-series forecasting using historical data  
- Advanced Snowflake optimization (clustering, materialized views)  
- Integration with real-world government renewable datasets  

---





⭐ If you find this project helpful, please consider giving it a star!
