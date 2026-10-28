# 🚗 Uber Trip Analysis — Power BI Dashboard & Booking Insights

*Analyzing 103K+ Uber bookings to understand booking trends, trip distances, revenue, payment preferences, and vehicle performance through an interactive Power BI dashboard.*

![Power BI](https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-F2C811?logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-EDA-blue)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Dashboard-orange)

## 1. 📌 Project Overview

Analyzed Uber trip data for June 2024 to evaluate booking performance, booking amounts, trip patterns, payment methods, and vehicle categories using an interactive dashboard.

## 2. 🎯 Business Questions & Objectives

- How do booking volumes and booking amounts vary over time?
- Which payment methods and trip types contribute most to booking value?
- Which vehicle categories generate the most bookings and revenue?
- What are the most frequent pickup and drop-off locations?
- How do trip distance and duration vary across bookings?

## 3. 📊 Key Findings & Insights

- **Total Bookings:** 103.73K bookings.
- **Total Booking Amount:** $1.55M.
- **Total Trip Distance:** 349K miles.
- **Average Trip Distance:** 3 miles.
- **Average Booking Amount:** $14.98.
- **Average Trip Time:** 16 minutes.
- **Vehicle Performance:** UberX led with approximately 38.7K bookings and $583.9K in booking value.
- **Payment Preferences:** Uber Pay accounted for approximately 70.7% of booking value.
- **Trip Type:** Day trips contributed 62.75% of booking value, compared with 37.25% for night trips.

## 4. 💡 Business Recommendations

- Monitor daily booking trends to identify fluctuations in demand.
- Evaluate vehicle-category performance to support fleet planning.
- Analyze pickup and drop-off hotspots to understand booking concentration.
- Compare day and night bookings to identify differences in trip activity.
- Track payment-method usage to understand customer payment preferences.

## 5. 🖼️ Dashboard Preview & Key Visuals

### Uber Trip Overview Dashboard

![Uber Trip Analysis Dashboard](Images/uber-trip-overview.png)

The interactive dashboard includes:

- **KPI Summary:** Bookings, booking amount, trip distance, average distance, average booking amount, and trip time.
- **Booking Trends:** Daily booking volumes across the selected period.
- **Payment Analysis:** Booking value by payment method.
- **Trip Type Analysis:** Day versus night booking value.
- **Vehicle Analysis:** Bookings, booking amount, average booking amount, and distance by vehicle.
- **Location Analysis:** Frequent pickup and drop-off points, location-level bookings, and preferred vehicles.

## 6. 🛠️ Tools & Technical Skills

- **Microsoft Power BI** — dashboard development and interactive reporting
- **Power Query** — data preparation and transformation, if used
- **DAX** — KPI calculations and measures, if used
- **Data Analysis & EDA** — identifying booking and trip patterns
- **Data Visualization** — KPI cards, trend charts, donut charts, and bar charts
- **Business Analysis** — interpreting booking and vehicle performance

## 7. ⚙️ Methodology & Analytical Workflow

1. Reviewed the trip dataset and its available fields.
2. Prepared and validated the data for analysis.
3. Developed KPIs for bookings, booking amounts, distances, and trip duration.
4. Analyzed trends by day, payment method, trip type, vehicle, and location.
5. Designed an interactive dashboard to present key metrics and comparisons.
6. Interpreted the findings and identified opportunities for further investigation.

## 8. 📂 Dataset Overview

| Attribute | Details |
|---|---|
| Analysis Period | 1–30 June 2024 |
| Total Bookings | 103.73K |
| Total Booking Amount | $1.55M |
| Total Trip Distance | 349K miles |
| Key Dimensions | Date, city, payment type, trip type, vehicle, pickup and drop-off location |
| Main Metrics | Bookings, booking amount, trip distance, average booking amount, trip time |

*Update the dataset filename, record count, and column details after verifying them against the source file.*

## 9. 📁 Repository Structure

```text
Uber Trip Analysis/
├── Data/
│   └── uber_trip_data.csv
├── Power BI Dashboard/
│   └── Uber Trip Analysis.pbix
├── Images/
│   └── uber-trip-overview.png
└── README.md
```

*Adjust the folder and filenames to match your final GitHub repository.*

## 10. 🚀 How to Run / Explore the Project

1. Clone or download the repository.
2. Open `Power BI Dashboard/Uber Trip Analysis.pbix` using Power BI Desktop.
3. Explore the dashboard pages and visualizations.
4. Use the date and city filters to investigate booking performance.
5. Select different metrics to compare payment, trip, vehicle, and location patterns.

## 11. ⚠️ Limitations & Assumptions

- The dashboard covers June 2024 only; findings may not generalize to other periods.
- Booking amount represents the reported booking value, not necessarily Uber's net revenue or profit.
- Dashboard percentages and averages depend on the underlying measure definitions.
- Observed patterns do not establish causation.
- Confirm the dataset source and redistribution permissions before publishing the raw data.