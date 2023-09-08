Z-score Scaling is a technique that transforms features by scaling them to have a mean of 0 and a standard deviation of 1.

## Definition

The Z-score of a data point xx is calculated as:
$$x' = \frac{x - \mu}{\sigma}$$

where μ is the mean and σ is the standard deviation of the feature.

## Importance

- **Distribution**: Z-score scaling ensures that the feature distributions have a mean of 0 and a standard deviation of 1.
- **Outliers**: It's useful when there are a few outliers, but not so extreme that you need clipping.

## Advantages and Limitations

- **Advantages**: Effective for algorithms that require features to be normalized, often for different reasons such as to ease convergence.
- **Limitations**: May not be suitable for data with extreme outliers.

## Applications

- **Comparative Analysis**: Useful for comparing test results between tests of different scales, like SAT vs ACT.
- **Machine Learning Algorithms**: Such as K-NN and logistic regression.

## Connection to Other Topics

- **[[Feature Scaling]]**: Z-score Scaling is a specific type of feature scaling.
- **[[Data Preprocessing]]**: It is a crucial step in the data preprocessing pipeline.
- **[[Principal Component Analysis (PCA)]]**: The effectiveness of Principal Component Analysis can be impacted by Z-score scaling.