
---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:**
  - OpenCV  
  - MediaPipe  
  - pynput / keyboard  
- **Hardware:**
  - NVIDIA Jetson Nano (target)  
  - USB Webcam  
- **Application Controlled:**
  - VLC Media Player  

---

## ✋ Gesture Mapping

| Gesture        | Action            |
|---------------|------------------|
| 🖐 Open Palm   | Play / Pause     |
| 👍 Thumb Up    | Volume Up        |
| 👎 Thumb Down  | Volume Down      |
| 👉 Swag Gesture| Next Track       |
| ✊ Fist        | Stop / Exit      |

---

## 🔬 Methodology

1. Capture real-time frames using **OpenCV**  
2. Detect hand landmarks (21 points) using **MediaPipe**  
3. Extract features:
   - Finger states (open/closed)  
   - Distance between landmarks  
4. Classify gestures using **rule-based logic**  
5. Apply **gesture stabilization** to avoid noise  
6. Map gestures → keyboard inputs → control VLC  

---

## 📊 Performance

| Metric        | Achieved Value |
|--------------|---------------|
| Accuracy     | > 90%         |
| Latency      | < 200 ms      |
| FPS          | 15–20 FPS     |

✔ Meets all project requirements  

---

## ⚡ Optimization Techniques

- Lightweight **MediaPipe model**  
- Rule-based logic (no training overhead)  
- Frame optimization for real-time speed  
- Gesture stabilization to reduce false positives  
- Efficient memory usage for edge deployment  

---

## 🧪 Results

- Real-time gesture detection works smoothly  
- VLC responds instantly to gestures  
- Stable performance under controlled lighting  

---

## ⚠️ Limitations

- Sensitive to lighting conditions  
- Limited gesture set  
- No learning/adaptive capability  
- Single-hand detection only  

---

## 🔮 Future Work

- Deep learning-based gesture classification (CNN/LSTM)  
- Multi-hand tracking  
- Dynamic gesture recognition  
- Integration with smart home systems  

---

## 🎥 Demo

👉 https://drive.google.com/file/d/1V9DD70qX7Oy16SYjNNYkqQ5PZZi1h2ZP/view?usp=sharing  

---

## 💻 GitHub Repository

👉 https://github.com/cscprojishnu/Bharath_AI_VLC_Nvidia_Jetson_Orin_Nano_Dev  

---

## 👨‍💻 Authors

- **Jishnu Teja Dandamudi** (Team Lead)  
- **Rupa Kandula**  

---

## 👨‍🏫 Guide

- **Dr. Rayappa David Amar Raj**  

---

## 📅 Date

February 2026  

---

## ⭐ Final Note

This project demonstrates how **computer vision + edge AI** can enable **natural, intuitive, and touchless interaction systems** with real-world applications.
