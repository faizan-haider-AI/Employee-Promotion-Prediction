
# 📊 Promotion Prediction using Machine Learning

This project predicts whether an employee will be promoted or not, based on historical HR data. The notebook includes full **EDA**, **preprocessing**, and **machine learning model building**, with a focus on Random Forest and Logistic Regression models. The final models are saved using `joblib` for future deployment or integration.

---

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Joblib

---

## 📁 Dataset

The dataset used is:
- `clustered_dataset.csv` (likely from a Kaggle source)
- Contains HR-related features such as:
  - Employee department
  - Previous year rating
  - Education
  - KPIs met
  - Awards won
  - Avg training hours

---

## 📌 Project Structure

| Section         | Description                                                    |
|----------------|----------------------------------------------------------------|
| ✅ EDA          | Null values, shape, datatype analysis, feature exploration     |
| 📉 Visualization| Distribution plots, correlation matrix, and feature-target relationships |
| ⚙️ Preprocessing | Label Encoding, Feature Engineering                           |
| 🤖 Model Training | Trained **Random Forest** and **Logistic Regression** models  |
| 💾 Model Saving | Models saved using `joblib`                                    |
| 📊 Evaluation   | Accuracy, confusion matrix, and classification report         |

---

## 📦 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/faizan-haider-AI/Employee-Promotion-Prediction
cd promotion-prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook promotion-prediction.ipynb
```

4. The trained models will be saved as:

```
random_forest_model.pkl
logistic_regression_model.pkl
```

---

## 📈 Model Performance

Evaluate both models using `accuracy_score`, `confusion_matrix`, and other classification metrics. Choose the best model based on:

- Accuracy
- Precision/Recall
- Business context (e.g. promotion fairness, interpretability)

---

## ✅ Example Output

```python
Random Forest Accuracy: 0.95
Logistic Regression Accuracy: 0.89
```
