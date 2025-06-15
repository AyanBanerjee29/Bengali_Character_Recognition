# BengaliOCR: Optical Character Recognition for Bengali Handwritten Characters


## 🔍 Project Overview

**BengaliOCR** is a deep learning-based Optical Character Recognition (OCR) system designed to identify and classify **Bengali handwritten characters**. The system uses Convolutional Neural Networks (CNNs) to process grayscale images and predict corresponding Bengali alphabets. 

This project demonstrates:

- Data preprocessing (grayscale conversion, resizing, normalization)
- CNN model building and training using TensorFlow/Keras
- Evaluation with accuracy and loss plots
- Prediction and visualization of sample results

---

## 📂 Dataset Information

- **Source:** [Mendeley Data Repository](https://data.mendeley.com/datasets/hf6sf8zrkc/2)
- **Dataset Name:** BanglaLekha-Isolated
- **Description:** This dataset contains 166,105 samples of 84 different Bangla handwritten characters (Digits, Basic Characters, and Compound Characters). Each image is a grayscale representation of an isolated handwritten Bangla character.

> **Note:** The dataset is not included in this repository due to size limitations. Please download it manually from the link above and extract it to a directory of your choice.

---

## 🧩 Model Architecture
-Input Layer: 64x64 grayscale images

-Convolutional Layers: Two Conv2D layers with ReLU activation

-Pooling Layer: MaxPooling2D

-Dropout Layers: To reduce overfitting

-Fully Connected Layers: Dense layers for classification

-Output Layer: Softmax activation for 84-class classification
-Conv2D -> Conv2D -> MaxPooling2D -> Dropout -> Flatten -> Dense -> Dropout -> Dense (Output)

---

## 🔥 Future Improvements
-Use Transfer Learning with pretrained models (e.g., ResNet, MobileNet) to improve accuracy
-Extend support for compound Bangla graphemes (যুক্তাক্ষর)



