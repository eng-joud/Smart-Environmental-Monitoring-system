# Smart Environmental Monitoring System

An end-to-end IoT and software systems solution designed to collect, process, and display real-time environmental data (Temperature & Humidity) using ESP32 and cloud protocols.

---

## 🏗️ System Architecture

![System Architecture](./architecture-diagram.png)

### Architecture Overview

1. **Sensor Level:** DHT22 collects real-time temperature and humidity metrics.
2. **Edge Processing:** ESP32 microcontroller processes sensor signals via GPIO pins.
3. **Data Transport:** Metrics are published using the MQTT protocol over Wi-Fi.
4. **Cloud & Visualization:** Data is ingested into Adafruit IO for real-time dashboard analytics.

---

## 🛠️ Tech Stack & Tools

* **Software Architecture:** Draw.io (Data Flow & System Design)
* **Embedded Controller:** ESP32 Microcontroller
* **Sensors:** DHT22 Temperature & Humidity Sensor
* **Protocols:** MQTT / Wi-Fi
* **Cloud Platform:** Adafruit IO Dashboard
* **Programming Language:** C++ (Arduino Framework)
