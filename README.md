

# 🌤️ Weather Forecast App – Tech Assessment 1

This project is my submission for **Tech Assessment 1** as part of the application for the **AI Engineer Intern position at Product Manager Accelerator (PMA)**.

It’s a clean, responsive, and real-time weather forecasting app that allows users to search for weather conditions in any location — by city, town, landmark, or zip code — and provides useful, visual weather data based on their query.

---

## ✅ What This App Can Do

* 🔍 **Search for weather** by any location — zip, city, landmark, or coordinates.
* 📍 Option to **use current GPS location** to get weather instantly.
* 🌡️ Displays **current weather** conditions:

  * Temperature
  * Feels-like
  * Humidity
  * UV Index
  * Wind Speed
  * Cloud Cover
* 📅 Includes a **5-day forecast** with date, temperature, and conditions.
* 🕒 Option to view **hourly forecast** (toggle button).
* 🗺️ Embeds a **Google Map** for the searched location.
* 🎨 Built with responsive UI for both desktop and mobile users.

---

## 💡 Why This App?

The goal of this assessment was to simulate a real-world product where users can check weather across locations and receive relevant forecast information, not just for today — but the days ahead. To make it helpful and user-centric:

* I enabled GPS-based search so users can check weather wherever they are.
* Added a toggle for hourly forecasts, in case someone is planning something time-sensitive.
* Used WeatherAPI to ensure **live**, **accurate**, and **non-static** data.
* Added visual elements like emojis and cards for clearer UX.
* Embedded Google Maps so users can **visualize the area** they're looking up.

---

## 🔧 Technologies Used

| Layer      | Tools & Frameworks                                 |
| ---------- | -------------------------------------------------- |
| Frontend   | React (Vite), Tailwind CSS, React Router           |
| APIs       | WeatherAPI, Browser Geolocation, Google Maps Embed |
| Deployment | Vercel (Frontend Hosting)                          |

---

## 📁 Folder Structure

```
src/
├── components/
│   ├── SearchBar.jsx
│   ├── WeatherCard.jsx
│   ├── ForecastList.jsx
│   ├── HourlyForecast.jsx
│   ├── MapView.jsx
├── App.jsx
├── App.css
└── main.jsx
```

---

## 🎯 Assessment 1 Requirements: ✅ Covered

| Requirement                                   | Status |
| --------------------------------------------- | ------ |
| Search by city, zip, coordinates, landmark    | ✅      |
| Display current weather with useful info      | ✅      |
| Use live API (no static data)                 | ✅      |
| Add 5-day forecast                            | ✅      |
| Show weather based on user’s current location | ✅      |
| Use icons or visual styling                   | ✅      |
| Responsive and user-friendly UI               | ✅      |

---

## 🙋‍♀️ About Me

**Anusha Shiva Kumar**

Graduate Research Assistant • Passionate about Data Science & Full Stack Development
[LinkedIn](https://linkedin.com/in/anusha-shiva-kumar) · [GitHub](https://github.com/your-username)

---
