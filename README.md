# 🌅 Sunset Forecast & Journal App

A **Python + PySide6** desktop application that provides real-time **sunset and sunrise forecasts**, **weather conditions**, and a **“BeReal-like” journaling feature** to capture and reflect on your daily sunsets — all displayed in an intuitive calendar view.

---

## ✨ Features

### 🌇 Geographical Forecast
- Accurate **sunrise and sunset times** for any location (by city or coordinates).

### 🌤️ Real-time Weather Tracking
- Displays **current weather data** including clouds, humidity, visibility, and temperature.

### 🌈 Sunset Quality Prediction
- **Basic Logic:** Rule-based system estimating sunset quality using weather parameters.  
- **AI Placeholder:** Framework ready for future integration of a machine learning model for enhanced prediction accuracy.

### 📸 Daily Sunset Journal
- Upload a **photo and caption** of your daily sunset.  
- Entries are saved locally in a **SQLite database**.  
- Acts as a digital “BeReal-like” sunset diary.

### 📅 Calendar Journal View
- Browse past sunset posts in an **interactive calendar**.  
- Click a date to view the photo, caption, and recorded weather/prediction data.

---

## 🧭 How to Use

### 🕓 Forecast Tab
1. Enter a **city name** or **latitude, longitude** coordinates.  
2. Click **Go** or press Enter to fetch **sunset, sunrise, and weather data**.  
3. Use **Refresh Data** to update information.  
4. View predictions for **Basic** and **AI** sunset quality.

### 📷 Post Sunset Tab
1. Click **Select Photo** to upload your sunset image.  
2. Add a **caption** describing your experience.  
3. Click **Post Sunset** to save your entry — automatically linked with current weather and forecast data.

### 📖 Journal Calendar Tab
- Highlighted days show when entries were posted.  
- Click a date to view its **photo**, **caption**, and **associated weather/prediction** details.

---

## 💡 Future Enhancements

- 🤖 **Advanced AI Model:** Integrate ML (TensorFlow / PyTorch) for high-accuracy sunset predictions using satellite and atmospheric data.  
- 📸 **Webcam Capture:** Allow direct photo uploads from webcam.  
- 🗺️ **Interactive Map:** Select locations visually.  
- 🔔 **Daily Notifications:** Remind users to post sunsets.  
- 👤 **User Accounts:** Add multi-user support and secure login.  
- ☁️ **Cloud Sync:** Enable backups via Firebase or AWS S3.  
- 📊 **Data Visualization:** Add charts for sunset quality trends.

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Framework:** PySide6 (Qt for Python)  
- **Database:** SQLite  
- **APIs:** Weather & Geolocation APIs  
- **Tools:** Pillow, Requests, Matplotlib (planned for visualization)

---

## 📫 Connect

- **LinkedIn:** [linkedin.com/in/filippo-di-marzio](https://www.linkedin.com/in/filippo-di-marzio)  
- **GitHub:** [github.com/Filippo-Dimarzio](https://github.com/Filippo-Dimarzio)  
- **Email:** fdmvlogs@gmail.com
