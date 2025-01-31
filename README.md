# React Native useRef Hook Async Operation Unmounting Issue

This repository demonstrates a common issue in React Native applications where using the `useRef` hook with asynchronous operations (like `setTimeout` or `setInterval`) can lead to unexpected behavior or crashes if the component unmounts before the asynchronous operation completes.

The `bug.js` file showcases the problematic code, illustrating how this error can occur. The `bugSolution.js` file provides a solution to prevent this issue by checking if the component is still mounted before executing the asynchronous operation's callback.