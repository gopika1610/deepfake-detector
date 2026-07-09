<!-- # 🛡️ DeepGuard - AI Deepfake Detection System

## 👥 Project Information

This repository showcases our **Final Year B.Tech Team Project** developed as part of the academic curriculum.

### My Contribution
- Frontend integration
- FastAPI API integration
- Testing and debugging
- Deployment support
- Documentation

> **Note:** This repository is maintained to showcase my contributions to our final-year academic project.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-0.109-green.svg" alt="FastAPI">
  <img src="https://img.shields.io/badge/TensorFlow-2.15-orange.svg" alt="TensorFlow">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
</p>

DeepGuard is an AI-powered application that analyzes video and audio files to detect potential deepfake content. The project combines computer vision, facial landmark analysis, and audio feature extraction to provide an authenticity assessment.

---

# ✨ Features

- 🎬 Video Deepfake Detection
- 🎵 Audio Analysis
- 👤 Face Landmark Detection
- 📊 Authenticity Score
- 🎨 Modern Responsive UI
- 🔒 Privacy-focused Processing
- 🚀 Fast Analysis

---

# 🖥️ Demo

| Frontend | Backend API |
|----------|-------------|
| https://deepfake-detector.vercel.app | https://deepguard-api-d568.onrender.com |

> **Note:** The backend hosted on Render may take 30–60 seconds to wake up after inactivity.

---

# 🚀 Quick Start

## Prerequisites

- Python 3.10+
- pip
- FFmpeg (Optional)

## Installation

### Clone Repository

```bash
git clone https://github.com/gopika1610/deepfake-detector.git
cd deepfake-detector
```

### Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux / macOS
source venv/bin/activate

pip install -r requirements.txt

python app.py
```

Backend runs at:

```
http://localhost:8000
```

### Frontend

```bash
cd frontend

python -m http.server 3000
```

Open:

```
http://localhost:3000
```

---

# 📁 Project Structure

```
deepfake-detector/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── models/
│   └── utils/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   └── js/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🔌 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| / | GET | API Information |
| /api/health | GET | Health Check |
| /api/analyze/video | POST | Video Analysis |
| /api/analyze/audio | POST | Audio Analysis |
| /api/analyze/full | POST | Multi-modal Analysis |
| /api/tips | GET | Security Tips |

---

# 🔬 Technologies Used

## Backend
- Python
- FastAPI
- TensorFlow
- OpenCV

## AI & Media Processing
- MediaPipe Face Mesh
- Librosa
- MFCC Features

## Frontend
- HTML
- CSS
- JavaScript

---

# 🎨 UI Features

- Responsive Design
- Drag & Drop Upload
- Dark Theme
- Glassmorphism Interface
- Progress Indicators

---

# 🔒 Privacy & Security

- Temporary file processing
- No permanent media storage
- Local server execution
- Configurable CORS support

---

# 🚀 Deployment

### Frontend
- Vercel

### Backend
- Render

---

# 📚 Learning Outcome

Through this project, I gained practical experience in:

- FastAPI
- REST API Development
- Frontend & Backend Integration
- Deployment using Vercel and Render
- Testing and Debugging
- Team Collaboration
- Git & GitHub

---

# ⚠️ Disclaimer

This repository showcases a Final Year academic team project. The project is intended for educational and learning purposes. Detection results should not be considered definitive and should be verified using multiple methods.

---

# 🙏 Acknowledgements

Special thanks to the open-source communities behind:

- MediaPipe
- OpenCV
- TensorFlow
- Librosa
- FastAPI

---

## 📄 License

This project is licensed under the MIT License.

---

<p align="center">
Made with ❤️ as a Final Year B.Tech Team Project
</p>