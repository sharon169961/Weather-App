

# Weather App

A simple and responsive weather application that displays real-time weather information for any location, built using **HTML**, **CSS**, and **JavaScript**. The app fetches data from the **OpenWeather API** to show temperature, humidity, wind speed, and more.

## Features
- **Search**: Allows users to search for weather information by city name.
- **Real-Time Data**: Displays live weather data such as temperature, humidity, and wind speed.
- **Responsive Design**: Optimized for both desktop and mobile screens.
- **Dynamic Weather Icons**: Shows different icons depending on the current weather (e.g., rain, clouds, etc.).
- **Error Handling**: Displays a friendly error message if the city name is invalid.

## Technologies Used
- **HTML**: For the structure of the application.
- **CSS**: For styling and making the app responsive.
- **JavaScript**: For functionality, handling user interactions, and fetching weather data.
- **OpenWeather API**: Used to gather real-time weather data for any location.

## How It Works
1. Enter a city name in the search box.
2. Click the search button to fetch the weather data.
3. The app displays the following information:
   - Current temperature (in Celsius)
   - Weather description (e.g., cloudy, rainy)
   - Humidity percentage
   - Wind speed (in km/h)
4. If an invalid city is entered, an error message will appear.



## API Key
The app uses the **OpenWeather API**. To make it work, you need to provide your own API key:
1. Sign up for a free account on the [OpenWeather website](https://openweathermap.org/) to get an API key.
2. Replace the placeholder API key in the `script` tag with your own:
   ```javascript
   const apiKey = 'your-api-key-here';
   ```

## Future Improvements
- **Add more weather details**: Display extended weather information like pressure, sunrise, sunset times, etc.
- **Geolocation Support**: Automatically detect the user’s location and show weather data without requiring a search.
- **Multi-language Support**: Allow users to switch between different languages for weather descriptions.

![image](https://github.com/user-attachments/assets/ad831684-b597-4033-b5e5-38d411a3946a)
![image](https://github.com/user-attachments/assets/4dfaaa78-23df-46f6-8f8c-0a5173002a1e)
![image](https://github.com/user-attachments/assets/479d3bc2-caef-4074-80ac-5ba8f5c3d263)



