# 📊 Clustering and Evaluation on Breast Cancer Dataset

## ✅ Algorithms Compared
- **K-Means**
- **Hierarchical**
- **Mean Shift**

## ⚙️ Preprocessing Techniques
- None
- Normalize
- PCA
- Transform

## 📈 Evaluation Metrics

| Metric                  | Interpretation       |
|-------------------------|----------------------|
| **Silhouette Score**    | Higher is better     |
| **Calinski-Harabasz**   | Higher is better     |
| **Davies-Bouldin**      | Lower is better      |

## 🔍 Key Findings

### ⭐ Best Performer: `K-Means + PCA`
- Silhouette Score: ~0.65
- Calinski-Harabasz: ~1641
- Davies-Bouldin: ~0.61

### 📌 Mean Shift
- Stable but insensitive to cluster count  
- Over-clustering tendency  
- Performs better with PCA

### 📌 Hierarchical
- Consistently poor across metrics  
- High overlap, high Davies-Bouldin

## 📊 PCA Visualizations
- **K-Means**: Clear, distinct clusters
- **Hierarchical**: Overlapping, unclear clusters
- **Mean Shift**: Over-clustering, scattered points

## ✅ Recommendation
> Use **K-Means with PCA** for optimal clustering results.
