# ✋ Hand Gesture-Based Woman Safety System  

## 📌 Overview  
This project enhances **women's safety** by recognizing **hand gestures** as distress signals. Using **computer vision and deep learning**, the system detects an **"OK" sign** from a human subject and triggers an emergency alert. The system is designed to work with **CCTV cameras** and **MQTT-based alert mechanisms**, ensuring **real-time response** to distress signals.  

## 🔍 Key Features  
- **Hand Gesture Recognition:** Detects the **"OK" hand sign** as a distress signal.  
- **Gender Identification:** Determines whether the subject is **male or female**.  
- **Automated Alert System:**  
  - 🚨 **Sends an SOS alert** to authorities via **MQTT**.  
  - 📸 **Captures and stores** images of the suspect.  
  - 🔊 **Activates a buzzer** to notify nearby people.  
- **Real-time Processing:** Uses **deep learning models** for fast and accurate detection.  
- **Edge Device Communication:** Alerts are processed and transmitted using **ESP32 and ESP8266**.  

## 🛠 Technologies Used  
- **YOLO Model** for real-time object and gesture detection.  
- **OpenCV & Mediapipe** for hand sign recognition.  
- **MQTT Protocol** for instant alert communication.  
- **Edge Processing** with **ESP32 & ESP8266** for local response.  
- **Google Colab for Cloud Processing** (requires GPU for execution).  

## 🚀 How It Works  
1. 📷 **Camera captures a human subject** in real-time.  
2. 🏷 **Gender detection** is performed.  
3. ✋ **Hand gesture recognition** checks for the **"OK" sign**.  
4. ⚡ If the **OK gesture** is detected:  
   - 🚨 **An SOS alert is sent** to authorities via **MQTT**.  
   - 📸 **Image of the suspect is captured and saved**.  
   - 🔊 **Buzzer is triggered** to alert nearby individuals.  

## 📂 Setting Up the System  
1. Download **hand-gesture-recognition-mediapipe.zip** from the **Hand Gesture GDrive link.txt** file.  
2. Extract the folder and navigate to it.  
3. Run **app.py** in the terminal (**requires a GPU-enabled system**).  
4. A **pop-up window** will open, detecting hand gestures.  
5. If the **"OK" sign** is detected, the alert mechanism is triggered.  

## EXAMPLE IMAGE

![image](https://github.com/user-attachments/assets/4493e5a1-af96-46a9-abd9-51446d82eee4)

