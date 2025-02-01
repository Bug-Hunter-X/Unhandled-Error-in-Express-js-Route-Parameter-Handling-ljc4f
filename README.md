This repository demonstrates a common error in Express.js route handling. The provided code snippet retrieves user details using parameters, but lacks proper error handling when the user is not found. This can lead to server errors or unexpected responses. The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the correct implementation.

The bug is that if a user with the specified ID does not exist, the code doesn't gracefully handle the missing user. This might cause unhandled exceptions or inconsistent responses. The solution includes proper error handling with a more descriptive 404 status code.