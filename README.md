# 🍷 Task 6 – K-Nearest Neighbors (KNN) Classification (AI & ML Internship)

This task demonstrates the use of the **K-Nearest Neighbors (KNN)** algorithm on the **Wine dataset** to classify different types of wines based on their chemical properties.

---

## 📂 Dataset

- **Source**: `sklearn.datasets.load_wine()`
- **Samples**: 178
- **Classes**: 3 (wine cultivars)
- **Features**: 13 numerical attributes (e.g., alcohol, magnesium, flavanoids)

---

## 🎯 Objective

- Normalize input features.
- Train a KNN classifier.
- Evaluate model using accuracy, confusion matrix, and classification report.
- Experiment with different values of K.
- Understand the impact of K and normalization in KNN.

---

## 🛠 Tools & Libraries

- Python 3
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 🔁 Steps Performed

1. Loaded the **Wine dataset** from `sklearn.datasets`.
2. Normalized features using `StandardScaler` to ensure all attributes contribute equally.
3. Split data into **train/test sets** using 80/20 ratio.
4. Trained multiple KNN models with different values of `K` (1–10).
5. Selected the best `K` based on test accuracy.
6. Evaluated the final model using:
   - Accuracy
   - Classification Report
   - Confusion Matrix (with heatmap)

---

## 📊 Results

| K | Accuracy |
|---|----------|
| 1 | ~0.94    |
| 3 | **~0.97** |
| 5 | ~0.94    |
| 7 | ~0.92    |

- **Best K**: 3
- **Final Accuracy**: ~0.97
- **Strong classification across all 3 wine types**

---

## 📘 Key Learnings

- **KNN is sensitive to scale**, so normalization is essential.
- Accuracy depends on the choice of `K`.
- Easy to implement, but expensive during prediction time.
- Visualization of confusion matrix helps in assessing model reliability.

---
