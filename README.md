## 📌 Abstract

This project proposes an **Audio-Visual Speech Recognition (AVSR)** system to assist people with hearing impairments by integrating both lip-reading and audio recognition technologies. The system uses a hybrid model combining image processing and machine learning techniques to recognize speech based on both audio and video inputs

## 🧠 Problem Statement

To predict spoken words using either:
- 🎥 Video input (lip movements) in absence of audio
- 🔊 Audio input in absence of video

---

## 🎯 Objectives

1. Create an English–Kannada speech database  
2. Develop algorithms for audio and video recognition  
3. Integrate AVSR components into a hybrid recognition model  
4. Validate the system's performance using accuracy metrics

---

## 💡 Methodology

- **Visual Pipeline:**  
  - Face Detection  
  - Lip Localization  
  - Feature Extraction  
  - Recognition (using HMM/DBN/CNN)

- **Audio Pipeline:**  
  - Feature Extraction (MFCC, DWT)  
  - Model Training & Recognition

- **Machine Learning Techniques Used:**  
  - CNN, HMM, DBN, LSTM  
  - Activation Functions (ReLU, Sigmoid, Tanh)  
  - Loss Functions (Cross Entropy)

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Frameworks:** TensorFlow, OpenCV, Keras, Scikit-learn  
- **Libraries:** NumPy, SciPy, Matplotlib, dlib  
- **Platform:** Ubuntu 16.04 LTS

---

## 📦 Requirements

### Hardware
- Intel i5 (6th Gen or above), 8 GB RAM
- Webcam + Microphone
- 20 GB Storage

### Software
- Python 3.x
- OpenCV, dlib, TensorFlow, Keras
- Jupyter Notebook (optional)

---

## 📊 Results Summary

- Accuracy improved using hybrid AVSR models
- Recognized both English and Kannada words
- Lip-reading using video recognition showed promising results under noisy conditions

---

## 🔭 Future Scope

- Real-time AVSR system with webcam integration  
- Multi-language support  
- Deployment in assistive devices for hearing-impaired individuals

---

## 📚 References

- HMM, DWT, PCA, and DBN-based models
- AVSR applications by Google & Oxford
- CUAVE Dataset, VGGNet, LSTM research

---

## 📝 License

This repository is part of an academic project and is intended for educational and research purposes only.

---
