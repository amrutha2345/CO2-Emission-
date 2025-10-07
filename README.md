# CO2-Emission
# CO₂ Emissions Analysis of Vehicles in Canada

## Overview
This project analyzes vehicle CO₂ emissions in Canada using a dataset from [Kaggle](https://www.kaggle.com). The dataset contains **7,385 records** and **12 attributes**, covering vehicle specifications, fuel consumption, and CO₂ emissions.  

The goal of this project is to **explore patterns, trends, and relationships** between vehicle characteristics and their environmental impact.

---

## Dataset Description

| Column | Description |
|--------|-------------|
| Make | Manufacturer (42 unique values, e.g., Ford, Toyota, BMW) |
| Model | Specific vehicle model (2000+ unique models) |
| Vehicle Class | 16 categories (Compact, SUV, Pickup, Station Wagon, etc.) |
| Engine Size (L) | Engine capacity in liters (1.0L to 8.4L) |
| Cylinders | Number of engine cylinders (3–12) |
| Transmission | 27 types (manual/automatic with different gears) |
| Fuel Type | 5 types (Regular, Premium, Diesel, E85, CNG) |
| Fuel Consumption | City, Highway, Combined (L/100 km) |
| Fuel Consumption (mpg) | Combined fuel efficiency in miles per gallon |
| CO₂ Emissions (g/km) | Target variable, 100–400+ g/km |

**Data Quality:**
- No missing or null values  
- Balanced across classes and manufacturers  
- Reliable and consistent  

---

## Operations Performed

### Data Cleaning & Exploration
- Verified dataset shape `(7385, 12)`  
- Checked for missing/null values → None found  
- Summarized descriptive statistics for numerical columns  
- Extracted unique values for categorical columns  

### Descriptive Analytics
- Distribution of CO₂ emissions (histograms, boxplots)  
- Vehicle class distribution (bar chart)  
- Transmission types and fuel type frequencies  
- Fuel consumption distributions (city vs highway)  

### Relationship Analysis
- Engine Size vs CO₂ emissions → Positive correlation  
- Cylinders vs Fuel Consumption → Higher cylinders = higher fuel use  
- Transmission vs Fuel Economy → Modern automatics more efficient  
- Fuel Type vs CO₂ emissions → Alternative fuels produce lower emissions  

---

## Key Insights

### Vehicle & Market Demographics
- 42 manufacturers, wide representation  
- SUVs and Pickup Trucks dominate dataset  
- Two-Seaters & Subcompacts least common  

### CO₂ Emissions
- Range: ~100 g/km (hybrids) to 400+ g/km (large SUVs/pickups)  
- Average: ~250 g/km  
- Distribution skewed toward mid-range vehicles  

### Fuel Consumption Trends
- City fuel use higher than highway  
- Combined consumption: ~4 L/100 km (efficient hybrids) to 20+ L/100 km (large SUVs)  
- Mid-sized cars balance efficiency and performance  

### Engine & Transmission
- Larger engines → higher emissions  
- Vehicles with 6+ cylinders disproportionately contribute to emissions  
- Modern automatic transmissions provide better efficiency  

### Fuel Type Insights
- Regular & Premium gasoline dominate  
- Diesel moderately present, E85 and CNG rare  
- Alternative fuels produce lower emissions  

---

## Recommendations

### Environmental Policy
- Incentivize adoption of hybrids and alternative fuel vehicles  
- Consider stricter emission standards for SUVs and large pickups  

### Automotive Industry Strategy
- Improve efficiency in high-demand SUV and pickup segments  
- Focus on smaller engines + turbocharging instead of high-cylinder designs  

### Consumer Awareness
- Educate buyers on lifetime fuel cost and emissions impact  
- Promote fuel-efficient models in the Canadian market  

### Future Analytics Opportunities
- Predictive modeling for emissions based on engine/fuel configuration  
- Clustering to identify eco-friendly vs high-emission vehicles  
- Time-series trends (if multi-year data available)  

---

## Tools & Libraries
- **Python 3.x**  
- **Pandas, NumPy, Matplotlib, Seaborn**  
- **Jupyter Notebook**
