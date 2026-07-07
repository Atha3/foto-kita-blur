# ✋ Foto Kita Blur

A fun **Computer Vision** project that recognizes hand gestures in real time using **MediaPipe** and **OpenCV**, then triggers different visual and audio effects based on the detected gesture.

Built with **Python**, **OpenCV**, **MediaPipe**, **NumPy**, and **Pygame**.

---

## ✨ Features

- 📷 Real-time webcam hand tracking
- ✌️ Peace Sign (V Sign) detection
- 👍 Thumbs Up detection
- ✊ Fist detection
- 🌫️ Fullscreen blur effect
- 🎨 Colored edge detection effect
- 🔴 Red overlay visual effect
- 🔊 Sound effects using Pygame
- ⌨️ Animated typewriter text
- ⚡ Smooth gesture detection with debounce

---

## 🎮 Supported Gestures

| Gesture | Effect |
|---------|--------|
| ✌️ Peace Sign | Fullscreen blur + typewriter text **"Foto Kita Blur"** + plays **Foto Kita Blur – Sal Priadi** |
| 👍 Thumbs Up | Colored edge detection + **"Mantap!"** text |
| ✊ Fist | Red overlay + **"Hidup Jokowi!!!"** text + meme sound |

---

## 📦 Installation

Clone this repository:

```bash
git clone https://github.com/Atha3/foto-kita-blur.git
cd foto-kita-blur
code .
```

### Option 1 — Install manually

```bash
py -3.12 -m pip install numpy opencv-python mediapipe pygame
```

### Option 2 — Install from requirements.txt

```bash
pip install -r requirements.txt
```

---

## ▶️ Run

```bash
py -3.12 hand_gesture_app.py
```

Press **ESC** to close the application.

---

## 🛠 Tech Stack

- Python
- OpenCV
- MediaPipe
- NumPy
- Pygame

---

## 📂 Project Structure

```
FotoKitaBlur/
│
├── hand_gesture_app.py
├── requirements.txt
├── FOTO KITA BLUR - SAL PRIADI (mp3cut.net).mp3
├── Hidup jokowi sound meme.mp3
├── README.md
└── assets/
```

---

## 🚀 How It Works

1. Launch the application.
2. Your webcam opens automatically.
3. MediaPipe tracks your hand landmarks in real time.
4. The application recognizes supported hand gestures.
5. Each gesture triggers a unique visual and audio effect.

---

## 💻 Requirements

- Python 3.10+
- Webcam
- Windows (tested)
- Linux/macOS (should work with compatible dependencies)

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, submit issues, or create pull requests for improvements and new gesture ideas.

---

## ⭐ Support

If you enjoyed this project, don't forget to **Star ⭐** the repository.

It helps others discover the project and motivates future development.