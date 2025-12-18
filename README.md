🪞 GEN-Z Smart Mirror (AI + IoT Based Interactive Mirror)
📌 Project Overview

The GEN-Z Smart Mirror is an intelligent, AI-powered interactive mirror designed to enhance daily personal care and smart living. It integrates Artificial Intelligence, Computer Vision, and IoT sensors to provide real-time environmental monitoring, face analysis, emotion detection, gesture control, and personalized grooming recommendations.

Unlike traditional mirrors, this system acts as a smart personal assistant, offering contextual insights, safety alerts, and hands-free interaction using gestures.

🎯 Key Features

👤 Face Detection & Analysis

Gender estimation

Emotion recognition

Face-shape identification

💇 AI-based Hairstyle Recommendation

Personalized suggestions based on face shape, gender, and emotion

✋ Gesture Control

Palm detection for hands-free interaction

🌡️ Environmental Monitoring

Temperature & humidity (DHT11)

Air quality monitoring (MQ-135)

Ambient light detection (LDR)

⚠️ Alert System

LED, buzzer, and fan activation on abnormal conditions

💡 Automatic Brightness & Cooling Control

🖥️ Real-Time Smart Display

Time, sensor data, alerts, and AI outputs

🛠️ Technologies Used
Hardware

Raspberry Pi 4 Model B

DHT11 Temperature & Humidity Sensor

MQ-135 Gas Sensor

LDR Sensor

USB Webcam

Relay Module & Cooling Fan

LEDs & Buzzer

7-inch HDMI Display

Two-Way Acrylic Mirror

Software

Programming Language: Python 3

Operating System: Raspberry Pi OS

Libraries & Frameworks:

OpenCV

TensorFlow / Keras

MediaPipe

NumPy

Adafruit_DHT

RPi.GPIO

IDE: Visual Studio Code

🧠 System Architecture

The system follows a layered architecture:

Input Layer: Sensors & webcam capture environmental and facial data

Processing Layer: Raspberry Pi performs AI inference and decision-making

Output Layer: Display, LEDs, buzzer, and fan provide feedback and alerts

⚙️ How It Works

Sensors continuously collect temperature, humidity, gas, and light data

Webcam captures the user’s face

AI models analyze:

Gender

Emotion

Face shape

Personalized hairstyle recommendations are generated

Gesture detection enables hands-free control

Alerts are triggered if unsafe conditions are detected

All results are displayed in real time on the smart mirror screen

▶️ How to Run the Project
Prerequisites

Raspberry Pi with Raspberry Pi OS installed

Python 3 installed

Camera & sensors connected properly

Steps
# Clone the repository
git clone https://github.com/your-username/gen-z-smart-mirror.git

# Navigate to project directory
cd gen-z-smart-mirror

# Install required libraries
pip3 install -r requirements.txt

# Run the main program
python3 main.py

📊 Testing & Performance

Face detection latency: < 300 ms

Gesture recognition response: < 1 second

Sensor refresh rate: Every 2 seconds

System stability tested for 6+ hours continuous run

🏆 Achievements

Presented at CICADA 2025 Project Expo

Participated in InnovateX 2025 Technical Fest

Recognized for innovation and practical implementation

🚀 Future Enhancements

Voice assistant integration (Google Assistant / Alexa)

Cloud & mobile app support

Biometric authentication (fingerprint / iris)

AR-based virtual try-on (hairstyles, cosmetics)

Health & fitness monitoring

Smart home automation integration

👨‍💻 Project Team

Anusha P K

Chandu C

Nagraj

Sai Charan Tej P N

Guide: Dr. Shabeen Taj G A
Department of Computer Science & Engineering
Government Engineering College, Ramanagara
