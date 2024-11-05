Here is the demo of this project 

[Demo Link](https://utkarsh-weather-app-anand.netlify.app) 

# Weather App

## Project Overview

The Weather App is a dynamic web application developed using React.js that provides real-time weather information for any city around the world. Users can easily search for a city and receive data including temperature, humidity, wind speed, and other essential weather details. This project demonstrates the use of React's component-based architecture, state management, and API integration.

## Features

- **Search Functionality**: Users can input any city name to fetch its current weather information.
- **Real-Time Data**: The app utilizes the OpenWeatherMap API to display up-to-date weather data.
- **Responsive Design**: The application is designed to be fully responsive, ensuring a seamless experience on both desktop and mobile devices.
- **Weather Details**: Displays various weather parameters such as:
  - Current Temperature
  - Humidity
  - Wind Speed
  - Weather Conditions (e.g., clear, cloudy, rainy)
- **User-Friendly Interface**: Intuitive UI for easy navigation and interaction.

## Technologies Used

- **React.js**: JavaScript library for building user interfaces.
- **OpenWeatherMap API**: External API used to fetch real-time weather data.
- **CSS/SCSS**: For styling the application and ensuring responsiveness.
- **Axios**: For making HTTP requests to the weather API.

## Getting Started

To get a local copy of the project up and running, follow these simple steps:

### Prerequisites

- Node.js (v14 or later)
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Install the required packages:
   ```bash
   npm install
   ```

4. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace it in the `src/config.js` file:
   ```javascript
   const API_KEY = 'YOUR_API_KEY';
   ```

5. Start the application:
   ```bash
   npm start
   ```

6. Open your browser and visit `http://localhost:3000` to view the app.

## Usage

- Enter the name of a city in the search bar.
- Click on the search button or press Enter to fetch the weather information.
- The app will display the current weather conditions, including temperature, humidity, and wind speed.

## Contributing

Contributions are welcome! If you would like to contribute to the Weather App, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- [React.js](https://reactjs.org/) for making web development more efficient.







