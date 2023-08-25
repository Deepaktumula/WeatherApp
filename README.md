# Weather App

Welcome to the Weather App project! This is a simple web application that allows users to search for weather information of a specific city and view the weather details for their current location.

## Features

- Search by city: Users can enter the name of a city to get its current weather information.
- Current location weather: The app detects the user's current location and displays its weather details.
- Weather information: The app shows key weather details such as temperature, humidity, wind speed, and weather condition.

## How to Use

1. Clone this repository to your local machine using:

git clone https://github.com/Deepaktumula/WeatherApp.git


2. Open the `index.html` file in a web browser to launch the app.

3. To search for weather information of a specific city:
- Enter the city name in the search input field.
- Click the "Search" button.
- The app will display the current weather details for the entered city.

4. To view weather details for your current location:
- Click the "Use My Location" button.
- The app will request your browser for location permission.
- Once permission is granted, it will display the current weather details for your location.

## Technologies Used

- HTML
- CSS
- JavaScript
- [OpenWeatherMap API](https://openweathermap.org/api) for weather data

## Setup and Configuration

To use this app, you'll need an API key from OpenWeatherMap. Replace `"YOUR_API_KEY"` in the `script.js` file with your actual API key.

`` javascript
const apiKey = "YOUR_API_KEY";

## Contributions
Contributions are welcome! If you'd like to contribute to the project, feel free to submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgements
Special thanks to codehelp and OpenWeatherMap for providing the weather data API.
