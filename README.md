# Weather_in_JS

A simple JavaScript application for retrieving and displaying weather information. This project demonstrates how to interact with a weather API, process JSON responses, and dynamically update the user interface with current weather data.

## Features

- Fetches real-time weather data for any city using a public weather API.
- Displays temperature, weather conditions, humidity, and wind speed.
- Responsive, user-friendly interface.
- Written in plain JavaScript—no frameworks required.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (optional, only if you want to run a local server)
- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nexusameer/Weather_in_JS.git
   cd Weather_in_JS
   ```

2. **(Optional) Start a local server:**
   - You can use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for VSCode or run a simple server using Node.js:
     ```bash
     npx serve .
     ```
   - Alternatively, open `index.html` directly in your browser.

3. **Get a Weather API key:**
   - Sign up for a free API key at [OpenWeatherMap](https://openweathermap.org/api) or another weather data provider.
   - Add your API key to the configuration section in the JavaScript code (see comments in `script.js` or similar file).

## Usage

1. Open the application in your browser.
2. Enter the name of a city and click "Get Weather".
3. View the current weather information displayed on the page.

## Example

![Weather App Screenshot](screenshot.png)

## Configuration

Locate the section in your JavaScript file where the API key is set, and replace `'YOUR_API_KEY'` with your actual key:

```js
const apiKey = 'YOUR_API_KEY'; // <-- Replace with your API key
```

## Project Structure

```
Weather_in_JS/
├── index.html
├── script.js
├── style.css
└── README.md
```

- `index.html` – Main HTML file
- `script.js` – JavaScript logic to fetch and display weather
- `style.css` – Styling for the app
- `README.md` – Project documentation

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for suggestions and improvements.
