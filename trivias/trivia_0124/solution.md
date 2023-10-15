# Solution

**D**

When you make an assignment to a variable in a scope, in this case our scope is the add2() function, the variable becomes local
to that scope and trump similarly named variables (x as assigned by x=1) in the outer scope.
The x+=2 statement in add2() assign a new value to x and the compiler recognizes it as a local variable.
