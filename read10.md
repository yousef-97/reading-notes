# The Call Stack and Debugging

### the call stack 

 is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions what function is currently being run and what functions are called from within that function<br />

#### What causes a stack overflow

 stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

**call stack**<br />

1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.

### JavaScript error messages && debugging

#### Types of error messages

* Reference errors:  when you try to use a variable that is not yet declared you get this type os errors.
* Syntax errors:this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse
* Range errors:for every thing related with range like (length of array can not be minus)
* Type errors: This is probably the most frequent error in JS, trying to access a property/method thinking that bar is of the type object when in reality, since it hasn’t been declared yet, it’s undefined which doesn’t have any baz available.



