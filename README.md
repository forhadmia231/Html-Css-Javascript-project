# 🌦️ Weather Application

A simple and beautiful weather app built using **HTML**, **CSS**, and **JavaScript**.  
This app fetches real-time weather data from the **OpenWeatherMap API** and displays the current temperature, humidity, wind speed, and weather condition for any city in the world.

---

## 🖼️ Preview
![Weather App Screenshot](images/preview.png)

---

## 🧩 Features
- 🌍 Search weather by city name  
- 🌡️ Displays temperature in Celsius  
- 💧 Shows humidity percentage  
- 🌬️ Displays wind speed  
- ⛅ Dynamic weather icons (Rain, Clouds, Clear, Drizzle, Mist)  
- ⚠️ Error message for invalid city names  

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **OpenWeatherMap API**

---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   ****
   cd weather-app
const apikey = "2006b9858c3fb022791dbc0cfed0666a";

   git clone https://github.com/forhadmia231/weather-app.git

   weather-app/
│
├── index.html
├── style.css
├── README.md
└── images/
    ├── preview.png
    ├── search.png
    ├── clouds.png
    ├── clear.png
    ├── rain.png
    ├── drizzle.png
    ├── mist.png
    ├── humidity.png
    └── wind.png

const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";
const response = await fetch(apiUrl + city + `&appid=${apikey}`);


