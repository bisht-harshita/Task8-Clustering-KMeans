# 🌀 K-Means Clustering — Mall Customer Segmentation

## 📌 Overview  
The goal is to apply **K-Means Clustering** on the **Mall Customer Segmentation dataset** to discover customer groups based on spending patterns and demographics.

The notebook goes beyond the basic clustering by including **EDA, PCA, silhouette analysis, and cluster profiling**, making the work comprehensive and unique.

---

## 📊 Dataset
- **Source:** Mall Customer Segmentation Data  
- **Features:**
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)
- **Target:** No labels (unsupervised learning)

---

## 🛠 Tools & Libraries
- Python 3.x  
- Pandas, NumPy (data handling)  
- Matplotlib, Seaborn (visualization)  
- scikit-learn (KMeans, Silhouette, PCA, scaling)

---

## 🚀 Features Implemented
1. **Exploratory Data Analysis (EDA)**
   - Dataset overview, missing values check
   - Gender distribution plot
   - Pairplot and correlation heatmap

2. **Preprocessing**
   - Feature selection (`Age`, `Annual Income`, `Spending Score`)
   - Feature scaling using `StandardScaler`

3. **Clustering**
   - K-Means applied with multiple values of K
   - Optimal K determined using **Elbow Method**

4. **Evaluation**
   - Silhouette Score for cluster quality
   - Silhouette visualization for multiple K values

5. **Visualization**
   - PCA (2D & 3D cluster visualization)
   - Cluster heatmap (mean feature values per cluster)

6. **Cluster Profiling**
   - Average age, income, and spending score per cluster
   - Insights into customer segments (e.g., high-income high-spending vs low-income low-spending)

---

## 📈 Results Summary
- **Elbow Method:** Optimal K ≈ 5  
- **Silhouette Score (K=5):** ~0.55 (good separation)  
- **Cluster Insights:**
  - Cluster 1: Younger customers with high spending
  - Cluster 2: Middle-aged, moderate income, low spending
  - Cluster 3: Older, high income but low spending
  - Cluster 4: Balanced income & spending
  - Cluster 5: High income, high spending (premium customers)

---

## 📷 Visual Outputs
- Gender distribution bar chart  
- Pairplot & correlation heatmap  
- Elbow Method plot  
- Silhouette analysis plots  
- PCA 2D and 3D cluster visualization  
- Cluster profile heatmap  

---

## 📝 Conclusion
- K-Means successfully grouped customers into meaningful clusters.
- PCA helped in visualizing clusters in 2D and 3D.
- Silhouette scores validated the cluster quality.
- Cluster profiling provided business insights (e.g., identifying premium vs budget customers).

---
