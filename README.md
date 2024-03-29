# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- Step-by-Step Procedure to Retrieve Weather Data using OpenWeatherMap API

**1. Sign Up for an API Key:
**
Before using the OpenWeatherMap API, you need to sign up on their website to get an API key.
Go to the OpenWeatherMap website (https://openweathermap.org/) and create an account if you don't have one already.
After logging in, navigate to the API Keys section and generate a new API key. Keep this key secure as it will be used to authenticate your requests.

**2. Construct the API Request URL:
**
The API endpoint for fetching weather data is https://api.openweathermap.org/data/2.5/weather.
Replace ${city} in the URL with the name of the city for which you want to retrieve weather data. For example, if you want to get weather data for London, the URL will be https://api.openweathermap.org/data/2.5/weather?q=London.
Replace ${apikey} with the API key you obtained in step 1.
So, the complete URL will look like: https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY.

