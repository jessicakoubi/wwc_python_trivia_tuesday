# Solution

**B**

Classes, such as list, may implement the *op=* operators differently making *a+=b* and *a=a+b* not behave the same way.

In our case *a=a+[4]* created a new list instance assigned to *a* while *c+=[4]* map to an *extend()* function that operate
in place, changing the value of both *c* and *d*.
