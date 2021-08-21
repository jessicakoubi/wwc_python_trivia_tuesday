# Solution

**C**

You can't sub-class the built-in *bool* class. This was made on purpose as sub-classing bool may break the invariant that True 
and False are the only instances of bool as explained in this discussion thread https://mail.python.org/pipermail/python-dev/2002-March/020822.html