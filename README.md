# 🚗 AI-Powered Driver Monitoring System

A real-time, vision-based driver monitoring system designed to detect drowsiness, distraction, and unsafe behavior using object detection and pose estimation. The system uses YOLOv5 for detecting driver-related objects and OpenPose to estimate body posture and facial landmarks. It triggers instant alerts to help reduce road accidents and improve transportation safety.

---

## 🧠 Technologies Used

- **YOLOv5** – Real-time object detection (e.g., mobile phone usage, seatbelt)
- **OpenPose** – Human pose and facial keypoint estimation
- **OpenCV** – Video stream handling and image processing
- **Python** – Core scripting and alert system
- **PyTorch** – Deep learning framework for YOLOv5
- **Sound/Visual Alerts** – For notifying drowsiness or distractions

---

## 🚀 Key Features

- 🔍 Detects drowsiness through eye blink rate and head posture
- 📵 Identifies distractions like phone use, yawning, or looking away
- 🔊 Triggers real-time visual or sound alerts
- 🧠 Analyzes driver pose to infer unsafe behavior
- 📹 Works on webcam/live stream input
- 💻 Lightweight and optimized for edge devices

---

## 🛠️ How It Works

1. **Input**: Real-time video stream (webcam or dashcam)
2. **Detection**:
   - YOLOv5 detects key objects (e.g., phone, hand positions).
   - OpenPose estimates driver pose and facial landmarks.
3. **Analysis**:
   - Drowsiness via eye closure and yawning detection
   - Distraction via gaze deviation and body pose
4. **Response**: Alerts are triggered using sound or pop-up visuals

---

