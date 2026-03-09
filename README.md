<!-- 🌌 Animated Header -->
<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=220&section=header&text=Hand%20Gesture%20Volume%20Control&fontSize=45&fontColor=ffffff&animation=fadeIn"/>
</p>

<!-- ⌨ Typing Animation -->
<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Control+System+Volume+With+Hand+Gestures;Computer+Vision+Project;OpenCV+%2B+MediaPipe+%2B+Python"/>
</p>

---

# 🏆 Tech Badges

![Python](https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FF6F00?logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)

---

# 📌 Project Overview

**Hand Gesture Volume Control** is a computer vision project that allows you to control system volume using hand gestures captured from a webcam.

This project uses **MediaPipe Hand Tracking** to detect hand landmarks and **OpenCV** for image processing. The distance between the **thumb and index finger** controls the volume level.

---

# 🧠 AI / Computer Vision Explanation

This project uses **hand landmark detection** provided by MediaPipe.

Steps involved:

1️⃣ Capture webcam frames using OpenCV  
2️⃣ Convert frame to RGB format  
3️⃣ MediaPipe detects **21 hand landmarks**  
4️⃣ Extract coordinates of thumb and index finger  
5️⃣ Calculate distance using **Euclidean distance**  
6️⃣ Map distance to system volume level  

Volume adjustment is performed using **Pycaw library**.

---

# 📊 Project Architecture


Webcam
│
▼
OpenCV Video Capture
│
▼
MediaPipe Hand Detection
│
▼
Landmark Extraction
│
▼
Distance Calculation
│
▼
Volume Mapping
│
▼
System Volume Control


---

# 📷 Live Demo

Add your demo GIF or screenshot here.

Example:



Or screenshot:



---

# 📦 Required Python Packages


opencv-python
mediapipe
numpy
pycaw
comtypes


---

# ⚙ Installation Guide

## 🪟 Windows

Clone repository


git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git


Move into project folder


cd YOUR_REPOSITORY_NAME


Install required packages


pip install opencv-python mediapipe numpy pycaw comtypes


Run the program


python volume_control.py


---

## 🐧 Linux

Clone repository


git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git


Move into project folder


cd YOUR_REPOSITORY_NAME


Install dependencies


pip3 install opencv-python mediapipe numpy pycaw comtypes


Run program


python3 volume_control.py


---

# ▶ Usage

1️⃣ Run the script  
2️⃣ Show your hand in front of the camera  
3️⃣ Move **thumb and index finger closer or farther**  
4️⃣ Volume will increase or decrease accordingly  

Press **SPACEBAR** to stop the program.

---

# 🚀 Future Improvements

• Add mute gesture  
• Multi-hand support  
• GUI interface  
• Cross-platform audio control  

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=120&section=footer"/>
</p>
