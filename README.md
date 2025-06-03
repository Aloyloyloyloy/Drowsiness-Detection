# 💤 Drowsiness Detection with YOLOv5 and OpenCV

This project implements a real-time drowsiness detection system using a custom-trained YOLOv5 model. The system can classify a person's state as **"awake"** or **"drowsy"** using webcam input. It includes tools for image data collection, model training, and real-time inference.

---

## Features

- Image collection from webcam
- Custom YOLOv5 model training
- Real-time detection using webcam
- Inference on static images

---

## Requirements

Install the following dependencies:

```bash
pip install opencv-python matplotlib torch torchvision torchaudio
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
