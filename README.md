# AI-Based-Cybersecurity-Threat-Detection-System
[Open in Colab](https://colab.research.google.com/drive/1LTd6DQALxCijJgKUQY5LYiz-kz6YMuj9?usp=sharing)

# 🔐 AI-Based Cybersecurity Threat Detection System

## 📌 Overview
This project presents an AI-powered Intrusion Detection System (IDS) designed to identify cyber threats and detect zero-day attacks using deep learning and anomaly detection techniques. The system analyzes network traffic patterns and classifies them as normal or malicious with improved accuracy.

---

## 🎯 Objectives
- Detect known and unknown cyber attacks
- Improve anomaly detection using deep learning models
- Provide explainable insights using XAI techniques
- Automate threat detection and response

---

## ⚙️ Features
- 🔍 Anomaly detection using Autoencoders  
- 🧠 Sequence modeling using LSTM & RNN  
- 📊 Explainable AI with SHAP & LIME  
- 📈 Visualization of attack patterns  
- ⚡ Automated detection workflow  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Scikit-learn, Pandas, NumPy  
- **Explainability:** SHAP, LIME  
- **Platform:** Google Colab  
- **Dataset:** NSL-KDD  

---

## 🧠 Model Architecture
- **LSTM (Long Short-Term Memory):** Captures sequential dependencies in network traffic  
- **RNN:** Identifies temporal attack patterns  
- **Autoencoder:** Detects anomalies by reconstruction error  

---

## 📊 Results
- Successfully detected anomalous network traffic  
- Improved zero-day attack detection capability  
- Reduced false positives using hybrid modeling  

> 📌 *(Add actual metrics like accuracy, precision, recall here if available)*

---

## 📂 Dataset
- NSL-KDD dataset used for training and testing  
- Includes both normal and attack traffic data  

---

## ▶️ How to Run

### Option 1: Run Locally
```bash
git clone https://github.com/Dharshini11042004/AI-Based-Cybersecurity-Threat-Detection-System.git
cd AI-Based-Cybersecurity-Threat-Detection-System
pip install -r requirements.txt
python main.py
