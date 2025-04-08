# 🌐 Smart Sensor Dashboard

A futuristic, real-time sensor dashboard built using **HTML, JavaScript, CSS**, and powered by **Blynk IoT Cloud**. It monitors and visualizes environmental data like temperature, humidity, AQI, and soil moisture using responsive cards and live charts.

---

## 🚀 Features

✅ Real-time data visualization using `Blynk Cloud`  
✅ Animated dark-themed UI with `Chart.js` line graphs  
✅ Live alerts based on thresholds (AQI, temperature, soil moisture)  
✅ Full CSV export of historical sensor logs  
✅ Mobile-responsive design  
✅ External Blynk dashboard launch button  
✅ Embedded external dashboards (if extended)

---

## 📦 Technologies Used

- **HTML5, CSS3, JavaScript (ES6+)**
- **Blynk Cloud API** – for fetching sensor data
- **Chart.js** – for responsive data visualizations
- **Google Fonts (Orbitron)** – for a sci-fi aesthetic
- **Responsive Flexbox Layout** – mobile-first design

---

## 🧠 Data Sources & Pins

Data is retrieved from Blynk Cloud using a set of virtual pins mapped as:

| Sensor Type       | Virtual Pin |
|-------------------|-------------|
| Humidity          | V0          |
| AQI               | V1          |
| Temperature       | V2          |
| Alerts (not used) | V3          |
| Soil Moisture G1  | V4          |
| Soil Moisture G2  | V5          |

> Make sure your Blynk device is configured with the correct virtual pins before deploying.

---

## 📁 Project Structure

```bash
📦 smart-sensor-dashboard/
├── index.html           # Main dashboard page
├── README.md            # Project overview and usage
