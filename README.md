# Wildfire-Severity-Analysis
Wildfire severity analysis using environmental data 

## Project Overview
Analysis of environmental factors affecting wildfire severity using the Forest Fires dataset (Montesinho Park, Portugal).

## Objective
To analyse environmental factors such as temperature, humidity, wind, and rainfall to understand: 
    • What conditions increase wildfire risk  
    • What factors influence how severe a wildfire becomes 

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

## Dataset
517 records of wildfire events with 13 variables, including temperature, humidity, wind, rainfall, and FWI indices.

## Key Findings
- August and September account for the majority of all fires
- High risk conditions (temp > 25°C + humidity < 30%) produce fires 7.4x more destructive than normal
- DC (Drought Code) is the strongest predictor of fire severity
- Rain has minimal impact due to near-zero values during the fire season
- Weekend fire patterns suggest human ignition sources

## Recommendations
1. Seasonal resource allocation
2. Drought index early warning system
3. High-risk condition alerts
4. DC monitoring system
5. Public awareness campaign

## Project Structure
- Forest_Fire_2.ipynb — Main analysis notebook
- forestfires.csv — Original dataset
- forestfires_clean.csv — Cleaned dataset
- forestfires_engineered2.csv — Feature-engineered dataset
