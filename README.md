
## 📌 Overview

The **Woman Safety Analytics System** is an AI-powered surveillance solution designed to detect and respond to potential threats in public spaces using CCTV cameras. 
# Traditional CCTV systems are reactive, meaning they only record footage and require manual monitoring to detect threats.
# This system is proactive, using AI-driven real-time analysis to detect potential threats before an incident escalates, ensuring faster response and improved safety 

The system has evolved over two versions:

- **Version 1.0:** Used **gesture detection** to recognize an **"OK" sign** as a distress signal.
- **Version 2.0:** Removed gesture detection and now **analyzes human bounding boxes** to identify **suspicious activities** based on proximity and duration of interactions.

## 🛠 Features

### ✅ **Version 1.0 – Hand Gesture-Based Safety System**

- **Detects "OK" Hand Sign** as a distress signal.
- **Gender Identification** to verify if the subject is male or female.
- **Automated Alert System**:
  - 🚨 **Sends an SOS alert** to authorities via **MQTT**.
  - 📸 **Captures suspect images** for security analysis.
  - 🔊 **Buzzer Activation** for nearby warnings.
- **Uses OpenCV & Mediapipe** for gesture detection.

### 🔄 **Version 2.0 – Suspicious Activity Detection (Bounding Box-Based)**

- **No Hand Gesture Detection** – Now focuses on **human proximity & duration analysis**.
- **Bounding Box Tracking**: Monitors humans within CCTV footage.
- **Proximity & Time-Based Analysis**: Detects prolonged close interactions.
- **Automated Alerts via MQTT** when potential threats are detected.
- **Image Logging** to capture suspicious activity.

## 🔧 Technologies Used

- **YOLO Model** for real-time object detection.
- **OpenCV & Deep Learning** for tracking and recognition.
- **MQTT Protocol** for instant alert communication.
- **ESP32 & ESP8266** for Edge Processing.
- **Strong Edge **processing (GPU recommended).ed).
