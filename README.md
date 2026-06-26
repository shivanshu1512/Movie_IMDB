# 🎬 IMDB Movie Reviews — Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-orange?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-50K%20Reviews-green?style=for-the-badge&logo=kaggle)
![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)

> A machine learning project for **binary sentiment classification** on 50,000 IMDB movie reviews using Natural Language Processing (NLP) techniques.

---

## 📌 Project Overview

This project aims to classify IMDB movie reviews as **Positive** or **Negative** using various NLP and Machine Learning approaches. The dataset contains 50,000 reviews — 25,000 for training and 25,000 for testing.

---

## 📂 Project Structure

```
Movie_IMDB/
│
├── dataset/                  # Dataset info & download instructions
│   └── README.md             # How to download the dataset from Kaggle
│
├── notebooks/                # Jupyter Notebooks
│   └── (your notebooks here)
│
├── src/                      # Source code
│   └── (your scripts here)
│
├── .gitignore                # Ignores large CSV files
└── README.md                 # You are here
```

---

## 📊 Dataset

| Property        | Details                                      |
|----------------|----------------------------------------------|
| **Source**      | [Kaggle — IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) |
| **Author**      | Lakshmipathi N                               |
| **Total Reviews** | 50,000                                     |
| **Training Set** | 25,000 reviews                              |
| **Testing Set** | 25,000 reviews                               |
| **Classes**     | Positive 👍 / Negative 👎                   |
| **Format**      | CSV (`review`, `sentiment`)                  |
| **Size**        | ~66 MB (uncompressed)                        |

> ⚠️ The dataset CSV is **not included** in this repo due to GitHub's 25MB file limit.
> See [`dataset/README.md`](./dataset/README.md) for download instructions.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/shivanshu1512/Movie_IMDB.git
cd Movie_IMDB
```

### 2. Download the Dataset

Follow the instructions in 👉 [`dataset/README.md`](./dataset/README.md)

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook / Script

```bash
jupyter notebook notebooks/
```

---

## 🧠 Approach

- **Text Preprocessing** — Lowercasing, removing HTML tags, stop words, punctuation
- **Feature Extraction** — TF-IDF / Word Embeddings
- **Models** — Logistic Regression, Naive Bayes, LSTM, BERT (planned)
- **Evaluation** — Accuracy, Precision, Recall, F1-Score

---

## 📈 Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression | Coming Soon |
| Naive Bayes         | Coming Soon |
| LSTM                | Coming Soon |

---

## 🛠️ Tech Stack

- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- NLTK / SpaCy
- TensorFlow / PyTorch (for deep learning)
- Matplotlib, Seaborn

---

## 📬 Contact

**Shivanshu Shukla**
- GitHub: [@shivanshu1512](https://github.com/shivanshu1512)

---

## ⭐ Star this repo if you found it helpful!
