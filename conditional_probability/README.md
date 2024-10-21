# Conditional Probability

```math
P(A|B) = \dfrac{P(A \cap B)}{P(B)}
```
**First step analysis**: A strategy for finding recursive solutions to multi-step problems.  
**Prior Probability**: The probability of an event before we update our probability with evidence.  
**Posterior Probability**: The probability of an event after we update our belief with evidence.  
**Intersection**: It is common to use both , and $\cap$ to represent intersection.  
```math
P(A,B) = P(A \cap B)
```
**Intersection of n events**: 
```math
P(A,B,C,D) = P(A)\; P(B|A) \; P(C|A,B) \; P(D|A,B,C)
```
**Independance**: Two events are independant when the following equation holds:  
```math
P(A\cap B) = P(A)P(B)
```
for three events, we need all four of these to hold:
```math
P(A \cap B) = P(A)P(B)
```
```math
P(A \cap C) = P(A)P(C)
```
```math
P(B \cap C) = P(B)P(C)
```
```math
P(A \cup B \cup C) = P(A)P(B)P(C)
```
If only the first three are true, we call these events pairwise independant.  

**Conditional Independence**: Events can be independent of one another under certain conditions, but not others.  
Ex. Imagine a that some classes are good and some are bad.  In good classes, you get a good grade by learning the material,  
in a bad class, grades are assigned randomly.  Let $G$ be the event that a class is good, $A$ be the event a student gets a good grade,  
and $W$ be the event that a student works hard.  Note the following:  
```math
P(A|G,W|G) \ne P(A|G)P(W|G)
```
but 
```math
P(A|G^c,W|G^c) = P(A|G^c)P(W|G^c)
```
