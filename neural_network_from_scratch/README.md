# Neural Network from Scratch 🧠

This project implements a basic neural network using only NumPy, without using any deep learning libraries.  
It is trained on real-world datasets for binary classification tasks and demonstrates forward/backpropagation from scratch.

## 📚 Features
- Forward propagation
- Backpropagation
- Sigmoid activation function
- Cross-entropy loss
- Weight updates using gradient descent

## 🧪 Datasets Used

### 1. Iris Dataset
- Source: `sklearn.datasets`
- Binary labels:
  - 1 → Setosa
  - 0 → Versicolor or Virginica
- Note: Accuracy reaches nearly 100% too easily due to class separability.

### 2. Breast Cancer Wisconsin Dataset
- Source: `sklearn.datasets`
- Binary labels:
  - 1 → Malignant
  - 0 → Benign
- Used to test generalization and observe more nuanced training behavior.

## 📂 Files
- `iris_binary_nn.ipynb` → Neural network using the Iris dataset
- `breast_cancer.csv` → Breast cancer dataset (if not loaded via sklearn)
- `requirements.txt` → Dependencies

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install numpy scikit-learn matplotlib
