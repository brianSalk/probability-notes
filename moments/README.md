# Moments
The $n^{th}$ moment of a random variable $X$ is
```math
E(X^n)
```
Moments provide us with information about a distribution.  
The first moment is the mean and the second moment helps us find the variance
```math
V(X) = \text{second moment} - \text{first moment}^2 = E(X^2) - E(X)^2
```
The third and fourth moment tell us about the *asymmetry* or a distributiona and about the *extreme* values.
## Central Tendency
The mean is an example of central tendency because it tells us something about the center of a distribution.  Other common measures of central tendency are median and mode
```math
Median(X) = P(X \le c) = \dfrac{1}{2}
```
AND
```math
Median(X) = P(X \gt c) = \dfrac{1}{2}
```
This is defined as such because of discrete distributions where there may not be a point where $P(X \lt c) = \dfrac{1}{2}$.  

The mode is the value that maximizes that PMF or PDF
```math
P(X = c) \gt P(X = x)
```
for all $x$ values
