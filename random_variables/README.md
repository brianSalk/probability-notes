# Random Variable
Random variables are apparently way more nuanced than I originally thought.  
I used to just think a random variable was a variable that can take on a random value from a given distribution, but I guess it is a function that maps a value from the sample space to the real number line.  
This idea of Random Variables as functions mapping the sample space to a real number was initially confusing to me, but I think the following example makes things a bit clearer:  
### Coin flipping where sample space is coin faces mapped to number of heads
|Sample Space|Real Number|
|------------|-----------|
|HH          |2          |
|HT          |1          |
|TH          |1          |
|TT          |0          |

So if we call our random variable $X$, we have the following mappings according to the above table:  
```math
X(HH) = 2
```
```math
X(HT) = 1
```
```math
X(TH) = 1
```
```math
X(TT) = 0
```
Which means that you can 'randomly' pass $HH, HT, TH,$ and $TT$ to $X$ with equal probability. 
Most of the time, we just care that $X$ could be any of the above, not specifically which one it is.  
**Support**: The support is all the possible values of $X$ that yield non-zero probability.  Support is something you can plug into $x$:
```math
P(X = x) \gt 0
```
