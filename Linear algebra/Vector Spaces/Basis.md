In linear algebra, a basis is a set of vectors that defines a coordinate system for a vector space. It is a fundamental concept that provides a way to represent any element of the vector space in a unique manner. Here's an exploration of the concept of a basis:

### Definition

A set B of vectors in a vector space V over a field F (such as the real numbers R or the complex numbers C) is called a basis if it satisfies the following two conditions:

1. **Linear Independence**: For every finite set of vectors {v1,…,vm}, if c1v1+⋯+cmvm=0 for some scalars c1,…,cm in F, then c1=⋯=cm=0.
2. **Spanning Property**: For every vector vv, one can choose scalars a1,…,an​ and vectors v1,…,vn​ such that v=a1v1+⋯+anvn.

The scalars aiai​ are called the coordinates of the vector with respect to the basis, and by the first property, they are uniquely determined.

### Examples

- **Standard Basis in R2**: The vectors e1=(1,0) and e2=(0,1) form a basis called the standard basis in R2.
- **Polynomial Basis**: The collection of all monomials B={1,X,X2,…} forms a basis for the vector space of polynomials in one indeterminate with coefficients in a field.

### Properties

- **Steinitz Exchange Lemma**: This lemma states that given a finite spanning set S and a linearly independent set L of elements of V, one may replace well-chosen elements of S by the elements of L to get a spanning set containing L, having its other elements in S, and having the same number of elements as S.
- **Dimension Theorem**: All bases of a vector space have the same cardinality, called the dimension of the vector space.
- **Change of Basis**: Given two (ordered) bases, it is often useful to express the coordinates of a vector with respect to one basis in terms of the coordinates with respect to the other. This can be done by the change-of-basis formula.

### Connections to Other Topics

- **[[Vector Spaces]]**: A basis is a linearly independent spanning set of a vector space.
- **[[Dimension]]**: The dimension of a vector space is the number of elements in any basis of the vector space.
- **[[Linear Independence]]**: Linear independence is a property that the vectors in a basis must satisfy.
- **[[Span]]**: The span of a set of vectors includes all possible linear combinations of those vectors, and a basis must span the entire vector space.
- [[Linear algebra]]