# Solution

**C**

The **OrderedDict()** class in the *collections** module is a subclass of **dict()** that keep track of the order in
which key/value pairs were added.
As of python 3.7, **dict()** objects are guaranteed to keep their insertion order (introduced in python 3.6) making **OrderedDict()**
mostly useful for their specialized methods used to rearranging dictionary order such as *move_to_end()* that are particularly useful
when implementing a caching system.
