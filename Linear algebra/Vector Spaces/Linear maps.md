In mathematics, and more specifically in linear algebra, a linear map (also known as a linear transformation or vector space homomorphism) is a mapping between two vector spaces that preserves the operations of vector addition and scalar multiplication. Here's a detailed explanation:

### Definition

A linear map f:V→W between two vector spaces V and W over the same field K is said to be linear if for any two vectors u,v∈V and any scalar c∈K, the following two conditions are satisfied:

1. **Additivity**: f(u+v)=f(u)+f(v)
2. **Homogeneity of Degree 1**: f(cu)=cf(u)

Thus, a linear map is operation preserving, meaning that it doesn't matter whether the linear map is applied before or after the operations of addition and scalar multiplication.

### Examples

- **Scaling Function**: A function f: R→R: x↦cx, where the graph is a line through the origin.
- **Zero Map**: The zero map between two vector spaces (over the same field) is linear.
- **Matrix Representation**: If A is a real m×n matrix, then f(x)=Ax describes a linear map Rn→Rm.

### Properties

- **Preservation of Origin**: A linear map always maps the origin of one space to the origin of the other.
- **Mapping of Subspaces**: It maps linear subspaces in one space onto linear subspaces in the other (possibly of a lower dimension).
- **Matrix Representation**: Linear maps can often be represented as matrices.

### Connections to Other Topics

- **[[Vector Spaces]]**: Linear maps operate between vector spaces and preserve their structure.
- **[[Scalars]]**: Scalars are involved in the definition of linear maps through scalar multiplication.
- **[[Linear Algebra]]**: Linear maps are fundamental to the study of linear algebra, connecting various concepts and structures.