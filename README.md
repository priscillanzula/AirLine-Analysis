# ✈️ Airline Delay Analysis Dashboard

## 📌 Overview
This interactive Power BI dashboard delivers deep insights into U.S. domestic airline operations, focusing on flight **delays**, **cancellations**, and **diversions**. With powerful filters and dynamic visuals, users can explore delay patterns, identify high-risk airports, and compare airline performance metrics over time.

---

## 🔍 Dashboard Highlights

### 🚦 Key Performance Indicators
- **Average Delay Per Flight**: 22.35 minutes  
- **Total Delay Minutes**: 22 million  
- **Total Flights Analyzed**: ~997,000  
- **Cancelled Flights**: 10,000  
- **Diverted Flights**: 2,000  

### 📊 Visualizations
1. **Quick View Filter**  
   - Dashboard-wide slicer to filter by airline, airport, or time period  
2. **Total Flights by Airline**  
   - Bar chart comparing flight volume per carrier (e.g., Southwest Airlines leading)  
3. **Cancelled & Diverted Flights**  
   - Comparative bar chart by airline  
4. **Monthly Delay Trends**  
   - Line chart illustrating seasonal delay fluctuations  
5. **Top 10 Airports with Most Delays**  
   - Ranked bar chart of high-delay airports  
6. **Delay Breakdown by Reason**  
   - Donut chart visualizing delay causes (weather, carrier, NAS, etc.)  

---

## 📁 Data Sources
The dashboard uses publicly available airline performance data, which includes:
- Flight delay minutes by reason  
- Airline and airport metadata  
- Monthly flight statistics across the U.S. domestic network  

---

## ⚙️ Technical Implementation

Built in **Power BI**, the dashboard leverages:
- **Power Query** for cleaning and transforming raw CSV data  
- **Unpivoted columns** to reshape delay reason fields  
- **Calculated measures** using DAX for KPIs like delay rates  
- **Table relationships** to link flights, airlines, and airports  
- **Visual-level filters** for more flexible drilldowns  

---

## 💡 Insights & Key Findings

- **Carrier & Weather Delays** account for ~36% of all delays  
- **Dallas Fort Worth (DFW)** consistently ranks as a high-delay airport  
- **Southwest Airlines** handles the most flights but also shows a high cancellation rate  
- **Clear seasonal patterns**: Delays spike during peak travel months  

---

## 🚀 How to Use

1. Clone or download this repo:
   ```bash
   https://github.com/priscillanzula/AirLine-Analysis.git
Open the .pbix file using Power BI Desktop

Explore the dashboard using filters to drill into specific airlines, airports, or months

Optionally replace data sources with your own for custom analysis


## 🔧 Requirements
Power BI Desktop (latest version recommended)

Basic understanding of data modeling and airline performance metrics

## 🔮 Future Enhancements

1. Geographic map visualizations for regional delay heatmaps

2. Predictive modeling for expected delay risk

3. Integration with real-time or near-real-time flight data

4. Deeper analysis into passenger impact and compensation

## 🙌 Acknowledgments

Built as a personal project to demonstrate Power BI skills, storytelling with data, and domain knowledge in aviation analytics.
Inspired by real-world airline data and industry reporting needs.



📄 License
This project is licensed under the MIT License.
