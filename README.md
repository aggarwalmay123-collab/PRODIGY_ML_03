## PRODIGY_ML_03

# 🐱🐶 Cat vs Dog Image Classification Using Support Vector Machine (SVM)

This project was completed as part of the **Machine Learning Internship at Prodigy InfoTech**.  
The aim is to implement a **Support Vector Machine (SVM)** classifier to distinguish between images of cats and dogs.

---

## 📌 Objective

Classify images into **Cat** or **Dog** categories using:
- **Image Preprocessing** (Resizing & Flattening)
- **Feature Extraction**
- **SVM Classifier Training & Testing**

This project serves as a foundation for more complex computer vision systems and demonstrates the use of traditional machine learning in image classification.

---

## 🧾 Dataset

- 📂 Dataset Name: **Dogs vs Cats**
- 📥 Source: [Kaggle Dogs vs Cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
---

## 🧠 Key Concepts

- **SVM (Support Vector Machine)**: Supervised learning algorithm to find the optimal boundary between two classes.
- **Image Preprocessing**: Resizing all images to `(40, 40)` and flattening into a 1D feature vector.
- **Model Evaluation**: Accuracy score, confusion matrix, and classification report.
- **Data Visualization**: Class distribution plots and sample prediction display.

---

## 💻 Technologies Used

| Tool/Library   | Purpose                         |
|----------------|----------------------------------|
| Python         | Programming Language             |
| NumPy          | Numerical Operations             |
| Matplotlib     | Data Visualization               |
| OpenCV / skimage| Image Reading & Resizing        |
| Scikit-learn   | Machine Learning Algorithms      |

---

## 📊 Steps Followed

1. **Data Loading**
 - Read images from `train/` and `test/` folders.
 - Resized to `(40, 40, 3)` and flattened into vectors.

2. **Preprocessing**
 - Encoded labels (`0` = cat, `1` = dog).
 - Converted feature list into NumPy arrays.

3. **Splitting Data**
 - Used `train_test_split` to create training and validation sets.

4. **Model Training**
 - Trained SVM with different kernels (`linear`, `rbf`).

5. **Evaluation**
 - Checked accuracy score.
 - Generated confusion matrix & classification report.

6. **Visualization**
 - Bar chart showing training set distribution.
 - Sample predictions for random test images.

---

## 🔗 Open in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zMULNJk9ONkWEI3UeK_atoWFgzkBLeKk?usp=sharing)

---

## 📈 Training Set Distribution

![Training Set Distribution](trainingset.png)  

---

## 📈 Test Set Distribution
![Test Set Distribution](testset.png)  

---

## 📸 Sample Predictions for cat and dog 

![Predictions](cat.png)  



![Predictions](dog.png)  

---

## 🔍 Insights Gained

- Balanced dataset helps prevent bias in model predictions.
- RBF kernel might improve accuracy but increases computation time.
- Image preprocessing significantly affects accuracy.

---
