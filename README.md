# 🌈 AuraDet  
### Facial Emotion Detection Web Application

AuraDet is a **real-time facial emotion detection web application** that uses **computer vision** and **deep learning** to identify human emotions from a live webcam feed and display them on a web interface.

---

## 🚀 Key Features

- 🎥 Live webcam-based emotion detection  
- 👥 Multi-face support  
- 🌐 Real-time web interface using Flask  
- ⚡ Optimized for smooth performance  
- 🧠 Uses pre-trained deep learning models  

---

## 🧠 Working Overview

1. Webcam captures live video  
2. Faces are detected using **OpenCV DNN**  
3. Emotions are predicted using **DeepFace**  
4. Results are streamed to the browser  

---

## 🛠️ Technologies Used

- Python  
- Flask  
- OpenCV  
- DeepFace  
- TensorFlow  
- HTML, CSS  

---

## 📁 Project Structure

```text
AuraDet/
├── backend/
│   ├── app.py
│   ├── deploy.prototxt
│   ├── res10_300x300_ssd_iter_140000.caffemodel
│   └── requirements.txt
│
├── frontend/
│   ├── templates/
│   │   └── index.html
│   └── static/
│       └── style.css
│
└── README.md
