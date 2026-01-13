# 🛡️ Phishing URL Detection System
#Author- Avaneesh Inamdar, Tean ZeroPhish\n
**Team ZeroPhish – Walchand College of Engineering, Sangli**

A complete machine learning system for detecting phishing URLs with a web interface built using Flask.

---

## 🚀 Features
- **Advanced Feature Engineering** – Extracts 11+ features from URLs (length, special characters, domain analysis, etc.)
- **Multiple ML Models** – Trains & compares Logistic Regression, Random Forest, and Gradient Boosting
- **Web Interface** – Clean Flask web app for real-time URL checking
- **Model Persistence** – Saves the best performing model for production use
- **Comprehensive Evaluation** – Accuracy, Precision, Recall, F1-score, Confusion Matrix
- **Hybrid Analysis Integration** – Optional sandbox analysis via [Hybrid Analysis](https://www.hybrid-analysis.com/)
- **Mode Selection** – Choose between fast *Model-only* mode or accurate *Hybrid* mode

---

## 📋 Requirements
- Python **3.7+**
- Install dependencies:
  ```bash
  pip install -r requirements.txt
