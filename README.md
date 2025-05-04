# Sensor Data Storage to Cloud using CC3200 TI Launchpad

This project demonstrates a smart, cloud-connected sensor system that reads data from a DHT11 sensor (temperature and humidity) and an LDR (light intensity), and uploads it to the cloud using the **CC3200 TI Launchpad** and the **Blynk IoT platform**. Users can monitor environmental data in real-time via the Blynk console on any device with internet access.

## 🔧 Key Features

- 📶 Real-time data acquisition and transmission using Wi-Fi-enabled CC3200 microcontroller
- 🌡️ Measures temperature and humidity using DHT11 sensor
- 💡 Measures light intensity using LDR sensor
- ☁️ Sends sensor data to Blynk cloud for remote monitoring
- 📱 Interactive Blynk dashboard with gauge widgets and LED indicators

## 📐 System Overview

### Hardware Components:
- CC3200 TI Launchpad (Wi-Fi enabled MCU)
- DHT11 Temperature and Humidity Sensor
- LDR (Light Dependent Resistor) Module
- Breadboard, Jumper Wires, USB Cable

### Software Tools:
- [Energia IDE](http://energia.nu/)
- Blynk App and Blynk Cloud Console

## 📊 How It Works

1. The CC3200 Launchpad continuously reads sensor data from DHT11 and LDR.
2. Data is transmitted to the **Blynk Cloud** via Wi-Fi.
3. Users can view live data on the **Blynk mobile app** or **web dashboard**.
4. A virtual LED reflects the LDR state (light detected or not).

## 🚀 Setup Instructions

1. **Install Energia IDE** and necessary board packages for CC3200.
2. **Upload the Arduino-compatible code** to CC3200 using Energia.
3. **Configure Blynk:**
   - Create a new project.
   - Add two Gauge widgets (for temperature and humidity).
   - Add one LED widget (for LDR status).
   - Use your `auth token`, SSID, and password in the code.
4. **Connect hardware**, power the board, and open the Blynk app to start monitoring!

## ✅ Advantages

- Remote access to real-time sensor data
- Low-cost, portable setup
- Ideal for industrial and healthcare environments where environmental monitoring is critical

## ⚠️ Limitations

- The system currently supports **monitoring only** — not control actions like fan automation.

## 🔮 Future Scope

- Add automated device control (e.g., fans, lights)
- Integrate more sensors like gas, motion, or sound
- Store data on cloud platforms like Firebase or AWS for long-term analysis

## 🏫 Institution

**Prof. Ram Meghe College of Engineering and Management**, Amravati  
Department of Electronics & Telecommunication Engineering  
Academic Year: 2022–2023
