# Phishing Email Detection Model

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Phishing%20Detection-red)
![License](https://img.shields.io/badge/License-MIT-green)

##  Overview

Phishing emails are one of the most common cyber threats used to steal sensitive information such as passwords, banking credentials, and personal data.

This project presents a Machine Learning-based Phishing Email Detection System that analyzes email content and embedded URLs to classify emails as **Phishing** or **Safe**. The model leverages Natural Language Processing (NLP) techniques and URL-based feature engineering to achieve high detection accuracy.

---

##  Objectives

* Detect phishing emails automatically.
* Extract meaningful features from email text and URLs.
* Train a machine learning model to distinguish between phishing and legitimate emails.
* Evaluate performance using industry-standard metrics.
* Provide real-time prediction capability.

---

##  Features

### Text Analysis

* TF-IDF Vectorization
* Keyword Frequency Analysis
* Email Content Processing

### URL Analysis

* URL Count Detection
* URL Length Analysis
* HTTPS Detection
* IP Address Detection
* Domain Complexity Measurement

### Machine Learning

* Random Forest Classification
* High Accuracy Prediction
* Real-Time Email Classification

### Evaluation

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

##  System Architecture

Email Dataset
↓
Text Preprocessing
↓
TF-IDF Feature Extraction
↓
URL Feature Extraction
↓
Feature Combination
↓
Random Forest Classifier
↓
Prediction
(Phishing / Safe)

---

## Project Structure

Phishing-Email-Detection-ML/

├── data/
│ └── emails.csv

├── models/
│ └── phishing_model.pkl

├── notebooks/
│ └── EDA.ipynb

├── src/
│ ├── train.py
│ ├── predict.py
│ ├── feature_extraction.py
│ └── utils.py

├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore

---

## Technologies Used

* Python
* Scikit-Learn
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Natural Language Processing (NLP)

---

## Dataset

The dataset contains email messages labeled as:

| Email Text                      | Label    |
| ------------------------------- | -------- |
| Verify your account immediately | phishing |
| Meeting scheduled tomorrow      | safe     |

### Labels

* phishing → 1
* safe → 0

---

## Installation

Clone the repository:

```bash
git clone https://github.com/KrishSingh06/Phishing-Email-Detection-ML.git
cd Phishing-Email-Detection-ML
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Model Training

Run:

```bash
python src/train.py
```

Example Output:

```text
Training Started...

Accuracy: 98.67%

Model Saved Successfully
```

---

## Predicting New Emails

Run:

```bash
python src/predict.py
```

Example Email:

```text
Dear User,

Your account has been suspended.

Please verify your account immediately:

http://secure-update-login.xyz
```

Prediction:

```text
PHISHING
```

---

##  Performance Metrics

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 98.67% |
| Precision | 97.50% |
| Recall    | 98.00% |
| F1 Score  | 97.50% |

---

## 📷 Results

### Confusion Matrix

Confusion Matrix:
[[1531   15]
 [  10  324]]

### Prediction Output

Prediction: 1.0

---

## 🧠 Feature Engineering

### Text Features

* TF-IDF Scores
* Keyword Frequency
* Text Length

### URL Features

* Number of URLs
* Average URL Length
* HTTPS Usage
* IP-Based URLs
* Domain Complexity

---

## Cybersecurity Applications

This project demonstrates practical applications of:

* Email Security
* Threat Intelligence
* Cybersecurity Analytics
* Phishing Detection
* Natural Language Processing
* Machine Learning Security

---

## 🔮 Future Enhancements

* BERT-Based Detection
* RoBERTa Integration
* Email Header Analysis
* URL Reputation Services
* Streamlit Dashboard
* Browser Extension
* Real-Time Detection API

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## License

Licensed under the MIT License.

---

## Author

### Krish Kumar 

Email:
[krishsingh1kj.ks@gmail.com](mailto:krishsingh1kj.ks@gmail.com)

GitHub:
https://github.com/KrishSingh06

LinkedIn:
https://www.linkedin.com/in/krish-kumar-singh-090987328/

If you found this project useful, consider giving it a ⭐ on GitHub.
