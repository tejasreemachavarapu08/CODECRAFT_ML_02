# 🛍️ Customer Segmentation using K-Means Clustering

This project applies the **K-Means clustering algorithm** to segment customers of a retail store based on their **annual income** and **spending score**. Customer segmentation helps businesses understand buying behavior and tailor marketing strategies accordingly.

---

## 📊 Dataset
- The dataset used is `Mall_Customers.csv`
- Features used for clustering:
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 🤖 Model Used
- **Algorithm**: K-Means Clustering
- **Library**: `sklearn.cluster.KMeans`
- **Optimization**: Elbow Method used to select the best number of clusters

---

## 🧪 Results
- Optimal number of clusters (K): `5` *(adjust if you used a different value)*
- Cluster labels assigned to each customer
- Visualized customer groups in a 2D scatter plot

---

## 📈 Visualizations
- Elbow method graph (Inertia vs K)
- Scatter plot of customer segments
- Cluster centroids (optional)

---

## 🧾 How to Run
```bash
1. Clone this repository
2. Install dependencies (e.g., pandas, matplotlib, sklearn)
3. Run the Jupyter Notebook to see the results
