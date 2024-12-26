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

A given distribution can have multiple medians and multiple modes.  
Mulpiple modes: there are multiple peaks with the same height  
Multiple mdedians: There is a gap in the middle of a symetrical distribution.  A median then lies on any value at that gap.
## Types of moments
As previously stated, the $n^{th}$ moment is $E(X^n)$.  But there are other types of moments such as:  
```math
\text{nth cetral moment} = E((X-\mu)^n)
```
```math
\text{nth standard moment} = E(\left( \dfrac{X - \mu}{\sigma} \right)^n)
```
