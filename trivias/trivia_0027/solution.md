# Solution

**B**

You can use **itertools.filterfalse(predicate, iterable)** to create an iterator that filter over the elements of an iterable (such as a list) and 
return only the elements for which the predicate is *False*.

In our example we return the list of elements in a range of 0 to 10 that are divisible by 3 using the modulo operator (*%*) as part of the predicate.