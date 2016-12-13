# Weather App Design

This is a starter project for a simple weather app using the [OpenWeatherMap](https://openweathermap.org/api) API (weather app originally created by [Mitchell Hudson](https://github.com/soggybag/)). The goal of this project is to design and style the weather application, beginning with a design in Sketch, then modifying and styling the html document to match the design as closely as possible.

### Objectives:
- [ ] Show a 5 day forecast.
- [ ] Show the 5 day forecast in another view and allow  between switching of views with a transition.
- [ ] Save more than one weather forecast in a list.
- [ ] Save multiple weather forecasts and show each in a view side by side.

### How it works:
- [ ] Gets the weather from OpenWeatherMap.org using their API.
  - Uses AJAX to load JSON data via jQuery's $.get() method.
  - Specifically this example uses both the Current weather forecast and the 5 day 3 hour forecast.
- [ ] Gets the geo location vis JS with navigator.geolocation.getCurrentPosition
- [ ] Stores a city location with local storage.
