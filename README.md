# To-Market

Weather Dashboard

This is a weather dashboard with form inputs that will run in the browser and feature dynamically updated HTML and CSS. It allows the user to search to view weather outlook for multiple cities so travelers can plan a trip accordingly.

OpenWeather API is used to retrieve weather data for cities. And localStorage is used to store persistent data.

Installation
Download or clone repository
Open the main page (index.html) on your browser to view
Use a text editor to view all coding, Visual Studio Coding is recommended.
Functionality
When searched for a city, the current and future conditions for that city will be presented and that city is added to the search history

When viewing current weather conditions for the city, the following is shown:

City name
Date
An icon representation of weather conditions
Temperature
Humidity
Wind speed
UV index
When viewing the UV index, it is presented with a color indicating severity (reference: Ultraviolet Index Wikipeadia)

#3EA72D 0-2 Low
#FFF300 3-5 Moderate
#F18B00 6-7 Orange
#E53210 8-10 Very High
#B567A4 11+ Extreme
When viewing the future weather conditions for the city, a 5-day forecast will be presented with the following information:

Date
An icon representation of weather conditions
Temperature
Humidity
When a city in the search history is clicked, the current and future conditions for that city is presented again

When the weather dashboard is opened, the last searched city forecast is presented

Features
HTML
CSS
Bootstrap
jQuery
Moment.js
Server-Side API - OpenWeather API
