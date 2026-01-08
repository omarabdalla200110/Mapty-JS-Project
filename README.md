# 🗺️ Mapty - Map Your Workouts

Mapty is a workout tracker application that allows users to log their running or cycling workouts based on their current location. It uses the **Geolocation API** to fetch coordinates and the **Leaflet Library** to render an interactive map.

## 📸 Preview
<img width="1918" height="867" alt="image" src="https://github.com/user-attachments/assets/28d11ffb-6dd2-4539-bad9-4c9119db9248" />

## 🚀 Live Demo
[View Live Site](https://omarabdalla200110.github.io/Mapty-JS-Project/)

## 🌟 Key Features
- **Geolocation Integration**: Automatically fetches the user's current position to center the map.
- **Interactive Map**: Click anywhere on the map to add a new workout location.
- **Custom Workout Data**: 
  - **Running**: Logs distance, time, and **Pace** (min/km).
  - **Cycling**: Logs distance, time, and **Speed** (km/h).
- **Data Persistence**: Workouts are saved in the browser's **LocalStorage**, so data is not lost when the page is reloaded.
- **Map Popups**: Custom styled markers and popups display the workout details and date.
- **Move to Marker**: Clicking a workout in the sidebar automatically pans the map to that specific marker.

## 🛠️ Built With
- **HTML5 & CSS3**: Layout and custom dark-theme styling.
- **JavaScript (ES6+)**: The core application logic.
- **Leaflet.js**: An open-source JavaScript library for mobile-friendly interactive maps.
- **OpenStreetMap**: The tile layer used for the map visual.

## 🧠 What I Learned
- **Object-Oriented Programming (OOP)**:
  - Structured the entire application using ES6 `Classes` (`App`, `Workout`, `Running`, `Cycling`).
  - Used **Inheritance** to share common properties (distance, duration) while keeping specific logic separate (cadence vs. elevation).
  - Implemented **Private Class Fields** (`#map`, `#workouts`) to protect data.
- **Geolocation API**: How to use `navigator.geolocation` to get browser coordinates.
- **External Libraries**: Learned how to read documentation and implement the **Leaflet** library to render maps and markers.
- **LocalStorage API**: Storing complex objects (arrays of workouts) using `JSON.stringify()` and retrieving them with `JSON.parse()`.
- **Project Architecture**: Planning the code structure (flowcharts) before writing the actual code.


---
*This project is part of The Complete JavaScript Course by Jonas Schmedtmann.*
