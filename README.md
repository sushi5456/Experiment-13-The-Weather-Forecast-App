<div align="center">

# 🌤️ Weather Forecast App

  <p>A sleek and responsive React application providing real-time weather metrics and 5-day temperature forecasts powered by the OpenWeather API.</p>

  <p>
    <img src="https://img.shields.io/badge/React-18.x-blue?style=for-the-badge&logo=react" alt="React" />
    <img src="https://img.shields.io/badge/Axios-HTTP%20Client-purple?style=for-the-badge&logo=axios" alt="Axios" />
    <img src="https://img.shields.io/badge/Chart.js-Data%20Visualization-orange?style=for-the-badge&logo=chart.js" alt="Chart.js" />
    <img src="https://img.shields.io/badge/OpenWeather-API-yellow?style=for-the-badge&logo=openweathermap" alt="OpenWeather API" />
  </p>
</div>

---

## 📌 Features

* **Real-Time Weather Lookup**: Instantly check current weather conditions for any city worldwide.
* **Detailed Metrics**: View comprehensive atmospheric data including temperature, "feels like" temperature, humidity levels, atmospheric pressure, and wind speed[cite: 2].
* **Interactive 5-Day Forecast**: Visualize temperature trends over a 5-day period (3-hour intervals) using dynamic **Chart.js** line graphs.
* **Clean & Modular Architecture**: Built with separation of concerns (`App`, `Weather`, and `WeatherChart` components)[cite: 1, 2, 3].

---

## 🛠️ Tech Stack

* **Frontend Library**: React.js
* **HTTP Client**: Axios[cite: 2]
* **Charting Engine**: Chart.js & `react-chartjs-2`[cite: 3]
* **API Service**: OpenWeather Map API (`/weather` & `/forecast` endpoints)[cite: 2, 3]

---

## 📂 Project Structure

```text
src/
│
├── App.js            # Main application layout container[cite: 1]
├── Weather.js        # Current weather search component & state handler[cite: 2]
└── WeatherChart.js   # 5-day trend visualization using Chart.js[cite: 3]
