# Uncommon HTML Error: Incorrect getElementByIdx

This repository demonstrates a common mistake in JavaScript when interacting with HTML elements using the `getElementById` method.  The error involves a simple typo or misunderstanding which leads to runtime errors.

## Bug Description
The `bug.html` file contains a typo in the JavaScript code. It uses `getElementByIdx` instead of `getElementById` to access a div element, causing a runtime error because the incorrect method does not exist.

## Solution
The `solution.html` file corrects the typo and shows the correct way to access an HTML element using `getElementById`. 

## How to Reproduce
1. Open `bug.html` in a web browser.
2. Observe the error in the browser's developer console.
3. Open `solution.html` to see the corrected code.

## Lessons Learned
Pay close attention to details when working with JavaScript and HTML.  A simple typo can lead to unexpected and difficult-to-debug errors. Using your browser's developer console is crucial for identifying and resolving these errors. Double-check your syntax and use the correct methods for DOM manipulation.