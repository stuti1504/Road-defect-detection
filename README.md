# Road Defect Detection 🚧

An AI-powered system to detect road surface defects such as potholes and cracks using the **YOLOv8 object detection algorithm**.  
This project automates road inspection by identifying defects in images and videos, helping infrastructure monitoring and smart city applications.

---

## 📌 Overview
Manual road inspection is time-consuming and inefficient. This project leverages **YOLOv8** to detect road defects accurately and efficiently. Training and experimentation were carried out in **Google Colab**, and the project includes an interactive interface via `app.py` for testing detection on images and videos.

---

## ✨ Features
- Detects multiple types of road defects with **bounding boxes and confidence scores**  
- **Fine-tuned YOLOv8 model** trained on a custom annotated dataset  
- Supports both **image and video input** for detection  
- **Data preprocessing and augmentation** to improve accuracy  
- Modular pipeline for **annotation, training, evaluation, and inference**  
- Interactive interface (`app.py`) for easy testing of images/videos  

---

## 🛠️ Technologies Used
- Python  
- YOLOv8 (Ultralytics, PyTorch)  
- OpenCV  
- NumPy  
- Matplotlib  
- Roboflow / LabelImg (for annotation)  
- Google Colab (for model training)  
- Streamlit / Flask (`app.py`) for interactive testing  

---

## 📂 Project Structure
road-defect-detection/
│── yolov8_training.ipynb # YOLOv8 training notebook
│── src/
│── app.py # Interactive interface
│── samples/ # Optional sample images
│── README.md
│── requirements.txt
│── .gitignore

---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/road-defect-detection.git
cd road-defect-detection
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the interactive app:

If using Streamlit:

bash
Copy code
streamlit run app.py
If using Flask:

bash
Copy code
python app.py
Use the interface to test detection on images or videos.

Note: Model weights (best.pt) and full dataset are not included. You can train the model using notebooks/yolov8_training.ipynb.
```
---

## 🔮 Future Enhancements
Real-time detection with live camera feed

GPS integration for defect mapping

Deployment as a mobile/web application
