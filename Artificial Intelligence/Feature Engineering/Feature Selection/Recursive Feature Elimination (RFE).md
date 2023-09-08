Recursive Feature Elimination is a wrapper-based feature selection algorithm that aims to find the most important features by recursively removing the least important ones.

## Definition

RFE works by fitting a model and ranking features based on their importance. The least important features are then eliminated, and the process is repeated until the desired number of features is reached. The algorithm takes two primary parameters:

- **Estimator**: The model used to evaluate feature importance.
- **n_features_to_select**: The number of features to keep.

## Importance

- **Dimensionality Reduction**: Helps in mitigating the Curse of Dimensionality.
- **Model Performance**: Enhances the model's predictive power by focusing on relevant features.
- **Computational Efficiency**: Reduces the computational cost and time.

## How It Works

1. Rank the importance of all features using the chosen machine learning algorithm.
2. Eliminate the least important feature.
3. Build a model using the remaining features.
4. Repeat steps 1-3 until the desired number of features is reached.

## Applications

- **High-Dimensional Data**: Particularly useful when dealing with high-dimensional datasets.
- **Model Optimization**: For improving the performance of machine learning models.

## Connection to Other Topics

- **[[Feature Selection]]**: RFE is a specialized technique within the broader scope of feature selection.
- **[[Feature Importance]]**: RFE uses feature importance metrics to rank and eliminate features.
- **[[Machine Learning]]**: Integral in optimizing machine learning models for better performance.