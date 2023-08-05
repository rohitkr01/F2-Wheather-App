# Project Overview- Weather Dashboard

## UI Reference
Figma: https://www.figma.com/file/B9yYQ9q9NKEDzxu488siDI/Weather-App---F2---Contest?type=design&node-id=2%3A811&mode=design&t=WTJbflzC3KC1AfEM-1

## Task Description
You are tasked with creating an interactive weather dashboard that allows users to add cities and view real-time weather information. The dashboard will have an input field and an "Add" button, and users will be able to add cities to a dynamically generated list of weather cards. Each card will display specific weather information, including an image corresponding to the weather condition (rainy, sunny, cloudy, windy). The application should provide a responsive and interactive user experience.

You will use the following OpenWeatherMap API endpoint: https://api.openweathermap.org/data/2.5/weather?q={CITY_NAME}&appid={API_KEY}&units=metric. You can generate your own API key by signing up at OpenWeatherMap.

This endpoint will return an object containing various weather-related properties, but you will focus on the following:

name: City Name
weather: Array containing weather conditions (e.g., "Rain", "Clear")
main: Object containing temperature, humidity, pressure
wind: Object containing wind speed and direction
clouds: Object containing cloudiness percentage
sys: Object containing country code, sunrise, and sunset times
Features
Add City: Implement an input field and an "Add" button to allow users to add cities. Validate the input to ensure that it's not empty and that the city hasn't been added before.

Weather Cards: Dynamically generate weather cards for each added city, displaying:
Weather icon corresponding to the condition (rainy, sunny, cloudy, windy)
City name, temperature (high, low, current), and weather condition
All other data received from the API (e.g., humidity, pressure, wind speed)

Sorting: Maintain the cities in an array and sort them by temperature from lowest to highest every time a city is added.

Responsive Design: Ensure that the dashboard is fully responsive and displays properly on both desktop and mobile devices.
Hints
To generate your own API key, sign up at https://openweathermap.org/appid and follow their instructions
You may use the `sort()` method to sort the array of cities by temperature.
Consider using a Set or an object to efficiently check for duplicate cities.

**************************************************
## Live WeatherApp

- City Addition: Easily add new cities through an intuitive input field and the "Add" button. The app validates inputs to ensure they're not empty and have not been added before.
- Live Weather Cards: Each city you add comes to life with a dedicated weather card. These cards showcase:
- Weather icons that vividly represent conditions (☔ rainy, ☀️ sunny, ☁️ cloudy, 💨 windy)
- Comprehensive weather information including current temperature, high and low temperatures, and weather conditions.
- Additional data from the API, such as humidity, pressure, and wind speed.
- Smart Sorting: The app maintains an array of cities and cleverly sorts them based on temperature. You'll always find the coldest and hottest cities at a glance.
- Responsive Display: Whether you're on a desktop or using your mobile device, the app's responsive design ensures a seamless and visually appealing experience.

Enjoy exploring the world's weather with these enriching features! 🌦️📱
