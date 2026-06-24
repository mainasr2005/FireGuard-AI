# 🔥 FireGuard AI

AI-Powered Fire Detection System using MobileNetV2 and Streamlit.

## 📌 Overview

FireGuard AI is a computer vision project that detects the presence of fire in images using Deep Learning and Transfer Learning techniques. The model is built on MobileNetV2 and deployed through a Streamlit web application, allowing users to upload images and receive instant predictions.

##   Features

* Fire / Non-Fire Image Classification
* Transfer Learning with MobileNetV2
* Interactive Streamlit Interface
* Data Augmentation for Better Generalization
* Class Imbalance Handling
* Model Evaluation with Accuracy, Confusion Matrix, and Classification Report
* Fast and Lightweight Deployment

## 🛠️ Technologies Used

* Python
* TensorFlow & Keras
* MobileNetV2
* Streamlit
* NumPy
* Matplotlib
* Scikit-Learn

## 📂 Project Structure

```text
FireGuard-AI/
│
├── app.py
├── fire_detection_model.keras
├── requirements.txt
├── README.md
└── dataset/
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/FireGuard-AI.git
cd FireGuard-AI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

##  Model Architecture

The project uses MobileNetV2 as a pre-trained backbone for feature extraction.

Architecture:

* MobileNetV2 (Pre-trained on ImageNet)
* Global Average Pooling Layer
* Dropout Layer (0.5)
* Dense Output Layer (Sigmoid)

## 📊 Results

The model was trained using transfer learning and data augmentation techniques to improve performance and generalization.

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 🔮 Future Improvements

* Real-Time Video Fire Detection
* Smoke Detection Module
* Emergency Alert Notifications
* CCTV Camera Integration
* Fire Severity Classification

## 👩‍💻 Author

Mai Nasr

Aspiring AI & Machine Learning Engineer passionate about Computer Vision, Deep Learning, and Intelligent Systems.
