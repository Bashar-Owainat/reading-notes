# REST
The rest parameter syntax allows a function to accept an indefinite number of arguments as an array, providing a way to represent variadic functions in JavaScript.

## Syntax

function f(a, b, ...theArgs) {
  // ...
}

## Description
The last parameter of a function definition can be prefixed with "..." (three U+002E FULL STOP characters), which will cause all remaining (user supplied) parameters to be placed within a "standard" JavaScript array. Only the last parameter in a function definition can be a rest parameter.