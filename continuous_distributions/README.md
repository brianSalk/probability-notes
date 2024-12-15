# Continuous Distributions
The probability density function (PDF) is analygous to the PMF for descrete varables.  
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
A valid PDF must integrate to 1.  
```math
\int_{- \infty}^{\infty} f(x) = 1
```
The height of a PDF is the probability that the actual value will be very close to that value.  


## Logistic Distribution
The logistic distribution has the following CDF
```math
F(x) = \dfrac{e^x}{1-e^x} \\ \\ \text{where } x \in R
```
we can differentiate the CDF to get the PDF
```math
F(x)` = f(x) = \dfrac{e^x}{(1-e^x)^2}
```
I am going to have to re-learn integral calculus in order to understand any of this:
### Brush up on basic integrals and derivatives.  
### Learn how to substitute in the bounds like the do on page 198 (rewrite this after you find out what it is called)
### Make sure you understand PMF and CDF really well, right now it is a bit shaky.

## Rayleigh Distribution
... skipping this for now...



