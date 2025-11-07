# 🌡️ Smart Weather Station

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?logo=raspberrypi)
![License](https://img.shields.io/badge/License-MIT-green)

## 📝 Description
My first IoT project - a smart weather station that monitors temperature and humidity in real-time using Raspberry Pi. The system features an LCD display for data visualization and a buzzer for temperature alerts.

## 🛠️ Technologies Used
- Python 3 - Main programming language
- RPi.GPIO - GPIO control library
- DHT11 - Temperature and humidity sensor
- LCD 1602 - Display for showing data
- Buzzer - Sound alerts for high temperature
- Raspberry Pi - Single-board computer

## 🚀 Features
- Real-time temperature monitoring
- Humidity level tracking
- LCD display output
- Sound alerts when temperature is too high
- Error handling for sensor failures

## 🔧 Installation & Usage
`bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/smart-weather-station.git

# Navigate to project directory
cd smart-weather-station

# Run the application
python src/main.py
