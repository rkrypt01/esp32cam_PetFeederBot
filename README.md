

# 🐾 PetFeederBot – ESP32-CAM Telegram Pet Feeder  

**PetFeederBot** is an automated pet feeder controlled via a Telegram bot. It allows pet owners to dispense food and receive live images from the ESP32-CAM module. The system ensures pets are fed on time and offers remote monitoring. 

<img src="https://github.com/user-attachments/assets/37f3dd4a-5740-4b71-bde5-364d7e1d3539" width="300">


## 📌 Features  
- Dispense pet food remotely using Telegram commands  
- Capture and send real-time photos from the ESP32-CAM  
- Toggle LED flash for better visibility in low light  
- Check device status and connectivity via Telegram  

## 🛠️ Requirements  
- **ESP32-CAM**  
- **Servo Motor (SG90 or MG995)**  
- **Telegram Bot API**

## 🔌 Circuit Diagram 
<img src="https://github.com/user-attachments/assets/76f7b72a-f4c4-48bb-a4a6-6061a933ee90" width="500">


## 🔧 Setup Instructions  

### 1️⃣ Connect the ESP32-CAM to Wi-Fi  
Modify the following lines in the code with your **Wi-Fi credentials**:  

```cpp
const char* ssid = "wifi name";
const char* password = "wifi password";
```

### 2️⃣ Set Up Telegram Bot  
- Create a **Telegram bot** using [@BotFather](https://t.me/BotFather).  
- Get your **Bot Token** and replace it in the code:  

```cpp
String BOTtoken = "YOUR_BOT_TOKEN_HERE";
```

- Find your **Chat ID** using [@myidbot](https://t.me/myidbot) and update:  

```cpp
String CHAT_ID = "YOUR_CHAT_ID_HERE";
```

### 3️⃣ Install required libraries, upload the code and Run!

