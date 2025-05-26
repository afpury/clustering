#  Clustering Algorithms Practice

This repository contains hands-on implementations and visualizations of several clustering algorithms as part of an academic assignment. All implementations are done using Python in Jupyter Notebook format.

---

## Project Structure

```
.
├── k-means.ipynb                  # K-Means Clustering
├── em_clustering_mnist.ipynb      # EM Clustering using binary MNIST
├── dendogram.ipynb                # Hierarchical Clustering with dendrogram
├── fuzzy_kmeans_clustering.ipynb  # Fuzzy K-Means Clustering
└── README.md
```

---

## Algorithms Covered

| Method             | Description |
|--------------------|-------------|
| **K-Means**        | Partitions data into k hard clusters using Euclidean distance. |
| **Fuzzy K-Means**  | Similar to K-Means, but assigns fuzzy membership values to each cluster. |
| **EM Clustering**  | Uses probabilistic approach (Bernoulli likelihood) to group binary image data. |
| **Hierarchical Clustering** | Bottom-up clustering visualized via dendrogram. |

---

## How to Run

1. Open each `.ipynb` file with Jupyter Notebook or JupyterLab.
2. Run the notebook step-by-step. Each notebook includes:
   - Data generation or loading
   - Clustering logic
   - Result visualization (scatter plots or dendrograms)

> Note: For EM clustering, the MNIST dataset in `.idx` format is required.

---

## References

https://github.com/ardianumam/Data-Mining-and-Big-Data-Analytics-Book/tree/master
