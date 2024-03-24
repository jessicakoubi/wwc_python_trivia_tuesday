# Solution

**C**

As of Python 3.12, the math module provide a `sumprod()` function that return the sum of products of values from two iterables. This is equivalent to
`sum(itertools.starmap(operator.mul, zip(p, q, strict=True)))` where p and q are the two iterables to calculate the sum of their product. 