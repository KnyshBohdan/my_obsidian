One-Hot Encoding is a preprocessing technique used to convert categorical data into a form that can be provided to machine learning algorithms.

## Definition

One-Hot Encoding is a method to quantify categorical data by converting each category into a new categorical column and assigning a binary value of 1 or 0. Each integer is mapped to a binary vector.

One-Hot Encoding:Categorical Data→Binary Vector

## How it Works

For example, if you have a feature like "Gender" with categories "Male" and "Female", One-Hot Encoding will create two new features, one for each category, and assign a value of 1 or 0 depending on the presence of that category.

Before: "Male", "Female"

After: "Male": [1, 0], "Female": [0, 1]

## Examples

1. **Fruits**: Apple, Mango, Orange → [1, 0, 0], [0, 1, 0], [0, 0, 1]
2. **Gender**: Male, Female → [1, 0], [0, 1]

## Advantages and Limitations

- **Advantages**: Eliminates the ordinal relationship between variables, making it suitable for nominal data.
- **Limitations**: Can lead to increased dimensionality, which may cause the model to be slow to train and prone to overfitting.

## Applications

- **Natural Language Processing**: For encoding words or phrases.
- **Recommender Systems**: For encoding different categories of items.

## Connection to Other Topics

- **[[Feature Encoding]]**: One-Hot Encoding is a type of feature encoding.
- **[[Data Preprocessing]]**: It is a part of the broader data preprocessing pipeline.
- **[[Machine Learning]]**: A preprocessing step in machine learning workflows