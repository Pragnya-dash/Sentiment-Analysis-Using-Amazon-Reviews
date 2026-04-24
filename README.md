# 🎯 Sentiment Analysis on Alexa Reviews

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![NLP](https://img.shields.io/badge/NLP-NLTK-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🧠 Overview

Analyze Amazon Alexa reviews and classify them as **Positive 😊** or **Negative 😡** using NLP & Machine Learning.

---

## ✨ Features

✔️ Text preprocessing (cleaning, stopwords, stemming)
✔️ Exploratory Data Analysis (EDA) 📊
✔️ TF-IDF vectorization
✔️ Model training (Logistic Regression / Naive Bayes)
✔️ Confusion Matrix & evaluation
✔️ Real-time sentiment prediction

---

## 📂 Dataset

* 📝 `verified_reviews` → Review text
* 👍 `feedback` → Sentiment (1 = Positive, 0 = Negative)
* ⭐ `rating`, 📅 `date`, 🎧 `variation`

---

## ⚙️ Workflow

```mermaid
graph TD
A[Raw Data] --> B[Data Cleaning]
B --> C[Text Preprocessing]
C --> D[EDA & Visualization]
D --> E[TF-IDF Vectorization]
E --> F[Model Training]
F --> G[Evaluation]
G --> H[Prediction]
```

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas, NumPy
* 🤖 Scikit-learn
* 🧹 NLTK
* 📈 Seaborn, Matplotlib
* ☁️ WordCloud

---

## 📊 Sample Output

| Review                              | Prediction  |
| ----------------------------------- | ----------- |
| "Amazing product, works perfectly!" | Positive 😊 |
| "Waste of money, not working"       | Negative 😡 |

---

## 🚀 Run Locally

```bash
git clone <your-repo-link>
cd sentiment-analysis
pip install -r requirements.txt
jupyter notebook
```

---

## 📈 Results

* High accuracy on test data
* Clear separation of positive & negative sentiments
* Insights from WordCloud & visualizations

---

## 🔮 Future Improvements

🚀 Add Neutral sentiment
🚀 Use Deep Learning (LSTM, BERT)
🚀 Deploy as a web app

---

## 🙌 Acknowledgements

Dataset: Amazon Alexa Reviews
Libraries: Scikit-learn, NLTK, Pandas

---

## ⭐ Show Some Love

If you like this project, consider giving it a ⭐ on GitHub!
