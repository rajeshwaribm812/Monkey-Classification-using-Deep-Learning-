# 🐒 Monkey Species Classification using Deep Learning

## 📌 Project Overview

This project focuses on classifying 10 species of monkeys using advanced deep learning architectures such as **InceptionV3**, **DenseNet121**, **ResNet50**, **Swin Transformer**, and **Vision Transformer (ViT)**. By leveraging **Transfer Learning**, the model achieves high accuracy with limited computational resources. The application is built using **Flask** for the front-end and **Python** for the back-end.

---

## 📊 Dataset

The dataset for this monkey species classifier was collected from [Kaggle](https://www.kaggle.com/datasets/utkarshsaxenadn/10-species-of-monkey-multiclass-classification/data).

* Original dataset size: ~10,000 color images
* Reduced to: **5,000 images** for optimized training
* Image resolution: **250 × 250 pixels** (RGB)
* Balanced across **10 classes**.

### 📂 Classes

1. Bald Uakari
2. Emperor Tamarin
3. Golden Monkey
4. Gray Langur
5. Hamadryas Baboon
6. Mandril
7. Proboscis Monkey
8. Red Howler
9. Vervet Monkey
10. White Faced Saki

## 🧠 Models Used

* InceptionV3
* DenseNet121
* ResNet50
* Swin Transformer
* Vision Transformer (ViT)

## 🖥️ Software Requirements

* **Operating System:** Windows 7 or later (Linux/macOS supported)
* **Front-End:** Flask
* **Back-End:** Python
* **Libraries:** TensorFlow, PyTorch, OpenCV, scikit-learn, NumPy, Matplotlib

## ⚙️ How It Works

1. Load and preprocess image data.
2. Resize to 250×250 pixels.
3. Train models using Transfer Learning.
4. Evaluate performance on test set.
5. Deploy model via Flask web app.

## 🚀 Features

* Real-time image classification
* Multiple deep learning model support
* High accuracy with reduced dataset
* Lightweight Flask interface
