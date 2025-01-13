# Joint Distributions
## Joint
A joint distribution is a distribution that discribes two or more random variables.  
```math
F_{X,Y}(x,y) = P(X \le x, Y \le y)
```
```math
p_{X,Y}(x,y) = P(X = x, Y = y)
```
## Marginal
This measures the probabilty of one variable, ignoring the other(s)
```math
P(X = x) = \sum_{y} P(X = x, Y = y)
```
## conditional
This is the probability of one variable given that another variable has a certain value.
```math
P(X = x \vert Y = y) = \dfrac{P(X = x, Y = y)}{P(Y = y)}
```
```math
P(X = x \vert Y = y) = \dfrac{P(Y = y \vert X = x)P(X = x)}{P(Y = y)}
```
## Covariance
Covariance is a measure of joint variability of two random variables.  The sign of the covariance tells us whether the corrolation is positive or negative, but it says nothing about the magnitude.
## Correlation
```math
Corr(X,Y) = \dfrac{Cov(X,Y}{\sqrt{Var(X)Var(Y)}}
```
In words, we divide the covriance by the product of the standard deviations of both distributions.  
Scaling and shifting have no impact on the correlation.  

## Finite Population Correction
The finite population correction is used to make our predictions more accurate when our population is relatively small.  
```math
FPC = \dfrac{N-n}{N-1}
```
The variance of the hypergeometric distribution is $FPC \cdot np(1-p)$
