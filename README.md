# 🔢 Handwritten Digits Classification using K-Nearest Neighbors (KNN)

This project implements a KNN classifier to recognize handwritten digits (0–9) using the built-in **Digits Dataset** from scikit-learn. It includes:

- Accuracy evaluation
- Confusion matrix
- 2D PCA projection + decision boundary visualization

## 📊 Dataset

- Source: `sklearn.datasets.load_digits()`
- 1797 samples, 64 features (8x8 grayscale images)
- 10 target classes: digits 0 through 9

## 🧠 Model

- K-Nearest Neighbors (KNN)
- `n_neighbors = 5`
- Preprocessing: `StandardScaler`

## 📊 Visuals

- Confusion Matrix
- Decision Boundary (via PCA)

## 🚀 How to Run

1. Open `digits_knn_classifier.ipynb` in Google Colab or Jupyter Notebook
2. Run all cells

## 🔧 Dependencies
1. scikit-learn
2. matplotlib
3. numpy

