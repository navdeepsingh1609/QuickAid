# Quick Aid -Smart Accident Detection & Rapid Response System

##  Project Overview

Quick Aid is a smart accident detection system designed to reduce response time and provide instant first aid by alerting authorities and emergency contacts.

The system uses data from onboard sensors (accelerometer, gyroscope, GPS) and machine learning models to detect accidents and automatically notify emergency services and pre-configured contacts with the user’s location.

**Goal:** Ensure a safer commute — especially for motorcyclists in high-traffic areas — and reduce permanent disabilities and fatalities by speeding up emergency response.

---

Live demo: [https://navdeepsingh1609.github.io/QuickAid/](https://navdeepsingh1609.github.io/QuickAid/)

YouTube demo: [https://www.youtube.com/watch?v=ih4bpkxB2-c](https://www.youtube.com/watch?v=ih4bpkxB2-c)

---
## 🔬 Research Work

This project is based on the following research work:

**Paper Title:** *QuickAid - Smart Accident Detection and Alert System*

**Authors:** *Dr. Anju Bala, Banaj Bedi, Navdeep Singh, Paras Sood, Rachit Narang*


📄  ([paper.pdf](https://drive.google.com/file/d/17TmLUnbFHxobFRn-noeoij4NYAGQFqyo/view?usp=drive_link))

---
## 🔍 How it works

1. **Data collection:** A device attached to the vehicle collects accelerometer, gyroscope and GPS data.
2. **Preprocessing:** Sensor signals are filtered, segmented, and features are extracted (time-domain and/or frequency-domain features).
3. **Modeling:** Trained ML models classify whether a segment indicates an accident. Supported models include:

   * Support Vector Classifier (SVC)
   * K-Means (used for anomaly detection/clustering)
   * Deep Learning model (e.g., CNN/LSTM) for temporal patterns
   * Logistic Regression (baseline)
4. **Decision & Alerting:** On detection, the system sends an alert (with GPS coordinates) to emergency contacts and authorities and triggers the mobile app notifications.

---

## 📱 Mobile App Features

* Register & manage user profile.
* Add / manage emergency contacts and devices.
* Receive live notifications and alert history.
* Share real-time GPS location with emergency responders.

---

