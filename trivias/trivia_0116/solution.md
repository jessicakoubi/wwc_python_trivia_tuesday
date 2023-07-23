# Solution

**C**

The *inspect* module can used to get lot of useful information about live objects. In our case, we give the path to the
json module to *inspect.getmodulename()* and get the module name which is *\_\_init\_\_* as the json module is a directory
on disk and doing *import json* will import the *json/\_\_init\_\_.py* file.
