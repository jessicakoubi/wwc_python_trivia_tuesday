# Solution

**C**

PEP692 introduce, in Python 3.12, the ability to have more precise type hinting for kwargs by using TypedDict. Instead of having type hint where all the kwargs must be of the same type, you
can use a TypedDict. Additionally, you can also use PEP655 to mark some of a TypedDict keys as required or optional but in PEP692 case, use regular arguments for required data, this was done
as an example only.
kwargs which don't follow the TypedDict will be detected by a static type checker such as mypy.
