# 🚑 AmbuRouteAI

An AI-powered smart traffic signal system for ambulances — built using YOLOv8 and OpenCV.



## 🔍 Overview

**AmbuRouteAI** detects ambulances in real-time using computer vision and dynamically manages traffic lights to ensure a clear path for emergency vehicles. This project reduces emergency response time and can be integrated into smart city systems.

---

## ⚙️ Features

- ✅ Real-time ambulance detection using YOLOv8
- ✅ Automated traffic signal control with OpenCV
- ✅ Live video or webcam feed support
- ✅ Easy integration with IoT and smart infrastructure
- ✅ Scalable and customizable Python codebase

---

## 🛠️ Tech Stack

| Component       | Technology          |
|----------------|---------------------|
| AI Detection    | YOLOv8 (Ultralytics) |
| Vision & I/O    | OpenCV, NumPy       |
| Backend         | Python              |
| Simulation      | OpenCV              |

---

## 🚀 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/Koushik-http/AmbuRouteAI.git
cd AmbuRouteAI
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# To run with a traffic video
python main.py -p traffic_video.mp4

# To run with a live webcam
python main.py -l

