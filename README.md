# 🌱 Plant Disease Detection using Explainable Deep Learning

## 📌 Overview

Plant diseases significantly affect agricultural productivity and farmer income. Early and accurate disease detection is crucial for reducing crop losses and ensuring sustainable agriculture.

This project presents an intelligent deep learning-based framework for automatic plant disease detection from leaf images. The system leverages transfer learning techniques and Explainable AI (XAI) using Grad-CAM to classify plant diseases and visually highlight the infected regions responsible for the prediction.

The proposed solution aims to assist farmers and agricultural experts in real-time disease diagnosis through a user-friendly web interface.

---

## 🚀 Features

* 🌿 Automatic plant disease classification from leaf images
* 🧠 Transfer Learning using state-of-the-art CNN architectures
* 🔍 Explainable AI using Grad-CAM
* 📊 Performance evaluation and robustness analysis
* 🌐 Real-time web-based disease diagnosis
* 📈 Visualization of training and validation metrics

---

## 🏗️ Project Architecture

```text
Input Leaf Image
        ↓
Image Preprocessing
        ↓
Data Augmentation
        ↓
Transfer Learning Models
(EfficientNetB0 / MobileNetV2)
        ↓
Disease Classification
        ↓
Grad-CAM Visualization
        ↓
Web Application Interface
```

---

## 📂 Project Structure

```text
plant-disease-detection/
│
├── dataset/
├── notebooks/
├── models/
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│   ├── evaluate.py
│   └── gradcam.py
│
├── web/
│   ├── app.py
│   ├── templates/
│   └── static/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🗂️ Dataset

The project utilizes publicly available plant disease datasets such as:

* PlantVillage Dataset
* Kaggle Plant Disease Datasets

Dataset typically contains healthy and diseased leaf images from multiple crop species.

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Flask
* Grad-CAM
* Google Colab

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Train the model:

```bash
python src/train.py
```

Run prediction:

```bash
python src/predict.py
```

Launch the web application:

```bash
python web/app.py
```

Open:

```text
http://localhost:5000
```

---

## 📊 Evaluation Metrics

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🔍 Explainable AI

Grad-CAM is integrated to provide visual explanations for model predictions by highlighting the affected regions of the leaf image.

---

## 🎯 Future Enhancements

* Mobile application deployment
* Multi-disease detection in a single image
* Real-time field image analysis
* IoT integration for smart agriculture

---

## 📜 License

This project is developed for academic and research purposes.
