# Swift Compile-Time Error: Missing ',' Separator in Function Call

This repository demonstrates a common Swift compile-time error that occurs when calling a function with multiple arguments but missing the comma (`,`) separator between them.

## Bug Description
The `calculateArea` function takes two `Double` arguments, `length` and `width`.  A compile-time error occurs when the function is called incorrectly without the comma separator between the arguments, resulting in a syntax error.

## Bug Solution
The solution involves ensuring that the comma separator is correctly used between function parameters when calling a function with multiple arguments.