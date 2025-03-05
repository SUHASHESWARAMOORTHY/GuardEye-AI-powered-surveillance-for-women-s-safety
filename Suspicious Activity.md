# 🚨 Woman Safety Analytics System (Version 2.0)

## 📌 Overview  

This project is an upgraded version of the Woman Safety Analytics System. In this version, **gesture detection has been removed**, and the system now focuses on detecting **suspicious activities** using **bounding boxes** around humans. It analyzes the **distance between individuals** and **how long they remain in close proximity**. The system ensures accuracy by verifying that the bounding boxes belong to the same individuals.  

## 🛠 Features  

- **Human Detection using Bounding Boxes**: Identifies people within CCTV footage.  
- **Proximity Analysis**: Measures the distance between individuals.  
- **Time-Based Suspicious Activity Detection**: Tracks how long people remain close.  
- **Automated Alerts**: Sends alerts to authorities if potential threats are identified.  
- **No Hand Gesture Detection**: Focuses entirely on **spatial analysis** instead.  

## 🔧 Technical Implementation  

- **Object Detection Model**: Tracks and generates bounding boxes.  
- **Distance & Duration Calculation**: Measures proximity and time duration.  
- **MQTT-Based Alert System**: Sends immediate notifications.  
- **Image Logging**: Captures and stores frames of suspected activities.  

## 🚀 How to Run  

1. 📂 **Access the required files**  
   - Download the **suspicious-activity-gdrive.txt** file, which contains a link to the dataset and script.  
   - Inside the drive folder, download **WO_cv2draw_box_copy.py** (the main execution file).  

2. 🖥 **Run the system**  
   - Open a **terminal** and navigate to the directory where the script is saved.  
   - Run the script using:  
     ```sh
     python WO_cv2draw_box_copy.py
     ```  
   - A pop-up window will open, analyzing **human bounding boxes** for suspicious activity.  

## 🎯 Future Enhancements  

- AI-based behavior analysis for better threat detection.  
- Edge processing for real-time analysis.  

## EXAMPLE IMAGE 

![IMG-20250305-WA0012](https://github.com/user-attachments/assets/047e47f4-8c1a-4988-9c63-cc9736fc1593)


---
