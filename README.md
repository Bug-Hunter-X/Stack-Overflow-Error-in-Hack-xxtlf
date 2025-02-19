# Stack Overflow Error in Hack

This repository demonstrates a stack overflow error in Hack programming language. The `foo` function recursively calls itself without a proper base case, leading to unbounded recursion and ultimately a stack overflow.

## Bug Description

The `foo` function calculates the factorial of a number using recursion.  However, it lacks a proper termination condition. For larger inputs, it will exhaust the call stack, resulting in a stack overflow error. 

## Bug Solution

The solution adds a check for negative input values to prevent stack overflow and returns an error message accordingly.