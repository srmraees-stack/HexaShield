# HexaShield

> **Nature-Inspired Smart Dust Control & Air Quality Monitoring System for Construction Sites**

HexaShield is a biomimetic construction dust mitigation platform inspired by the airflow behavior of beehives. The project combines smart environmental sensing, real-time monitoring, and airflow-aware dust control concepts to help reduce PM2.5 pollution around construction zones.

This repository contains the frontend dashboard prototype for monitoring environmental conditions such as:
- Air Quality Index (AQI)
- MQ-135 Gas Sensor Readings
- Temperature & Humidity
- Light Intensity (LDR)
- ESP32-based live sensor integration

---

#Problem Statement

Construction sites contribute significantly to urban air pollution.

Fine particulate matter such as PM2.5 spreads rapidly through airflow and affects:
- Construction workers
- Nearby residents
- Schools & hospitals near active sites
- Elderly people and children

Traditional dust barriers mainly block visibility rather than controlling airborne particulate movement.

HexaShield approaches this problem differently:

> Instead of fighting airflow, it works *with* airflow using biomimetic design principles inspired by beehives.

---

#Biological Inspiration

HexaShield takes inspiration from natural honeycomb structures found in beehives.

## Why Hexagons?
- High structural strength
- Efficient material usage
- Better airflow distribution
- Natural particle interaction surfaces

Inside a beehive:
- Air slows down through narrow hexagonal pathways
- Pollen particles collide with sticky wax walls
- Clean air continues flowing while particles remain trapped

HexaShield adapts this principle for smart construction dust management.

---

#Features

## 📊 Smart Monitoring Dashboard
Interactive real-time dashboard displaying:
- AQI values
- MQ-135 gas sensor readings
- Temperature
- Humidity
- LDR light intensity

##Login Interface
Animated login experience with futuristic industrial styling.

##Live Sensor Charts
Integrated visualizations using Chart.js.

##Alert System
Automatic environmental alerts for unsafe sensor conditions.

##ESP32 Integration
Supports ESP32-based environmental sensor communication.

##Biomimetic UI Design
Custom hexagonal animated interface inspired by honeycomb structures.

---

#Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Frontend Structure |
| CSS3 | UI Styling & Animations |
| JavaScript | Dashboard Logic |
| Chart.js | Data Visualization |
| ESP32 | Sensor Communication |
| MQ-135 | Air Quality Monitoring |
| DHT Sensor | Temperature & Humidity |
| LDR | Light Intensity Detection |

---

#Project Structure

```bash
HexaShield/
│
├── index.html
├── styles.css
├── index.js
├── sensorData.json
└── README.md
```

---

#Getting Started

## Clone the Repository

```bash
git clone https://github.com/srmraees-stack/HexaShield.git
cd HexaShield
```

## Run the Project

Open:

```bash
index.html
```

in your browser.

No additional installation is required.

---

# Sensor System

Example sensor data:

```json
{
  "temperature": 24.7,
  "humidity": 41.9,
  "ldr": 2568,
  "gas": 520,
  "aqi": 29
}
```

Future versions aim to support:
- Real-time ESP32 streaming
- Cloud-based analytics
- Predictive AQI alerts
- Construction compliance monitoring
- Smart dust filtration feedback systems

---

# Vision

HexaShield aims to become:
- A smart dust-control infrastructure system
- A sustainable alternative to traditional green construction nets
- A scalable urban environmental protection platform
- A real-time compliance and monitoring solution for smart cities

---

# Future Improvements

- IoT cloud integration
- Live sensor streaming
- Mobile application
- AI-based dust prediction
- GIS-based pollution heatmaps
- Smart filtration analytics
- Deployment-ready construction modules

---

# Dashboard Preview

Add screenshots or demo GIFs here.

Suggested additions:
- Login screen
- AQI dashboard
- Sensor charts
- ESP32 connection workflow

---

# 💡 Tagline

> **“Nature-Inspired Dust Solutions for Smarter Cities.”**
