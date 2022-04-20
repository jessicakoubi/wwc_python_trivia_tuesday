# Solution

**A**

**os.path.relpath()** will return a relative filepath to the given path from either the current directory or a given start path.

We use it in our example to replace the start of the path that correspond to a user directory. It's a safer alternative to **str.replace()** when
dealing with paths, especially if we have some structure repetition in our path or we are dealing with a mix of separators.
