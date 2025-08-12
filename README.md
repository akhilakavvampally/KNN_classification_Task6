# KNN_classification_Task6
using KNN algorithm for classification using iris dataset
# 🔍 K-Nearest Neighbors (KNN) Classification - Iris Dataset

This project implements the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris Dataset**.  
It was created as part of **AI & ML Internship - Task 6**.

---

## 📌 Project Overview
- **Goal:** Understand and implement KNN for classification.
- **Dataset:** [Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
- **Tools Used:**  
  - Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
  - Google Colab for execution

---

## 📂 Dataset
The Iris dataset contains:
- **150 samples**  
- **4 features:** sepal length, sepal width, petal length, petal width  
- **3 classes:** Setosa, Versicolor, Virginica

---

## ⚙️ Steps Performed
1. **Load dataset** from scikit-learn.
2. **Normalize features** using StandardScaler.
3. **Train-test split** (80% train, 20% test).
4. **Test different K values** from 1 to 10.
5. **Select best K** based on accuracy.
6. **Evaluate model** using accuracy, confusion matrix, classification report.
7. **Visualize decision boundaries** using first two features.

---

## 📊 Example Results

- K=3 → Accuracy: 1.0000
- K=5 → Accuracy: 1.0000
- Best K: 3
- Classification Report:
- precision recall f1-score support
- setosa 1.00 1.00 1.00 10
- versicolor 1.00 1.00 1.00 9
- virginica 1.00 1.00 1.00 11


