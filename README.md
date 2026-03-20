# 🌤️ SkyFetch - Weather Dashboard

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![HTML](https://img.shields.io/badge/HTML5-Markup-orange?logo=html5)
![CSS](https://img.shields.io/badge/CSS3-Styling-blue?logo=css3)
![API](https://img.shields.io/badge/API-OpenWeatherMap-lightblue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A beautiful and interactive weather dashboard that provides **real-time weather data and 5-day forecasts** for any city worldwide.

---

## 🚀 Live Demo

👉 https://skyfetch-weather-dashboard-iota.vercel.app

---

## 📌 Why This Project

- 🌍 Real-world **API integration project**
- ⚡ Optimized using **Async/Await + Promise.all()**
- 🧠 Structured using **Prototypal Inheritance (OOP)**
- 💾 Persistent user data with **localStorage**
- 📱 Designed with **responsive UI & great UX**

---

## ✨ Features

- 🔍 Search weather for any city worldwide
- 🌡️ Current temperature, conditions, and icon
- 📊 5-day weather forecast
- 💾 Recent searches saved locally
- 🔄 Auto-load last searched city
- ⏳ Loading spinner during API calls
- ❌ Error handling for invalid inputs
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

| Category        | Technology |
|----------------|-----------|
| Structure      | HTML5 |
| Styling        | CSS3 (Grid, Flexbox, Animations) |
| Logic          | JavaScript (ES6+) |
| API Calls      | Axios |
| Weather API    | OpenWeatherMap API |
| Storage        | localStorage |

---

## 🧠 Key Concepts Demonstrated

- Prototypal Inheritance (OOP)
- Constructor Functions & Prototype Methods
- Async/Await & Promises
- Promise.all() for parallel API calls
- DOM Manipulation
- Event Handling
- Error Handling (try-catch)
- localStorage API
- Responsive Web Design

---

## 🧩 Features Breakdown

### 🌦️ Weather Functionality
- Fetch current weather data
- Fetch 5-day forecast
- Process forecast into daily summaries
- Display icons, temperature, and descriptions

### ⚡ API Optimization
- Axios for API calls
- Async/Await for cleaner code
- Promise.all() for parallel requests (faster performance)

### 🧠 OOP Architecture
- WeatherApp constructor function
- Prototype methods for modular structure:
  - init()
  - handleSearch()
  - getWeather()
  - getForecast()
  - displayWeather()
  - displayForecast()

### 💾 Data Persistence
- Save recent searches (max 5)
- Avoid duplicate entries
- Auto-load last searched city
- Clear history functionality

### 🔍 Search & UX
- Enter key support
- Input validation
- Disabled button during loading
- Loading spinner feedback
- User-friendly error messages

### 🎨 UI/UX Enhancements
- Responsive layout (mobile-first)
- Forecast cards with grid layout
- Hover effects and animations
- Clean and modern interface

---

## 🧪 Testing

- ✅ Tested with multiple cities (London, Paris, New York, Tokyo)
- ✅ Valid city search works correctly
- ✅ Invalid city error handling works
- ✅ Empty input validation tested
- ✅ Loading state verified
- ✅ Enter key functionality tested
- ✅ localStorage persistence verified
- ✅ Responsive design across devices
- ✅ No console errors

---

## 📸 Screenshots

<img width="1469" height="835" src="https://github.com/user-attachments/assets/0d2408f1-59c3-4856-bffc-e33ecb96d3e6" />
<img width="1467" height="832" src="https://github.com/user-attachments/assets/9181d74b-3ba7-4b71-9e13-2291486484a8" />
<img width="1470" height="834" src="https://github.com/user-attachments/assets/b83a90f7-9975-47ec-8b54-89feab151829" />

---

## 📁 Project Setup

```bash
# Clone the repository
git clone https://github.com/your-username/skyfetch.git

# Navigate to project
cd skyfetch

# Open in browser
open index.html
```

---

## 🏆 Technical Highlights

### Why Prototypal Inheritance?
- Memory efficient
- Shared methods across instances
- Clean and scalable structure
- Industry-relevant JS pattern

### Why Promise.all()?
- Faster API responses
- Parallel data fetching
- Improved user experience

---

## 🧠 Architecture Overview

```
User Input (Search City)
        │
        ▼
Event Listener (handleSearch)
        │
        ▼
WeatherApp Controller (OOP)
        │
        ├── getWeather() ───────► OpenWeather API
        │
        ├── getForecast() ─────► OpenWeather API
        │
        ▼
Promise.all() (Parallel Calls)
        │
        ▼
Data Processing Layer
        │
        ├── processForecastData()
        │
        ▼
UI Rendering
        │
        ├── displayWeather()
        ├── displayForecast()
        │
        ▼
DOM Update (UI Update)
        │
        ▼
localStorage (Recent Searches)
```

---

## ⚡ Performance Metrics

| Metric        | Score |
|--------------|------|
| Performance  | 95+ 🚀 |
| Accessibility| 90+ ♿ |
| Best Practices | 95+ ✅ |
| SEO          | 90+ 🔍 |

---

## 🔮 Future Enhancements

- 📍 Geolocation-based weather detection
- 🌡️ Temperature unit toggle (°C / °F)
- 🌙 Dark mode
- ⏰ Hourly forecast
- 🌪️ Weather alerts
- 📡 Offline support (PWA)

---

## 📝 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Author

**Arpita Singh**

- GitHub: https://github.com/arpitasi1gh  
- LinkedIn: https://www.linkedin.com/in/arpitasi1gh/

---

## 🙏 Acknowledgments

- Weather data provided by OpenWeatherMap API  
- Icons from OpenWeatherMap  
- Built as part of Frontend Web Development Advanced Course  
