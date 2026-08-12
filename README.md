# Iris_Clustering
Unsupervised learning project applying KMeans and Hierarchical clustering to discover natural groupings in the Iris dataset using sklearn


## Dataset used
- **Source:** `sklearn.datasets.load_iris` 
- **Size:** 150 samples × 4 features
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
- **Species column dropped** — unsupervised clustering problem

## Algorithms Implemented
| Algorithm | Approach |
|-----------|----------|
| KMeans  | Centroid-based partitioning with Elbow Method |
| Hierarchical  | Agglomerative merging with Dendrogram visualization |

## Results 

| Algorithms | Silhouette Scores | Cluster Sizes |
|-----------|-----------------|---------------|
| **KMeans** | **0.4599** ✅ | 53, 50, 47 (balanced) |
| Hierarchical | 0.4467 | 71, 49, 30 |

- KMeans produced more balanced clusters and a higher silhouette score
- Hierarchical dendrogram independently confirmed K=3 as the optimal number of clusters
- Both algorithms clearly separated Setosa (small petals) from the other two species

## Libraries Used
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy

## How to Run
1. Open `Iris_Clustering.ipynb` in Google Colab https://colab.research.google.com/drive/1ghZnNigjUARPKJ0WZXc-M6g8pU5zrYg9?usp=sharing


```
