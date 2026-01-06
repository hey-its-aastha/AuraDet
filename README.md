# AuraDet
Facial Emotion Detection

AuraDet is a real-time facial emotion detection web application that uses computer vision and deep learning to identify human emotions from a live webcam feed and display them on a web interface.

Key Features
1.Live webcam-based emotion detection
2.Multi-face support
3.Real-time web interface using Flask
4.Optimized for smooth performance
5.Uses pre-trained deep learning models

Working Overview
1.Webcam captures live video
2.Faces are detected using OpenCV DNN
3.Emotions are predicted using DeepFace
4.Results are streamed to the browser

Technologies Used
Python
Flask
OpenCV
DeepFace
TensorFlow
HTML, CSS

📁 Project Structure
AuraID/
├── backend/
│   ├── app.py
│   ├── deploy.prototxt
│   ├── res10_300x300_ssd_iter_140000.caffemodel
│   └── requirements.txt
├── frontend/
│   ├── templates/index.html
│   └── static/style.css
└── README.md

How to Run
cd backend
pip install -r requirements.txt
python app.py

Open:
http://127.0.0.1:5000
