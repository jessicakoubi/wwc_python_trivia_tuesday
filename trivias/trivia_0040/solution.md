# Solution

**B**

The **ord()** method takes a string representing a Unicode character and returns its code point (as an integer). The **char()** method
do the inverse and return the string representation of a Unicode character from it's code point.

In our case, we first get the *$* code point, add 8328 to it which is the code point of *€* and then use **char()** to get its string
representation.
