 
Problem 21: Factorial (Recursive)  [Easy]
Description: Write a recursive function factorial(n) that returns the factorial of a non-negative integer n.
Example:
Input: 5  → Output: 120 (5×4×3×2×1)Input: 0  → Output: 1
Hint: Base case: factorial(0) = 1. Recursive case: n * factorial(n-1).

 
 
 
 
 
 
Problem 22: Fibonacci Sequence  [Easy]
Description: Write a function fibonacci(n) that returns the nth number in the Fibonacci sequence.
Example:
Input: 6  → Output: 8 (0,1,1,2,3,5,8...)
Hint: Try both iterative and recursive approaches.

 
 
 
 
 
 
Problem 23: Create a Counter with Closure  [Medium]
Description: Write a function makeCounter() that returns an object with increment, decrement, and getCount methods using closure.
Example:
const c = makeCounter();c.increment(); c.increment();c.getCount(); // 2
Hint: Use a variable inside the outer function that inner functions can access.

 
 
 
 
 
 
Problem 24: Curry a Function  [Medium]
Description: Write a function curry(fn) that converts a function of two arguments into a curried version.
Example:
const add = curry((a,b) => a+b);add(2)(3); // 5
Hint: Return a function from inside a function.

 
 
 
 
 
 
Problem 25: Memoize a Function  [Medium]
Description: Write a function memoize(fn) that caches the results of a function so repeated calls with the same input return the cached result.
Example:
const memoAdd = memoize(n => n + 10);memoAdd(5); // 15 (computed)memoAdd(5); // 15 (from cache)
Hint: Use an object as a cache inside the outer function.












```

Day 5 — Node.js & Express
Topic: Server, REST APIs & Middleware
Q61. What is Node.js and how does it differ from browser JavaScript?
Q62. What is the Node.js event loop and how does it handle async operations?
Q63. What is Express.js and why is it used with Node.js?
Q64. What is middleware in Express.js? Give three examples.
Q65. What is the difference between app.use() and app.get() in Express?
Q66. How do you handle errors in Express.js?
Q67. What are environment variables and how do you manage them in Node.js?
Q68. Explain the difference between CommonJS (require) and ES Modules (import) in Node.
Q69. What is CORS and how do you enable it in an Express app?
Q70. What is the purpose of the package.json file?
Q71. What is npm and what is the difference between dependencies and devDependencies?
Q72. How do you create a RESTful API with Express? Explain the standard HTTP methods.
Q73. What is JWT (JSON Web Token) and how is it used for authentication?
Q74. What is bcrypt and why is it used for password hashing?
Q75. What is the difference between synchronous and asynchronous file operations in Node.js?


```