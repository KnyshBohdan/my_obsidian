In mathematics, and more specifically in linear algebra, a linear transformation (or linear map) is a mapping between two vector spaces that preserves the operations of vector addition and scalar multiplication. It plays a central role in various mathematical disciplines and has numerous applications in science and engineering.

### Definition

A function f:V→Wf:V→W between two vector spaces VV and WW over the same field KK is said to be a linear transformation if the following two conditions are satisfied:

1. **Additivity**: f(u+v)=f(u)+f(v)f(u+v)=f(u)+f(v)
2. **Homogeneity of Degree 1**: f(cu)=cf(u)f(cu)=cf(u)

Here, uu and vv are vectors in VV, and cc is a scalar in KK.

### Properties

- A linear map always maps the origin of VV to the origin of WW.
- Linear maps can often be represented as matrices.
- If a linear map is a bijection, then it is called a linear isomorphism.
- In the case where V=WV=W, a linear map is called a linear endomorphism.

### Examples

1. **Scaling**: The function f:R→R:x↦cxf:R→R:x↦cx, where cc is a scalar, is a linear map.
2. **Zero Map**: The map x↦0x↦0 between two vector spaces (over the same field) is linear.
3. **Matrix Representation**: If AA is a real m×nm×n matrix, then f(x)=Axf(x)=Ax describes a linear map Rn→RmRn→Rm.

### Applications

- **Geometry**: Linear transformations are used to describe geometric transformations such as rotations and reflections.
- **Differential Equations**: They are used in solving linear differential equations.
- **Computer Graphics**: Linear transformations are used in scaling, rotating, and translating objects in computer graphics.
- **Functional Analysis**: They are fundamental in the study of functional spaces.

### Connections

- [[Matrices]]: Linear transformations can be represented using matrices.
- [[Eigenvalues and Eigenvectors]]: Eigenvalues and eigenvectors are associated with linear transformations.
- [[Linear algebra]]
