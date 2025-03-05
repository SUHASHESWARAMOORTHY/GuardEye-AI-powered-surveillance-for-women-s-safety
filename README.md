# GuardEye-AI-powered-surveillance-for-women-s-safety
The Woman Safety Analytics System is an AI-powered surveillance solution that utilizes CCTV cameras for gender detection and gesture recognition to identify distress signals. Upon detecting potential threats or violence, the system triggers SOS alerts to authorities for immediate response. It employs advanced computer vision algorithms to monitor .


# 🚨 Woman Safety Analytics System

## 📌 Overview  
The **Woman Safety Analytics System** is an AI-powered surveillance solution utilizing **CCTV cameras** for **gender detection and gesture recognition** to identify distress signals. Upon detecting potential threats or violence, the system **triggers SOS alerts** to authorities and **notifies nearby individuals**. This system ensures **public security** through automated threat detection and rapid emergency response.  

## 🔍 Key Features  
- **Gender Detection:** Identifies whether the subject is male or female.  
- **Hand Gesture Recognition:** Detects the **"OK" sign** as a distress signal.  
- **Automated Alert System:** If a distress gesture is detected:  
  - 🚀 **Sends an SOS alert** to authorities using **MQTT**.  
  - 🔊 **Activates a buzzer** to alert nearby people.  
- **Violence Detection:** Recognizes violent activities in the monitored area.  
- **Real-time Monitoring:** Uses **computer vision algorithms** for continuous analysis of CCTV footage.  

## 🛠 Technologies Used  
- **YOLO Model** for real-time object detection.  
- **OpenCV & Deep Learning** for gesture and gender recognition.  
- **MQTT Protocol** for instant alert communication.  
- **Edge Processing** using ESP modules for local response.  

## 🚀 How It Works  
1. 📷 **Camera captures a human subject** in the monitored area.  
2. 🏷 **Gender is identified** (Male/Female).  
3. ✋ **Hand gesture detection** is performed to check for the **"OK" sign**.  
4. 🔔 If an **"OK" sign** is detected:  
   - 🚨 **Alert sent to authorities via MQTT**.  
   - 🔊 **Buzzer activated** to notify nearby individuals.  
5. ⚠️ **System also detects instances of violence** and triggers alerts accordingly.  

## 🎯 Goal  
To enhance **women's safety** by leveraging **AI-powered surveillance**, enabling **quick response** to distress situations in **public spaces**.  

---
