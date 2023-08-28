Imagine you have a set of vectors, and you want to know what you can "reach" by combining them through addition and scalar multiplication. The span of a set of vectors is the collection of all possible vectors you can create using these operations. It's a way to describe how a particular set of vectors fills a space.

### Definition

Given a vector space V over a field K, the span of a set of vectors (not necessarily finite) is defined as the intersection of all subspaces containing those vectors. It's referred to as the subspace spanned by those vectors. Mathematically, the span of a set S is given by:
$$span(S) = \{ \sum_{i = 1}^{k} \lambda_i v_i | k \in N, v_i \in S, \lambda_i \in K\}$$

### Examples

1. **Three-Dimensional Space**: The real space R3 has (−1,0,0),(0,1,0),(0,0,1) as a spanning set. This particular spanning set is also a basis.
2. **Two-Dimensional Space**: The set (1,0,0),(0,1,0),(1,1,0) is not a spanning set of R3, since its span is the space of all vectors in R3 whose last component is zero.

### Theorems

- **Equivalence of Definitions**: The set of all linear combinations of a subset is the smallest linear subspace containing that subset.
- **Size of Spanning Set**: Every spanning set of a vector space must contain at least as many elements as any linearly independent set of vectors from that space.
- **Spanning Set Can Be Reduced to a Basis**: Any set of vectors that spans a finite-dimensional vector space can be reduced to a basis by discarding vectors if necessary.

### Connections to Other Topics

- **[[Vector Spaces]]**: The span is a subspace of a vector space, and it helps in understanding the structure of that space.
- **[[Subspaces]]**: The span itself is a subspace, and understanding spans is crucial to grasp the concept of subspaces.
- **[[Linear Algebra]]**: Span is a fundamental concept in linear algebra, connecting to other key ideas like basis, linear independence, and dimension.

### Conclusion

The concept of span in linear algebra is a powerful tool for understanding how vectors can be combined to fill a space. It's a bridge between individual vectors and the larger structure of vector spaces,