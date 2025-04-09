# 🧠 Customer Segmentation using K-Means Clustering

This project segments customers based on key features like Age, Income, and Spending Score using the K-Means clustering algorithm.

## 📁 Dataset
- **Source**: Mall Customers dataset (sample data)
- **Features used**:
  - Age
  - Annual Income
  - Spending Score
  - Genre (encoded)
  - IncomePerAge (engineered)

## ⚙️ Workflow

1. Data Cleaning & Encoding
2. Feature Engineering: Created `IncomePerAge`
3. Feature Scaling: StandardScaler
4. Finding Optimal Clusters: Elbow Method + Silhouette Score
5. Clustering with K-Means
6. Visualizations

## 📊 Project Results

- **Best number of clusters (k)**: **9** (based on silhouette score)
- **Highest Silhouette Score**: **~0.33**
- **Clustering visualized on**: `Income` vs. `Spending Score`

> While the elbow method pointed toward k = 5, we selected k = 9 for final clustering due to a higher silhouette score, indicating better-defined clusters.

## 📌 Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📈 Visualizations
- Elbow Method for choosing `k`
- Cluster visualization

## 🚀 How to Run

1. Clone the repo  
2. Open in Jupyter Notebook or Google Colab  
3. Run all cells in order

---

### 🤝 Connect with Me

- LinkedIn: [Vijay patidar](www.linkedin.com/in/vijay-patidar-ai)
