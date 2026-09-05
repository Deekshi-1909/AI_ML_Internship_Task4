# AI & ML Internship - Task 4: Classification with Logistic Regression

## 🎯 Objective
Built a binary classifier using **Logistic Regression** to predict breast cancer diagnosis (Malignant vs. Benign) using the Breast Cancer Wisconsin Dataset.

---

## 🛠️ Tools & Libraries Used
* **Python** 
* **Scikit-learn** (Dataset, Splitting, Scaler, Model, & Metrics)
* **Pandas** & **NumPy** (Data manipulation)
* **Matplotlib** (Visualization)

---

## 📈 Model Performance & Evaluation Results
The model was trained on an 80/20 train-test split, and features were standardized using `StandardScaler`. 

### 1. Confusion Matrix
* **True Negatives (0 predicted as 0):** 41
* **False Positives (0 predicted as 1):** 2
* **False Negatives (1 predicted as 0):** 1
* **True Positives (1 predicted as 1):** 70

### 2. Classification Metrics
* **Overall Accuracy:** 97%
* **ROC-AUC Score:** 0.9974
