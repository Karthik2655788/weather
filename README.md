Weather App

Project Overview

The Weather App is a simple web application developed using HTML, CSS, and JavaScript. It allows users to enter a city name and fetch real-time weather information using the OpenWeatherMap API. The application displays the current temperature, humidity, weather condition, wind speed, and feels-like temperature in a clean and responsive card interface.

⸻

Features

* Search weather by city name
* Displays current temperature in Celsius
* Shows humidity percentage
* Displays weather condition
* Shows feels-like temperature
* Displays wind speed
* Weather icon based on current condition
* Dark Mode / Light Mode toggle
* Responsive and user-friendly interface
* Error handling for invalid city names

⸻

Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Fetch API
* JSON
* OpenWeatherMap API

⸻

Skills Gained

* DOM Manipulation
* API Integration
* Fetch API
* JSON Parsing
* Asynchronous Programming (Async/Await)
* Error Handling
* Responsive Web Design

⸻

Project Structure

Weather-App/
│
├── index.html
└── README.md

⸻

How It Works

1. User enters a city name.
2. JavaScript sends a request to the OpenWeatherMap API using the Fetch API.
3. The API returns weather data in JSON format.
4. JavaScript parses the JSON response.
5. The application displays:
    * City Name
    * Temperature
    * Feels Like Temperature
    * Humidity
    * Wind Speed
    * Weather Condition
    * Weather Icon

⸻

API Used

OpenWeatherMap API

API Endpoint:

https://api.openweathermap.org/data/2.5/weather

Required Parameters:

* q – City Name
* appid – API Key
* units=metric – Temperature in Celsius

Example Request:

https://api.openweathermap.org/data/2.5/weather?q=Delhi&appid=YOUR_API_KEY&units=metric

⸻

How to Run

1. Download or clone the project.
2. Open the index.html file in a code editor.
3. Replace the placeholder API key with your own OpenWeatherMap API key:

const apiKey = "YOUR_API_KEY";

4. Save the file.
5. Open index.html in any modern web browser.
6. Enter a city name and click Get Weather.

⸻

Sample Cities

* Delhi
* Mumbai
* Hyderabad
* Bengaluru
* Chennai
* Visakhapatnam
* Kolkata
* Pune
* London
* New York
* Tokyo
* Paris
* Dubai
* Sydney
* Singapore

⸻

Future Enhancements

* 5-Day Weather Forecast
* Current Location Weather using Geolocation API
* Sunrise and Sunset Time
* Air Quality Index (AQI)
* Weather Map Integration
* Theme Preference Saved using Local Storage
* Search History
* Multiple Language Support

⸻

Output

The application displays:

* City Name
* Weather Icon
* Current Temperature
* Feels Like Temperature
* Humidity
* Wind Speed
* Weather Condition

⸻

Author

Angati Bhuvana Karthik

B.Tech Computer Science Engineering
GITAM Deemed University, Visakhapatnam

Email: bangati@gitam.in

GitHub: https://github.com/Karthik2655788

LinkedIn: https://www.linkedin.com/in/angati-bhuvana-karthik

⸻

Conclusion

This Weather App demonstrates the integration of a third-party REST API with a web application. It showcases practical usage of HTML, CSS, JavaScript, DOM manipulation, Fetch API, and JSON parsing to build an interactive, responsive, and user-friendly application that provides real-time weather information.
