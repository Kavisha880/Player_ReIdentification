# ⚽ Player Re-Identification Using YOLOv8 + Appearance Features

An AI-based computer vision project to detect and re-identify football players across video frames using **YOLOv8** and visual similarity techniques (like color histogram + cosine similarity). Designed to handle camera movement and occlusions.

---

## 📽️ Demo

> ⚡ *Player detection + tracking with consistent ID assignment across frames — even when players leave and reappear!*

*(<img width="1363" height="718" alt="image" src="https://github.com/user-attachments/assets/854ea38b-0b6c-46e2-aa80-dde77e5a8e31" />
)*

---

## 🚀 Features

- 🔍 Real-time player detection using **YOLOv8**
- 🧠 Extracts appearance features for matching
- 🔁 Re-identifies same player in different frames
- ⚽ Works on football match videos (extendable to other sports)
- 🧩 Modular code: Easy to extend/upgrade

---


## 🚀 Key Features

- 🔍 **Player Detection using YOLOv8**  
  Accurate, fast object detection using Ultralytics YOLOv8 on each video frame.

- 🧠 **Appearance-Based Re-Identification**  
  Re-assigns consistent IDs based on visual features like clothing color, player size, and bounding box data.

- 🔁 **Handles Occlusion and Frame Skips**  
  Even if a player disappears for a few frames (e.g. due to crowding or camera pan), they are re-identified correctly.

- 🧩 **Modular Design**  
  Code is clean, well-organized, and easy to extend with new models or logic.

- 📼 **Supports Any Video Input**  
  You can analyze football matches, surveillance clips, or crowd scenes.

---

## 🧠 Tech Stack

| Tool / Library      | Description                          |
|---------------------|--------------------------------------|
| Python              | Core programming language            |
| OpenCV              | Image & video frame processing       |
| Ultralytics YOLOv8  | Real-time player detection           |
| NumPy               | Data operations and matrix handling  |
| scikit-learn        | Cosine similarity for re-ID matching |
| Matplotlib          | Visualization (optional debugging)   |

---

## 📁 Folder Structure
📦 player-reidentification
├── data/ # Input video(s)
├── yolov8/ # YOLO model weights
├── reid/ # Re-identification logic
├── utils/ # Helper scripts (draw boxes, distance metrics)
├── main.py # Main execution file
├── requirements.txt # All dependencies
└── README.md # Project documentation (this file)

## 🔮 Future Scope

- ✅ Integrate **DeepSORT** or **ByteTrack** for smoother tracking  
- 🧠 Train a custom **deep learning-based Re-ID model**  
- 🔢 Add **OCR for jersey number** recognition  
- 🖥️ Add **real-time webcam/livestream support**  
- 📊 Generate match stats (distance covered, touches, passes etc.)

## 👩‍💻 About Me

Hey! I'm **Kavisha Gupta**, an engineering student passionate about building real-world AI solutions that make an impact.  
I built this project as part of my learning journey in computer vision, deep learning, and intelligent video analytics.

- 💬 I enjoy solving practical problems using Python, OpenCV, and YOLO.  
- 💡 Always building, always learning.  
- 📫 [Connect with me on LinkedIn](https://www.linkedin.com/in/kavisha-gupta)

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share it — just give credit if you do 😊

## 📦 requirements.txt

```txt
ultralytics==8.0.168  
opencv-python==4.9.0.80  
numpy==1.26.4  
matplotlib==3.8.4  
scikit-learn==1.4.2  


