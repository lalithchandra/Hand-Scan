# ✋ Hand-Scan

This project is a simple real-time **hand scanner** using **OpenCV** and **MediaPipe**. When a hand is detected within a transparent hand template overlay on the webcam feed, a custom video (`vid.mp4`) is triggered and displayed as a response.

---

## 🧠 How It Works

1. The webcam feed is captured using OpenCV.
2. A transparent `.png` hand template (`hand_template.png`) is overlaid in the center of the video feed.
3. MediaPipe detects the user's hand landmarks in real-time.
4. If the detected hand fits entirely within the overlay template:
   - A pre-defined video (`vid.mp4`) is played.

