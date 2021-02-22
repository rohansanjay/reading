# Algorithm Design by Jon Kleinberg & Eva Tardos

### 1.1: Stable Matching

- Perfect matching: each member of M and each member of W appears in exactly one pair in S'
  - Neither single hood nor polygamy
- Instability: (m, w') not in S but each of m and w' prefers the other to their partner in S
- Stable matching; *perfect* and *no instability* with respect to S
  - There can be more than one stable matching depending on which party chooses first
- G-S Algorithm 
  - The matches of each women only get better because they will leave for higher preference
  - The matches of each man only get worse because they start with their top
  - O(n^2) because n * n total possible combinations
  - Every man/woman must be matches -> perfect matching
    - Proof by contradiction
  - The matching is stable
    - Proof by contradiction
  - Woman are unhappy if men propose, men are unhappy if women propose
    - Men will start at their top choice and go down -> could end up ideas regardless of women matchings
  - All executions yield the same matchings
    - Prove that each man ends up with best possible partner by contradiction
    - Each woman is paired with worst valid partner

### 2.2: Asymptotic Order of Growth

- Upper bounds - big O
  - T(n) is the worst case run time of an algo with size input n
    - T(n) is big O f(n) if fo sufficiently large n, T(n) is bounded by a constant multiple of f(n)
    - Requires a constant c to exist that works for all n -> c cannot depend on n
  - A function can have many upper bounds
- Lower bounds - Omega
  - T(n) is at least a constant multiple of some specific function f(n)
- Tight bounds - Theta
  - If a running time is both big O f(n) and Omega f(n), T(n) grows exactly like f(n) to within a constant factor
  - Or if f(n) and g(n) converges to a positive constant as n goes to infinity, then f(n) = theta g(n)



