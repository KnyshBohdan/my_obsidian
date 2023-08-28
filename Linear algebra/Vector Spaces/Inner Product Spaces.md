An inner product space is a significant concept in linear algebra, particularly in the study of vector spaces. It generalizes the dot product and is used to define [[Hilbert space]]s, allowing for formal definitions of geometric notions such as lengths, angles, and orthogonality of vectors.

### Definition

An inner product space is a vector space V over a field (either the real numbers R or the complex numbers C) together with an operation called an inner product. The inner product of two vectors in the space is a scalar, often denoted with angle brackets as ⟨a,b⟩. An inner product must satisfy the following three properties for all vectors x,y,z∈V and all scalars a,b∈Fa,b∈F:

1. **Conjugate Symmetry**: $⟨x,y⟩=\overline{⟨y,x⟩}$
2. **Linearity in the First Argument**: ⟨ax+by,z⟩=a⟨x,z⟩+b⟨y,z⟩
3. **Positive-Definiteness**: If x is not zero, then ⟨x,x⟩>0

### Examples

- **Real Numbers**: The real numbers are an inner product space with arithmetic multiplication as its inner product.
- **Complex Numbers**: The complex numbers become an inner product space with the inner product $⟨x,y⟩:=x\overline{y}$
- **Euclidean Vector Space**: The real nn-space $R^n$ with the dot product is an inner product space.

### Basic Properties

- **Norm Induction**: An inner product naturally induces an associated norm, so every inner product space is a normed vector space.
- **Symmetry**: Over the real numbers, conjugate-symmetry reduces to symmetry, and sesquilinearity reduces to bilinearity.

### Connections to Other Topics

- **[[Vector Spaces]]**: Inner product spaces are a specific type of vector space with an additional structure that allows for geometric interpretations.
- **[[Linear Algebra]]**: Inner product spaces are foundational in linear algebra, leading to the study of Hilbert spaces in functional analysis.
- **[[Scalars]]**: The inner product of two vectors results in a scalar, connecting to the concept of scalars in linear algebra.