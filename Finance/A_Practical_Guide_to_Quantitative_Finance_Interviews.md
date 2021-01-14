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