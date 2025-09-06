# ID3 Decision Tree Classifier (from Scratch)

This project implements the **ID3 Decision Tree algorithm** in Python from scratch without using machine learning libraries like `scikit-learn`. It builds a decision tree based on entropy and information gain.

---

## 📌 Features
- Implements **ID3 Algorithm** using Entropy and Information Gain.
- Builds a decision tree from a CSV dataset.
- Supports:
  - Recursive tree construction.
  - Printing the decision tree in a readable format.
  - Prediction for new instances.
- Handles:
  - Pure subsets (all same class).
  - No remaining attributes (uses majority class).
  - Empty branches (assigns majority class).

---

## 📊 Dataset
- The dataset should be in **CSV format**.
- The **last column** (or a column named `answer`) is treated as the target variable.
- Example dataset:

```csv
outlook,temp,humidity,wind,answer
sunny,hot,high,weak,no
sunny,hot,high,strong,no
overcast,hot,high,weak,yes
rain,mild,high,weak,yes
