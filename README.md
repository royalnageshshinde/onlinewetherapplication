# onlinewetherapplication

# Weather API

A simple weather API built with **Node.js** and **Express.js** to fetch weather data for predefined cities.

## Features
- Get weather details (temperature, condition) for cities.
- Supports metric (Celsius) and imperial (Fahrenheit) units.

## Installation
1. Clone the repository and navigate to the project folder:
   ```bash
   mkdir weather-api && cd weather-api
   ```
2. Initialize and install dependencies:
   ```bash
   npm init -y && npm install express
   ```
3. Add the server code to `server.js`.

## Usage
1. Start the server:
   ```bash
   node server.js
   ```
2. Make requests:
   - Example: `http://localhost:3000/weather?units=metric&q=London`

## Deployment
Deploy to platforms like netlify or Vercel for public access.

## License
Licensed under MIT. Modify as needed.
