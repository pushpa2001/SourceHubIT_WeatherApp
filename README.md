# SourceHubIT_WeatherApp
A simple and responsive weather application built using React (Vite) and OpenWeather API. The app allows users to search for any city worldwide and view real-time weather conditions, including temperature, humidity, wind speed, and weather icons.

# Tech Stack

React (Vite) – Frontend framework for fast development
Axios – For API requests
OpenWeather API – For fetching weather data
HTML/CSS – For styling 

Input:
User enters a city name in a search bar.

Output:
Display of weather details for the entered city, including:
Current temperature
Weather description (e.g., sunny, rainy)
Wind speed
Humidity level

# Go to the project directory
cd weather

# Install dependencies
npm install

# Start the development server
npm run dev

API Setup  

Go to OpenWeather and sign up for a free API key.

Create a .env file in the root of your project and add:

code:VITE_WEATHER_API_KEY=your_api_key_here

Restart your development server.

Project Structure
weatherapp/
 ├── public/              # Static files
 ├── src/
 │   ├── components/      # Reusable UI components
 │   ├── App.jsx          # Main App Component
 │   ├── index.css        # Global styles
 │   └── main.jsx         # Entry point
 ├── .env              
 ├── package.json
 └── README.md
 








