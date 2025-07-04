#  Smart Blind Stick Using Arduino

This project presents a **Smart Blind Stick** designed to assist visually impaired individuals by detecting obstacles using an ultrasonic sensor and alerting them through a buzzer and LED. The core objective is to enhance mobility and safety with affordable electronics.

## 📦 Components Used

- 🧠 **Arduino Uno** – Microcontroller for processing sensor input and controlling outputs  
- 📡 **Ultrasonic Sensor (HC-SR04)** – For obstacle detection by measuring distance  
- 💡 **LED** – Visual alert when obstacle is detected  
- 🔊 **Buzzer** – Audio alert to notify the user of nearby objects  
- 🔋 **9V HW Battery** – Power source for portability  
- 🔌 **Wires, Breadboard or PCB** – For circuit assembly  

## ⚙️ Working Principle

The ultrasonic sensor continuously sends out ultrasonic waves and receives the reflected signals. When an object is detected within a defined range, the Arduino processes this data and:

- Activates the **buzzer** to produce sound
- Turns on the **LED** for visual indication

This provides real-time feedback to the user, helping them navigate around obstacles.

## 🔧 How to Use

1. Assemble the components as per the circuit diagram.
2. Upload the Arduino code via Arduino IDE.
3. Power the circuit using a 9V battery.
4. Move the stick around — buzzer and LED will alert you if an object is nearby.

## 🛠️ Applications

- Assisting visually impaired people in navigating indoor/outdoor environments
- Can be extended with GPS, vibration motors, or IoT features for advanced usage
