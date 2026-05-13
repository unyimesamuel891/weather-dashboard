# SKYES — Weather Dashboard

A dark-themed weather dashboard I built to practice working with external APIs and async JavaScript patterns.

**Live Demo:** [weather-dashboard-theta-cyan.vercel.app](https://weather-dashboard-theta-cyan.vercel.app)

![preview](./preview.png)

## What it does

- Fetches real-time weather + 5-day forecast from OpenWeatherMap
- Renders a 24-hour temperature line chart with Chart.js
- Displays humidity, wind speed, visibility and pressure at a glance
- Fires both API calls simultaneously using `Promise.all` to cut load time in half

## Built with

- Vanilla JavaScript (ES6+)
- Chart.js
- OpenWeatherMap API
- HTML & CSS

## Running locally

1. Grab a free API key at [openweathermap.org](https://openweathermap.org/api)
2. Open `index.html` and replace `YOUR_API_KEY` with your key
3. Open the file in your browser — no build step needed
