# Comparative Report: PCA vs t-SNE

## Objective
The objective of this project is to compare two popular dimensionality reduction techniques: Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE).

## Dataset
The Iris dataset was used for this comparison. It contains 150 samples, 4 numerical features, and 3 flower species.

## PCA Results
- Reduced the dataset from 4 dimensions to 2 principal components.
- Preserved most of the important variance.
- Fast execution time.
- Easy to interpret.

## t-SNE Results
- Reduced the dataset into a 2-dimensional visualization.
- Produced clearer cluster separation than PCA.
- Slower than PCA because of iterative optimization.
- Better for visualization of complex data.

## Comparison

| Feature | PCA | t-SNE |
|---------|-----|--------|
| Speed | Fast | Slow |
| Linear | Yes | No |
| Visualization | Good | Excellent |
| Preserves Variance | Yes | No |
| Preserves Local Structure | Moderate | Excellent |

## Conclusion
PCA is suitable for fast dimensionality reduction and feature extraction, while t-SNE is better for visualizing clusters and discovering hidden structures in high-dimensional datasets. Both techniques are valuable depending on the project requirements.
