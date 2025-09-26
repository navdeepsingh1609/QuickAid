# 🚑 Quick Aid – Smart Accident Detection & Rapid Response System

[![Product Landing Page](https://img.shields.io/badge/🌐-Landing%20Page-navy?style=for-the-badge)](https://navdeepsingh1609.github.io/QuickAid/)
[![Device Demo](https://img.shields.io/badge/▶️-Device%20Demo-olive?style=for-the-badge)](https://drive.google.com/file/d/1w4qY6samHpi1G0tuCXOObkXv7N-5Hdz4/view?usp=sharing)
[![Introduction](https://img.shields.io/badge/▶️-Introduction-purple?style=for-the-badge)](https://www.youtube.com/watch?v=ih4bpkxB2-c)
[![Research Paper](https://img.shields.io/badge/Research%20Paper-blue?style=for-the-badge&logo=readthedocs)](https://drive.google.com/file/d/17TmLUnbFHxobFRn-noeoij4NYAGQFqyo/view?usp=drive_link)
[![License: MIT](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)](LICENSE)


[![Watch on YouTube](https://img.youtube.com/vi/ih4bpkxB2-c/0.jpg)](https://www.youtube.com/watch?v=ih4bpkxB2-c)  



## 📖 Project Overview

Quick Aid is a smart accident detection system designed to **reduce response time** and provide **instant first aid** by alerting authorities and emergency contacts.

The system uses data from onboard sensors (**accelerometer, gyroscope, GPS**) and **machine learning models** to detect accidents and automatically notify emergency services and pre-configured contacts with the user’s location.

✨ **Goal:** Ensure a safer commute — especially for motorcyclists in high-traffic areas — and reduce permanent disabilities and fatalities by **speeding up emergency response**.


## 🔬 Research Work 

This project is based on the following research work:

**Paper Title:** *QuickAid – Smart Accident Detection and Alert System*  
**Authors:** *Dr. Anju Bala, Banaj Bedi, Navdeep Singh, Paras Sood, Rachit Narang*  

[![Research Paper](https://img.shields.io/badge/Research%20Paper-blue?style=for-the-badge&logo=readthedocs)](https://drive.google.com/file/d/17TmLUnbFHxobFRn-noeoij4NYAGQFqyo/view?usp=drive_link)


## 🔍 How It Works

1. **Data Collection:** Device attached to the vehicle collects accelerometer, gyroscope, and GPS data.  
2. **Preprocessing:** Sensor signals are filtered, segmented, and features are extracted (time & frequency domain).  
3. **Modeling:** Trained ML models classify whether a segment indicates an accident. Supported models:  
   - Support Vector Classifier (SVC)  
   - K-Means (anomaly detection / clustering)  
   - Deep Learning (CNN/LSTM for temporal patterns)  
   - Logistic Regression (baseline)  
4. **Decision & Alerting:** On detection, the system sends an alert (with GPS coordinates) to emergency contacts and authorities and triggers mobile app notifications.  


## 📱 Mobile App Features

- Register & manage user profile.  
- Add / manage emergency contacts and devices.  
- Receive live notifications and alert history.  
- Share real-time GPS location with emergency responders.  

