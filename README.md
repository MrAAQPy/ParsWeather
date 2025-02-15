### 🌤️ ParsWeather – Iran's Weather Information Package 🇮🇷  

ParsWeather is a Python package designed to fetch **real-time weather information** for cities across **Iran**. ☀️🌧️🌪️  

With this package, you can easily get **temperature, air quality, radar images, sunrise/sunset times, and more**! 📡🌎  

---

## 📥 Installation  

You can install **ParsWeather** using **pip**:  

```bash
pip install ParsWeather
```

---

## 🚀 How to Use  

Using **ParsWeather** is super simple! Here’s a quick example:  

```python
from ParsWeather import WeatherForecast as wf  

print(wf.get_temperature("تهران"))  # 🌡️ Get the current temperature  
print(wf.get_realfeel("تهران"))  # 🤔 Get the real feel temperature  
print(wf.get_air_quality("تهران"))  # 🍃 Get air quality status  
print(wf.get_air_quality_aqi("تهران"))  # 📊 Get air quality index (AQI)  
print(wf.get_dust_dander_data("تهران"))  # 🏜️ Check dust & allergen levels  
print(wf.get_weather_forecast("تهران"))  # 🌦️ Get the full weather forecast  
print(wf.get_radar_image_link("تهران"))  # 🛰️ Get a radar image link  
print(wf.get_sun_times("تهران"))  # 🌅 Get sunrise & sunset times  
print(wf.get_forecast_details("تهران"))  # 🔎 Detailed forecast information  
print(wf.get_supported_cities())  # 📍 List of supported cities  
print(wf.get_weather_forecast_air_aqi("تهران"))  # 🌍 Weather & AQI combined  
```

---

## 🏆 Why Use **ParsWeather**?  

✔ **Accurate & Up-to-Date** – Always provides the latest weather data.  
✔ **Easy to Use** – Just a few lines of code to get **detailed forecasts**.  
✔ **Comprehensive** – Covers **temperature, air quality, sunrise/sunset, radar images, and more!**  
✔ **Supports Persian Cities** – Designed specifically for **Iran**! 🇮🇷  

---

📌 **Get started today and never get caught in bad weather again!** ⛈️✨
