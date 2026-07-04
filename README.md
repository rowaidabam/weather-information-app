# Weather Information App

## Overview

The Weather Information App is a Java desktop application that provides real-time weather information and weather forecasts for cities around the world. It features a user-friendly graphical interface built with Java Swing and retrieves live weather data using the OpenWeatherMap API.

## Features

* Search for weather information by city name.
* Display current temperature, humidity, wind speed, and weather conditions.
* Show weather icons based on current conditions.
* Display a multi-day weather forecast.
* Support for Celsius and Fahrenheit temperature units.
* Maintain a searchable history of previously searched cities.
* Simple and intuitive graphical user interface (GUI).

## Technologies Used

* Java
* Java Swing
* OpenWeatherMap API
* JSON (org.json library)
* HTTPURLConnection

## Project Structure

```text
src/
├── WeatherApp.java
└── WeatherAPIService.java
```

## Requirements

* Java JDK 17 or later (or the version compatible with your project)
* IntelliJ IDEA (recommended)
* Internet connection
* OpenWeatherMap API Key

## Setup

1. Clone this repository.
2. Open the project in IntelliJ IDEA.
3. Add the required JSON library (`org.json`) to the project dependencies.
4. Obtain an API key from OpenWeatherMap.
5. Replace the placeholder API key in `WeatherAPIService.java`:

```java
private static final String API_KEY = "YOUR_API_KEY_HERE";
```

6. Run `WeatherApp.java`.

## How to Use

1. Launch the application.
2. Enter a city name.
3. Click **Search**.
4. View the current weather information and forecast.
5. Select your preferred temperature unit (Celsius or Fahrenheit).

## Future Improvements

* Display weather by GPS location.
* Add hourly weather forecast.
* Improve UI design with modern themes.
* Cache recent searches.
* Add support for additional weather providers.

## Author

Developed as a Java programming course project by **Rowaida**.
