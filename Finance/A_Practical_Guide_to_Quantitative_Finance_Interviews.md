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

  - $$
    {n \choose r} = \frac{n!}{(n - r)!r!}
    $$

- Binomial theorem: 
  $$
  (x + y)^n = \sum_{k = 0}^{n}{n \choose k}x^ky^{n-k}
  $$
  - This makes sense because for ex, coefficient of x<sup>2</sup>y<sup>2</sup> means you choose 2 x's and 2 y's

- Inclusion-Exclusion Principle: 
  $$
  P(E_1 \cup E_2) = P(E_1) + P(E_2) - P(E_1E_2)...
  $$
  

#### Conditional Probability and Bayes' Formula

- Conditional probability:
  - P(A | B) = P(AB) / P(B)
- Multiplication rule:
  - P(E<sub>1</sub> E<sub>2</sub> ... E<sub>n</sub>) = P(E<sub>1</sub>) * P(E<sub>2</sub> | E<sub>1</sub>) ...
- Independence
  - P(EF) = P(E) * P(F)
- Bayes formula
  - P(F | E) = [P(E | F) * P(F)] / [P(E | F) P(F) + P(E | F<sup>c</sup>) P(F<sup>c</sup>)]

