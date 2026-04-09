# 🧠 NLP Text Classification (YouTube Spam Detection)

## 📌 Overview

This project implements a complete Natural Language Processing (NLP) pipeline for spam detection using machine learning techniques.

The model classifies YouTube comments as Spam or Not Spam by applying text preprocessing, feature extraction, and classification algorithms.

---

## 🎯 Objective

- Perform NLP preprocessing on raw text data  
- Implement:
  - Tokenization  
  - Stopword Removal  
  - Stemming & Lemmatization  
- Convert text into numerical form using:
  - CountVectorizer  
  - TF-IDF  
- Train a classification model  
- Evaluate model performance  

---

## 📂 Dataset

- YouTube Spam Dataset  
- Contains YouTube comments labeled as:
  - 1 → Spam  
  - 0 → Not Spam  

Dataset Source: Kaggle  

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- NLTK  

---

## 🧠 Model Pipeline

### 🔹 Text Preprocessing

- Lowercasing  
- Tokenization  
- Removal of punctuation  
- Stopword removal  
- Stemming  
- Lemmatization  

---

### 🔹 Feature Extraction

- CountVectorizer (Bag of Words)  
- TF-IDF Vectorizer  

---

### 🔹 Classification Model

- Multinomial Naive Bayes  

---

## 📐 Mathematical Concept

TF = (Number of times word appears) / (Total words)  
IDF = log(Total Documents / Documents containing word)  
TF-IDF = TF × IDF  

---

## 🔄 Training Details

- Train-Test Split: 80:20  
- Models trained using:
  - CountVectorizer  
  - TF-IDF  
- Comparison performed between both approaches  

---

## 📊 Evaluation Metrics

- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## 📈 Results

- TF-IDF performed better than CountVectorizer  
- The model successfully classified spam and non-spam comments  
- Achieved good accuracy on test data  

---

## 🚀 How to Run

1. Clone the repository  
git clone https://github.com/your-username/deep-learning.git  

2. Install dependencies  
pip install numpy pandas matplotlib seaborn scikit-learn nltk  

3. Run the notebook  
jupyter notebook  

4. Upload the dataset (Youtube-Spam-Dataset.csv) and run all cells  

---

## 💡 Key Learnings

- Importance of text preprocessing in NLP  
- Difference between CountVectorizer and TF-IDF  
- How machine learning models handle text data  
- Evaluation of classification models  

---

## 📌 Note

This project is implemented for educational purposes to understand the complete NLP pipeline from raw text to classification.

---

## 👩‍💻 Author

Sakshi Pakwanne
