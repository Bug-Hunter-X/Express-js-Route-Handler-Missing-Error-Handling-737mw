# Express.js Route Handler Missing Error Handling

This repository demonstrates a common error in Express.js route handlers: missing error handling for database queries.  The `/users/:id` route fetches user data but lacks proper handling for cases where the database query fails or the user is not found.

The `bug.js` file shows the problematic code. The `bugSolution.js` file provides the corrected version with comprehensive error handling.