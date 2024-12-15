# Continuous Distributions
the PDF of a continuous distribution is the derivative of the CDF.
```math
P(X = x) = \int_a^a f(x) dx = f(a) - f(a) = 0
```
for all values $x$.  In words, the probability of getting a single value with a continuous function is $0$.  Therefore, we must ask the following:
```math
P(a \lt X \lt b) = f(b) - f(a) = \int_a^b f(x) dx
```
Which is the formal way of asking "given some function $f$, what is the probability that f returns a value between $a$ and $b$".  Notice that it does not matter if we include $a$ and $b$ in our range, because the probability of the function returning *exactly* $a$ or exactly $b$ is $0$.
```math
P(a \lt X  \lt b) = P(a \le X \le b)
```
**In summary, to find a probability of radom variable of a function of a continuous distribution, integrate over the desired range.**
