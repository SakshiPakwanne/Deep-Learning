# Assignment 6: Encoder–Decoder Models with and without Attention – Comparative Study

## 📌 Overview
This project presents a comparative study of **Seq2Seq Encoder–Decoder Models** with and without the **Attention Mechanism** for text summarization tasks. The goal is to analyze how attention improves contextual understanding, output quality, and long-sequence handling.

---

## 🎯 Problem Statement
Text summarization aims to generate concise and meaningful summaries from large text data.

Traditional Seq2Seq models face a major limitation:
- Entire input is compressed into a fixed-length context vector
- Causes information loss
- Poor performance on long sequences

To solve this, the **Attention Mechanism** was introduced, allowing the decoder to focus on important parts of the input dynamically.

---

## 🏗️ Model Architecture

### 🔹 Encoder
- Processes input text sequence
- Converts words into vector embeddings
- Uses **Bidirectional GRU**
- Produces:
  - Hidden states for all time steps
  - Final context representation

### 🔹 Decoder
- Generates output summary word-by-word
- Uses:
  - Previous predicted word
  - Hidden state
  - Context vector

### 🔹 Attention Layer
- Compares decoder hidden state with encoder outputs
- Assigns weights to important input words
- Creates dynamic context for better decoding

---

## 📂 Dataset Used
Common datasets for text summarization:

- CNN / DailyMail
- News datasets
- Custom text datasets

---

## ⚙️ Technologies Used
- Python
- TensorFlow / PyTorch
- NumPy
- Jupyter Notebook

---

## 📊 Performance Comparison

| Metric | Without Attention | With Attention |
|--------|------------------|----------------|
| Loss | 2.9000 | 1.800 |
| Accuracy | 24% | 35% |
| Training Time | 25–40 sec | 35–55 sec |
| Output Quality | Poor | Good & Fluent |

---

## 📈 Results Analysis

### ✅ With Attention
- Better context understanding
- Improved sequence alignment
- Better handling of long inputs
- Lower loss and higher accuracy

### ❌ Without Attention
- Fixed context vector limitation
- Information loss
- Poor output quality
- Weak performance on long sequences

---

## 🚫 Limitations

### Without Attention
- Fixed-length memory bottleneck
- Poor long-sequence learning
- Lower accuracy

### With Attention
- Higher computational cost
- Slower training
- More parameters

---

## 🧠 Conclusion
Attention mechanisms significantly improve Encoder–Decoder models by allowing dynamic focus on relevant input tokens.

This study confirms that attention-based Seq2Seq models are more efficient and reliable for tasks like:

- Text Summarization
- Machine Translation
- Sequence Generation

---

## 📁 Files Included
- `PEC_Assignment6.docx`
- `Assignment6(2).ipynb`

---

## 👨‍💻 Author
**Sakshi Pakwanne**  
MIT Academy of Engineering

---
