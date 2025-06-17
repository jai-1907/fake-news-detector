# 📰 Fake News Detector

> **Detect fake news articles using machine learning and NLP.**  
> Built with TF-IDF + PassiveAggressiveClassifier 💡  
> Ready to demo, showcase, or scale 🧠

---

## 🚀 Project Overview

This project classifies news articles as **Fake 🟥** or **Real 🟩** using a supervised ML model.  
The goal is to combat misinformation using AI and natural language processing.

---

## 🧠 Tech Stack

- 🐍 Python
- 📦 scikit-learn
- ✂️ TF-IDF Vectorization
- ⚔️ PassiveAggressiveClassifier
- 📄 Pandas / CSV
- 💾 Pickle for model saving

---

## 📁 Folder Structure

```
fake-news-detector/
├── data/
│   ├── Fake.csv
│   └── True.csv
├── model/
│   ├── model.pkl
│   └── vectorizer.pkl
├── notebooks/
│   └── fake_news_model.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

Used the **Fake and Real News Dataset** from Kaggle:  
[🔗 Kaggle Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

- `Fake.csv`: Fake news articles
- `True.csv`: Real news articles

---

## 🛠 How to Use

### 🔹 1. Clone this Repo
```bash
git clone https://github.com/your-username/fake-news-detector.git
cd fake-news-detector
```

### 🔹 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 3. Run the Notebook
```bash
jupyter notebook notebooks/fake_news_model.ipynb
```

The notebook handles training, testing, evaluation, and saving the model.

---

## ✅ Output Example

```text
✅ Accuracy: 96.54%
📊 Confusion Matrix:
[[563   5]
 [ 22 498]]
```

---

## 💻 Future Plans

- [ ] 🌐 Add Streamlit web app for live predictions  
- [ ] 📉 Improve model generalization  
- [ ] 🧪 Add experiment tracking and logging

---

## 👤 Author

**Jai Sarkar**  
AI Enthusiast | Code Architect | Builder of Blue 💙  
[GitHub Profile](https://github.com/your-username)

---

## ⭐️ Give it a star if you liked it!

Help support the project 💫
