# Express.js Route Handler Error
This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input. The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.

## Bug Description
The `bug.js` file shows a route handler that fetches a user based on their ID.  It fails to handle cases where the ID is not a number or is missing. This can result in runtime errors.

## Solution
The `bugSolution.js` file demonstrates improved error handling. It includes checks to validate the user ID and gracefully handles cases where the user is not found or the ID is invalid.