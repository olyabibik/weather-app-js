# JavaScript Weather App
A simple weather application built using HTML, CSS and JavaScript. This app allows users to search for real-time weather conditions in any city using a public weather API.

## How it works
- User enters a city name into the input field
- JavaScript fetches data from the weather API
- Weatehr data is displayed dynamically on the page

## API Key
To make this app work, you need a weather API key:
1. Sign up at [OpenWeatherApp] (https://openweathermap.org/)
2. Replace the placeholder YOUR_API_KEY in the JS File:
   const api = {
    endpoint: "https://api.openweathermap.org/data/2.5/",
    key: "YOUR_API_KEY"
}
