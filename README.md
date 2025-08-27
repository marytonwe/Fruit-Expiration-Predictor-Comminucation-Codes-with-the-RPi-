# Fruit Expiration Predictor with Raspberry Pi & Embedded AI

Tackling the challenge of food waste with a low-cost, embedded AI system that predicts fruit ripeness and lifespan non-invasively. This was our final year undergraduate project, developed in collaboration with my project partner, Emmanuel Ibiang.

## Problem Statement

Globally, over 30% of food is wasted, and nearly half of that is fruits and vegetables. This system aims to reduce that loss by providing an affordable, automated way for suppliers and consumers to monitor their produce.

## How It Works

A suite of sensors connected to a Raspberry Pi gathers environmental data from the fruit (e.g., ambient temperature, humidity, and volatile organic compound (VOC) gas levels). This data is then fed into a lightweight machine learning model running directly on the Raspberry Pi for fast, offline predictions (Edge AI).

### Key Features
- **Hardware Prototyping:** A custom sensor array integrated with a Raspberry Pi.
- **Sensor Integration:** Python scripts to handle real-time data collection from multiple sensors.
- **Embedded Machine Learning:** A trained classification model deployed on-device.
- **TALS in Action:** The entire system is **Low-cost**, **Adaptable** to different fruits, and built with **Scalable**, available components (**Thin computing**).

## Tech Stack & Components
- **Hardware:** Raspberry Pi, DHT22 Sensor, MQ-series Gas Sensor.
- **Software:** Python
- **Libraries:** Scikit-learn (for the ML model), Pandas, RPi.GPIO

## Results & Impact

On a small test dataset of 30 bananas under controlled lab conditions, the system achieved 97% accuracy in distinguishing expiration grades. While preliminary, these results highlight the potential of low-cost, non-invasive technology to reduce food waste in the supply chain. Future work will test additional fruit types and larger datasets to validate generalization.
