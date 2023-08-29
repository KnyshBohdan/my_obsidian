Clustering is an unsupervised learning technique used to group similar data points together based on their features. Unlike classification, clustering does not rely on predefined labels, making it useful for discovering hidden patterns in data.

## Definition

Clustering involves partitioning a data set into subsets (clusters), so that data points in the same cluster are more similar to each other than to those in other clusters. The algorithm aims to find natural groupings among the data points.

## Types of Clustering

1. **K-Means Clustering**: Divides the data into 'K' number of clusters based on feature similarity.
2. **Hierarchical Clustering**: Builds a tree of clusters by successively merging or splitting groups.
3. **Density-Based Clustering (DBSCAN)**: Forms clusters based on the density of data points.

### Measures of Similarity

- **Euclidean Distance**: Commonly used for points in a plane.
- **Cosine Similarity**: Often used in text analysis.
- **Jaccard Index**: Used for comparing the similarity of sets.

## Applications

- **Market Segmentation**: Grouping customers based on purchasing behavior.
- **Social Network Analysis**: Identifying communities within social networks.
- **Fraud Detection**: Identifying unusual patterns that do not conform to expected behavior.
- **Medical Imaging**: For segmenting different parts like tissues, bones in MRI scans.

## Challenges

- **Choosing the Right Number of Clusters**: Often not known a priori and must be computed from the data.
- **High Dimensionality**: Clustering in high-dimensional spaces can be computationally intensive.

## Connection to Other Topics

- **[[Unsupervised Learning]]**: Clustering is a primary technique within unsupervised learning.
- **[[Feature Engineering]]**: The process of selecting and transforming variables for clustering.
- [[Machine Learning]]
- [[Artificial Intelligence]]