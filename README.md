# car-damage-detection-app
# 🚗 Car Damage Detection POC | VROOM Cars x AtliQ Technologies

## 🔍 Overview

This repository contains the Proof of Concept (POC) for an **automated car damage detection system** developed for **VROOM Cars** by **AtliQ Technologies**. The goal is to classify damage to a car’s **front** and **rear** sides into one of six predefined categories using deep learning and computer vision. 

This POC lays the groundwork for a full-fledged AI-powered car inspection system that reduces manual intervention, speeds up evaluation, and improves consistency in damage assessment.

---

## 🎯 Problem Statement

Given an image of a car, the system should detect and classify its condition into one of the following six categories:

1. Front Normal  
2. Front Breakage  
3. Front Crushed  
4. Rear Normal  
5. Rear Breakage  
6. Rear Crushed  

The model is expected to achieve an **accuracy of at least 75%** and is delivered through an interactive **Streamlit** web app.

---

## ✅ Deliverables

- ✔️ Trained ML model (Car damage classification)
- ✔️ Source code (modular and well-commented)
- ✔️ Streamlit web app for real-time image upload and damage prediction
- ✔️ Accuracy > 75% on validation data

---

## 📦 Tech Stack

- **Python 3.9+**
- **TensorFlow / Keras**
- **OpenCV**
- **Streamlit**
- **scikit-learn**
- **Pillow**
- **NumPy / Pandas**
- **Matplotlib / Seaborn** (for EDA)

---
car-damage-detection/
│
├── model/                      
├── src/                       
│   ├── train.py
│   └── utils.py
├── app/                     
│   └── app.py
├── data/                       
├── requirements.txt
├── README.md
└── .gitignore
