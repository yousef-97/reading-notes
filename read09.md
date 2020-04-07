# Functional Programming
Functional programming is a programming paradigm a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 

The first fundamental concept we learn when we want to understand functional programming is pure functions. Functional programming *returns the same result if given the same arguments* (it is also referred as deterministic)and *does not cause any observable side effects*.

**Observation**: mutability is discouraged in functional programming.

If *we follow these two simple rules, it gets easier to understand our programs*. Now every function is isolated and unable to impact other parts of our system. Pure functions are *stable*, *consistent*, and *predictable*. Given the same parameters, pure functions will always return the same result. We donâ€™t need to think of situations when the same parameter has different results â€” because it will never happen.

*pure functions + immutable data = referential transparency*

## Functions as first-class entities

The idea of functions as first-class entities is that functions are also treated as values and used as data.

Functions as first-class entities can:
1. refer to it from constants and variables
2. pass it as a parameter to other functions
3. return it as result from other functions

The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.

## Higher-order functions
When we talk about higher-order functions, we mean a function that either:
* takes one or more functions as arguments, or
* returns a function as its result

# Refactoring

Here are some straightforward to implement methods that can lead to easier to read code. There are no absolutes when it comes to clean code â€” there's always an edge case!

* Return early from functions
* Cache variables so functions can be read like sentences
* Check for Web APIs before implementing your own functionality

*It's important to get your code right the first time because in many businesses there isn't much value in refactoring. Or at least, it's hard to convince stakeholders that eventually uncared for codebases will grind productivity to a halt.

