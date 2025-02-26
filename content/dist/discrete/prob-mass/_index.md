---
title: Probability mass functions
type: docs
toc: false
weight: 2
---

The probability that a discrete random variable $X$ takes on a particular value $x$, that is, $P(X = x)$, is frequently denoted $f(x)$.
The function is typically called the probability mass function, although some authors also refer to it as the probability function, the frequency function, or probability density function.
We will use the common terminology, the probability mass function, and its common abbreviation the pmf.

!!! quote annotate "Probability mass function"

    The probability mass function, $P(X = x) = f(x)$, of a discrete random variable $X$ is a function that satisfies the following properties:

    -   $P(X = x) = f(x) > 0$ if $x \in$ the support $S$,(1)
    -   $\sum_{x \in S} f(x) = 1$.(2)
    -   $P(X \in A) = \sum_{x \in A} f(x)$.(3)

1.  For every element $x$ in the support $S$, all of the probabilities must be positive.
    Note that if $x$ does not belong in the support $S$, then $f(x) = 0$.
2.  If you add up the probabilities for all of the possible values $x$ in the support $S$, then the sum must equal 1.
3.  To determine the probability associated with the event $A$, you just sum up the probabilities of the $x$ values in $A$.

Since $f(x)$ is a function, it can be presented:

-   in tabular form
-   in graphical form
-   as a formula
