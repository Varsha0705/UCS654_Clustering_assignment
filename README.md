# UCS654_Clustering_assignment
# Clustering Analysis on Iris Dataset

A comparative study of clustering algorithms applied to the famous Iris dataset with various preprocessing techniques.

## Dataset

- **Name**: Iris Dataset
- **Source**: UCI Machine Learning Repository
- **Features**: 
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Classes**: Iris-setosa, Iris-versicolor, Iris-virginica

## Clustering Methods

This analysis compares three clustering techniques:
- K-Means Clustering
- Hierarchical (Agglomerative) Clustering
- Mean Shift Clustering

## Preprocessing Approaches

Each clustering method was tested with four preprocessing variations:
- Raw Data (No preprocessing)
- Normalization (StandardScaler)
- Principal Component Analysis (PCA)
- Combined Normalization + PCA

## Evaluation Metrics

Performance of each method was evaluated using:
- **Silhouette Score**: Measures how similar objects are to their cluster compared to other clusters
- **Calinski-Harabasz Index**: Higher values indicate better-defined clusters
- **Davies-Bouldin Score**: Lower values indicate better clustering

## Key Findings

- K-Means with Normalization and PCA achieved the best performance on Silhouette and Calinski-Harabasz metrics
- Mean Shift performed well with Normalization but showed reduced effectiveness with PCA
- Hierarchical Clustering demonstrated consistent but slightly lower performance compared to K-Means
- Data preprocessing substantially improved clustering quality across all methods

## Repository Contents

- `iris_clustering_analysis.ipynb`: Complete analysis notebook (Google Colab)
- `README.md`: Project documentation

## Usage Instructions

1. Open the notebook in Google Colab
2. Execute all cells to reproduce the analysis
3. Examine visualization outputs and results table
4. Experiment with different parameter settings as desired

## Conclusion

This study demonstrates the significant impact of preprocessing techniques on clustering performance and confirms K-Means as the most effective algorithm for this particular dataset when properly preprocessed.
