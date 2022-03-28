# Solution

**B**

The **re.sub()** method can be used to replace a pattern in a string by another string. In our case, we convert a camel-cased string
into a snake-case one. We use backreferences in the string we want to replace to by calling the matched group of characters, for
example *\1* in it.
Effectively adding an underscore between each capitalized words first, then converting every upper-cased characters into lower case ones.
