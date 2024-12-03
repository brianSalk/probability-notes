# Expectation
## Expected Value
The expected value is the mean value you would get if you ran the experiment over and over.  
If two distributions are identical, they have the same expected value but *vis-versa* is not true, two very different distributions can have the same expected value.  
the expected value of a r.v. of a distribution is expressed as $E(X)$ or $E[X]$.  
Do not confuse $E(x)$ with the r.v. $X$.  These are two different things.  A random variable is a function and the expected value is a value.  
A radndm variable tells you something about the variation.  
## Notation
the notation $E(X)$ is often abreviated to $EX$, meaning that $EX^2$ means the mean of the function $X^2$, not $(EX)^2$
## Linearity
If we have $2$ random variables, $X$ and $Y$, the following holds
```math
E(X+Y) = E(X) + E(Y)
```
and if you have a constant $c$, 
```math
cE(X) = E(cX)
```
We can find the average in a *grouped* or *ungrouped* way.  
## Expected values of distributions
The expected value of a binomial distribution is:
```math
np
```

For hypergenomic:
```math
\dfrac{sn}{N}
```
where $n$ is sample size, $N$ is population size and $s$ is number of successes in the population.

For Negative Binomial...

## Indicator variables
An indicator random variable $I_A = 1$ if event $A$ occures, else $I_A = 0$  
remember the follwoing identities:
```math
I_A^k = I_A \text{ when } k \text{ is positive}
```
```math
I_{A^c} = 1 - I_A
```
```math
I_{A \cup B} = I_A + I_B - I_AI_B
```
```math
I_{A \cap B} = I_AI_B
```
## St. Peterburgs Paradox
Look at the following function:
```math
f(i) = \sum_{i = 1}^{\infty} i \frac{1}{i^2}
```
The expected value of this function is $\infty$, but if there were a game with such returns, no body would pay more than a few dollars to play such a game.  Think about playing roulette and doubling your bet each time you lose.

## LOTUS (Law Of The Unconcious Statistition)
dispite all that we learned about linear functions, if a given function $g$ is not linear, then 
```math
g(E(X)) \ne E(g(X))
```
So how do we find $E(g(X))$?  We can use
```math
\sum_{x} g(x)P(X = x)
```
