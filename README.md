# 🔐 Phishing Website Detector using Machine Learning

An intelligent phishing website detection system built using machine learning and Python. This tool predicts whether a given website is legitimate or phishing based on a variety of URL-based and domain-related features.

I designed and developed this project with the goal of enhancing online safety and awareness. It includes a custom-built desktop GUI using Tkinter for ease of use, and utilizes machine learning models trained on real-world datasets to classify websites in real time.

---

## 🚀 Features

- 🔍 **Real-time URL Classification** – Detects phishing websites based on input URLs.
- 🧠 **Machine Learning Models** – Trained using Random Forest, Logistic Regression, and Decision Tree.
- 🎨 **Custom GUI** – Fully interactive Python Tkinter interface designed for intuitive use.
- 📊 **Feature Extraction** – Analyzes 30+ features like domain length, presence of special symbols, SSL certificate status, and more.
- 💾 **Model Saving** – Uses Joblib to save and load trained models efficiently.
- ⚠️ **Alert System** – Visual result display with phishing or safe warnings.

---

## 🖥️ GUI Preview

![UI Screenshot](https://github.com/sriman-19/Fake-Website-Detection/blob/main/UI%20Screenshot)<!-- Replace with actual screenshot path -->

---

## 🧰 Tech Stack

- Python  
- Tkinter (for GUI)  
- Scikit-learn  
- Pandas  
- NumPy  
- Joblib

---

## 📁 Project Structure

```bash
Phishing-detector-main/
│
├── static/
│   └── style.css              # Custom CSS for the web-based interface
│
├── templates/
│   └── index.html             # HTML template for the homepage UI
│
├── phishing_detector.py       # Main Flask backend to handle user input and predictions
├── train_model.py             # Script to train the machine learning model
├── extract_features.py        # Extracts features from URLs for classification
├── phishing_model.pkl         # Trained ML model saved for prediction
├── dataset.csv                # Dataset containing labeled phishing and legitimate URLs
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

---

## 📊 How It Works

1. User enters a URL into the GUI.
2. Features are extracted from the URL using pre-defined logic.
3. The saved ML model predicts whether the site is phishing or legitimate.
4. Result is displayed instantly in the GUI with a warning message if malicious.

---
