# React Router Dom: Missing Route for Non-Matching Paths

This repository demonstrates a common error in React Router Dom v6 where navigating to a non-existent path leads to an empty screen rather than the expected behavior of a 404 page or default route.

The `bug.js` file shows the incomplete implementation.  The `bugSolution.js` demonstrates the solution.

## Bug
The main issue is the lack of a wildcard route to handle paths that don't match any explicitly defined routes.  Without it, React Router simply renders nothing.