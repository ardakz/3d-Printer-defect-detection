# 3D Printer Defect Detection (YOLOv8)

This project is a computer vision system for detecting defects in 3D printing using YOLOv8. It automates quality control by analyzing images in real time and sending alerts when defects are detected.

## 🚀 Features
- Defect detection using YOLOv8 (segmentation)
- Dataset preprocessing and augmentation
- Real-time monitoring with camera
- Telegram bot notifications
- Optimized for performance (quantization, pruning)

## 📊 Dataset
- ~5000 images
- Cleaned, filtered, and annotated using Roboflow
- Augmented with:
  - rotation
  - scaling
  - brightness/contrast changes

Proper dataset preparation is critical, since model performance heavily depends on data quality and diversity :contentReference[oaicite:0]{index=0}.

## 🧠 Model
- YOLOv8 segmentation
- Transfer learning used
- Tuned hyperparameters:
  - learning rate
  - batch size
- Evaluated using:
  - Precision / Recall
  - mAP

YOLO-based models are widely used for real-time defect detection due to high speed and accuracy :contentReference[oaicite:1]{index=1}.

## ⚙️ Pipeline
1. Data collection & cleaning  
2. Annotation (Roboflow)  
3. Preprocessing & augmentation  
4. Model training  
5. Evaluation  
6. Deployment  

## 📷 Hardware
- High-performance PC (GPU)
- Camera for real-time monitoring

## 🔔 Integration
- Telegram API for notifications
- Sends alerts when defects are detected

## 📌 Results
- Improved detection accuracy after augmentation and tuning
- Real-time defect detection system implemented

## 🧩 Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Roboflow
- Telegram API

## 👨‍💻 Author
Ardak Abdullaev  
Big Data Analytics student (AITU)
