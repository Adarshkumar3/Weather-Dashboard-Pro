# Weather Dashboard
# demo -https://github.com/Adarshkumar3/Weather-Dashboard-Pro/blob/main/Web%20capture_17-9-2024_24427_.jpeg

## Overview
This Weather Dashboard is a sleek, modern web application that provides users with current weather information and forecasts for cities around the world. Built with HTML, CSS,  JavaScript,and Api ,it offers a responsive design that works seamlessly across desktop and mobile devices.

## Features
- **Current Weather Display**: Shows detailed current weather information including temperature, feels-like temperature, humidity, wind speed, and UV index.
- **5-Day Forecast**: Provides a visual forecast for the next 5 days.
- **Temperature Chart**: Displays a line graph of maximum and minimum temperatures for the 5-day forecast.
- **Search Functionality**: Allows users to search for weather information by city name.
- **Favorite Locations**: Users can save and quickly access their favorite locations.
- **Responsive Design**: Adapts to various screen sizes for optimal viewing on both desktop and mobile devices.

## Technologies Used
- HTML5
- CSS3 (with custom properties and flexbox/grid layouts)
- JavaScript (ES6+)
- jQuery
- Chart.js for data visualization
- WeatherAPI (via RapidAPI) for weather data

## Setup and Installation
1. Clone the repository or download the HTML file.
2. Open the HTML file in a web browser.

   Note: This project uses CDN links for jQuery and Chart.js, so an internet connection is required for full functionality.

## API Configuration
This project uses the WeatherAPI through RapidAPI. To use the application:

1. Sign up for a free account at [RapidAPI](https://rapidapi.com/).
2. Subscribe to the [WeatherAPI](https://rapidapi.com/weatherapi/api/weatherapi-com/) on RapidAPI.
3. Replace the `API_KEY` constant in the JavaScript code with your own API key.

```javascript
const API_KEY = 'YOUR_RAPIDAPI_KEY_HERE';
```

## Usage
1. Enter a city name in the search bar and press the search button or hit enter.
2. View the current weather, 5-day forecast, and temperature chart for the searched city.
3. Click "Add to Favorites" to save a city to your favorites list.
4. Click on a favorite city to quickly load its weather information.
   

## Customization
- The color scheme can be easily customized by modifying the CSS variables in the `:root` selector.
- Additional weather details or forecast information can be added by modifying the `displayCurrentWeather` and `displayForecast` functions.

## Known Issues
- The application requires an internet connection to fetch weather data and load external libraries.
- API usage is limited based on your RapidAPI subscription plan.

## Future Enhancements
- Implement geolocation to automatically detect the user's current location.
- Add more detailed hourly forecasts.
- Integrate air quality data and other environmental information.
- Implement local storage to persist favorite locations across sessions.

## Contributing
Contributions to improve the Weather Dashboard are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

## License
This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
