# 🧠 Deep Learning Assignment 3

## 🛰️ Semantic Segmentation using SegNet (Remote Sensing Images)

---

## 📌 Project Overview

This project focuses on **semantic segmentation of aerial/satellite images** using a deep learning model called **SegNet**.

The goal is to classify each pixel of an image into meaningful land cover classes such as buildings, vegetation, roads, etc.

This type of task is widely used in:

* Remote sensing
* Urban planning
* Land use analysis

---

## 🎯 Objective

* Understand semantic segmentation using deep learning
* Implement **SegNet from scratch**
* Train and evaluate the model on remote sensing dataset
* Compare performance with official implementation

---

## 📂 Dataset

* **ISPRS Potsdam Dataset** (remote sensing benchmark)
* Data includes:

  * IRRG images (Infrared, Red, Green)
  * DSM (Digital Surface Model)
  * Ground truth labels

👉 Total classes:

* Impervious surfaces
* Buildings
* Low vegetation
* Trees
* Cars
* Clutter 

👉 Input format:

* 4-channel image (IRRG + DSM) 

---

## ⚙️ Methodology

### 1. Data Preparation

* Loaded IRRG images and DSM data
* Combined into 4-channel input
* Converted labels into class maps

### 2. Patch Extraction

* Images divided into **128×128 patches**
* Created dataset of ~98 patches 

### 3. Dataset Split

* Training: 68 samples
* Validation: 14 samples
* Testing: 16 samples 

### 4. Model: SegNet

* Encoder–Decoder architecture
* Pixel-wise classification
* Handles semantic segmentation

Two models used:

* ✅ Custom SegNet (implemented from scratch)
* ✅ Official SegNet (from GitHub repo) 

---

## 🏗️ Training Details

* Epochs: 20
* Loss Function: Weighted Cross Entropy
* Optimizer: SGD/Adam (as used in notebook)
* Evaluation Metrics:

  * Accuracy
  * F1 Score

---

## 📊 Results

### 🔹 Our SegNet

* Accuracy: **58.1%**
* F1 Score: **38.9%** 

### 🔹 Official SegNet

* Accuracy: **56.8%**
* F1 Score: **39.8%** 

👉 Both models show **very similar performance**, validating the correctness of our implementation.

---

## 📈 Key Observations

* Model performs best on **Low Vegetation**
* Poor performance on **Cars (very few samples)**
* Limited training data (only 3 tiles) affects accuracy 

---

## 🖼️ Output

(Add your images here 👇)

### Prediction Output

![Segmentation Output](<img width="573" height="497" alt="image" src="https://github.com/user-attachments/assets/bbeb9714-9d2c-4be2-b50f-42e0ceafe906" />
.)

### Training Curves

![Training Curve](<img width="1087" height="409" alt="image" src="https://github.com/user-attachments/assets/10d07b7e-ca09-40f0-94fb-3574cb5dac8c" />)

---

## ▶️ How to Run

1. Open notebook in Google Colab
2. Upload dataset (ISPRS Potsdam)
3. Run all cells step-by-step
4. Model will train and generate predictions

---

## 🛠️ Technologies Used

* Python
* PyTorch
* NumPy
* Matplotlib
* Rasterio
* Google Colab

---

## 🔍 Key Learnings

* Deep understanding of **semantic segmentation**
* Practical implementation of **SegNet architecture**
* Handling real-world **remote sensing data**
* Model evaluation using **F1 score and accuracy**

---

## 🚀 Future Improvements

* Train on full dataset (all 38 tiles)
* Use advanced models (U-Net, DeepLabV3+)
* Improve class imbalance handling
* Apply data augmentation

---

## 📎 Repository

👉 Notebook:
https://github.com/iBhanupratap/DL-assignement_3/blob/main/DL_assignment3_final.ipynb

---

## ⭐ About Me

I am currently pursuing M.Tech in **Geoinformatics and Natural Resources (IIT Bombay)** and building skills in:

* Remote Sensing
* Deep Learning
* Geospatial AI

---

⭐ If you like this project, consider giving it a star!

