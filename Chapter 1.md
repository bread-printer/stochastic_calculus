# 1. Brownian Motion
-----

## 1. What is Brownian Motion?

**Brownian Motion** IS a random motion or random process which the given subjects move in small, independent, contionous increments.
Usually used to explain the movement of stochastic/random objects like pollen in the wind, atomic particles in water, or market prices.

**Brownian Motion** (denoted as _W(t)_ or _B(t)_) has the following charasteristics:
- Increments are continous ( $\lim_{x\to\ a} f(x)$ = f(a) ) where a,x $\in$ ℚ ≥ 0
- Increments of a particle over disjoint time are independent of one another
- Each increment is assumed to be bombarded by a large number of independent collisions, hence with many random collisions, this approaches a normal distribution of increments by the [Central Limit Theorem](https://www.statisticshowto.com/probability-and-statistics/normal-distributions/central-limit-theorem-definition-examples/)

Setting the Browninan motion within a one dimensional enviroment and time is commonly referred to as the Wiener process.

The collection of these random variables indexed by the continous time parameter _t_ is a _random process_ with the following properties:
- The increment is continous; when recording starts: time and position are at _B(t) = 0_
- Increments over non-overlapping time intervals are independent random variables
- The increment over any time length _u_ from _t_ is _(t + u)_ with a mean μ = 0, $σ^2$ = _u_

The term independent increments means that for every choice of nonnegative real numbers:
0 ≤ $s_{1}$ ≤ $t_{1}$ ≤ $s_{2}$ ≤ $t_{2}$ ≤ ... $s_{n}$ ≤ $t_{n}$ ≤ ${inf}$
Thus for the random variables:
$W_{t_{1}}$ - $W_{s_{1}}$, $W_{t_{2}}$ - $W_{s_{2}}$, ... $W_{t_{n}}$ - $W_{s_{n}}$ are jointly independent

Since we have a normal distribution 
