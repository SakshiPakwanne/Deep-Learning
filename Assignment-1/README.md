🧠 Neural Network from Scratch (Python)
📌 Overview

This project implements a simple feedforward neural network from scratch using Python and NumPy, without using any deep learning libraries like TensorFlow or PyTorch.

The goal is to understand the core working of neural networks, including forward propagation, backpropagation, and gradient descent.

🎯 Objective
Build a neural network manually
Implement:
Forward Pass
Backpropagation
Gradient Descent
Train the model on a real-world dataset
Display updated weights in each epoch
📂 Dataset
Breast Cancer Wisconsin Dataset
Binary classification:
1 → Malignant
0 → Benign

📥 Kaggle Link:
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

⚙️ Technologies Used
Python
NumPy
Pandas
Matplotlib
🧠 Neural Network Architecture
Input Layer: Based on dataset features
Hidden Layer: 10 neurons
Output Layer: 1 neuron (Binary classification)

Activation Function:

Sigmoid
📐 Mathematical Formulation
Forward Pass:

Z1 = XW1 + b1
A1 = sigmoid(Z1)

Z2 = A1W2 + b2
A2 = sigmoid(Z2)

Loss Function:

Binary Cross Entropy
L = -[y log(A2) + (1-y) log(1-A2)]

Backpropagation:

dZ2 = A2 - y
dW2 = A1ᵀ · dZ2

dZ1 = dA1 · sigmoid'(Z1)
dW1 = Xᵀ · dZ1

🔄 Training Details
Optimizer: Gradient Descent
Learning Rate: 0.01
Epochs: 50
Weights are updated and printed after every epoch
📊 Evaluation Metrics
Accuracy
Precision
Recall
📈 Results

The model successfully learns to classify tumors as malignant or benign with good accuracy.

🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/neural-network-from-scratch.git
Install dependencies:
pip install numpy pandas matplotlib
Run the notebook:
jupyter notebook
Upload the dataset (data.csv) and execute all cells.
💡 Key Learnings
Understanding of neural network internals
Manual implementation of backpropagation
Importance of normalization
Effect of learning rate on training
📌 Note

This project is implemented purely for educational purposes to understand the fundamentals of neural networks.

👩‍💻 Author

Sakshi Pakwanne
