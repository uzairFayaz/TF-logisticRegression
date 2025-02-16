# Logistic Regression with TensorFlow

## 📌 Overview
This project demonstrates a **Logistic Regression** model using **TensorFlow**. The model predicts a **binary outcome (0 or 1)** based on a single feature and visualizes the decision boundary.

## 📂 Project Structure
```
├── logistic_regression.py  # Main script for logistic regression
├── README.md               # Project documentation
```

## 📜 Description
Logistic regression is a statistical method for **binary classification**. It applies the **sigmoid activation function** to map predictions between **0 and 1**. The dataset consists of random numbers (0–10), labeled as **1 if X > 5**, otherwise **0**.

## 🔧 Requirements
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## 📦 Installation
```sh
pip install tensorflow numpy matplotlib
```

## 🚀 Usage
Run the Python script to train the model and visualize the decision boundary:
```sh
python logistic_regression.py
```

## 📊 Model Summary
- **Input**: Single numerical feature (X)
- **Output**: Binary classification (0 or 1)
- **Activation Function**: Sigmoid
- **Loss Function**: Binary Cross-Entropy
- **Optimizer**: Adam
- **Training Data**: 100 random samples (X, y)

## 🖼 Visualization
The script generates a plot showing:
- **Blue points**: Training data
- **Red curve**: Sigmoid function (decision boundary)

## 🔹 Sample Output
```
Predictions: [[0.]
              [1.]]
```
- If **X = 2**, the model predicts **0**
- If **X = 7**, the model predicts **1**

## 🏆 Key Takeaways
✅ Logistic regression is useful for **binary classification** problems.
✅ Uses the **sigmoid activation function**.
✅ Loss function: **Binary Cross-Entropy**.
✅ Can be extended for **multi-class classification (Softmax)**.



