## 🔒 SmartCam-Lock Security System

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&color=00008B&center=true&vCenter=true&width=800&height=100&duration=4000&lines=SmartCam-Lock+Security+System+🔐;" />
</h1>
## Features

- **ESP32-CAM:** Captures real-time photos when motion is detected.
- **PIR Motion Sensor:** Detects movement and triggers the camera.
- **Solenoid Lock with Relay Control:** Secure your doors with remote control.
- **Telegram Integration:** Sends photos and lock control options via Telegram for remote security management.
- **Instant Alerts:** Notifies you instantly when someone approaches the device.

## Components Used

- ESP32-CAM (Microcontroller with Camera)
- PIR Motion Sensor (Passive Infrared Sensor)
- Solenoid Lock
- Relay Module (for controlling the lock)
- Jumper Wires
- Power Supply

## How It Works

The **ESP32-CAM** captures images whenever the **PIR Motion Sensor** detects movement near the system. The captured image is immediately sent via **Telegram**, allowing the user to verify the event. Through Telegram, the user can remotely control the **solenoid lock** (unlock/lock) via the relay module, enhancing the security system's flexibility and remote management.

## Installation

1. Clone the repository:
   <div align="center">
    <a href="https://github.com/TechArcanist/SmartCam-Lock-Security-System.git">
        <img src="https://img.shields.io/badge/Clone_Repository-007ACC?style=for-the-badge&logo=github&logoColor=white" />
    </a>
   </div>

2. Set up the ESP32-CAM and install the required libraries for the camera, Telegram, and relay control.

3. Upload the code using the Arduino IDE or PlatformIO and configure the Telegram Bot Token and Chat ID.

## Usage

- The PIR motion sensor triggers the ESP32-CAM to take a picture when movement is detected.
- The photo is sent via Telegram for you to view.
- Using the Telegram interface, you can lock or unlock the solenoid lock based on the situation.
- This makes it ideal for smart home security where you can monitor and control access remotely.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/3b16d8c9-d111-4b15-bd52-812120de0c24)


## Video Demonstration

https://github.com/user-attachments/assets/1edc0d9c-5074-49bd-9e3f-be521f7ef96b

## Developed by

**Lavitra Sahu**. Contributions are welcome!

## Future Improvements

- Add face recognition for enhanced identification.
- Integrate video streaming capabilities.
- Develop a mobile app for seamless access and management of the security system.

---

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&color=00008B&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Thanks+for+Visiting!+👋;" />
</h1>
