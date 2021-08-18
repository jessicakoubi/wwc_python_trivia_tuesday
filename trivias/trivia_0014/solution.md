# Solution

**C**

If you define one or more rich comparison methods in your class, you can use the functools.total_ordering decorator to automatically add 
the other comparison methods. It can reduce the amount of code you have to write but does come with a slight speed hit and a more complex
stack trace.