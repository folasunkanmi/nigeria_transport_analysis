# Nigeria Transport Operations – Business Report

**Prepared by:** Folasunkanmi  
**Role:** Data Analyst  
**Date:** October 2026  
**Project:** Inter-City Transport Performance Analysis

---

## 1. Executive Summary

This report analyses 240 inter-city trips across major Nigerian cities. The goal is to understand fuel efficiency, revenue performance, causes of delays, and the impact of delays on customer satisfaction.

**Key Finding:** Delays above 15 minutes significantly reduce customer ratings. Road conditions and Evening Peak periods are the strongest drivers of delay.

**Top Recommendation:** Focus improvement efforts on road quality and Evening Peak scheduling to protect both customer satisfaction and profitability.

---

## 2. Dataset & Scope

- **Records analysed:** 240 trips  
- **Columns:** 23  
- **Period:** January 2026  
- **Cities:** Lagos, Abuja, Kano, Port Harcourt, Akure, Jos and others  
- **Nature of data:** Demonstration / sample dataset designed to reflect realistic operational patterns. It is **not** verified data from a live transport company.

---

## 3. Methodology

1. Data cleaning and quality checks (missing values, outliers, data types)
2. Creation of key metrics (fuel efficiency, operating profit, delay categories)
3. Exploratory analysis by transport mode, route, weather, road condition, and time of day
4. Visual analysis of relationships (especially Delay vs Customer Rating)
5. Translation of findings into practical business recommendations

Tools used: Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook.

---

## 4. Key Insights

### Fuel & Operations
- BRT and higher-capacity modes carry more passengers but have higher total fuel consumption.
- Fuel efficiency varies noticeably across transport modes.

### Revenue
- Lagos routes consistently generate the highest revenue.
- Profitability is strongly influenced by both passenger volume and operating costs.

### Delays
- Delays are highest during **Evening Peak** periods.
- Poor road conditions and adverse weather significantly increase average delay.

### Customer Satisfaction
- Customer ratings drop sharply once delay exceeds **15 minutes**.
- There is a clear negative relationship between delay duration and rating.

---

## 5. Business Recommendations

| Priority | Recommendation                                      | Expected Benefit                          |
|----------|-----------------------------------------------------|-------------------------------------------|
| High     | Improve road quality on high-delay corridors        | Lower delays → higher ratings & retention |
| High     | Add buffer time / extra capacity in Evening Peak    | Reduced lateness during critical hours    |
| Medium   | Focus commercial efforts on Lagos high-revenue routes | Maximise revenue growth                 |
| Medium   | Set internal service standard: Delay < 15 mins      | Protect customer satisfaction             |
| Medium   | Monitor fuel intensity by mode regularly            | Cost control and efficiency gains         |

---

## 6. Next Steps for Management

1. Validate these findings with live operational data.
2. Create a simple Power BI or Excel dashboard for ongoing monitoring.
3. Pilot scheduling changes on the worst-performing Evening Peak routes.
4. Track the impact of any road improvement initiatives on delay and ratings.

---

## 7. Conclusion

This analysis shows that relatively small operational improvements — especially around road conditions and peak-hour scheduling — can have a meaningful impact on both customer experience and business performance.

The combination of clear metrics, visual evidence, and actionable recommendations makes this a practical foundation for decision-making.

---

**Prepared by Folasunkanmi**  
Data Analyst | Python • SQL • Excel • Power BI • Machine Learning
