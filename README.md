# Express.js Route Handler Error Handling Bug

This repository demonstrates a common error in Express.js route handlers:  missing error handling for invalid input.  The `bug.js` file contains a vulnerable route that crashes if a non-numeric ID is provided. The `bugSolution.js` file provides a corrected version with robust error handling.