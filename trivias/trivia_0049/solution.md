# Solution

**C**

You can check if a file or directory have a specific set permissions (in our case, write access) with the **os.access()** method, the second argument correspond
to the permissions either in its binary representation (such s *664*), or using one of *os* *os.R_OK*, *os.W_OK*, *F_OK* or *os.X_OK* value.
