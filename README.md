# 🧠 Breast Cancer Classification using K-Nearest Neighbors (KNN)

This project uses the K-Nearest Neighbors (KNN) machine learning algorithm to classify whether a tumor is benign or malignant based on key diagnostic features. The dataset used is the well-known **Breast Cancer Wisconsin (Diagnostic) Dataset**, commonly used for binary classification problems in medical data science.

---

## 📁 Project Structure

- `Breast-Cancer-KNN.ipynb` — Main Jupyter notebook containing:
  - Data loading and preprocessing
  - Exploratory Data Analysis (EDA)
  - Feature selection
  - KNN model training and evaluation
  - Accuracy and performance metrics

---

## 📊 Dataset Overview

The dataset contains 30 numeric features computed from digitized images of fine needle aspirates (FNAs) of breast masses. These features represent characteristics like radius, texture, smoothness, and more.

- **Target**: Diagnosis (`M` = malignant, `B` = benign)
- **Features**: Mean, standard error, and worst values of:
  - Radius
  - Texture
  - Perimeter
  - Area
  - Smoothness, etc.

---

## 🧪 Model

- **Algorithm**: K-Nearest Neighbors (KNN)
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Key steps**:
  - Data normalization
  - Train-test split
  - Model tuning with different values of `k`
  - Accuracy and confusion matrix analysis

---

## ✅ Results

- Achieved high accuracy on test data.
- Visualization of performance through confusion matrix and accuracy scores.
- Analysis of optimal `k` value for the best model performance.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/breast-cancer-knn.git
   cd breast-cancer-knn
