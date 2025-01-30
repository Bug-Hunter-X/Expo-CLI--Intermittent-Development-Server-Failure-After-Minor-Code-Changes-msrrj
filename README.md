# Expo CLI: Intermittent Development Server Failure

This repository demonstrates a bug encountered with the Expo CLI where the development server fails to start after making seemingly minor changes to the project's code.  The issue is characterized by cryptic error messages or the development server hanging indefinitely.  Common troubleshooting steps, such as `expo start --reset`, often prove ineffective.

## Reproduction Steps

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run `expo start`.  The project should load successfully.
4. Make a small change to the project (e.g. add a comment, change a variable name) in `bug.js`.
5. Run `expo start` again. The development server may fail to start or hang.

## Solution

The solution is provided in `bugSolution.js`.  It involves [explain solution concisely here, e.g. cleaning the project cache, explicitly defining dependencies etc.].

## Note

This bug appears to be intermittent and not easily reproducible across different systems and Expo versions. This repository provides a starting point for debugging and further investigation.