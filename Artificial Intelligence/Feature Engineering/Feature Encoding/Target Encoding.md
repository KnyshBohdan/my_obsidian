Target Encoding is a method for converting categorical variables into numerical format by using the mean of the target variable for each category.

## Definition

Target Encoding replaces each category in a categorical feature with the average value of the target variable for that category. In mathematical terms, for a binary classifier, it calculates the probability p(t=1∣x=ci), where tt denotes the target, x is the input, and cici​ is the i-th category.

Target Encoding:Category→Mean(Target Variable)

## How it Works

For example, if you have a feature like "City" with categories "New York" and "San Francisco", and the target variable is "Salary", then each category is replaced by the average salary of people living in that city.

## Advantages and Limitations

- **Advantages**: Efficiently handles high cardinality categorical variables, avoids the "Curse of Dimensionality."
- **Limitations**: Risk of overfitting and target leakage.

## Techniques to Avoid Overfitting

1. **Leave-One-Out Encoding**: Uses the mean target value of all data points in the category except the current row.
2. **Smoothing**: Combines the category mean with the global mean.
3. **Adding Noise**: Adds Gaussian noise to reduce overfitting.

## Applications

- **Regression Models**: Where the target variable is continuous.
- **Classification Models**: Where the target variable is categorical.

## Connection to Other Topics

- **[[Feature Encoding]]**: Target Encoding is a type of feature encoding.
- **[[Data Preprocessing]]**: It is a part of the broader data preprocessing pipeline.
- **[[Machine Learning]]**: A preprocessing step in machine learning workflows.