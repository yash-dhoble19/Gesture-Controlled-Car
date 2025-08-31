# 🤖 Gesture Controlled Car using ESP32 + OpenCV + MediaPipe

This project demonstrates a **gesture-controlled robot car** powered by an **ESP32** and a **laptop camera**.  
The car connects to Wi-Fi and listens for **UDP packets** containing driving commands (`f, b, l, r, s`).  
A Python script uses **MediaPipe Hands** to track gestures in real-time and sends these commands over the network.

---





## 📌 Features
- ✋ **Gesture Recognition** using MediaPipe
- 📡 **UDP Communication** between PC → ESP32
- 🚗 **Motor Control** (forward, back, left, right, stop) via L298N H-Bridge
- ⚡ Low-latency, real-time response
- 🛑 Safety stop function

---

## 🛠️ Hardware Requirements
- ESP32 Dev Board  
- Motor Driver Module (L298N or L293D)  
- 2 DC Motors + Robot Chassis + Wheels  
- Battery Pack (7.4V – 12V recommended)  
- Laptop/PC with webcam  

---

## 🧑‍💻 Software Requirements
- Arduino IDE with ESP32 Board Package
- Python 3.9+ with required libraries:
  ```bash
  pip install opencv-python mediapipe
