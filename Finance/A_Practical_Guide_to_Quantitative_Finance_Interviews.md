# A Practical Guide to Quantitative Finance Interviews by Xinfeng Zhou

### Chapter 4 Probability Theory

#### 4.1 Basic Probability Definitions and Set Operations

- Outcome (ω): the outcome of an experiment
- Sample space (Ω): set of all possible outcomes
- P(ω) = Probability of an outcome [ P(ω) ≥ 0, ∀ ω ∈ Ω, ∑P(ω) = 1]
- Events = a set of outcomes and a subset of the sample space
  - P(A) = probability of event A
  - A ∪ B = A union B = set of outcomes in event A or B or both
  - A ∩ B = A intersect B = set of outcomes in A and B
- Mutually exclusive: A ∩ B = ∅ (empty set)
  - For mutually exclusive events E<sub>1</sub>, E<sub>2</sub>, ... , E<sub>n</sub>, P(∪ E<sub>x</sub>) = ∑ P(E<sub>x</sub>)
- Random variable: a function that maps each outcome in the sample space into a set of real numbers

#### 4.2 Combinatorial Analysis

- Basic principle of counting
  
  - There are a total of N<sub>1</sub> * N<sub>2</sub> * ... * N<sub>k</sub> possible outcomes
  
- Permutation = rearrangement of object into distinct sequences (order matters)
  
  - There are N! / (N<sub>1</sub>! * N<sub>2</sub>! * ... * N<sub>k</sub>!) different permutations...
  
- Combination = unordered collection of objects

  - ![equation](https://latex.codecogs.com/gif.latex?%7Bn%20%5Cchoose%20r%7D%20%3D%20%5Cfrac%7Bn%21%7D%7B%28n%20-%20r%29%21r%21%7D)

- Binomial theorem: 

  - ![equation](https://latex.codecogs.com/gif.latex?%28x%20&plus;%20y%29%5En%20%3D%20%5Csum_%7Bk%20%3D%200%7D%5E%7Bn%7D%7Bn%20%5Cchoose%20k%7Dx%5Eky%5E%7Bn-k%7D)
  - This makes sense because for ex, coefficient of x<sup>2</sup>y<sup>2</sup> means you choose 2 x's and 2 y's

- Inclusion-Exclusion Principle: 

  - ![equaiton](https://latex.codecogs.com/gif.latex?P%28E_1%20%5Ccup%20E_2%29%20%3D%20P%28E_1%29%20&plus;%20P%28E_2%29%20-%20P%28E_1E_2%29...)

  

