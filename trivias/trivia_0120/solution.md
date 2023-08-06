# Solution

**A**

The *Women* class is a descriptor whose *\_\_get\_\_()* method always returns the constant *"code"*. In the a.x attribute lookup, the dot operator finds *'x': 5* in the class dictionary. In the *a.y* lookup, the dot operator finds a descriptor instance, recognized by its *\_\_get\_\_* method. Calling that method returns *"code"*.

The value *"code"* is not stored in either the class dictionary or the instance dictionary. Instead, it's computed on demand.
