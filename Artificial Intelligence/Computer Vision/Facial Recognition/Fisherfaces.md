Fisherfaces is an approach used in computer vision, pattern recognition, and machine learning to create a subspace that best separates or discriminates between different classes of data. It is particularly useful in the context of face recognition, where the goal is to identify faces under varying conditions by projecting face images onto a feature space that emphasizes the differences between classes.

![[Pasted image 20231108183005.png]]
## Definition

Fisherfaces are derived from Linear Discriminant Analysis (LDA), which is a generalization of Fisher's linear discriminant, a method used in statistics to find a linear combination of features that characterizes or separates two or more classes of objects or events. The resulting combinations can be used as a linear classifier or, more commonly, for dimensionality reduction before later classification.

## Explanation

The Fisherfaces method involves finding a set of vectors in the image space that best discriminate between faces from different subjects. This is achieved by maximizing the ratio of the between-class scatter to the within-class scatter. The Fisherfaces are the directions along which the projections of the classes are most well separated.

## Examples

- If you have a dataset of face images from 100 different subjects, the Fisherfaces method will try to find the directions in the image space that best separate these 100 classes from each other.
- The first few Fisherfaces might capture the most significant variations between faces, such as the presence of glasses, the shape of the jawline, or the hairstyle.

## Properties

- Fisherfaces are less sensitive to variation in lighting and facial expression than Eigenfaces.
- They are the eigenvectors associated with the largest eigenvalues of the between-class scatter matrix, after normalizing for within-class scatter.
- The number of Fisherfaces is at most C−1, where CC is the number of classes, due to the rank of the between-class scatter matrix.

## Applications

Fisherfaces are widely used in face recognition systems, particularly in scenarios where the number of available training images is limited, and the variations between the classes are subtle. They are also used in other pattern recognition tasks where class separation is crucial.

## Connection to Other Topics

- [[Eigenfaces]]: Fisherfaces can be considered an extension of Eigenfaces, focusing more on class separability.
- [[Principal Component Analysis (PCA)]]: PCA is used in the initial step of Fisherfaces to reduce dimensionality and to handle the singularity of the within-class scatter matrix.
- [[Two-Dimensional Linear Discriminant Analysis]]: An extension of Fisherfaces that operates directly on image matrices rather than one-dimensional vectors.
- [[Artificial Intelligence]]
- [[Facial Recognition]]
- [[Computer Vision]]