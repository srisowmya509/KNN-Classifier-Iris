# KNN Classifier on Iris Dataset 🌸

This project applies the **K-Nearest Neighbors (KNN)** algorithm to the famous **Iris dataset** using Scikit-learn. It covers the complete process from data normalization, model training, evaluation, to visualizing decision boundaries.

---

## 📂 Features
- ✔️ Normalized features using `StandardScaler`
- ✔️ Classification using `KNeighborsClassifier`
- ✔️ Tested for multiple values of `K` (1, 3, 5, 7)
- ✔️ Evaluated using Accuracy and Confusion Matrix
- ✔️ Visualized decision boundaries (for 2 features)

---

## 📊 Dataset
- **Dataset Used:** Iris dataset from `sklearn.datasets`
- **Features Used:** First two features (`sepal length` and `sepal width`) for visualization

---

## 🚀 How to Run (In Google Colab)
1. Open [Google Colab](https://colab.research.google.com)
2. Copy and paste the code from `KNN_Classifier.ipynb` or this repository
3. Run all cells to:
   - Normalize data
   - Train KNN models
   - Plot decision boundaries
   - Display confusion matrices

---

## 📸 Sample Output

| K | Accuracy | Visualization |
|---|----------|----------------|
| 1 | High     | Fine-grained decision regions |
| 3 | Good     | Smoother decision boundaries |
| 5 | Balanced| More general boundaries |
| 7 | Moderate| Overgeneralized regions |

---

