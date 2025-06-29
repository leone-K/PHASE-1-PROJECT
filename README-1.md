
# ✈️ Aviation Risk Analysis

## 📌 Overview
This project analyzes U.S. aviation accident data to determine which aircraft types have the lowest risk for a new aviation business venture. The goal is to provide actionable insights based on past accident trends, severity of incidents, and geographic distribution.

## 🎯 Business Understanding
A new aviation division is evaluating which aircraft to purchase. To support this decision, we analyzed historical accident data to:
- Identify aircraft with the fewest and least severe accidents.
- Understand trends over time and across locations.
- Recommend safer aircraft models to reduce business risk.

## 📊 Data Understanding and Analysis
**Source:** U.S. National Transportation Safety Board  
**Period Covered:** 2015–2023  
**Key Fields:**
- `Aircraft_Type`
- `Event_Date`, `Year`
- `Injury.Severity`
- `Total.Fatal.Injuries`
- `Latitude`, `Longitude`

**Analysis Performed:**
- Total accidents by aircraft type
- Fatal vs non-fatal accident comparison
- Yearly trend of fatalities
- Injury breakdown by aircraft
- Geographic accident map
- Treemap and heatmaps for severity

Interactive dashboard created using Tableau Public.

## ✅ Conclusion
Aircraft such as **Boeing 737** and **Airbus A320** showed lower fatality rates per accident. These models are recommended based on consistent safety performance. Accident frequency alone does not indicate risk—severity and fatal injury ratio are more important.

## 📁 Files in this Repository
- `aviation_dashboard_sample.csv`: Cleaned sample dataset
- `aviation_risk_analysis_presentation.pptx`: Final presentation slides
- `aviation_risk_analysis_notebook.ipynb`: Data preparation and export notebook (Python)
- `README.md`: This documentation file

## 🔗 Tableau Dashboard
[View the interactive dashboard on Tableau Public](https://public.tableau.com/)

---
*Prepared by Leone Kamau | June 2025*
