# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle yet easily missed error in JavaScript when interacting with the HTML DOM.

The `bug.html` file contains a typo in the `getElementById` function, causing the code to fail silently without any error messages.

The `bugSolution.html` file provides the corrected version of the code.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe that the text within the div element does not change, even though the JavaScript code attempts to modify it.
4. Open `bugSolution.html` to see the corrected code and the expected behavior.

## Lesson Learned

Always double-check for typos, especially in function names and variable names.  Even a small mistake can lead to unexpected behavior and debugging challenges.