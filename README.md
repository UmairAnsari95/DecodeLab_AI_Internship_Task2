# 📊 Project 2: Data Classification Using AI
### DecodeLabs Industrial Training Kit — Batch 2026

---

## 🚀 Overview
This project implements a complete supervised learning pipeline for classifying data using scikit-learn. Built as part of the DecodeLabs AI Engineering track, it demonstrates the full journey from raw data to a validated, production-style classification model — no shortcuts, no black boxes.

---

## 🎯 Objective
Build a basic but professionally validated classification model that can:
- 📥 Load and understand a dataset
- ✂️ Split data into training and testing sets
- 🤖 Apply a supervised classification algorithm
- 📈 Evaluate performance with real metrics — not just accuracy

---

## 🧠 Dataset
Iris Dataset (via `sklearn.datasets.load_iris()`)

- 🌸 150 samples, perfectly balanced
- 🏷️ 3 classes: Setosa, Versicolor, Virginica
- 📐 4 features: sepal length/width, petal length/width

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐼 pandas | Data handling & inspection |
| 🔢 numpy | Numerical operations |
| 📊 matplotlib / seaborn | Visualization |
| 🧮 scikit-learn | Preprocessing, modeling, evaluation |

> ⚠️ No TensorFlow, PyTorch, XGBoost, or hyperparameter search tools used — pure algorithmic logic, as required.

---

## 🔬 Workflow (IPO Framework)

INPUT

- Loaded dataset, checked shape, `.info()`, `.describe()`
- Verified: zero missing values, zero duplicates ✅

PROCESS

- 🔀 80:20 stratified train-test split (`random_state=42`)
- ⚖️ Feature scaling via `StandardScaler` (mean=0, variance=1)
- 🧩 Trained Logistic Regression classifier

OUTPUT

- ✅ Accuracy, Precision, Recall, F1 Score
- 🧾 Full Classification Report
- 🔥 Confusion Matrix heatmap
- 📊 Feature Importance chart (via model coefficients)

---

## 📈 Key Results

- 🏆 High accuracy across all three classes
- 🌟 Setosa perfectly separable; minor overlap only between Versicolor/Virginica
- 🥇 Petal length & petal width identified as the most influential features

---

## 💡 Conclusion

This notebook proves the fundamental ML pipeline works end-to-end: train → test → validate. It's a real-world-ready foundation before moving on to more advanced models like neural networks and computer vision. 🚧➡️🧠

---

## 👨‍💻 Author

Umair Sajid

🎓 AI Engineering Intern | DecodeLabs Batch 2026

---

