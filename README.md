# ♻️ Plastic Waste Detection via Spectral Signature Analysis
### Deep Learning-Based Marine Plastic Waste Detection and Segmentation

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-6E40C9)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![Google Colab](https://img.shields.io/badge/Platform-Google_Colab-F9AB00?logo=googlecolab&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

Plastic Waste Detection via Spectral Signature Analysis is a deep learning research project developed to automatically identify and segment marine plastic waste from underwater imagery. The system leverages **YOLOv8 Instance Segmentation** to perform accurate object detection and pixel-level segmentation, supporting environmental monitoring and intelligent waste management applications.

The project covers the complete deep learning workflow including dataset preparation, preprocessing, model training, evaluation, inference, and visualization using Google Colab.

---

# 📂 Repository Structure

```text
Plastic-Waste-Detection/
│
├── Plastic_Waste_Detection.ipynb      # Complete training & inference notebook
├── README.md
├── requirements.txt
│
├── screenshots/
│   ├── Home.png
│   ├── Training.png
│   ├── ConfusionMatrix.png
│   ├── Prediction1.png
│   ├── Prediction2.png
│   └── Results.png
│
├── weights/
│   └── best.pt
│
└── LICENSE
```

---

# 🏗 Project Workflow

```text
             Underwater Dataset
                     │
                     ▼
          Data Preprocessing
                     │
                     ▼
      YOLOv8 Segmentation Training
                     │
                     ▼
          Model Optimization
                     │
                     ▼
           Model Evaluation
                     │
                     ▼
          Image Segmentation
                     │
                     ▼
      Plastic Waste Detection
```

---

# ✨ Key Highlights

- ♻️ Automated Plastic Waste Detection
- 🧠 YOLOv8 Instance Segmentation
- 🎯 Pixel-Level Object Segmentation
- 🌊 Marine Waste Monitoring
- 📊 Model Performance Evaluation
- 📈 Precision, Recall & F1 Metrics
- 🖼️ Segmentation Mask Visualization
- ⚡ GPU Accelerated Training
- 📓 Google Colab Implementation
- 🚀 End-to-End Deep Learning Pipeline

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Deep Learning Framework | PyTorch |
| Detection Model | YOLOv8 Segmentation |
| Computer Vision | OpenCV |
| Visualization | Matplotlib |
| Numerical Computing | NumPy |
| Notebook Environment | Google Colab / Jupyter Notebook |
| Dataset Format | YOLO Segmentation |

---

# 🔬 Project Pipeline

## 📥 Dataset Preparation

> 📖 **Description**  
> The dataset is prepared in YOLO segmentation format containing training and validation images along with polygon annotations for marine plastic waste categories.

---

## 🧹 Data Preprocessing

> 📖 **Description**  
> Images and annotations are validated and organized for efficient deep learning training using the Ultralytics YOLOv8 framework.

---

## 🧠 Model Training

> 📖 **Description**  
> A YOLOv8 segmentation model is trained using GPU acceleration with configurable epochs, batch size, and image resolution to learn pixel-level representations of marine debris.

---

## 📊 Model Evaluation

> 📖 **Description**  
> The trained model is evaluated using confusion matrices, precision-recall curves, F1-score analysis, and segmentation performance metrics.

---

## 🖼 Image Inference

> 📖 **Description**  
> The trained model performs inference on unseen underwater images, generating segmented masks, bounding boxes, and confidence scores for detected plastic waste objects.

---

# 📸 Project Screenshots

## 🏠 Project Overview

![Home](screenshots/Home.png)

---

## 📈 Training Results

![Training](screenshots/Training.png)

---

## 📊 Confusion Matrix

![Confusion Matrix](screenshots/ConfusionMatrix.png)

---

## 🎯 Prediction Result 1

![Prediction1](screenshots/Prediction1.png)

---

## 🎯 Prediction Result 2

![Prediction2](screenshots/Prediction2.png)

---

## 📉 Performance Metrics

![Results](screenshots/Results.png)

---

# 📈 Model Outputs

The project generates multiple evaluation artifacts including:

- Training Loss Curves
- Precision Curves
- Recall Curves
- F1 Score Curves
- Precision–Recall Curves
- Confusion Matrix
- Segmentation Predictions
- Validation Batch Results

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/Nravitejareddy/Plastic-Waste-Detection.git

cd Plastic-Waste-Detection
```

---

## 2. Install Dependencies

```bash
pip install ultralytics

pip install opencv-python

pip install matplotlib

pip install numpy

pip install pyyaml
```

or

```bash
pip install -r requirements.txt
```

---

## 3. Open Notebook

Launch:

```text
Plastic_Waste_Detection.ipynb
```

using

- Google Colab
- Jupyter Notebook

---

## 4. Train Model

Run all notebook cells sequentially to:

- Download Dataset
- Prepare Dataset
- Train YOLOv8 Segmentation Model
- Evaluate Performance
- Perform Image Inference

---

# 📊 Performance Evaluation

The trained model generates comprehensive evaluation metrics including:

- 📈 Precision Curve
- 📈 Recall Curve
- 📈 F1 Score Curve
- 📈 Precision–Recall Curve
- 📊 Confusion Matrix
- 🖼 Prediction Samples
- 📉 Training Statistics

---

# 🔮 Future Improvements

- ☁️ Cloud Deployment
- 📱 Mobile Application Integration
- 🎥 Real-time Video Segmentation
- 🌊 Autonomous Marine Monitoring
- 🤖 Edge AI Deployment
- 📡 Drone-Based Plastic Detection
- 🛰 Satellite Image Integration
- 🧠 Multi-Spectral Image Analysis

---

# 📄 License

This repository was developed as part of an academic research project and is maintained for educational and portfolio purposes.

---

# 👨‍💻 Author

**Ravi Teja Reddy N**

Computer Science & Engineering Graduate

🐙 GitHub: https://github.com/Nravitejareddy

---

# ⭐ Project Status

> ✅ **Completed** — Research implementation demonstrating deep learning-based marine plastic waste detection using YOLOv8 instance segmentation with end-to-end training, evaluation, and inference.

---

> **Plastic Waste Detection via Spectral Signature Analysis — Advancing Intelligent Marine Waste Monitoring through Deep Learning.**
