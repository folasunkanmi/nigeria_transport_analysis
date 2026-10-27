# Nigeria Transport Data Analysis

**Data Analytics Case Study** | Jupyter Notebook • Python • Pandas • Data Visualization

Analysis of 240 inter-city trips across Nigeria focusing on fuel efficiency, revenue performance, delays, and customer satisfaction.

---

## Business Problem

Transport operators in Nigeria face rising fuel costs, frequent delays, and pressure to maintain customer satisfaction while remaining profitable.  
This project answers key operational questions:

- Which transport modes are most fuel-efficient?
- Which routes generate the highest revenue and profit?
- What factors drive trip delays?
- How do delays affect customer ratings?
- Where should management focus improvement efforts?

---

## Dataset Overview

| Detail                    | Description                                      |
|---------------------------|--------------------------------------------------|
| Records                   | 240 inter-city trips                             |
| Time Period               | January 2026                                     |
| Cities Covered            | Lagos, Abuja, Kano, Port Harcourt, Akure, Jos + others |
| Key Metrics               | Distance, Fuel Consumed, Revenue, Operating Cost, Delay, Customer Rating, Passenger Count |

---

## Analysis Performed

1. **Fuel Efficiency Analysis**  
   Compared fuel consumption per kilometre across different transport modes (BRT, Motorcycle, etc.).

2. **Revenue & Profitability Analysis**  
   Examined total revenue, operating profit (Revenue – Operating Cost), and best-performing routes.

3. **Delay Analysis**  
   Investigated average delays by city, weather conditions, road quality, and time of day (Morning/Evening Peak).

4. **Customer Experience Analysis**  
   Explored the relationship between trip delays and customer ratings.

5. **Exploratory Data Analysis (EDA)**  
   Data cleaning, missing value checks, outlier detection, and distribution analysis using Pandas.

---

## Key Insights

- **BRT buses** carry the highest passenger volume but consume more fuel overall.
- **Delays** are significantly higher during Evening Peak hours and on poor road conditions.
- **Lagos routes** generate the highest total revenue.
- Customer ratings drop sharply when delay exceeds **15 minutes**.
- Weather and road conditions are strong predictors of delay.

---

## Business Recommendations

1. **Prioritise road quality improvements** on high-delay routes to reduce late arrivals and improve ratings.
2. **Adjust scheduling** for Evening Peak periods — add buffer time or extra vehicles where delays are consistent.
3. **Focus retention & marketing efforts** on high-revenue Lagos corridors.
4. **Monitor fuel efficiency** closely for high-volume modes (especially BRT) and explore optimisation opportunities.
5. **Set a clear service standard**: aim to keep delays under 15 minutes to protect customer satisfaction.

---

## Tools Used

- **Python** (Pandas, NumPy)
- **Jupyter Notebook**
- **Matplotlib & Seaborn** for professional visualizations
- Data cleaning & Exploratory Data Analysis techniques

---

## How to Run

```bash
git clone https://github.com/folasunkanmi/nigeria_transport_analysis.git
cd nigeria_transport_analysis
pip install pandas matplotlib seaborn jupyter
jupyter notebook nigeria_transport_project.ipynb
```

Open the notebook and run all cells to reproduce the full analysis and visualizations.

---

## Project Structure

```
nigeria_transport_analysis/
├── README.md
├── Nigeria_Transport_Analytics_Dataset.csv
└── nigeria_transport_project.ipynb      # Full analysis notebook
```

---

## Author

**Folasunkanmi**  
Data Analyst & Aspiring Data Scientist  
Skills: Python • SQL • Excel • Power BI • Machine Learning • Jupyter  
GitHub: [folasunkanmi](https://github.com/folasunkanmi)

---

This project demonstrates the ability to turn raw operational data into clear business insights and actionable recommendations.
