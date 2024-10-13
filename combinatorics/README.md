# combinatorics

**Permutations of strings with 2 chars**: AABABBABBB has $4$ A's and $6$ B's.  We can use either ${10 \choose 4}$ or ${10 \choose 6}$
**Derivation of multinomial coefficient using binomial coefficient**: counting permutations of AAABBBCCD, 
```math
{9 \choose 3} {6 \choose 3} {3 \choose 2} {1 \choose 1} = { 9 \choose 3,3,2}
```
**Stars and Bars**: We have $n$ indistinguishable balls and $k$ distinct buckets to put them in.  For $n=10$ and $k=4$, one possible arrangement is:
```math
|***|*****|*|*|
```
Since the first and last character must be `|`, we can actually subtract $1$,
```math
***|*****|*|*
```
```math
{10 + 4 - 1 \choose 10}
```
Other examples - we have $k$ ingredients and choose one ingredient $n$ times.  
**Isomorphic Problem**: Two problems that actually lead to the same equation.  Examples are (count binary strings of length $n$ vs. $n^2$).
**Story Proof**: A mathematical proof that is simply explaining an insight about why some statement is true.  
