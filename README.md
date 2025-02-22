# Unhandled Promise Rejection in React Native

This repository demonstrates a common error in React Native applications where an unhandled promise rejection within a `useEffect` hook causes the app to crash on Android devices. The issue arises from improper error handling when fetching data from an API.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version with proper error handling using `try...catch` block within `useEffect`.