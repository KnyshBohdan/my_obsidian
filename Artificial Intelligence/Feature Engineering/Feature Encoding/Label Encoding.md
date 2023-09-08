Label Encoding is a preprocessing technique used to transform categorical data into a form that can be fed into machine learning algorithms.

## Definition

Label Encoding is the process of converting the categorical data variables into numerical form so that machine learning algorithms can understand them. It assigns a unique integer to each category within a feature.

Label Encoding:Categorical Data→Numerical Data

## How it Works

Suppose you have a categorical feature with values like "Low", "Medium", and "High". Label Encoding will replace these with integers like 0, 1, and 2, respectively.

Before: "Low", "Medium", "High"

After: 0,1,2

## Examples

1. **Height Categories**: Tall, Medium, Short → 0, 1, 2
2. **Income Levels**: Low, Medium, High → 0, 1, 2

## Limitations

- **Priority Issue**: Label Encoding can introduce a new problem, as it assigns a unique number (starting from 0) to each class of data. This may lead to the generation of priority issues during model training.

## Applications

- **Ordinal Data**: Best suited for ordinal data where the categories have a clear sense of order.
- **Tree-Based Algorithms**: Often used with algorithms that can handle ordinal data like Decision Trees and Random Forests.

## Connection to Other Topics

- **[[Feature Encoding]]**: Label Encoding is a type of feature encoding.
- **[[Data Preprocessing]]**: It is a part of the broader data preprocessing pipeline.
- **[[Machine Learning]]**: A preprocessing step in machine learning workflows.