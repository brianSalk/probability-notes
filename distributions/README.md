# Distributions
## Normal distribution
A continuous distribution that is symmetric and has a bell shape.  This distribution shows up all over nature.  
If you sample ***virtually any*** distribution and take the mean of the samples, the distribution created by those sample means will approximate a normal distribution.  
## Binomial distribution
A discrete distribution that represents the probability of getting $r$ successes out of $n$ trials with probability of success $p$.  
When $p$ is close to $0.5$ and $n$ is arbitrarily large, the binomial distribution approximates the normal distribution.  
```math
pbinom(n,r,p) = {n \choose r} p^r (1-p)^{n-r}
```
## Bernouli distribution
A special case of the binomial distribtution where $n=1$.  
## Poisson distribution
A discrete probability distribution that gives the probability of getting $k$ successes in a period of time, given the $\lambda$, where $\lambda$ is the probabilty that that event happens once in a period of time.  
## Hypergeometri distribution
A discrete probability distribution that represents the probability that two randmly assigned categories will both be assigned to $k$ of the elements.  Another way of looking at this is the hypergeometic distribution is the like the binomial distribution without replacement.  This approximates the binomial distribution when $\lim\limits_{n/N \to \infty} X = 0$ where $X$ is a random variable from the hypergeometric distribution.
```math
phyper(N, n, S, s) = \dfrac{{S \choose s} {N-S \choose n-s}}{{N \choose n}}
```
Where:  
$N = \text{population size}$  
$n = \text{sample size}$  
$S = \text{successes in population}$  
$s = \text{successes in sample}$
## Uniform distribution
Use this when sampling from $N$ unique elements with replacement if each element has the same probability of being selected.

## Geometric distribution
The geometric distribution describes the number of independant trials needed to get 1 success when probability of success is $p$.  
Some books define the geometric distribution as the number of failures before the success.
```math
Geom(X) = P(X = k) = (1-p)^kp
```
## Negative Binomial distribution
This distribution gives the number of failures until $r$ successes where each trial is independant and has probability $p$.  
```math
P(X = n) = {n + r - 1 \choose r- 1 } p^rq^n
```
