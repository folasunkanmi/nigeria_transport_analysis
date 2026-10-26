# Nigeria Transport Analysis

## Overview
Analysis of 240 inter-city trips across Nigeria focusing on operational efficiency, profitability, and service quality. This project explores how distance, weather, road conditions, and transport modes affect fuel consumption, revenue, delays, and customer satisfaction.

## Dataset
- Source: Nigeria_Transport_Analytics_Dataset.csv (240 rows, 23 columns)
- Period: January 2026
- Cities Covered: Lagos, Kano, Abuja, Port Harcourt, Akure, Jos + 7 others
- Key Columns: Distance_km, Fuel_Consumed_L, Total_Revenue_NGN, Delay_min, Transport_Mode, Passenger_Count, Customer_Rating

## Key Analysis Performed
1. Fuel Efficiency: Fuel consumption per km by transport mode (BRT vs Motorcycle vs others)
2. Revenue Analysis: Total revenue, profit margin (Revenue - Operating Cost), best performing routes
3. Delay Analysis: Average delay by city, weather, road condition, and travel period (Morning/Evening Peak)
4. Customer Experience: Correlation between delay and customer rating
5. EDA: Checked missing values, outliers, distributions using Pandas

## Key Insights
- BRT buses carry highest passenger volume but consume more fuel
- Delays are highest during Evening Peak and poor road conditions
- Lagos routes generate highest revenue
- Customer ratings drop significantly when Delay > 15 mins

## Tools Used
- Python, Pandas, NumPy
- Matplotlib / Seaborn for visualization
- Jupyter Notebook

## How to Run
pip install pandas matplotlib seaborn
Open nigeria_transport_project.ipynb
