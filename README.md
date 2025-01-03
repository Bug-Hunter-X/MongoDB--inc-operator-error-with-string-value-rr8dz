# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, if a string value is provided instead of a number, it will result in an error. 

The `bug.js` file shows the incorrect usage, and `bugSolution.js` provides the corrected version. 

## Steps to Reproduce

1.  Make sure that you have MongoDB installed and running.
2.  Create a collection named 'myCollection'.
3.  Insert a document containing the `count` field (e.g., `{_id: 1, count: 0}`).
4.  Run the code in `bug.js`. You'll encounter an error because the `$inc` operator is given a string.