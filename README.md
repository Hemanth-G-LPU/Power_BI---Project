# 🌤️ Weather Dashboard — Power BI + WeatherAPI

An interactive, visually rich **Weather Monitoring Dashboard** built in **Power BI**, powered by real-time data from [WeatherAPI.com](https://www.weatherapi.com/). It combines current conditions, a 7-day forecast, air quality, and rain probability into a single dark-themed, data-storytelling dashboard.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![WeatherAPI](https://img.shields.io/badge/Data-WeatherAPI.com-1a73e8?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)

---

## 📖 Table of Contents
- [Preview](#-preview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Data Source](#-data-source)
- [Project Structure](#-project-structure)
- [How It Works](#-how-it-works)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Enhancements](#-future-enhancements)
- [Documentation](#-documentation)
- [Author](#-author)

---

## 📸 Preview

![Weather Dashboard Overview](./images/Weather_Dashboard.png)

*Full dashboard view: current conditions, 7-day forecast, sunrise/sunset, air quality index, and rain probability for Aurangabad.*

---

## 🔧 Features

- 🌍 **Current Weather** — city, temperature, condition, humidity, wind, visibility
- 📈 **7-Day Forecast** — line chart with daily icons and temperatures
- 🌅 **Sunrise & Sunset** times
- 💨 **Air Quality Index** — PM2.5, PM10, CO, O3, NO2, SO2 with a health status gauge
- 🌧️ **Daily Rain Probability** (%)
- ⚡ **UV Index, Pressure & Wind Speed** cards
- 📱 **Interactive City Switching** (e.g., Aurangabad ↔ Satara ↔ Pune ↔ Nagpur)

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Data Source | [WeatherAPI.com](https://www.weatherapi.com) (`/current.json`, `/forecast.json`) |
| ETL / Modeling | Power Query, DAX |
| Visualization | Power BI Desktop |
| Format | JSON → Power BI data model |

---

## 🌐 Data Source

**WeatherAPI.com** — a free weather API providing current conditions and forecast data in JSON format.

- Endpoints used: `/current.json` and `/forecast.json`
- Data pulled with an API key and loaded into Power BI via the **Web connector**
- Key fields: temperature, humidity, wind speed, AQI components, sunrise/sunset, rain probability, UV index, pressure, visibility

---

## 📁 Project Structure

```
Power_BI---Project/
├── weather_dashboard.pbix   # Main Power BI dashboard file
├── images/                  # Dashboard screenshot used in this README
│   └── Weather_Dashboard.png
├── data/                    # Sample/exported weather data (if included)
└── README.md
```

---

## ⚙️ How It Works

1. Weather data is fetched from WeatherAPI.com using an API key.
2. Data is imported into Power BI via Power Query and cleaned (null handling, format standardization).
3. Calculated columns and DAX measures are built for KPIs like AQI category, rain probability, and forecast trends.
4. The report is laid out into a single dark-themed dashboard page with cards, a line chart, a radial gauge, and a city slicer for interactivity.

To explore it yourself:
1. Get a free API key from [WeatherAPI.com](https://www.weatherapi.com).
2. Open `weather_dashboard.pbix` in Power BI Desktop.
3. Update the Web connector query with your API key.
4. Refresh the data.

---

## 🧠 Skills Demonstrated

- ✅ Data Integration using a REST API
- ✅ Power BI data model design
- ✅ Dashboard design principles (layout, color, UX)
- ✅ Custom KPIs, DAX measures, and cards
- ✅ Weather & AQI interpretation
- ✅ Slicing and forecast visualization

---

## 💡 Future Enhancements

- Add more cities via slicer/dropdown
- Auto-refresh with a scheduled API fetch
- Historical weather trend analysis (subject to API support)
- AI-based weather prediction
- Real-time, always-on dashboard hosting

---

## 📄 Documentation

A full project report covering the ETL process, data source, and analysis is included in this repo, written as part of the INT 387 course at Lovely Professional University.

📢 [Project post on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7452782074182152192/)

---

## 👤 Author

**Hemanth Gummadidala**
B.Tech CSE, Lovely Professional University

- 📧 Email: hemanthgummadidala29@gmail.com
- 🔗 LinkedIn: [hemanth-gummadidala](https://www.linkedin.com/in/hemanth-gummadidala-617037333/)
- 💻 GitHub: [Hemanth-G-LPU](https://github.com/Hemanth-G-LPU)

---

⭐ If you found this project useful or inspiring, please consider giving it a star!
