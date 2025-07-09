# 🌤️ Weather App

A modern, responsive weather application built with HTML, CSS, and JavaScript that provides real-time weather information and forecasts for cities worldwide.

## ✨ Features

### 🏠 **Home Page (Current Location)**
- **Automatic Location Detection**: Uses geolocation to automatically detect and display weather for your current location
- **Current Weather Display**: Shows temperature, weather description, humidity, and "feels like" temperature
- **Today's Forecast**: Displays today's minimum and maximum temperatures with weather conditions
- **6-Day Forecast**: Horizontal scrollable forecast showing weather predictions for the next 6 days
- **Dynamic Weather Icons**: Visual weather representations that change based on current conditions

### 🔍 **Search Page**
- **City Search**: Search for weather information by city, state, or country names
- **Detailed Weather Info**: Comprehensive weather details including:
  - Wind speed
  - Atmospheric pressure
  - Humidity percentage
  - Sunrise and sunset times
- **Error Handling**: User-friendly error messages for invalid city searches

### 🌍 **World Weather Page**
- **Multi-City Management**: Add and track weather for multiple cities worldwide
- **Quick City Addition**: Search and add new cities with a simple interface
- **Persistent Display**: Shows weather cards for all added cities
- **Default Cities**: Pre-loaded with popular cities (London, Paris, New York, Mumbai, Tokyo)

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Weather API**: OpenWeatherMap API
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Rubik)
- **Styling**: Custom CSS with responsive design

## 🚀 Getting Started

### Prerequisites
- A modern web browser with JavaScript enabled
- Internet connection for API calls
- Location services enabled (for current location feature)

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Allow location access when prompted (for current location feature)

### API Key Setup
The application uses the OpenWeatherMap API. The current API key is included in the code, but for production use, you should:
1. Sign up at [OpenWeatherMap](https://openweathermap.org/api)
2. Get your own API key
3. Replace the `apiKey` variable in the JavaScript files

## 📱 Features Breakdown

### Navigation
- **Location Arrow**: Home page with current location weather
- **Magnifying Glass**: Search page for city weather lookup
- **Globe Icon**: World weather page for multi-city management

### Weather Conditions Supported
- ☀️ Clear/Sunny
- 🌧️ Rain
- ❄️ Snow
- ☁️ Clouds
- 🌫️ Mist/Fog
- 🌫️ Haze
- ⚡ Thunderstorm

### Responsive Design
- Mobile-first approach
- Responsive layout that adapts to different screen sizes
- Touch-friendly interface
- Smooth animations and transitions

## 🌟 Key Features

1. **Real-time Data**: Live weather updates from OpenWeatherMap API
2. **Location Services**: Automatic current location detection
3. **Multi-city Support**: Track weather for multiple cities
4. **Responsive Design**: Works seamlessly on desktop and mobile devices
5. **User-friendly Interface**: Intuitive navigation and clear weather displays
6. **Error Handling**: Graceful handling of API errors and invalid searches


