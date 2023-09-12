# Image-Clustering
 Tissue Segmentation using Image Clustering

## Introduction
Educational Data Mining (EDM) leverages data mining techniques for educational research. Clustering, an unsupervised machine learning approach, plays a crucial role in EDM. This case study explores model selection for clustering using PathologyGAN and ResNet50 datasets.

## Methods
We employed K-Means and Hierarchical Clustering on PathologyGAN and ResNet50 datasets, reduced dimensionality using PCA and UMAP, and selected optimal K values.

## Results

**Hierarchical Clustering**
1. PathologyGAN PCA: Optimal K=9
2, PathologyGAN UMAP: Optimal K=9
3. ResNet50 PCA: Optimal K=7
4. ResNet50 UMAP: Optimal K=9

**K-Means Clustering**
1. PathologyGAN PCA: Optimal K=3
2. PathologyGAN UMAP: Optimal K=5
3. ResNet50 PCA: Optimal K=7
4. ResNet50 UMAP: Optimal K=5

UMAP features provided better separation compared to PCA. K-means and Hierarchical Clustering showed comparable results, with selection based on dataset characteristics.

## Discussion
1. UMAP performed better for dimensionality reduction, providing improved cluster separation.
2. Model selection should consider domain knowledge and dataset characteristics.
3. K-Means is suitable when the number of clusters is known; Hierarchical Clustering aids in determining clusters.
4. Evaluation metrics like Silhouette Score and V-Measure help in choosing the optimal K
