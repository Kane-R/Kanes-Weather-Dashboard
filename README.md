# Kanes Weather Dashboard "Weather Dreamer"
Interesting and inspiring weather dashboard application designed to help keep the masses who are locked indoors entertained yet still misserable. Includes search functionality to discover current weather conditions and the future weather outlook for cities all around the world. 

Go to https://kane-r.github.io/Kanes-Weather-Dashboard/ and start using 😊

## About The Project

Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. 

## User Story

```
As someone who is locked indoors during the 2020 Toilet Paper Crisis, I'd like to imagine myself in other places.
I want to be inspired, but mainly distracted by interesting content relating to anything ..the weather will do.
I want details to help keep me distracted, details such as the weather forecast, several days in advance, and intersting images that relate to the city and weather of my search. 
So that I can think of places I'd like to know about and perhaps visit when this truly crappy situation is over.

```

## Development Strategy

* Use the [OpenWeather API](https://openweathermap.org/api) and/or [DarkSky API](https://darksky.net/dev) to retrieve weather data for cities. 
  
* Use AJAX to hook into the API to retrieve data in JSON format.

* App should be able to run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

* Display the following under current weather conditions:

  * City
  * Date
  * Icon image (visual representation of weather conditions)
  * Temperature
  * Humidity
  * Wind speed
  * UV index

* Include a search history so that users can access their past search terms. Clicking on the city name should perform a new search that returns current and future conditions for that city. 

* Include a 5-Day Forecast below the current weather conditions. Each day for the 5-Day Forecast should display the following:

  * Date
  * Icon image (visual representation of weather conditions)
  * Temperature
  * Humidity

## Demo

![weather dashboard](./img/server-side-demo.png)

## User Specifications

- [x] Fully functional, deployed application.

- [x] GitHub repository with a unique name and a README describing the project.

- [x] User can search for weather reports by city using the openweathermap API.

- [x] After searching for a city, the following information is displayed:

  *  Current temperature
  *  Current humidity
  *  Windspeed
  *  Uv index
  *  5 day forecast

- [x] Application uses icons to represent weather conditions.

- [x] Application stores previously searched for cities in localstorage and displays them to the user.

- [x] Application loads last searched city forecast on page load.

## Extra Futures/Spefications

- [x] Use the [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) to add the user's current location to the initial landing page.

- [x] Use [DarkSky API](https://darksky.net/dev) to get daily forecast

- [x] Use Materialize CSS for UI

## End Result

![end result](./img/demo.gif)

## Tech Stack

1. Fron-end: Materialize CSS
2. jQuery
3. Deployed on GitHub Pages

## Licence

This project is licensed under the MIT License.