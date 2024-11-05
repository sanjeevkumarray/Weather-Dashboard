# Weather Dashboard

Welcome to the Weather Dashboard! This application provides real-time weather data and a 5-day forecast for any city you choose. Users can easily search for cities, manage their favorites, and toggle between Celsius and Fahrenheit for temperature readings.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Key](#api-key)
- [JSON Server](#json-server)
- [Live Demo](#live-demo)
- [License](#license)

## Features
- **City Search:** Easily search for a city to view current weather and a 5-day forecast.
- **Favorites Management:** Add and remove cities from a favorites list with full CRUD functionality.
- **Real-Time Data:** Access real-time weather information based on the user's current location.
- **Today's Highlights:** View important weather details such as Sunrise/Sunset times, Humidity, Pressure, Visibility, and "Feels Like" temperature.
- **Daily Updates:** Get hourly weather updates every 3 hours along with wind speed data.
- **5-Day Forecast:** Access detailed weather forecasts for the next five days.
- **Light and Dark Modes:** Switch between light and dark themes with persistence through local storage.
- **Last Searched City:** The application remembers the last searched city, even after refreshing the page.

## Technologies Used
This project is built using the following technologies:
- **Frontend:** React.js, CSS Modules
- **APIs:** OpenWeatherMap API for weather data
- **State Management:** Context API
- **Development Tools:** Vite for build tooling, ESLint and Prettier for code linting and formatting

## Installation
To set up and run the Weather Dashboard locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/sanjeevkumarray/Weather-Application
    ```

2. Navigate to your project directory:
    ```bash
    cd your-project-directory
    ```

3. Create a `.env` file and add your OpenWeatherMap API key:
    ```bash
    echo "REACT_APP_OPENWEATHERMAP_API_KEY=your-api-key-here" > .env
    ```

4. Install the required dependencies:
    ```bash
    npm install
    ```

5. Run the application in development mode:
    ```bash
    npm run dev
    ```

Replace `your-project-directory` with the actual name of your project folder, and `your-api-key-here` with your OpenWeatherMap API key.

## Usage
- Enter a city name in the search bar to get the current weather and 5-day forecast.
- Click the "Add to Favorites" button to save a city for easy access later.
- Manage your favorites list by removing cities or viewing their weather data.
- Use the toggle switch to switch between Celsius and Fahrenheit temperature scales.
- The last searched city will be retained across sessions, even after page refresh.

## API Key
To obtain an API key from OpenWeatherMap:
1. Visit the [OpenWeatherMap website](https://openweathermap.org/).
2. Sign up for a free account.
3. After signing in, navigate to the API section and generate a new API key.
4. Update your application code with your actual API key.

## JSON Server
The project employs a JSON server to manage favorite cities, supporting the following operations:
- **Create:** Add new favorite cities.
- **Read:** Retrieve existing favorite cities.
- **Update:** Edit favorite city entries.
- **Delete:** Remove cities from the favorites list.

## Live Demo
Experience the Weather Dashboard live at: [Weather Application](https://weatherito-dashboard.netlify.app/)

## Video Demo
Experience the Weather Dashboard live at: [Weather Application] (https://www.loom.com/share/236ef11969f140daaf6b276ab708f6a2?sid=8d1204ef-dab7-4410-838a-94304eec2d03)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
