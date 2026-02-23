# PROJECT LOG — EU Headline Inflation Analysis (2025)

## 1. Objective

To analyze headline inflation (HICP – YoY) across selected major EU economies in 2025 and assess average inflation levels and volatility to evaluate pricing stability.

Countries selected:
- Germany
- France
- Spain
- Italy
- Netherlands

Rationale:
These countries represent major EU economies with significant population and market impact.

---

## 2. Data Source

Source: Eurostat  
Dataset: HICP – Monthly Data (Annual Rate of Change)  
Code: prc_hicp_manr  
Years analyzed: 2024–2025  

Reason for choosing this dataset:
- Official harmonized EU inflation metric
- Comparable across countries
- Public and widely recognized economic indicator

---

## 3. Data Cleaning Process

Steps performed:

1. Removed metadata columns:
   - DATAFLOW
   - LAST UPDATE
   - freq
   - unit
   - OBS_FLAG
   - CONF_STATUS

2. Filtered for:
   - COICOP: All-items HICP
   - Monthly frequency
   - Annual rate of change

3. Restructured dataset:
   - Converted wide format to long format
   - Created columns:
     - Country
     - Month
     - Inflation_YoY
     - Year
     - Month_Number
     - Date

4. Converted Year column to numeric format to ensure pivot compatibility.

---

## 4. Key KPIs Built

1️⃣ Average Inflation (2025)

Calculated mean inflation for each country to compare pricing pressure levels.

2️⃣ Inflation Volatility (2025)

Calculated standard deviation of monthly inflation values to measure stability.

Rationale:
Standard deviation provides a simple and interpretable measure of variability.

---

## 5. Analytical Decisions

- Focused on 2025 to provide recent and actionable insight.
- Used YoY inflation instead of MoM to reduce short-term noise.
- Selected headline inflation for public comparability.

---

## 6. Key Findings

- France showed lowest average inflation.
- Netherlands exhibited highest volatility.
- Germany demonstrated strongest stability.

---

## 7. Business Interpretation

- Higher volatility increases pricing risk.
- Stable markets support predictable margin planning.
- Inflation level alone does not determine business attractiveness.

---

## 8. Tools Used

- Google Sheets
- Pivot Tables
- STDEV
- Dashboard design
- Eurostat open data
