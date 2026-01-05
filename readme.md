🌦️ Weather App
A sleek, modern weather dashboard that provides real-time atmospheric data using the OpenWeatherMap API. This project demonstrates advanced JavaScript techniques including async/await, dynamic DOM manipulation, and responsive CSS design.

🚀 Live Demo
[Insert your GitHub Pages link here]

✨ Features
Real-time Data: Fetches live temperature, humidity, and weather conditions.
Dynamic Visuals: Custom weather emojis and gradient backgrounds that reflect current conditions.
Smart Error Handling: Graceful handling of "City Not Found" or empty search queries with visual shake animations.
Responsive Design: Uses clamp() and Flexbox to ensure a beautiful experience on both mobile and desktop.
🛠️ Technical Breakdown
📡 API Integration
The app communicates with the OpenWeatherMap API to retrieve JSON data. It uses the fetch API wrapped in an async function to ensure smooth, non-blocking UI updates.

🧠 Logic Highlights
Data Destructuring: Efficiently extracts data from complex nested API responses.
Condition Mapping: A custom getWeatherEmoji function uses weather IDs (e.g., 200 for Thunderstorm, 800 for Clear) to display the correct icon.
DOM Manipulation: Elements are created and appended dynamically to the card container.