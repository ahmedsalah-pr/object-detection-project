# 🚀 YOLOv8 Object Detection App (Streamlit)

A professional **web-based object detection app** built with **YOLOv8** and **Streamlit**.  
Supports **images**, **videos**, and **real-time webcam detection** with a clean UI.

---

## 📌 Features

- 📷 Upload and detect objects in **images**
- 🎬 Run detection on **videos**
- 🎥 **Live webcam** object detection
- ⚡ Powered by **YOLOv8** (Ultralytics)
- 🔧 Custom dataset training support

---

## 📂 Project Structure
YOLO-Streamlit-App/
│── app.py # Main Streamlit application
│── requirements.txt # List of required dependencies
│── README.md # Project documentation
│
├── model/ # Pre-trained or custom YOLO weights
│ └── yolov8n.pt
│
├── dataset/ # Custom dataset (optional for training)
│ ├── images/ # Training/validation images
│ └── labels/ # YOLO annotation files
│
└── runs/ # YOLO training results (auto-generated)
├── detect/ # Detection results
├── train/ # Training logs and checkpoints
└── weights/ # Saved trained weight

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmedsalah-pr/yolo-streamlit-app.git
   cd yolo-streamlit-app

