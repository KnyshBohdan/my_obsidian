Linear Discriminant Analysis is a method used to find a linear combination of features that characterizes or separates two or more classes of objects or events. It is a generalization of Fisher's linear discriminant.

## Definition

LDA aims to model the difference between the classes of data by finding a linear combination of features that maximizes the between-class variance and minimizes the within-class variance.

LDA:High-Dimensional Data→Low-Dimensional Data

## Key Concepts

- **Discriminant Function**: A function that takes a data point and outputs a score for each class.
- **Class Labels**: The categories to be predicted.
- **Feature Vector**: The set of variables used for making the prediction.

## How it Works

LDA works by assuming that the conditional probability density functions for each class are normally distributed. It then uses Bayes' theorem to estimate the probabilities and make predictions.

## Advantages and Limitations

- **Advantages**: Effective for dimensionality reduction, less prone to overfitting, and computationally efficient.
- **Limitations**: Assumes that the independent variables are normally distributed and that the classes have identical covariance matrices.

## Applications

- **Classification Problems**: Such as bankruptcy prediction and facial recognition.
- **Dimensionality Reduction**: Often used before applying another machine learning algorithm.

## Connection to Other Topics

- **[[Principal Component Analysis (PCA)]]**: Unlike PCA, LDA takes into account class labels.
- **[[Logistic Regression]]**: LDA is similar but assumes normally distributed features.
- **[[Machine Learning]]**: Used for both classification and dimensionality reduction.