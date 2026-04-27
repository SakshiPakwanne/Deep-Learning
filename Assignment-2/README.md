📘 Encoder–Decoder Models with and without Attention
Comparative Study (Deep Learning Assignment)
📌 Objective

The objective of this assignment is to understand, implement, and compare Encoder–Decoder models with and without Attention mechanisms, and analyze their performance on sequence-to-sequence tasks.

📂 Project Structure
├── Assignment_2_DL.ipynb     # Main implementation notebook
├── data/                    # Dataset files
├── models/                  # Saved models
├── outputs/                 # Results, predictions, graphs
└── README.md                # Project documentation
🧠 Overview

Encoder–Decoder models are widely used for sequence-based tasks such as:

Machine Translation
Text Summarization
Speech Recognition

This project compares:

🔹 Baseline Model → Encoder–Decoder (without Attention)
🔹 Improved Model → Encoder–Decoder (with Attention)

📖 Assignment Breakdown
🔹 Part 1: Research Paper Review
Studied recent paper (2023–2025)
Analyzed:
Problem statement
Model architecture
Attention mechanism
Dataset
Contributions & limitations
🔹 Part 2: Code Study & Execution
Executed official implementation
Understood:
Model architecture
Training pipeline
Attention working
Captured output screenshots
🔹 Part 3: Implementation & Comparison

Two models were implemented:

✅ Model 1: Without Attention (Baseline)
Standard Encoder–Decoder
Fixed context vector
✅ Model 2: With Attention
Dynamic context generation
Better alignment between input & output

📊 Evaluation Metrics
Loss
Accuracy / BLEU Score
Training Time
Output Quality

📈 Results & Comparison
Metric	Without Attention	With Attention
Loss	Higher	Lower
Accuracy/BLEU	Moderate	Higher
Training Time	Faster	Slightly Slower
Output Quality	Limited	Improved

🔍 Analysis
✔ Benefits of Attention
Better context understanding
Improved handling of long sequences
Accurate word alignment

❌ Limitations without Attention
Information loss in long sequences
Poor performance on complex inputs

⚙️ Technologies Used
Python
PyTorch / TensorFlow
Jupyter Notebook
NumPy, Matplotlib

🚀 How to Run
Install dependencies:
pip install torch numpy matplotlib
Open Jupyter Notebook:
jupyter notebook
Run:
Assignment_2_DL.ipynb

📚 Conclusion

This project demonstrates that Attention mechanisms significantly improve Encoder–Decoder models, especially for long and complex sequences, making them essential in modern deep learning applications.

👨‍💻 Author
Name:Sakshi Pakwanne
Batch:AIML4
Subject: Deep Learning

🔗 References
Research papers (2023–2025)
Official GitHub implementations
Documentation of PyTorch / TensorFlow
