# 🌅 Sunset Forecast & Journal App

This is a desktop application built with Python and PySide6 that provides sunset and sunrise times, current weather conditions, a basic sunset quality prediction, and a unique "BeReal-like" journaling feature to capture and store your daily sunset photos and thoughts in a calendar format.

✨ Features
Geographical Sunset/Sunrise Forecast: Get accurate sunrise and sunset times for any location (by city name or latitude/longitude).

Real-time Weather Tracking: Display current weather conditions (clouds, humidity, visibility, temperature) for the specified location.

Sunset Quality Prediction (Basic & AI Placeholder):

Basic Logic: A rule-based system to predict sunset quality based on weather parameters.

AI Placeholder: Structure in place to integrate a more sophisticated Machine Learning model for enhanced predictions in the future.

Daily Sunset Journal (BeReal-like):

Post a photo of your daily sunset.

Add a caption to describe your experience.

Entries are stored locally in a SQLite database.

Calendar Journal View:

Browse your past sunset entries in an intuitive calendar format.

Click on a date to view the photo, caption, and associated weather/quality data for that day.


📝 How to Use
Forecast Tab:

Enter a city name or a latitude, longitude pair in the input field.

Click "Go" or press Enter to fetch sunset times and weather data for that location.

Click "Refresh Data" to update the information for the current location.

Observe the "Sunset Quality (Basic)" and "Sunset Quality (AI)" predictions.

Post Sunset Tab:

Click "Select Photo" to choose a sunset image from your computer.

Add a descriptive caption in the text area.

Click "Post Sunset" to save your entry to the journal. The app will automatically associate the current location and weather data from the "Forecast" tab with your post.

Journal Calendar Tab:

The calendar will highlight days for which you have posted a sunset entry.

Click on a highlighted date to view the photo, caption, and associated weather and quality information for that specific sunset.

💡 Future Enhancements
Advanced AI Model: Train a more sophisticated ML model (e.g., using TensorFlow or PyTorch) for highly accurate sunset quality predictions, potentially incorporating satellite imagery or more detailed atmospheric data.

Webcam Integration: Allow users to capture photos directly from their webcam for the "Post Sunset" feature.

Interactive Map: Integrate a map widget to visually select locations.

Notifications: Implement daily reminders to post a sunset.

User Accounts: For multi-user support (if desired, would require a more robust database/backend).

Cloud Sync: Sync journal entries to a cloud service (e.g., Firebase, AWS S3) for backup and cross-device access.

Data Visualization: Add charts or graphs to visualize sunset quality trends over time.
