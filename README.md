# 📰 Fake News Detection Web App

## 📌 Overview

This project is a Machine Learning-powered web application that detects whether a news headline is **Fake or Real**. It uses Natural Language Processing (NLP) techniques and a trained classification model to analyze text and provide instant predictions through a simple web interface.

---

## 🚀 Key Features

* Real-time fake news prediction
* Pre-trained ML model for classification
* Fast prediction using TF-IDF vectorization
* Flask-based web application
* Simple and user-friendly interface

---

## 🧠 Tech Stack

* **Language:** Python
* **Framework:** Flask
* **Machine Learning:** Scikit-learn
* **NLP:** TF-IDF Vectorization
* **Libraries:** Pandas, NumPy, Pickle
* **Frontend:** HTML (Jinja Templates)

---

## 📂 Project Structure

```
Fake-News-Detection/
│
├── app.py
├── finalized_model.pkl
├── vectorizer.pkl
├── news_large.csv
├── Fake News Detection.ipynb
├── templates/
│   ├── index.html
│   └── prediction.html
├── static/
│   └── image.svg
├── requirements.txt
└── Procfile
```

---

## ⚙️ How It Works

1. User enters a news headline
2. Text is transformed using TF-IDF vectorizer
3. Model predicts whether the news is Fake or Real
4. Result is displayed on the web page

---

## ▶️ Installation & Setup

```bash
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
pip install -r requirements.txt
python app.py
```

Open in browser:

```
http://127.0.0.1:5000/
```

---

## 🧪 Model Details

* Supervised machine learning classifier
* TF-IDF used for feature extraction
* Model and vectorizer saved using pickle
* Trained on labeled fake and real news dataset

---

## 📊 Dataset

* Contains labeled news data (Fake/Real)
* Used for training and evaluation
* Helps model learn patterns of misinformation

---

## 🌐 Deployment

* Includes Procfile (Heroku-ready)
* Uses Gunicorn for production

---

## 💡 Future Improvements

* Integrate live news APIs
* Use deep learning models (LSTM, BERT)
* Improve UI/UX
* Add multi-language support

---

## 👩‍💻 Author

**Meezan Mulla**
AI/ML Engineering Student | Data Science Enthusiast

