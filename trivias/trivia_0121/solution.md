# Solution

**C**

You can use the seek() function to control which chunk of data you want to read. This can be particularly useful when dealing with
large amount of data that either don't fit in memory, is too slow to read in one loop or where you know the consistent position of
the data you are interested in.
