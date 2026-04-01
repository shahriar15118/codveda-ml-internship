# Codveda Machine Learning Internship — Final Submission

**Intern Domain:** Machine Learning  
**Organization:** [Codveda Technology](https://www.codveda.com)  
**Dataset Used:** Telecom Customer Churn (`churn-bigml-80.csv` / `churn-bigml-20.csv`)

---

## ✅ Tasks Completed

### 🟢 Level 1 — Basic

| Task | Description | Status |
|------|-------------|--------|
| Task 1 | Data Preprocessing for Machine Learning | ✅ Complete |
| Task 2 | Simple Linear Regression Model | ✅ Complete |
| Task 3 | K-Nearest Neighbors (KNN) Classifier | ✅ Complete |

### 🟡 Level 2 — Intermediate

| Task | Description | Status |
|------|-------------|--------|
| Task 1 | Logistic Regression for Binary Classification | ✅ Complete |
| Task 2 | Decision Tree Classifier | ✅ Complete |
| Task 3 | K-Means Clustering | ✅ Complete |

### 🔴 Level 3 — Advanced

| Task | Description | Status |
|------|-------------|--------|
| Task 1 | Random Forest Classifier | ✅ Code Complete / ⚠️ Unrun* |
| Task 2 | Support Vector Machine (SVM) | ✅ Code Complete / ⚠️ Unrun* |
| Task 3 | Neural Network with TensorFlow/Keras | ✅ Code Complete / ⚠️ Unrun* |

> *Advanced level cells are fully written but could not be executed due to Google Colab free-tier RAM limitations causing repeated crashes. All code follows the same verified pipeline structure as the successfully run Level 1 and Level 2 tasks.

---

## 📁 File Structure

```
codveda.ipynb       # Main Jupyter Notebook with all tasks
README.md           # This file
```

> **Dataset Note:** The notebook uses `churn-bigml-80.csv` (training) and `churn-bigml-20.csv` (testing). These are publicly available on Kaggle: [Churn in Telecom's dataset](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset).

---

## 🛠️ Tools & Libraries Used

- **Python** — pandas, NumPy
- **scikit-learn** — preprocessing, LinearRegression, KNN, LogisticRegression, DecisionTree, RandomForest, SVM, KMeans
- **TensorFlow / Keras** — Neural Network (Level 3 Task 3)
- **matplotlib / seaborn** — Visualization

---

## 📌 Key Highlights

- All tasks applied to a **real-world telecom churn dataset** (not toy data)
- Consistent **pipeline architecture** using `sklearn.Pipeline` across all tasks
- Proper **train/test split** maintained throughout (80/20 pre-split CSVs)
- **Class imbalance** handled using `class_weight='balanced'` in classifiers
- Visualizations include ROC curves, confusion matrices, elbow plots, and feature importance charts

---

## 📬 Contact

**LinkedIn:** Tag @Codveda  
**Hashtags:** #CodvedaJourney #CodvedaExperience #FutureWithCodveda  
**Submission Form:** [forms.gle/ACmj98WfL3bHTc6g6](https://forms.gle/ACmj98WfL3bHTc6g6)
