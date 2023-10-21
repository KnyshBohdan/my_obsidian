The Extreme Value Theorem (EVT) is a fundamental theorem in calculus that guarantees the existence of global extrema for continuous functions over closed intervals. It is a cornerstone in optimization theory and has applications in various fields like economics, engineering, and data science.

#### Definition

Let f:[a,b]→Rf:[a,b]→R be a continuous function on a closed interval [a,b][a,b]. Then f(x)f(x) attains both a global maximum and a global minimum, i.e., there exist points c,d∈[a,b]c,d∈[a,b] such that:

f(c)≥f(x)≥f(d)∀x∈[a,b]f(c)≥f(x)≥f(d)∀x∈[a,b]

#### Explanation

The theorem essentially states that if you have a continuous function defined on a closed interval, then the function will have both a highest and lowest value within that interval. Imagine hiking on a continuous trail from point A to point B; you will encounter both the highest and lowest points on that trail.

#### Examples

1. f(x)=x2f(x)=x2 on [−1,1][−1,1]  
    The function attains a global minimum at x=0x=0 and a global maximum at x=−1x=−1 or x=1x=1.
    
2. f(x)=sin⁡(x)f(x)=sin(x) on [0,π][0,π]  
    The function attains a global minimum at x=πx=π and a global maximum at x=0x=0.
    

#### Properties

- Applicability: The function must be continuous on the closed interval.
- Uniqueness: The extrema are not necessarily unique.

#### Applications

- In economics, the theorem is used to find optimal pricing strategies.
- In engineering, it is used to identify stress points in materials.
- In data science, it is used in optimization algorithms like gradient descent.

#### Connection to Other Topics

- [[Optimization Theory]]: EVT is the foundational theorem for many optimization algorithms.
- [[Calculus of Variations]]: EVT can be generalized to functions of functions, leading to optimization in function spaces.
- [[Machine Learning]]: In machine learning algorithms like Support Vector Machines or Neural Networks, optimization of a loss function is crucial, and EVT ensures the existence of such optima under certain conditions.
- [[Operations Research]]: EVT is often used in linear programming and other optimization methods to guarantee the existence of optimal solutions.
- [[Statistical Theory]]: EVT has extensions into statistics, particularly in the theory of extreme values, which is crucial for risk assessment in various fields like finance and environmental science.
- [[Calculus]]