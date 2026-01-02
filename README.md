# Road Defect Detection 🚧

An AI-powered system to detect road surface defects such as potholes and cracks using the **YOLOv8 object detection algorithm**. This project supports automated and accurate infrastructure monitoring from images and videos.

---

## 📌 Overview
Road infrastructure maintenance is critical for safety and transportation efficiency. This project leverages **deep learning–based object detection** to automatically identify road defects, reducing the need for manual inspection and enabling scalable monitoring solutions.

---

## ✨ Features
- Detects multiple types of road defects with **bounding boxes and confidence scores**
- **Fine-tuned YOLOv8 model** trained on a custom annotated dataset
- Supports **image and video input** for defect detection
- Includes **data preprocessing and augmentation** for improved accuracy
- Modular pipeline for **annotation, training, evaluation, and inference**

---

## 🛠️ Technologies Used
- Python  
- PyTorch (YOLOv8 – Ultralytics)  
- OpenCV  
- Roboflow / LabelImg (for annotation)  
- Google Colab (for training and experimentation)

---

## 📂 Project Workflow
1. Dataset collection and annotation  
2. Data preprocessing and augmentation  
3. YOLOv8 model training in Google Colab  
4. Model evaluation  
5. Inference on images and videos  

---

## 🚀 Usage
```bash
pip install ultralytics opencv-python
yolo task=detect mode=predict model=best.pt source=path/to/input
