# AI Classroom Rating System

## 📌 Project Overview

AI Classroom Rating System is an AI-based classroom monitoring system that analyzes classroom audio in real time. It helps detect noise levels, abusive language, and voice emotions to improve classroom discipline and monitoring.

The system provides separate access for **Student, Teacher, and HOD**.

## 🎯 Objectives

* Real-time classroom monitoring
* Noise level detection
* Hindi and English abusive language detection
* Voice emotion analysis
* Real-time alerts
* Discipline score generation
* Reports and analytics

## 🏗️ Project Structure

```text
AI-Classroom-Rating-System/
│
├── backend/
│   ├── main.py
│   ├── routes/
│   ├── models/
│   ├── services/
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── package.json
│
├── ai_engine/
│   ├── noise_detection/
│   ├── abusive_word_detection/
│   └── emotion_analysis/
│
└── README.md
```

## ⚡ Quick Start

### Prerequisites

* Python 3.x
* Node.js & npm
* MongoDB
* Git
* VS Code

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## 🤖 AI Engine

The AI engine processes classroom audio and performs:

* **Noise Detection** – Measures classroom noise levels.
* **Abusive Language Detection** – Detects inappropriate words in Hindi and English.
* **Emotion Analysis** – Analyzes emotions from voice.
* **Discipline Analysis** – Generates an overall classroom discipline score.

## 🔗 API Endpoints

REST APIs connect the frontend with the backend.

| Endpoint         | Method | Purpose           |
| ---------------- | ------ | ----------------- |
| `/login`         | POST   | User login        |
| `/register`      | POST   | User registration |
| `/monitor/start` | POST   | Start monitoring  |
| `/monitor/stop`  | POST   | Stop monitoring   |
| `/alerts`        | GET    | Get alerts        |
| `/reports`       | GET    | Get reports       |

## 🛣️ Frontend Routes

* `/login` – User Login
* `/student` – Student Dashboard
* `/teacher` – Teacher Dashboard
* `/hod` – HOD Dashboard
* `/monitoring` – Classroom Monitoring
* `/reports` – Reports

## 🛠️ Tech Stack

* **Frontend:** React.js, HTML, CSS, JavaScript
* **Backend:** Python, FastAPI
* **AI/NLP:** Python, NLP, Machine Learning
* **Database:** MongoDB
* **API:** REST API
* **Tools:** Git, GitHub, VS Code

## ✨ Features

* Role-based login
* Student, Teacher and HOD dashboards
* Real-time classroom monitoring
* Noise detection
* Hindi & English abusive language detection
* Voice emotion analysis
* Real-time alerts
* Discipline score
* Reports and analytics

## 🔄 System Workflow

```text
User Login
    ↓
Student / Teacher / HOD
    ↓
Teacher Starts Monitoring
    ↓
Classroom Audio Captured
    ↓
AI Engine Analysis
    ↓
Noise + Language + Emotion Detection
    ↓
Alerts & Discipline Score
    ↓
Dashboard & Reports
```

## 🚀 Future Enhancements

* Improved AI accuracy
* Advanced emotion recognition
* Mobile application
* Cloud deployment
* Advanced analytics
* Automated report generation

ct is developed for academic and educational purposes.
