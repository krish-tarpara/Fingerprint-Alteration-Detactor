# 🔍 Fingerprint Alteration Detection using CNN

## 📌 Overview

Biometric systems are often assumed to be secure—but what happens when fingerprints are tampered with?

This project focuses on detecting **altered (fake) vs real fingerprints** using a Convolutional Neural Network (CNN). The goal is to simulate real-world biometric spoofing scenarios and evaluate how well a deep learning model can identify manipulated fingerprint data.

---

## 🧠 Approach

The project follows a standard deep learning pipeline:

* **Dataset**: SOCOFing (real and altered fingerprint images)
* **Preprocessing**:

  * Resizing images to a uniform shape (96×96)
  * Normalization for stable training
  * Data augmentation to improve generalization
* **Model**:

  * CNN architecture with Conv2D and MaxPooling layers
  * Designed to automatically extract fingerprint features
* **Training**:

  * Implemented using TensorFlow/Keras in Google Colab
  * Performance monitored using accuracy and loss metrics

---

## 📊 Results

* Achieved **96.94% accuracy** on unseen test data
* Model demonstrates strong ability to distinguish between authentic and altered fingerprints
* Generalizes well across different fingerprint variations

---

## 🚀 Key Highlights

* Simulates **real-world biometric security threats**
* Handles image variability using augmentation techniques
* End-to-end pipeline from raw data → trained model → evaluation

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy / Matplotlib
* Google Colab

---

## 📁 Project Structure

```
├── requirements.txt     
├── ML_project (2).ipynb  # Model training and evaluation
├── README.md          # Project documentation
```

---

## 🔮 Future Improvements

* Add confusion matrix and detailed evaluation metrics for deeper performance analysis
* Improve robustness for highly complex fingerprint alterations
* Develop a **restoration model to reconstruct altered fingerprints** using techniques like autoencoders or GANs
* Deploy as a web app (e.g., Streamlit) for real-time fingerprint classification
* Experiment with advanced architectures (ResNet, Transfer Learning)


