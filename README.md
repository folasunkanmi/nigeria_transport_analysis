# Nigeria Transport Data Analysis

**Data Analytics Case Study** | Jupyter Notebook • Python • Pandas • Data Visualization

Analysis of **240 inter-city trips** across Nigeria focusing on fuel efficiency, revenue performance, delays, road conditions, and customer satisfaction.

---

## Business Problem

Transport operators in Nigeria face rising fuel costs, frequent delays, and pressure to maintain customer satisfaction while remaining profitable.  
This project answers practical operational questions:

- Which transport modes are most fuel-efficient?
- Which routes generate the highest revenue and profit?
- What factors drive trip delays?
- How do delays affect customer ratings?
- Where should management focus improvement efforts?

---

## Dataset Information

| Detail              | Description                                      |
|---------------------|--------------------------------------------------|
| Records             | 240 inter-city trips                             |
| Columns             | 23                                               |
| Time Period         | January 2026                                     |
| Cities Covered      | Lagos, Abuja, Kano, Port Harcourt, Akure, Jos + others |
| Key Metrics         | Distance, Fuel Consumed, Revenue, Operating Cost, Delay, Customer Rating, Passenger Count |

**Dataset Origin**: This is a **demonstration / sample dataset** created for analytical practice. It is designed to reflect realistic patterns in Nigerian inter-city transport operations but should **not** be treated as verified real operational data from any specific transport company.

---

## Methodology

1. **Data Understanding & Cleaning**  
   Loaded the dataset, checked for missing values, data types, and outliers using Pandas.

2. **Feature Engineering**  
   Created useful metrics such as fuel efficiency (litres per km), operating profit, and delay categories.

3. **Exploratory Data Analysis (EDA)**  
   Analysed distributions, correlations, and patterns across transport modes, routes, weather, and road conditions.

4. **Visualization**  
   Created clear charts to show relationships between delays, revenue, fuel use, and customer satisfaction.

5. **Insight Generation & Recommendations**  
   Translated findings into practical business recommendations for transport operators.

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
3. **Focus commercial attention** on high-revenue Lagos corridors.
4. **Monitor fuel efficiency** closely for high-volume modes (especially BRT).
5. **Set a clear service standard**: aim to keep delays under 15 minutes to protect customer satisfaction.

---

## Visualizations

The Jupyter Notebook contains multiple professional charts, including:

- Fuel efficiency by transport mode
- Revenue and profit by route
- Delay distribution by time of day and road condition
- Relationship between delay and customer rating
- Occupancy and performance comparisons

All visualizations are generated inside the notebook when you run it.

---

## How to Run the Notebook

### Option 1: Local Setup (Recommended)

```bash
# 1. Clone the repository
git clone https://github.com/folasunkanmi/nigeria_transport_analysis.git
cd nigeria_transport_analysis

# 2. Create and activate a virtual environment (optional but recommended)
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS / Linux:
source venv/bin/activate

# 3. Install required packages
pip install pandas numpy matplotlib seaborn jupyter

# 4. Launch Jupyter
jupyter notebook
```

Then open `nigeria_transport_project.ipynb` and run all cells (**Cell → Run All**).

### Option 2: Google Colab
1. Upload the notebook and CSV to Google Colab
2. Run the cells in order

---

## Project Structure

```
nigeria_transport_analysis/
├── README.md
├── REPORT.md                            # Polished business report
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

This project demonstrates the ability to analyse operational data, generate clear insights, and provide actionable recommendations that support business decisions.
