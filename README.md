# Uncommon HTML Error: Accessing DOM Element Before Loading

This repository demonstrates a common yet easily overlooked error in HTML/JavaScript: attempting to access a DOM element before it's fully loaded into the page.  This can lead to unexpected errors and unexpected behavior.  The `bug.html` file shows the error, while `bugSolution.html` provides a corrected version.

## The Problem

The issue arises when JavaScript code tries to interact with an HTML element (e.g., get its content, change its properties) before the browser has fully parsed and rendered that element. In `bug.html`, we try to access `myDiv`'s innerHTML before the browser has added it to the DOM.