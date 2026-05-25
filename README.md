<img width="607" height="459" alt="image" src="https://github.com/user-attachments/assets/c743b7b9-0fea-443e-aa1f-de65a17744f4" /># SmartWalk: Parkinson’s Disease Detection and Gait Analysis System

##  Project Overview

SmartWalk is an IoT and Machine Learning-based wearable gait analysis system developed for the early detection and monitoring of Parkinson’s Disease (PD). The system analyzes gait parameters such as cadence, knee flexion variability, and double limb support time (DLST) using sensor-based smart footwear and wearable modules.

The project combines embedded systems, real-time data acquisition, and machine learning algorithms to classify healthy individuals and Parkinson’s patients based on walking patterns.

---

##  Objectives

- Detect abnormal gait patterns associated with Parkinson’s Disease
- Monitor postural stability and walking behavior in real time
- Predict fall risk using gait analysis
- Classify healthy individuals and PD patients using Machine Learning
- Provide real-time alerts using buzzer and vibration feedback

---

##  System Components

### Hardware Components
- ATmega 2560 Microcontroller
- Instrumented Shoes with FSR Sensors
- Knee Flexion Recorder (Bend Sensor)
- Ultrasonic Sensor (HC-SR04)
- Vibration Sensor
- Buzzer

### Software & Tools
- Arduino IDE
- Google Colab
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

##  Machine Learning Models Used

### 1. K-Means Clustering
- Used for gait pattern classification
- Number of clusters: 2
  - Healthy Individuals
  - Parkinson’s Patients
- Features Used:
  - Cadence
  - Double Limb Support Time (DLST)
  - Knee Flexion Variability

### 2. Gaussian Mixture Model (GMM)
- Used for probabilistic gait classification
- Provides soft clustering for overlapping gait patterns
- Better handling of mild Parkinson’s symptoms compared to K-Means

---

##  Features Extracted

The system analyzes:
- Heel-Strike Events
- Toe-Off Events
- Cadence
- Stride Length
- Knee Flexion Variability
- Double Limb Support Time (DLST)
- Postural Stability
- Turning Hesitation

---

##  Project Workflow

1. Sensor Data Collection
2. Real-Time Gait Monitoring
3. Data Storage using SD Card
4. Feature Extraction
5. Data Processing in Google Colab
6. Machine Learning-Based Classification
7. Real-Time Alert Generation

---

##  Results

- Successfully differentiated Parkinson’s patients from healthy individuals
- Achieved approximately 87% classification accuracy using K-Means Clustering
- GMM clustering improved classification for overlapping gait patterns
- Real-time vibration and buzzer alerts helped detect gait instability and freezing of gait (FoG)
  <img width="607" height="459" alt="image" src="https://github.com/user-attachments/assets/7d0513bc-5143-44a0-a88a-2d1234c8543e" />


---

##  Applications

- Early Detection of Parkinson’s Disease
- Fall Risk Prediction
- Remote Patient Monitoring
- Rehabilitation and Therapy Assessment
- Elderly Care and Assistive Healthcare Systems

---


