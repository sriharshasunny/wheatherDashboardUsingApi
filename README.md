# 🌤 Weather Dashboard

A simple, responsive weather application built with **HTML, CSS, and
JavaScript**, using the [OpenWeatherMap
API](https://openweathermap.org/api) to fetch real-time weather data.

## 🚀 Features

-   Search for weather by **city name**.\
-   Displays:
    -   Current temperature\
    -   Feels like temperature\
    -   Humidity\
    -   Wind speed\
    -   Pressure\
    -   Max/Min temperature\
    -   Sunrise & Sunset times\
    -   Cloud coverage\
    -   Coordinates (lat, lon)\
-   Weather icon updates dynamically.\
-   **Glassmorphism UI** with gradient background.\
-   Default city loads automatically (**Hyderabad**).

## 📂 Project Structure

    weatherdashboard.html   # Main HTML file (includes CSS + JavaScript)

## ⚙️ Setup & Usage

1.  Clone or download this repository.\
2.  Open the `weatherdashboard.html` file in your browser.\
3.  Enter a city name in the search bar and click **Search**.\
4.  Weather details will appear instantly.

## 🔑 API Key

This project uses [OpenWeatherMap API](https://openweathermap.org/).\
- A sample key is already included (`apiKey` inside `<script>`).\
- Replace it with your own API key for production use:\
`javascript   const apiKey = "YOUR_API_KEY_HERE";`

## 🎨 UI Preview

-   Gradient background with **modern glassmorphism card**.\
-   Responsive grid for weather details.\
-   Smooth hover effects on search button.

## 📌 Future Enhancements

-   5-day weather forecast.\
-   Save recent searches.\
-   Dark/Light mode toggle.\
-   Geolocation-based weather (auto-detect).
