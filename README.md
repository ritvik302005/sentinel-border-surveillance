# 🛡️ SENTINEL — Border Surveillance System



> **A real-time AI-powered border surveillance system with advanced threat detection, person tracking, night vision, and intelligent zone monitoring.**

---



---

## ⚡ Features

- 🎯 **Real-time Person Detection** — YOLOv8-powered multi-person tracking with unique ID assignment
- 🚨 **Loiter Detection** — Flags individuals who stay in a zone beyond a threshold time
- 👥 **Surge Detection** — Detects sudden crowd gatherings or mass movements
- 🌙 **Night Vision Mode** — Enhanced low-light video processing for 24/7 surveillance
- 📍 **Restricted Zone Drawing** — Draw custom sectors and tripwires on the video feed
- 📊 **Threat Level System** — Dynamic LOW / MEDIUM / HIGH threat status display
- 🎥 **Live Video Feed** — Real-time WebSocket-based video streaming
- 🗂️ **Alert Log** — Auto-recorded event history with timestamps

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Python, FastAPI |
| AI/ML | YOLOv8 (Ultralytics) |
| Video | OpenCV |
| Streaming | WebSocket (uvicorn[standard]) |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Node.js 16+
- pip

### Backend Setup
```bash
cd border\ survailance
pip install -r requirements.txt
pip install 'uvicorn[standard]'
python run.py
```

### Frontend Setup
```bash
cd surveillance-dashboard
npm install
npm start
```

The app will be available at `http://localhost:3000`

---

## 📁 Project Structure

```
sentinel-border-surveillance/
├── border survailance/        # Python Backend
│   ├── run.py
│   └── requirements.txt
└── surveillance-dashboard/    # React Frontend
    ├── src/
    └── package.json
```

---

## 💡 Why SENTINEL?

Traditional surveillance systems require constant human monitoring. SENTINEL uses AI to automatically detect threats, track individuals, and alert operators — enabling smarter, faster, and more reliable border security.

---

## 📄 License

MIT License © 2026 Ritvik

---

> Built for intelligent, real-time border security. 🔒
