
# 🩺 MediScan – Health Ally  
## A Deep Learning Tool for Tuberculosis and Eye Disease Prediction

MediScan is a **web-based deep learning healthcare application** designed to support **early, non-invasive disease detection**. It uses **Convolutional Neural Networks (CNNs)** and **Transfer Learning (VGG19)** to analyze medical images and predict:

- **Tuberculosis (TB)** from Chest X-ray images  
- **Eye diseases** (Cataract, Glaucoma, Diabetic Retinopathy) from Retinal Fundus images

<img width="1000" height="579" alt="image" src="https://github.com/divyabharathynadar/MediScan/blob/main/MediScan.png">

This project was developed as part of an **M.Sc. Bioinformatics Master’s Thesis (2022–2024)**. It was developed using publicly available Kaggle datasets, consisting of approximately **3,500 chest X-ray images** for Tuberculosis detection and around **4,500 retinal fundus images** for eye disease classification, resulting in a total of **~8,000 medical images** before augmentation.

---

## 🔍 Project Overview

Early detection of diseases like Tuberculosis and eye disorders is critical for timely treatment and better outcomes.  
However, traditional diagnostic methods are often:

- Invasive  
- Time-consuming  
- Expensive  
- Limited in accessibility, especially in resource-constrained settings  

**MediScan** addresses these challenges by providing a **multi-disease prediction system** using deep learning and a **user-friendly web interface** built with Streamlit.

---

## ✨ Key Features

- 🧠 Deep learning–based multi-disease prediction  
- 🫁 Tuberculosis detection from Chest X-rays  
- 👁️ Eye disease classification from retinal images  
- 🔁 Transfer Learning using pre-trained **VGG19**  
- 🌐 Web-based application using **Streamlit**  
- 📊 High model performance:
  - **TB Model Accuracy:** 93.8%
  - **Eye Disease Model Accuracy:** 87%

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Deep Learning:** TensorFlow, Keras  
- **Model Architectures:** CNN, VGG19 (Transfer Learning)  
- **Data Processing:** NumPy, Pandas  
- **Visualization:** Matplotlib  
- **Web Framework:** Streamlit  
- **Development Tools:** Google Colab, Anaconda, Spyder  
- **Dataset Source:** Kaggle  

---

## 🧩 Problem Statement

- Traditional diagnostic techniques for Tuberculosis and eye diseases often lack speed, accuracy, and accessibility.  
  Most AI-based systems focus on **single-disease prediction**, creating gaps in identifying co-occurring conditions.

- MediScan bridges this gap by providing a **unified deep learning system** capable of predicting **multiple diseases from medical images**, supporting early intervention and proactive healthcare.

---

## 🏗️ System Architecture

1. User uploads a medical image (Chest X-ray or Retinal Fundus image)  
2. Image preprocessing (resizing, normalization)  
3. Processed image passed to trained deep learning model  
4. Model predicts disease class  
5. Result displayed with relevant information and preventive guidance  

---


---

## 📊 Dataset Description

- **TB Dataset:** Chest X-ray images from Kaggle  
- **Eye Disease Dataset:** Retinal fundus images from Kaggle  

### Preprocessing Steps
- Image resizing to `224 × 224`  
- Pixel value normalization  
- Data augmentation to reduce overfitting  
- Train–validation split  

> ⚠️ Note: Full datasets are not included in this repository due to licensing restrictions.

---

## 🧠 Model Development

### 🫁 Tuberculosis Detection Model
- Architecture: CNN  
- Input: Chest X-ray images  
- Loss Function: Binary Crossentropy  
- Optimizer: Adam  
- Evaluation Metrics: Accuracy, Precision, Recall  
- **Final Accuracy:** 93.8%

### 👁️ Eye Disease Detection Model
- Architecture: VGG19 (Transfer Learning)  
- Base layers frozen + custom dense layers  
- Classes:
  - Cataract  
  - Glaucoma  
  - Diabetic Retinopathy  
  - Normal  
- **Final Accuracy:** 87%

---

## 🌐 Web Application (Streamlit)

The Streamlit application allows users to:

- Upload medical images  
- Get instant disease predictions  
- View disease-related information and preventive measures

---


* By **Divyabharathy Nadar** - [Linkedin](https:https://www.linkedin.com/in/divyabharathy-nadar/) | [Github](https://github.com/divyabharathynadar/)
