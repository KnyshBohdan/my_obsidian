Min-Max Scaling is a data normalization technique that scales features by transforming them into a specified range, usually $[0, 1]$

## Definition

Min-Max Scaling is mathematically defined as:
$$x^` = \frac{x - min(x)}{max(x) - min(x)}$$

where x′ is the scaled value, xx is the original value, and min(x) and max(x) are the minimum and maximum values of the feature, respectively.

## Importance

- **Uniformity**: Ensures that all features contribute equally to the model's performance.
- **Distance Metrics**: Particularly useful for algorithms like K-NN and K-means that rely on distance calculations.

## Advantages and Limitations

- **Advantages**: Simple to implement, scales features to a uniform range.
- **Limitations**: Sensitive to outliers, as extreme values can distort the scaling.

## Applications

- **Classification Algorithms**: Such as SVM and Logistic Regression.
- **Clustering Algorithms**: Like K-means.
- **Neural Networks**: To speed up the convergence during training.

## Connection to Other Topics

- **[[Feature Scaling]]**: Min-Max Scaling is a specific type of feature scaling.
- **[[Data Preprocessing]]**: It is a crucial step in the data preprocessing pipeline.
- **[[Machine Learning]]**: Affects the performance of various machine learning algorithms.
