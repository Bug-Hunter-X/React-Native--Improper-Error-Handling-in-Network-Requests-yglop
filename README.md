# React Native: Improper Error Handling in Network Requests

This repository demonstrates a common error in React Native applications: improper error handling in asynchronous network requests. The original code uses the `fetch` API in a way that doesn't handle errors effectively. This can lead to unexpected crashes or silent failures.

The `bug.js` file contains the problematic code. The `bugSolution.js` file demonstrates the correct way to handle network requests using async/await and try...catch blocks for comprehensive error handling.