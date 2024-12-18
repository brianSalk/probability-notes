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
\int_{- \infty}^{\infty} f(x) = 1 \\ dx
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

## Uniform distribution
There is also a continuous version of the Uniform distribution. 
The expected value of a continuous Uniform distribution is
```math
E(X) = \int_b^a xdx = \dfrac{1}{2}
```
the varaiance is
```math
VAR(X) = E(X)^2 - E(X^2) = \dfrac{1}{4} - \dfrac{1}{3} = \dfrac{1}{12}
```

### location-scale transformation of Uniform distribution
Let $X$ be a r.v of a uniform distribution
```math
X = Unif(a,b)
```
and let $Y$ be the transformed random variable
```math
Y = \sigma + X \mu
```
Where $\sigma$ changes the location and $\mu$ changes the scale.  
In other words:  
$\sigma$: Moves the original distribution left or right  
$\mu$: stretches or shrinks the distribution  
If you transform a Uniform distribution, you always get another Uniform distribution.  
### Standard Uniform Distribution
the Uniform distribution
```math
Unif(0,1)
```
is known as the standard uniform distribution.  Because it is always a value between $0$ and $1$, the probaiblity of a r.v. being within a certain range is equivalent to the range.  We can then use transformations to get new r.v.s.  
We do ***not*** apply the tranformation to the distribution, but instead to the r.v.

## Fundamental Theorem of Simulation

Given a random variable from the distribution $Unif(0,1)$, we can construct a random variable from any other continuous distribution.  The inverse also works.  
### Inverse CDF.
The inverse CDF is also known as the quartile function.  The inverse CDF is a function where you plug in the desired probability and you get the x value associated with that probability.


