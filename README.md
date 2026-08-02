# Weather Forecast Web App 🌤️ `V1.1.0`

A modern, fast, and gorgeous weather forecasting application built strictly with **Vanilla JavaScript** and **Tailwind CSS**. It delivers real-time weather information, hourly forecasts, weekly trends, and air quality metrics for any city worldwide—**no signups or API keys required**.

🔗 **Live Demo:** [sagarlamon.github.io/Weatherforecaste/](https://sagarlamon.github.io/Weatherforecaste/)

---

## What's New in `V1.1.0` 🚀

Version 1.1.0 introduces a major visual and feature overhaul to make the app more premium, informative, and interactive:

*   **📈 Interactive SVG Temperature Chart:** A beautiful, responsive vector line graph mapping hourly temperature trends and displaying precipitation chances (`💧 30%`) directly inside the chart timeline.
*   **📌 Pinned Cities & Recent History Dashboard:** Pin your favorite cities with one click using the star icon. Pinned cities and search history are saved locally in your browser (`localStorage`) for quick badge-style navigation.
*   **🎨 Dynamic Weather Background Gradients:** A living UI that adapts its gradient background based on the weather conditions (Clear, Cloudy, Rainy, Snowy, Thunderstorm) while strictly respecting your preference for Light or Dark Mode.
*   **📊 Expanded Metrics Grid:** View current precipitation depth (mm), UV index with severity indicators, and beautifully formatted local Sunrise & Sunset times.
*   **✨ Premium Skeleton Loading States:** Replaced the generic loading spinner with responsive, modern shimmering card blocks that mirror the actual weather panels.
*   **🖱️ Interaction Fix:** Resolved an overlapping CSS stacking context issue, making suggestions dropdown list options fully clickable and interactive with mouse pointers.

---

## Core Features

-   **Real-time Weather:** Instantly fetch temperature, feels-like temperature, humidity, wind speed, and weather condition details.
-   **Air Quality Index (AQI):** Monitors local air quality with clean, human-readable color badges.
-   **Weekly Outlook:** A clean 7-day outlook showing maximum and minimum temperature scales.
-   **Smart Location Service:** Tap the navigation icon to request current geolocation and reverse-geocode address names using OpenStreetMap.
-   **Dark & Light Mode Toggle:** Smooth, transition-ready theme switching with persistent client-side storage.
-   **Mobile-First Responsive Design:** Looks and behaves beautifully across all viewports (mobile, tablet, desktop).

---

## Tech Stack & Data Sources

-   **Frontend:** HTML5, CSS3 (Vanilla + Google Fonts), JavaScript (ES6)
-   **Utility Styling:** Tailwind CSS v4 Runtime
-   **Weather Data Engine:** [Open-Meteo API](https://open-meteo.com) (Free, open-source weather and Air Quality data)
-   **Reverse Geocoding:** [OpenStreetMap Nominatim API](https://nominatim.org/)

---

## Project Philosophy

This app demonstrates that you don't need heavy frameworks (like React, Vue, or Angular) to build a fast, dynamic, and visually stunning web application. By utilizing modern web APIs, native SVG render loops, and efficient localStorage caching, the application remains lightweight, fast to load, and easy to maintain.

---

Made with ❤️ by **Sagar**
