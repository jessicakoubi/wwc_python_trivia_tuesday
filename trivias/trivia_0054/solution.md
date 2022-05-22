# Solution

**A**

**PEP3107** introduced the concept of function annotations to python 3.0 to add arbitrary metadata annotations to Python functions.
It's often used to define which type of object (such as list, float, string, ...) an argument is supposed to be in order to have a
third-party library such as *mypy* do typechecking but annotation are arbitrary and their interpretation left to external libraries.
