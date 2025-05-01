# TASK5
Decision Trees and Random Forests
# 🧠 Task 5: Decision Trees & Random Forests (Heart Disease Prediction)

This project is part of an AI & ML Internship. It involves applying Decision Tree and Random Forest classifiers to predict the presence of heart disease using a real-world dataset.

---

## 📁 Dataset

- **Name**: Heart Disease Dataset
- **Source**: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Rows**: 303
- **Columns**: 14 (13 features + 1 target)
- **Target**: `target` (1 = Disease present, 0 = No disease)

---

## 📌 Objectives

- Train a **Decision Tree Classifier**
- Visualize the decision tree using `plot_tree`
- Control tree depth and **analyze overfitting**
- Train a **Random Forest Classifier**
- Compare model accuracies
- Interpret **feature importances**
- Evaluate with **cross-validation**

---

## 🛠️ Tools & Libraries Used

- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (sklearn)

---

## 📊 Model Performance

| Model            | Accuracy (Test Set) |
|------------------|---------------------|
| Decision Tree    | ~80%                |
| Random Forest    | ~85%                |
| Cross-Validation | ~83–86%             |

---

## 🔍 Key Insights

- Limiting `max_depth` helps **reduce overfitting** in Decision Trees.
- Random Forest provides better **generalization** and accuracy.
- Features like `cp`, `thalach`, and `oldpeak` were found to be important.

---

## 🖼️ Visualizations Included

- Target distribution plot
- Decision tree structure (colored)
- Accuracy vs Tree Depth graph
- Random Forest feature importance bar chart

---
