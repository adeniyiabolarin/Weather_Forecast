# Weather App

A responsive Weather App built with HTML, CSS, and Vanilla JavaScript that fetches real-time weather data using the OpenWeather API.

## Features

* Search weather by city name
* Real-time weather information
* Temperature display in Celsius
* Humidity display
* Dynamic weather emojis
* Error handling for invalid cities
* Loading state while fetching data
* Responsive and clean user interface

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* OpenWeather API

## Project Structure

```txt
weather-app/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## How It Works

The application allows users to enter a city name and retrieve current weather information using the OpenWeather API. The app dynamically updates the UI with:

* City name
* Temperature
* Humidity
* Weather description
* Weather emoji based on weather condition

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/weather-app.git
```

### 2. Open the Project Folder

```bash
cd weather-app
```

### 3. Get Your OpenWeather API Key

Visit the OpenWeather website and create a free API key:

https://openweathermap.org/api

### 4. Add Your API Key

Inside `script.js`, replace:

```javascript
const apiKey = "YOUR_API_KEY";
```

with your actual API key.

### 5. Run the Project

Open `index.html` in your browser.

## Future Improvements

* 5-day weather forecast
* Dark mode
* Geolocation support
* Search history
* Fahrenheit temperature option
* Better mobile responsiveness

## Learning Outcomes

This project helped reinforce understanding of:

* DOM Manipulation
* Event Handling
* Async/Await
* Fetch API
* Working with APIs
* Error Handling
* Dynamic UI Rendering
* JavaScript Destructuring
* CSS Flexbox

## Author

Adeniyi Abolarin

Frontend Developer focused on building responsive and interactive web applications using modern JavaScript and React.
