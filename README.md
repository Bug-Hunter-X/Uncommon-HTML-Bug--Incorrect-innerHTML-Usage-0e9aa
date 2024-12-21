# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates an uncommon bug related to the incorrect use of the `innerHTML` property in HTML.  The `innerHTML` property expects a string value to be assigned to it. Attempting to assign non-string values (like numbers) can lead to unexpected behavior or errors.

## Bug Description
The bug occurs when a non-string value (in this case, a number) is assigned to the `innerHTML` property of an HTML element.  This can result in the element not being updated correctly or in unexpected JavaScript errors in some browsers.

## Bug Reproduction
1. Open `bug.html` in a web browser.
2. Observe the output.  The `div` element with the id "myDiv" may appear empty or display unexpected content, depending on the browser.

## Solution
The solution involves ensuring that only string values are assigned to `innerHTML`.  The example in `bugSolution.html` provides the correct approach.
