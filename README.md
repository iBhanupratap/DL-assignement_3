# DL-assignement_3
# 🧠 Deep Learning Assignment 3

## 🛰️ Multispectral Image Sharpening using PCA

---

## 📌 Project Overview

This project focuses on sharpening multispectral satellite images using **Principal Component Analysis (PCA)**.

The main goal is to enhance image quality by improving spatial details while preserving spectral information. This type of technique is widely used in **remote sensing and geospatial analysis**.

---

## 🎯 Objective

* Understand how PCA works in image processing
* Apply PCA for multispectral image sharpening
* Improve visual clarity of satellite images
* Compare original and enhanced images

---

## 🧾 Problem Statement

Multispectral images contain multiple bands, but they often lack sharp spatial details.
The challenge is to enhance the image without losing important spectral information.

This project solves that problem using PCA-based transformation.

---

## 📂 Dataset

* Multispectral satellite image (multi-band data)
* Loaded and processed in Google Colab
* Each band represents different spectral information

---

## ⚙️ Methodology

The complete workflow followed in this project:

### 1. Data Loading

* Load multispectral image
* Separate individual spectral bands

### 2. Preprocessing

* Normalize image data
* Prepare matrix format for PCA

### 3. PCA Transformation

* Apply PCA to convert correlated bands into principal components
* Identify major components containing maximum information

### 4. Image Sharpening

* Modify principal components to enhance spatial details
* Combine with original data

### 5. Reconstruction

* Convert PCA data back to original image space
* Generate sharpened output image

### 6. Visualization

* Compare original vs sharpened image
* Analyze improvement in clarity

---

## 📊 Results

* Sharpened image shows **better edges and details**
* Visual clarity is significantly improved
* Important features are more distinguishable
* Noise is reasonably controlled

---

## 🖼️ Output Visualization

> ⚠️ (Add your images here after uploading to GitHub)

### Original Image

![Original](your_image_link_here)

### Sharpened Image

![Sharpened](your_image_link_here)

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**
2. Upload the required input image
3. Run all cells step-by-step
4. View output images and results

---

## 🛠️ Technologies Used

* Python
* Google Colab
* NumPy
* Matplotlib
* Scikit-learn (PCA)
* OpenCV (if used)

---

## 🔍 Key Learnings

* Practical understanding of PCA
* Handling multispectral satellite data
* Image processing using Python
* Importance of dimensionality reduction in real-world problems

---

## 🚀 Future Improvements

* Apply Deep Learning models (CNN-based sharpening)
* Use high-resolution satellite datasets
* Compare PCA with other fusion techniques
* Automate parameter tuning

---

## 📎 Repository Link

👉 Notebook:
https://github.com/iBhanupratap/DL-assignement_3/blob/main/DL_assignment3_final.ipynb

---

## ⭐ About Me

I am currently pursuing M.Tech in **Geoinformatics and Natural Resources (IIT Bombay)** and building strong skills in:

* Remote Sensing
* Machine Learning
* Deep Learning
* Geospatial Analysis

---

⭐ If you found this project useful, feel free to star the repository!
