# Uncommon HTML Bug: Accessing Non-Existent DOM Property

This repository demonstrates a subtle bug that can occur in HTML/JavaScript when attempting to access a property of a DOM element that does not exist. This can lead to unexpected errors or exceptions, which can be difficult to debug without a careful review of the code.

## Bug Description
The bug occurs in `bug.html`.  The script tries to access a property (`nonExistentProperty`) on the `myDiv` element that is not defined. This will cause a runtime error.

## Solution
The solution in `bugSolution.html` demonstrates how to check for the existence of a property before trying to access it, avoiding the runtime error.  It showcases the use of the `hasOwnProperty` method for robust property verification.
