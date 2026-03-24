# 🌤️ Weather App

A responsive weather application built with **React.js** that fetches real-time weather data using the OpenWeatherMap API.

---

## 🚀 Features

- 🔍 Search weather by city name
- 🌡️ Displays real-time temperature and weather conditions
- 🖼️ Dynamic weather icons (Clouds, Rain, Clear, Mist, Error)
- ⚡ Fast and responsive UI built with React
- 🌐 Powered by OpenWeatherMap API

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| React.js | Frontend framework |
| JavaScript (ES6+) | App logic |
| CSS | Styling |
| OpenWeatherMap API | Weather data |

---

## 📁 Project Structure
```
weather-app/
├── public/
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── Components/
│   │   ├── Myapp.js
│   │   └── Weather.js
│   ├── images/
│   │   ├── Clouds.png
│   │   ├── Rain.png
│   │   ├── Clear.png
│   │   ├── mist.png
│   │   └── error.png
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

**2. Install dependencies**
```bash
npm install
```

**3. Add your API Key**

Open `src/Components/Myapp.js` and replace the API key:
```js
const API_KEY = "your_openweathermap_api_key_here";
```

**4. Start the development server**
```bash
npm start
```

App runs at `http://localhost:3000`

---

## 🌐 API Reference
```
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
```

---

## 📦 Build for Production
```bash
npm run build
```

---

## 📄 License

MIT License

---

## 👤 Author

**Your Name**  
GitHub: [@ysharadjha](https://github.com/sharadjha)
