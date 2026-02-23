# EU Headline Inflation Analysis (2025)

## 📊 Project Overview
This project analyzes headline inflation (HICP – annual rate of change) for selected major EU economies in 2025.

Countries included:
- Germany
- France
- Spain
- Italy
- Netherlands

The goal was to explore average inflation levels and volatility across countries and discuss potential business implications.

---

## 📂 Dataset
Source: Eurostat  
Dataset: HICP – Monthly Data (Annual Rate of Change)  
Years analyzed: 2024–2025  

Raw dataset available in:
data/raw_eurostat_data.csv

---

## 🧹 Data Cleaning
- Removed unnecessary metadata columns
- Filtered for selected countries
- Converted year column to numeric format
- Restructured data into long format
- Created proper date column

---

## 📈 Key Analysis

### 1️⃣ Average Inflation (2025)

| Country      | Avg Inflation |
|-------------|--------------|
| France      | 0.93 |
| Italy       | 1.64 |
| Germany     | 2.27 |
| Spain       | 2.69 |
| Netherlands | 2.98 |

France shows the lowest average inflation in 2025, while the Netherlands shows the highest.

---

### 2️⃣ Volatility (Standard Deviation – 2025)

| Country      | Std Dev |
|-------------|---------|
| Germany     | 0.29 |
| France      | 0.30 |
| Italy       | 0.30 |
| Spain       | 0.42 |
| Netherlands | 0.48 |

The Netherlands exhibits the highest inflation volatility, while Germany shows the most stability.

---

## 📊 Dashboard

See dashboard visualization:

![Dashboard Screenshot](dashboard/dashboard_screenshot.png)
---

## 💡 Business Insights

- Lower inflation environments may create pricing flexibility.
- Higher volatility increases pricing risk.
- Stable inflation markets may support predictable margin planning.

---

## 🛠 Tools Used
- Google Sheets
- Pivot Tables
- Standard Deviation (STDEV)
- Dashboard Visualization
- Eurostat Public Data

---

## 👤 Author
Vahid Darzi  
Junior Data Analyst Portfolio Project – February 2026
