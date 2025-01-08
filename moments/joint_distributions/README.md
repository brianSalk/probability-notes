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
