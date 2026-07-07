# Financial Fraud Detection using Artificial Neural Network (ANN)

## 📌 Project Overview

This project detects fraudulent credit card transactions using an Artificial Neural Network (ANN). Since fraud transactions are very rare compared to genuine transactions, the SMOTE (Synthetic Minority Oversampling Technique) was used to balance the training dataset before training the model.

The objective of this project is to build a machine learning model that can accurately classify transactions as genuine or fraudulent.

---

## 📂 Dataset

- Dataset: Credit Card Fraud Detection Dataset
- Source: Kaggle
- Total Records: 284,807
- Features: 30 input features
- Target Column: Class
  - 0 = Genuine Transaction
  - 1 = Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- SMOTE (imbalanced-learn)

---

## 📊 Project Workflow

1. Load the dataset
2. Explore and analyze the dataset
3. Check missing values
4. Analyze class imbalance
5. Split the dataset into training and testing sets
6. Apply SMOTE to balance the training data
7. Standardize the features
8. Build an Artificial Neural Network (ANN)
9. Train the model
10. Evaluate model performance
11. Generate predictions
12. Display Confusion Matrix and Classification Report

---

## 🧠 ANN Architecture

- Input Layer: 30 Features
- Hidden Layer 1: 16 Neurons (ReLU)
- Hidden Layer 2: 8 Neurons (ReLU)
- Output Layer: 1 Neuron (Sigmoid)

Optimizer:
- Adam

Loss Function:
- Binary Crossentropy

Evaluation Metric:
- Accuracy

---

## 📈 Results

The ANN model was trained successfully after balancing the dataset using SMOTE.

Evaluation included:

- Test Accuracy
- Confusion Matrix
- Classification Report

---

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Upload the `creditcard.csv` dataset.
3. Run all cells from top to bottom.
4. View the evaluation metrics and graphs.

---

## 👩‍💻 Author

Ajeeta Singh


Project: Financial Fraud Detection using ANN
