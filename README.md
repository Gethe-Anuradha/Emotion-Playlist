# Emotion-Playlist
# 🎵 Emotion-Driven Playlist Generator

An AI-powered web application that detects a user's emotion in real time using a webcam and automatically generates a music playlist that matches their mood.

---

## 🚀 Demo
> Upload a photo or use your webcam → App detects your emotion → Get a personalized playlist instantly!

---

## 🧠 How It Works

1. **Emotion Detection** — OpenCV captures the user's facial expression via webcam
2. **Classification** — TensorFlow deep learning model classifies the emotion (Happy, Sad, Angry, Neutral, Surprised)
3. **Playlist Generation** — Based on detected emotion, the backend fetches and returns a curated playlist
4. **Frontend Display** — React UI displays the playlist in a clean, interactive interface

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js |
| Backend | Python, Flask |
| AI / ML | TensorFlow, OpenCV |
| API | REST API (Flask) |
| Language | Python 3.x, JavaScript |

---

## 📁 Project Structure

```
emotion-playlist-generator/
│
├── backend/
│   ├── app.py               # Flask REST API
│   ├── model/
│   │   └── emotion_model.h5 # Trained TensorFlow model
│   ├── utils/
│   │   └── detect.py        # OpenCV emotion detection logic
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   └── components/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Gethe-Anuradha/emotion-playlist-generator.git
cd emotion-playlist-generator
```

### 2. Backend Setup
```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 3. Frontend Setup
```bash
cd frontend
npm install
npm start
```

### 4. Open in browser
```
http://localhost:3000
```

---

## 📦 Requirements

```
flask
tensorflow
opencv-python
numpy
flask-cors
```

---

## ✨ Features

- 🎭 Real-time facial emotion detection using webcam
- 🎶 Mood-based automatic playlist generation
- 🔗 REST API backend with Flask
- ⚡ Fast and responsive React frontend
- 🧪 Tested and validated emotion classification pipeline

---

## 🎯 Key Learnings

- Built and integrated a deep learning model using TensorFlow
- Developed RESTful APIs with Flask for frontend-backend communication
- Applied OpenCV for real-time image processing
- Practiced end-to-end software development lifecycle (SDLC)

---

## 👩‍💻 Developer

**Anuradha Gethe**
- 🔗 [LinkedIn](https://www.linkedin.com/in/anuradha-gethe-a27232213)
- 🐙 [GitHub](https://github.com/Gethe-Anuradha)
- 📧 anuradhagethe845@gmail.com
