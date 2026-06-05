# Air Quality & Pollution Checker

A responsive web application that allows users to monitor air quality and pollution levels for locations around the world using real-time data from the OpenWeatherMap API.

## Overview

Air pollution has become one of the most critical environmental challenges affecting human health and quality of life. This project helps users check the Air Quality Index (AQI) and view the concentration of various pollutants in the atmosphere for any location.

The application supports searching locations through city names or geographic coordinates and provides real-time environmental data through API integration.

---

## Features

✅ Real-time Air Quality Index (AQI)

✅ Search locations using city names

✅ Automatic location suggestions

✅ Latitude and Longitude based search

✅ Air Quality Status Classification

✅ Detailed pollutant concentration analysis

✅ Responsive user interface

✅ Modal-based result display

✅ Browser Geolocation Support

---

## Pollutants Monitored

The application displays the concentration of:

- Carbon Monoxide (CO)
- Nitrogen Monoxide (NO)
- Nitrogen Dioxide (NO₂)
- Ozone (O₃)
- Sulphur Dioxide (SO₂)
- Fine Particulate Matter (PM2.5)
- Coarse Particulate Matter (PM10)
- Ammonia (NH₃)

---

## Air Quality Classification

| AQI | Status |
|------|---------|
| 1 | Good |
| 2 | Fair |
| 3 | Moderate |
| 4 | Poor |
| 5 | Very Poor |

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (ES6 Modules)

### APIs
- OpenWeatherMap Geocoding API
- OpenWeatherMap Air Pollution API

### Other Technologies
- Browser Geolocation API

---

## Project Structure

```text
Air-Quality-Pollution-Checker/
│
├── index.html
├── style.css
├── script.js
├── countries.js
├── bgImage.png
└── README.md
```

---

## How It Works

### Step 1

Enter a city name or provide latitude and longitude coordinates.

### Step 2

The application uses the OpenWeatherMap Geocoding API to identify the location.

### Step 3

The coordinates are sent to the Air Pollution API.

### Step 4

The API returns:

- Air Quality Index (AQI)
- Pollution Status
- Pollutant Concentrations

### Step 5

Results are displayed in a user-friendly modal window.

---

## Learning Outcomes

Through this project, I learned:

- API Integration
- Asynchronous JavaScript
- Fetch API
- ES6 Modules
- DOM Manipulation
- Event Handling
- Geolocation API
- Responsive Web Design
- Environmental Data Visualization

---

## Future Enhancements

- Air Quality History Tracking
- Pollution Trend Charts
- Dark Mode
- Interactive Maps Integration
- Nearby Pollution Monitoring
- Health Recommendations Based on AQI
- Export Reports as PDF

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/air-quality-pollution-checker.git
```

### Open Project

Open `index.html` using:

- Live Server (Recommended)
- Any modern web browser

---

## Author

**Suryansh Agrawal**  
B.Tech Computer Science Engineering (Artificial Intelligence & Machine Learning)

### Connect With Me

- GitHub: [Suryanshhh](https://github.com/Suryanshhh)
- LinkedIn: [Suryansh Agrawal](https://www.linkedin.com/in/suryansh-agrawal-734648239/)

---

⭐ This project was developed to explore API integration, environmental data analysis, and frontend web development using modern JavaScript.
