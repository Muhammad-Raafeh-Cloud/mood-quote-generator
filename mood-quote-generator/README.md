# 🎭 Mood-Aware Quote Generator

A real-time AI application that detects your facial expression through the webcam and displays an inspiring quote that matches your current mood!

**Author:** Rao Muhammad Raafeh  
**University:** FAST-NUCES, Faisalabad  
**Degree:** BS Software Engineering  

---

## ✨ Features

- 🎥 Real-time webcam face detection
- 🧠 AI emotion recognition (7 moods)
- 💬 Mood-matched inspirational quotes
- 📋 Copy quote to clipboard
- 🕐 Mood history tracking
- 🎨 Beautiful dark UI with animations
- ⚡ No installation needed — runs in browser!

---

## 🎭 Detected Moods

| Mood | Emoji | Quote Theme |
|---|---|---|
| Happy | 😄 | Joy & Positivity |
| Sad | 😢 | Hope & Strength |
| Angry | 😠 | Calm & Patience |
| Surprised | 😲 | Wonder & Curiosity |
| Fearful | 😨 | Courage & Bravery |
| Disgusted | 🤢 | Perspective & Change |
| Neutral | 😐 | Motivation & Wisdom |

---

## 🚀 How to Run

### Method 1 — Python Local Server (Recommended)
```bash
# Go to project folder
cd mood-quote-generator

# Run local server
python -m http.server 8000

# Open browser at:
# http://localhost:8000
```

### Method 2 — VS Code Live Server
- Install **Live Server** extension in VS Code
- Right click `index.html` → **Open with Live Server**

---

## ⚙️ How It Works

```
User opens browser
      ↓
AI models load automatically from CDN
(No manual download needed!)
      ↓
User clicks Start Camera
      ↓
face-api.js reads webcam frames
      ↓
Detects face + emotion every 1.5 seconds
      ↓
Picks matching quote from database
      ↓
Displays quote with animation
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **face-api.js** | Face detection + emotion recognition |
| **HTML5 getUserMedia** | Webcam access |
| **HTML/CSS/JavaScript** | Frontend UI |
| **CDN Models** | AI model files (auto-loaded) |

---

## 📚 AI Concepts Used

- **Computer Vision** — processing live video frames
- **Deep Learning** — pre-trained neural network for emotion detection
- **Tiny Face Detector** — lightweight fast face detection model
- **Face Expression Net** — classifies 7 emotions from face

---

## ⚠️ Requirements

- ✅ Modern browser (Chrome, Firefox, Edge)
- ✅ Internet connection (for loading AI models)
- ✅ Webcam / Camera
- ✅ Camera permission allowed in browser

---

## 📬 Contact

**Rao Muhammad Raafeh**  
📧 muhammadraafeh5@gmail.com  
🔗 linkedin.com/in/muhammad-raafeh
