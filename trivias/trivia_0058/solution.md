# Solution

**C**

When a mutable argument is used as a default value it doesn't get initialized every time the function is called. Instead, the most
recent value assigned to them is used.
In our example, we call the function 4 times and append *1* to the list each time.
