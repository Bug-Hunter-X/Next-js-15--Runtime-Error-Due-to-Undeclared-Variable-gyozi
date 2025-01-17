# Next.js 15: Runtime Error Due to Undeclared Variable

This repository demonstrates a common runtime error in Next.js 15 applications caused by referencing an undeclared variable.  The error is subtle and might not be caught during development.

## Bug Description

The `about.js` file contains a typo in variable declaration, leading to a runtime error.  The application does not gracefully handle the error, causing a crash.

## Solution

The `aboutSolution.js` file provides a corrected version where the variable is correctly declared and handled.

## How to reproduce

1. Clone the repository.
2. Run `npm install`
3. Run `npm run dev`
4. Navigate to `/about`
5. Observe the runtime error.