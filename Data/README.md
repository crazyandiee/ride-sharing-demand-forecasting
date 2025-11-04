# 📊 Data Folder

This folder contains datasets used for the NYC Taxi Demand Forecasting & Weather Impact Analysis project.

## Files Included
| File Name | Description |
|----------|-------------|
| NYC_Taxi_Weather_Jan2023.csv | Final processed dataset for Power BI dashboards. Includes hourly taxi demand, weather features, and engineered time variables. |

---

## 📌 Data Source
- NYC TLC — Yellow Taxi Trip Records  
- NOAA — Weather (Central Park Station)

Time period: **January 2023**

Merged & cleaned in Python before being imported into Power BI.

---

## 🧩 Data Dictionary

| Column | Description |
|--------|-------------|
| `pickup_hour` | Hour and date timestamp (feature for time-series) |
| `trip_count` | Count of taxi trips per hour |
| `tmpf` | Temperature in Fahrenheit |
| `relh` | Humidity (%) |
| `p01i` | Rain probability (0–1) |
| `weekday` | Numerical day of week (0=Mon … 6=Sun) |
| `WeekdayName` | Name of day — for visualization |
| `is_weekend` | 1 = Sat/Sun, 0 = Mon–Fri |

---

## 🔍 Usage
Used for:
✅ Power BI dashboards  
✅ Weather → Demand relationship analysis  
✅ Business insights & ML evaluation  
