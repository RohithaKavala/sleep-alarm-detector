😴 Sleep Alarm Detector
🚨 Real-Time Drowsiness Detection Using Computer Vision

Detects prolonged eye closure through a webcam and instantly triggers an alarm to prevent sleep, loss of focus, and microsleep incidents.







🌟 Overview

Sleep Alarm Detector is a real-time computer vision application that continuously monitors eye activity using a webcam and facial landmark tracking.

When the user's eyes remain closed beyond a defined threshold, the system immediately:

🚨 Activates an alarm
🔴 Displays a visual warning overlay
👁️ Tracks eye closure duration
⚡ Responds in real time

This project demonstrates practical applications of Computer Vision, Facial Landmark Detection, and Human State Monitoring.

✨ Key Features
Feature	Description
👁️ Eye Tracking	Monitors eye activity in real time
🧠 Face Mesh Detection	Uses MediaPipe's facial landmark model
⚡ Instant Detection	Detects prolonged eye closure
🔊 Alarm System	Plays warning sound automatically
📷 Webcam Monitoring	Live video processing
🎯 EAR Analysis	Eye Aspect Ratio based detection
🚨 Alert Overlay	Visual danger indication
💻 Lightweight	Fast and efficient execution
🛠️ Technology Stack
Technology	Purpose
Python	Core Application Development
OpenCV	Real-Time Video Processing
MediaPipe	Facial Landmark Detection
NumPy	Mathematical Calculations
Pygame	Alarm Playback
📂 Project Structure
sleep-alarm-detector/
│
├── sleep_alarm.py
├── alarm.mp3
├── requirements.txt
└── README.md
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/RohithaKavala/sleep-alarm-detector.git
cd sleep-alarm-detector
2️⃣ Install Dependencies
pip install -r requirements.txt
▶️ Run the Application
python sleep_alarm.py

Press Q to exit.

🧠 How It Works
Step 1 — Face Detection

MediaPipe Face Mesh detects facial landmarks from the webcam feed.

Step 2 — Eye Landmark Extraction

Eye-related facial landmarks are extracted in real time.

Step 3 — EAR Calculation

The Eye Aspect Ratio (EAR) is calculated continuously.

Step 4 — Drowsiness Detection

When EAR remains below the threshold for a predefined duration:

🔴 Alert mode activates
🔊 Alarm starts playing
🚨 Visual warning appears
Step 5 — Recovery

Once the eyes reopen, the alarm stops and monitoring resumes.

📸 Project Screenshots
🟢 Awake State

Add screenshot here

🔴 Alert State

Add screenshot here

🎯 Skills Demonstrated

✅ Computer Vision

✅ Real-Time Video Processing

✅ Facial Landmark Tracking

✅ MediaPipe Integration

✅ OpenCV Applications

✅ Event-Driven Programming

✅ Python Development

✅ Human State Monitoring

🚀 Future Improvements
📊 Drowsiness Statistics Dashboard
👁️ Blink Counter
📁 CSV Activity Logging
🎨 Improved User Interface
🔔 Multiple Alarm Options
🌐 Web Dashboard Integration
💡 What I Learned

Through this project, I gained hands-on experience with:

Real-time webcam applications
Computer vision workflows
MediaPipe Face Mesh
Eye Aspect Ratio (EAR) analysis
Alarm and event systems
Practical Python development
👨‍💻 Author
Rohitha Kavala

Final Year B.Tech CSE Student

Passionate about Software Development, Web Technologies, and building impactful real-world applications.

⭐ If you found this project interesting, consider giving it a star!
