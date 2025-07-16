# 🎯 Customer Segmentation Using K-Means Clustering

A complete machine learning project to segment customers using unsupervised learning and extract actionable business insights from raw customer data.



 📌 Problem Statement

Businesses often waste marketing budgets by treating all customers equally. The goal is to segment customers based on their demographics and purchasing behavior, identify high-value groups, and create targeted strategies.

---

## 🧠 ML Solution

Using the **KMeans Clustering algorithm**, we segmented the customers into 5 distinct groups using:

- Age
- Annual Income
- Spending Score
- Gender (one-hot encoded)

After performing Elbow Method analysis, **K=5** was found to be optimal.

---

## 📊 Dataset Features

| Feature         | Description                        |
|----------------|------------------------------------|
| Gender          | Male/Female (One-hot encoded)     |
| Age             | Customer's age                    |
| Annual Income   | Income in thousands ($k)          |
| Spending Score  | Based on purchasing activity      |
| Target          | Business-labeled target customer  |

📁 Dataset: `data/target_customers.csv`

---

## 🔍 Cluster Summary & Target Insights

| Cluster | Profile Summary                    | Target % | Action Plan                       |
|---------|-------------------------------------|----------|-----------------------------------|
| 0       | High income, low spending           | 100% ✅  | Upsell premium services           |
| 1       | Young, high spenders                | ~        | Loyalty rewards                   |
| 2       | Low income, low spending            | ~        | Low marketing focus               |
| 3       | Older, moderate spenders            | 0% ❌   | Exclude from campaigns            |
| 4       | Balanced earners                    | ~        | Retention strategies              |

---

## 📈 Visualizations

- Elbow plot to determine optimal clusters  
- Cluster distribution scatter plots  
- Target mapping per cluster

---

## 🛠️ Tech Stack

- `Python`
- `Pandas`, `NumPy`
- `Scikit-learn` (KMeans)
- `Matplotlib`, `Seaborn`

