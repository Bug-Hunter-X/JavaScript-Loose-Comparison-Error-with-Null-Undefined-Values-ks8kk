# JavaScript Loose Comparison Error with Null/Undefined Values

This repository demonstrates a common error in JavaScript when using loose comparison (==) with null or undefined values.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version using strict equality (===).

## Problem

Loose comparison (==) can lead to unexpected results when comparing values like null and undefined.  In the example, the function `foo` attempts to handle null/undefined gracefully. However, loose equality can produce counter-intuitive behavior which can be hard to debug.

## Solution

The best practice is to always use strict equality (===) for comparisons to avoid these unexpected behaviors. The `bugSolution.js` file demonstrates the improved version using strict equality.