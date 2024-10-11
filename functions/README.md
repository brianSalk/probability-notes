# Functions
## PMF
A probability mass function is a discrete function that tells you the probability of a random variable having a certain value.  
the PMF for a fair 6-sided die is:  
```math
f_X(x) = P(X = x) = \dfrac{1}{6} \text{\quad , if \quad } X \in \{1,2,3,4,5,6\}  
```
Where $X$ is a random variable and $x$ is one of $\\{1,2,3,4,5,6\\}$

## PDF
Same as probability mass function except it is a continuous function so we need to use the limit of a range.  
```math
f_X(x) = \lim_{\Delta \to \infty^{+}} \dfrac{x \lt X \le x + \Delta }{Delta}
```
Where $X$ is a random variable and $x$ is a specific value in the function  
## CDF:
A distribution that shows cumulative probability.  
```math
F_X(x) = P(X \le x)
```
For a fair $6$ sided die, 
```math
F_X(x) = P(X \le x) = \dfrac{x}{6} \text{\quad , if \quad } X \in \{1,2,3,4,5,6\}  
```
