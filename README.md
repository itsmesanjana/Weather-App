# Weather App

This Weather App is a simple web application created using HTML, CSS, and JavaScript. It allows users to check the current weather conditions for a specific location, including temperature, humidity, wind speed, and more.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [API Used](#api-used)
- [Contributing](#contributing)


## Features

- Current weather display: Shows the current weather conditions for a specified location.
- Temperature units: Allows users to switch between Celsius and Fahrenheit units.
- Location search: Users can search for a specific location to check its weather.
- Responsive design: The app is designed to be responsive and work well on different screen sizes.

## Demo

A live demo of the Weather App can be accessed [here](https://65b7ba44e0090e07109ed0f7--luminous-arithmetic-24a518.netlify.app/).

## Installation

To run the Weather App locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the `index.html` file in your web browser.

Alternatively, you can use a local development server such as [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in Visual Studio Code to run the project.

## Usage

Once the Weather App is running, follow these steps to check the weather:

1. Enter a location in the search bar.
2. Press the "Search" button or hit Enter.
3. The current weather conditions for the specified location will be displayed.

You can also switch between Celsius and Fahrenheit units by clicking on the respective buttons.

## API Used

This Weather App utilizes the [OpenWeatherMap API]('https://api.openweathermap.org/data/2.5/weather') to fetch weather data for different locations.

To use the OpenWeatherMap API, you need to sign up for an API key and replace the placeholder in the `scripts/weather.js` file with your actual API key.

```javascript
const apiKey = '6b471c16bf715fd4155162d2a3272bad';
