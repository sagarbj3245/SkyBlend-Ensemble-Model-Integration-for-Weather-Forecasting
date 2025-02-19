# Skyblnd: Real Time Weather Forecasting

Skyblnd is a simple Django project that provides real-time weather forecasting for any location in the world. The app displays current weather conditions, weather forecast, and historical weather data.

## Resources Used
- **Google Places JavaScript API**: For place name auto-completion.
- **OpenWeatherMap API**: For fetching weather details.
- **Chart.js**: For plotting charts of previous weather data.
- **AOS (Animate on Scroll)**: For adding animation effects when scrolling.

## Features
- Get real-time weather data for any location.
- View past weather conditions.
- Interactive charts to visualize weather trends.
- Place name auto-completion when searching.

## How to Use

Follow the steps below to set up the project locally:

### 1. Get API Keys
- **Google API Key**: 
  - Visit [Google Cloud Platform](https://cloud.google.com/).
  - Create a project and enable the **Google Places JavaScript API**.
  - Copy your **API Key** and paste it into the `./templates/core/home.html` file.
  
- **OpenWeatherMap API Key**:
  - Visit [OpenWeatherMap](https://openweathermap.org/).
  - Create an account and generate an **API Key**.
  - Paste the **API Key** into the `./weather_details/views.py` file.

### 2. Install Dependencies
- Install Python 3.x if it's not already installed.
- Navigate to the project folder in your terminal/command prompt.
- Install the required dependencies by running:

  ```bash
  pip install -r requirements.txt

