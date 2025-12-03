
---

# 📘 **Assignment 02 — Data Preprocessing (Image Data)**

## 📝 **Overview**

This assignment focuses on **preprocessing image data** for machine learning and deep learning tasks.
The objective is to understand how images can be cleaned, transformed, normalized, and prepared for models such as CNNs.

We work with basic image operations like:

* Loading and visualizing images
* Resizing and reshaping
* Converting color spaces (RGB → Grayscale)
* Normalization & scaling
* Data augmentation
* Saving & batching preprocessed images

---

## 🧠 **What I Learned**

* How to load images using **OpenCV / PIL**
* How to visualize images using **Matplotlib**
* How image **dimensions**, **channels**, and **pixel values** work
* How to normalize pixel values (0–255 → 0–1)
* How to convert images to grayscale
* Basics of **data augmentation** (rotation, flip, crop)
* How preprocessing affects model performance

---

## 🛠 **Technologies & Packages Used**

* Python 3.x
* NumPy
* Pandas (if metadata used)
* OpenCV (`cv2`)
* PIL (optional)
* Matplotlib / Seaborn
* TensorFlow / Keras (optional for augmentation)

---

## 📂 **Folder Structure**

```
Assignment-02-Data-Preprocessing-Image/
│── Assignment-02.ipynb
│── sample_images/ (optional)
│── preprocessed/ (optional)
│── README.md
│── requirements.txt
```

---

## ▶️ **How to Run This Assignment**

### **1. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **2. Open the Notebook**

```bash
jupyter notebook Assignment-02.ipynb
```

### **3. Run the cells in order**

The notebook includes:

* Loading images
* Visualizing raw images
* Applying preprocessing
* Saving processed images

---

## 🖼 **Key Image Preprocessing Techniques Covered**

### 🔹 **1. Image Loading**

```python
img = cv2.imread("image.jpg")
```

### 🔹 **2. Resizing**

```python
resized = cv2.resize(img, (128, 128))
```

### 🔹 **3. Grayscale Conversion**

```python
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
```

### 🔹 **4. Normalization**

```python
normalized = img / 255.0
```

### 🔹 **5. Data Augmentation**

```python
datagen = ImageDataGenerator(rotation_range=20, horizontal_flip=True)
```

---

## ✔️ **Results**

* Successfully loaded & displayed images
* Applied preprocessing transformations
* Observed how preprocessing improves model readiness
* Exported preprocessed images into structured folders

---

## ✒️ **Author**

**Sumit Kumar**
AI • Cloud • Software Engineering
2025

---

If you want, I can also generate the **requirements.txt** for Assignment 02 or a **complete notebook template** (clean, sectioned, ready for GitHub + Colab).
Just say the word 🚀
