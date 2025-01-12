# Unhandled Asynchronous Error in Node.js

This repository demonstrates a common error in Node.js: unhandled errors occurring within asynchronous operations, specifically within a `setTimeout` callback in an Express.js server.

The `bug.js` file shows the problematic code. The error is thrown inside the `setTimeout` callback, making it difficult to handle with standard `try...catch` blocks.  The `bugSolution.js` file provides a solution using error handling within the asynchronous operation.