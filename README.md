# Uncommon HTML Errors
This repository demonstrates two uncommon but potentially frustrating errors in HTML:

1. **Attempting to access a non-existent element:**  The code attempts to manipulate an element's `innerHTML` property before verifying the element's existence. If the element isn't found, a runtime error occurs.
2. **Referencing an element before its declaration:** The code attempts to access and modify an element before it's added to the DOM. This leads to a null pointer or similar error.

The `bug.html` file showcases these errors. The `bugSolution.html` file provides corrected versions with appropriate error handling and element creation.