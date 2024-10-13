<p align="center">
  <a href="https://github.com/Rohit-rp12/weather-app">
    <img src="https://github.com/Rohit-rp12/weather-app/blob/main/images/logo.jpg" height="128">
  </a>
  <h1 align="center">Wow - Weather App</h1>
</p>


## Overview

Welcome to the Weather App! This application allows users to search for weather information by city name or by their current location. The app displays temperature, humidity, and wind speed data in a visually appealing format, including a bar chart for easy comparison.

## Features

- **Search by City**: Enter a city name to get the current weather information.
- **Geolocation**: Automatically fetch weather data based on your current location.
- **Dynamic Weather Icons**: Display relevant weather icons based on the current weather conditions.
- **Bar Chart**: Visual representation of temperature, humidity, and wind speed.
- **Error Handling**: Displays an error message for invalid city names.
- **Responsive Design**: Works well on both desktop and mobile devices.

## Technologies Used

- **HTML**: Structure of the app.
- **CSS**: Styling of the app.
- **JavaScript**: Functionality and interactivity.
- **jQuery**: Simplified DOM manipulation and AJAX requests.
- **Chart.js**: For creating the bar chart.
- **OpenWeatherMap API**: Fetching weather data.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. **Open `index.html` in your browser**:
    ```bash
    open index.html
    ```

## Usage

1. **Search for a City**:
    - Enter the name of the city in the search box.
    - Click the search button or press Enter.
    - The weather information for the city will be displayed.

2. **Use Geolocation**:
    - Allow the browser to access your location.
    - The weather information for your current location will be displayed automatically.

## File Structure

```
weather-app/
├── images/
│   ├── clouds.png
│   ├── clear.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   ├── wind.png
│   └── globe.png
├── index.html
├── style.css
└── README.md
```

## Code Overview

### `index.html`

- Contains the structure of the app, including the header, search input, weather display, and chart canvas.
- Includes links to external libraries and stylesheets.

### `style.css`

- Styles the app, including layout, colors, fonts, and animations.
- Ensures the app is responsive and visually appealing.

### JavaScript (Embedded in `index.html`)

- Handles fetching weather data from the OpenWeatherMap API.
- Updates the DOM with the fetched weather data.
- Renders the bar chart using Chart.js.
- Handles error messages for invalid city names.

## Contribution

If you have a better solution or want to suggest improvements, feel free to open an issue or submit a pull request. Contributions are always welcome!

## Deployment

The project is deployed, and you can check it by tapping on the following link:

[Weather App Deployment](https://wow-weather-app.netlify.app/)

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for the weather data API.
- [Chart.js](https://www.chartjs.org/) for the charting library.
- [jQuery](https://jquery.com/) for simplifying JavaScript.


---

Thank you for using our App! 🌍

---

