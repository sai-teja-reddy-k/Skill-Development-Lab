# Weather Information Visualization Using ES6 Features

**Developed by Saiteja**

## Table of Contents

1. [Aim](#aim)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Installation & Setup](#installation--setup)
5. [Usage](#usage)
6. [API Configuration](#api-configuration)
7. [File Structure](#file-structure)
8. [License](#license)

## Aim

To explore and implement modern ES6 features—arrow functions, callbacks, Promises, and async/await—by building a weather application that fetches real-time data from the OpenWeatherMap API and visualizes it using Chart.js.

## Technologies Used

* **HTML5** for page structure
* **CSS3** for styling and layout
* **JavaScript (ES6+)** for application logic
* **Chart.js** for graphical data visualization
* **OpenWeatherMap API** for real-time weather data

## Features

* Fetches current weather data from OpenWeatherMap
* Validates user input to ensure a non-empty city name
* Utilizes Promises and async/await for API calls
* Dynamically updates the UI with weather details:

  * Temperature
  * Humidity
  * Weather description
* Visualizes temperature and humidity in a bar chart using Chart.js
* Handles errors gracefully with user-friendly messages

## Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-repo/weather-visualization.git
   ```
2. **Navigate to the project directory**

   ```bash
   cd weather-visualization
   ```
3. **Open the application**

   * Launch `index.html` in your web browser.

## Usage

1. Enter a valid city name into the input field.
2. Click the **Fetch Weather** button.
3. View the current temperature, humidity, and weather description.
4. Inspect the bar chart for a visual comparison of temperature and humidity.

## API Configuration

1. Register at [OpenWeatherMap](https://openweathermap.org/) and obtain an API key.
2. In `script.js`, replace the placeholder with your actual API key:

   ```javascript
   const apiKey = 'YOUR_API_KEY';
   ```

## File Structure

```plaintext
weather-visualization/
├── css/
│   └── styles.css         # Custom styles for layout and charts
├── js/
│   └── script.js          # Fetch logic and ES6 feature implementations
├── index.html             # Main application page
└── README.md              # Project documentation
```

## License

This project is licensed under the [MIT License](LICENSE).
