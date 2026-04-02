# weatherapp
# ☁️ Nimbus Weather
Nimbus is a sleek, responsive weather application built with vanilla JavaScript. It provides real-time weather data and dynamic forecasts using the Open-Meteo API for a fast, key-free experience.

<p align="center">
  <img src="nimbus-logo.png" alt="Nimbus Logo" width="200">
</p>

---

## 🚀 Features
* **No-Key Setup:** Powered by the [Open-Meteo API](https://open-meteo.com/), so you don't need to manage API keys.
* **Real-time Updates:** Displays current temperature, wind speed, and weather codes.
* **Geolocation:** Automatically fetches weather data based on latitude and longitude.
* **Dynamic Backgrounds:** The UI transitions based on current weather conditions.
* **Responsive Design:** Fully optimized for desktop, tablet, and mobile viewing.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **API:** [Open-Meteo](https://open-meteo.com/)
* **Icons:** FontAwesome / Weather Icons

---

## ⚙️ Installation & Setup
To run Nimbus locally on your machine:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/nimbus-weather.git](https://github.com/your-username/nimbus-weather.git)
    ```
2.  **Navigate to the project directory**
    ```bash
    cd nimbus-weather
    ```
3.  **Launch the App**
    * Open `index.html` in your favorite browser. 
    * *Note: Since Open-Meteo is a public API, no API key configuration is required!*

---

## 📂 Project Structure
```text
nimbus/
├── index.html      # App structure and layout
├── style.css       # Custom styling and animations
├── script.js       # Logic for Open-Meteo fetch and UI updates
├── nimbus-logo.png # Application logo
└── assets/         # Local images and icons
