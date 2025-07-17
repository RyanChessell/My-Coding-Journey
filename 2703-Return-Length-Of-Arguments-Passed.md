# LeetCode 2703 - Return Length of Arguments Passed

📅 **Date Solved:** July 17, 2025  
🧠 **Language:** JavaScript  
⏱ **Runtime:** 36ms (Top 83.7%)  
📦 **Memory:** 53.14MB (Top 76.5%)

---

![Problem Screenshot](./assets/2703-problem.png)

## Problem Summary

Write a function `argumentsLength` that returns the count of arguments passed to it.

### Example 1:
```js
argumentsLength(5); // Output: 1
```

## Example 2:
```js
argumentsLength({}, null, "3"); // Output: 3
```

## My Solution (JavaScript)
/**
 * @param {...(null|boolean|number|string|Array|Object)} args
 * @return {number}
 */
var argumentsLength = function(...args) {
    return args.length;
};


## What I Learned
- How to use the rest parameter (...args) in JavaScript
- args.length directly gives us the count of passed arguments
- This is a good intro to JavaScript function parameter flexibility

## What I Can Improve
- Should test edge cases like no arguments passed
- Practice similar questions with logic inside the function, not just parameter handling

