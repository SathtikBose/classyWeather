# 🌤️ Classy Weather

A sleek, clean, and interactive weather application built with React class-based components. This project provides a 7-day weather forecast for any location worldwide using the Open-Meteo API.

[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen.svg)](https://sathtikbose.github.io/classyWeather/)

## 🚀 Features

- **Global Search:** Find weather data for any city or location.
- **7-Day Forecast:** Detailed daily predictions including max/min temperatures.
- **Dynamic Icons:** Visual weather indicators using WMO weather codes.
- **Country Identification:** Automatically displays the country flag for the searched location.
- **Responsive Design:** Optimized for a seamless experience across devices.
- **Class-Based Architecture:** Demonstrates robust use of React class components and lifecycle methods.

## 🛠️ Tech Stack

- **Framework:** [React 19](https://reactjs.org/)
- **API (Weather & Geocoding):** [Open-Meteo](https://open-meteo.com/)
- **Styling:** CSS3
- **Deployment:** GitHub Pages

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SathtikBose/classyWeather.git
   cd classyWeather
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.

## 🏗️ Project Structure

```text
src/
├── App.js         # Core logic, state management, and main components
├── index.css      # Global styles and layout
└── index.js       # Application entry point
```

## 📝 How It Works

1. **Geocoding:** When a user enters a location, the app first calls the Open-Meteo Geocoding API to retrieve coordinates (latitude/longitude) and location details.
2. **Weather Fetching:** Using the retrieved coordinates, it makes a second call to the Open-Meteo Forecast API to get the 7-day weather data.
3. **State Management:** The application state (location, weather data, loading status) is managed within the `App` class component.

---

Built with ❤️ by [Sathtik Bose](https://github.com/SathtikBose)
