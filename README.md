# Live Weather Dashboard

A sleek, responsive, single-page web application that provides real-time weather data for any city in the world. This project demonstrates core frontend development skills, including DOM manipulation, asynchronous JavaScript, and third-party API integration.

## Features
* **Real-Time Data:** Fetches live meteorological data (temperature, conditions, humidity) using the OpenWeatherMap API.
* **Asynchronous JavaScript:** Implements modern `async/await` syntax and the `fetch` API to handle network requests efficiently without blocking the main thread.
* **Responsive UI:** Features a modern, card-based interface styled entirely with custom CSS (no external CSS frameworks required).
* **Error Handling:** Gracefully handles invalid city inputs and network errors, displaying user-friendly feedback.
* **Zero Dependencies:** Built purely with HTML5, CSS3, and Vanilla JavaScript.

## Tech Stack
* **HTML5** (Structure)
* **CSS3** (Styling & Animations)
* **Vanilla JavaScript** (Logic & API calls)
* **OpenWeatherMap API** (Data Source)

## Installation & Setup

Because this is a pure frontend application, there is no build step or server setup required.

1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/NikhilBhima-24/live-weather-dashboard.git](https://github.com/NikhilBhima-24/live-weather-dashboard.git)
   cd live-weather-dashboard
   ```

2. **API Key Configuration:**
   * Go to [OpenWeatherMap](https://openweathermap.org/) and create a free account to get an API key.
   * Open `index.html` in your text editor.
   * Locate the line `const API_KEY = 'YOUR_API_KEY_HERE';` around line 55.
   * Replace `YOUR_API_KEY_HERE` with your actual API key.

## Usage
Simply double-click the `index.html` file to open it directly in any modern web browser. Enter a city name into the search bar and hit "Search" to view the live weather conditions.
