# CSS calc() Function Error: Missing Spaces

This repository demonstrates a common error when using the `calc()` function in CSS.  The `calc()` function requires spaces around the +,-,*,/ operators. Failure to include these spaces results in unexpected behavior.

## Bug

The `bug.css` file contains CSS with missing spaces in the `calc()` function. This leads to the width of the element not being calculated as intended.

## Solution

The `bugSolution.css` file shows the corrected version with the necessary spaces added to the `calc()` function, resolving the unexpected calculation.

## How to reproduce

1. Open `bug.html` in your browser.
2. Observe the width of the element.  It will be incorrect due to the missing spaces.
3. Open `bugSolution.html` in your browser.
4. Observe the corrected width calculation, resulting from the correct use of the `calc()` function.