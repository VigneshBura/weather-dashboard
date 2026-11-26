# Weather Dashboard

A responsive weather dashboard built with plain HTML, CSS and JavaScript. Search any city and see current weather, hourly and 5-day forecasts, a temperature trend chart and air quality.

**Live demo:** _add your GitHub Pages link here_

![Screenshot](screenshot.png)

## Features

- City search (button or Enter key) with error handling for unknown cities
- Current temperature, feels like, high/low, humidity, wind, pressure, visibility, UV index, precipitation
- Next 12 hours and next 5 days forecast
- Temperature trend chart (Chart.js)
- Air quality index (US AQI) with colour-coded category
- Sunrise and sunset times in 12-hour format
- °C / °F toggle
- Simple weather advice (umbrella, sunscreen, heat)
- Responsive layout for laptop and phone

## Tech used

- HTML5, CSS3 (Grid, Flexbox, media queries)
- JavaScript (async/await, fetch, DOM manipulation)
- Chart.js
- Open-Meteo Geocoding, Forecast and Air Quality APIs (no API key needed)

## Run locally

1. Download or clone this repository
2. Open `index.html` in a browser (internet connection required)

## What I learned

- Calling REST APIs with `fetch` and `async/await`
- Handling errors with `try/catch`
- Rendering data into the DOM and keeping UI state in sync
- Building a responsive layout with CSS Grid

## Future improvements

- Auto-detect location
- Day/night theme
- Favourite cities
- Rebuild with React and a Python (FastAPI) backend

Data provided by [Open-Meteo](https://open-meteo.com/).
