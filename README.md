# RespiGuard: IoT Respiratory Monitoring System

Final-year project for the **Internet of Things** module of my BSc (Hons) Computing Science at Coventry University (CU London).

RespiGuard is a working IoT system that remotely monitors elderly patients living with **COPD** (chronic obstructive pulmonary disease). It collects respiratory sensor readings, sends them to the cloud and shows each patient's data in a mobile app and a computer dashboard, with an alert whenever a reading is unsafe.

## How it works

1. **Sensors + Arduino Uno** collect the patient's respiratory readings.
2. **Python** processes the readings and sends the data to the **cloud**.
3. A **MySQL** backend stores the readings so each patient's data can be analysed over time.
4. A **mobile app** and a **computer dashboard** show the data for remote monitoring.
5. If a reading falls outside a safe range, the system sends an **alert**.

## Tech used

- Arduino Uno and sensors
- Python
- Cloud data transfer and storage
- MySQL
- Mobile app and computer dashboard

## My role

I managed the project independently, from requirements through design, build, testing and the final report.

## Status

This repository documents the project. Source code and screenshots will be added.

---

👤 **Daksh** · [LinkedIn](https://www.linkedin.com/in/daksh-computing) · [GitHub](https://github.com/daksh-computing)
