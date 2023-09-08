PCA is a statistical technique used for reducing the dimensionality of a dataset by transforming it into a new coordinate system where the variation in the data can be described with fewer dimensions than the original data.

## Definition

The objective of PCA is to find a set of orthogonal axes, known as principal components, along which the variance of the data is maximized.

PCA:High-Dimensional Data→Low-Dimensional DataPCA:High-Dimensional Data→Low-Dimensional Data

## Key Steps

1. **Standardization**: Normalize the range of variables so that each contributes equally to the analysis.
2. **Covariance Matrix Computation**: Identify correlations between variables.
3. **Eigenvalue and Eigenvector Calculation**: Identify the principal components.
4. **Feature Vector Creation**: Decide which principal components to keep.
5. **Data Transformation**: Recast the data along the principal component axes.

## Advantages and Limitations

- **Advantages**: Simplifies data, improves algorithm performance, and aids in data visualization.
- **Limitations**: Loss of interpretability, and sensitive to the scaling of variables.

## Applications

- **Data Visualization**: Reducing data to 2 or 3 dimensions for plotting.
- **Machine Learning**: Used as a preprocessing step to improve model performance.
- **Genomics**: Used in population genetics and microbiome studies.

## Connection to Other Topics

- **[[Linear Discriminant Analysis (LDA)]]**: Unlike PCA, LDA uses class labels.
- **[[Feature Engineering]]**: PCA is a type of feature extraction.
- **[[Machine Learning]]**: Commonly used in both supervised and unsupervised learning.
- **[[Clustering]]**: Often used before clustering algorithms to reduce dimensions.
- **[[Regression]]**: Can be used to deal with multicollinearity in regression models.