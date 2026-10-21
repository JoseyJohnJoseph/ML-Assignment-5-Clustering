# ML Assignment 5 – Clustering

## Overview
This project applies unsupervised machine learning techniques to the Iris dataset using KMeans and Hierarchical Clustering.

## Dataset
The Iris dataset is loaded from `sklearn.datasets`. It contains 150 samples with four numerical features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Species labels are excluded from clustering.

## Algorithms Implemented

### 1. KMeans Clustering
KMeans partitions the dataset into three clusters by assigning each data point to its nearest centroid.

### 2. Hierarchical Clustering
Agglomerative Hierarchical Clustering builds clusters by repeatedly merging similar data points or groups. A dendrogram is used to visualize the hierarchical structure.

## Visualization
Principal Component Analysis (PCA) reduces the four numerical features to two dimensions for plotting the clustering results.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- SciPy
- Google Colab
- Jupyter Notebook

## How to Run
1. Open `ML_Assignment_5_Clustering.ipynb` in Google Colab or Jupyter Notebook.
2. Run the cells sequentially.
3. Review the clustering visualizations and dendrogram.

## Conclusion
The assignment demonstrates how KMeans and Hierarchical Clustering identify groups in numerical data without using species labels.

## Author
Josey John Joseph
