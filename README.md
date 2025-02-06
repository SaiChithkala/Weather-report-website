#  Weather App

A simple weather application that fetches real-time weather data using the OpenWeatherMap API. Users can enter a city name to get current weather conditions, including temperature, humidity, and wind speed.

# Features
- Search for weather data by city name.
- Displays temperature, humidity, and wind speed.
- Shows weather condition images based on the forecast.
- Handles invalid city names with an error message.
- Responsive design for different screen sizes.

# Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeatherMap API

# How to Run
1. Clone the repository:
 
   git clone https://github.com/yourusername/weather-app.git
 
2. Navigate to the project folder:
 h
   cd weather-app

3. Open `index.html` in a web browser.

# API Key Configuration
This project uses the OpenWeatherMap API. To use it:
1. Sign up at [OpenWeatherMap](https://openweathermap.org/) and get an API key.
2. Replace the existing API key in `index.html`:
   javascript
   const apiKey = "YOUR_API_KEY";
 

# File Structure

weather-app/
│── index.html         # Main HTML file
│── style.css          # Styling file
│── script.js          # JavaScript logic (embedded in HTML)
│── images/            # Weather condition icons
└── README.md          # Project documentation


# Future Improvements
- Add a background that changes based on the weather.
- Implement geolocation-based weather fetching.
- Improve UI/UX with better animations.

# License
This project is open-source and available under the [MIT License](LICENSE).




