# 🌍 WanderGrid — Interactive City Explorer & Travel Dashboard

**WanderGrid** is a responsive, single-page travel explorer and real-time city telemetry dashboard built with semantic HTML5, Tailwind CSS, and modular Vanilla JavaScript. 

Originally created as a static multi-page CSS Grid beginner layout, this project was refactored into a dynamic, API-driven web application featuring live weather, real-time timezone clocks, live currency conversion, interactive maps, and a persistent travel bucket list.

---

## ✨ Key Features

- **🌐 8 Curated Global Destinations:** Explore **London, Paris, Tokyo, Mumbai, New York City, Cairo, Sydney, and Rio de Janeiro**—plus instant sidebar search filtering by city, country, or region.
- **✨ Smart City Auto-Fill Search:** Click **"+ Add Custom City"** and search any city in the world via the **Open-Meteo Geocoding API** to auto-fill its country, coordinates, IANA timezone, and local currency.
- **⛅ Live Weather Telemetry:** Fetches real-time temperature, wind speed, and sky conditions from the **Open-Meteo Weather API**.
- **🕒 Real-Time Local Clocks:** Uses the native JavaScript `Intl.DateTimeFormat` API to display accurate local times and day/night indicators for any timezone.
- **💱 Live Currency Converter:** Converts `INR`, `USD`, or `EUR` into the destination's local currency using live ECB rates from the **Frankfurter API** (with built-in offline fallback rates).
- **🗺️ Interactive Landmark Maps:** Powered by **Leaflet.js** and **OpenStreetMap**, featuring clickable landmark pins and smooth `flyTo()` map animations.
- **✅ Persistent Bucket List:** Track visited landmarks across sessions with a live progress bar backed by browser `localStorage`.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS (CDN), Vanilla JavaScript (ES6+)
- **APIs & Libraries:**
  - [Open-Meteo Weather & Geocoding APIs](https://open-meteo.com/)
  - [Frankfurter Currency Exchange API](https://www.frankfurter.app/)
  - [Leaflet.js](https://leafletjs.com/) & OpenStreetMap
  - [Lucide Icons](https://lucide.dev/) & Google Fonts (*Playfair Display* & *Inter*)

---

## 🚀 Getting Started

No build tools or package installations are required!

1. Clone this repository:
   ```bash
   git clone https://github.com/paulsontn/travel-dashboard.git
   ```
2. Open `index.html` directly in any modern web browser (or use VS Code Live Server).

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).