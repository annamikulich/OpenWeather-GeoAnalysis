# 🌍 WeatherPy – Global Weather Analysis with OpenWeatherMap API

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to gather weather data for over 500 randomly selected global cities. The goal is to analyze and visualize weather patterns based on latitude.

---

## 🧠 Project Goals

- Generate 500+ random geographic coordinates
- Match them to real-world cities using `citipy`
- Fetch live weather data via OpenWeatherMap API
- Perform climate analysis by latitude
- Visualize temperature, humidity, wind speed, and cloudiness

---

## 🗂 Project Structure

WeatherPy/
├── WeatherPy.ipynb # Main notebook (data collection + analysis)
├── VacationPy.ipynb # Optional travel recommendation extension
├── api_keys.py # API keys (not included in repo)
├── .gitignore # Hides API keys from version control
└── README.md


---

## 🔧 Technologies Used

- `matplotlib` – for visualization
- `pandas`, `numpy` – for data handling
- `requests` – for API calls
- `citipy` – to map lat/lon to nearest city
- `OpenWeatherMap` – weather data source

---

## 🗝 Setup Instructions

1. Create a file called `api_keys.py`:

```python
# api_keys.py
weather_api_key = "your_api_key_here"
Install required libraries:
pip install pandas matplotlib numpy requests citipy
Run the WeatherPy.ipynb notebook
📊 Example Visuals

Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Wind Speed
Latitude vs. Cloudiness
Each chart helps answer:
How does the weather change as we move north or south?

📦 Output

The project outputs a city_data_df with fields like:

City | Country | Lat | Lon | Temp (F) | Humidity (%) | Wind Speed | Cloudiness
🧭 Bonus: VacationPy

Use the VacationPy.ipynb to filter cities by ideal weather conditions and plot hotel locations on a map using Google Places API.

📌 Use Cases

Weather trend analysis for travel planning
Machine learning feature generation (e.g. temp by region)
Data storytelling for geography or climate education
