# Uncommon HTML Bug: Accessing Non-Existent Element

This repository demonstrates a subtle HTML bug related to attempting to modify the `innerHTML` property of a non-existent element.  The bug only manifests during runtime and doesn't involve syntax errors, making it harder to detect.

## Bug Description:
The `bug.html` file contains a script that tries to change the content of an element with the ID `myDiv2`. However, no such element exists in the HTML structure. This results in a runtime error.

## Solution:
The `bugSolution.html` file provides a corrected version. It either checks for the element's existence before attempting modification or correctly creates the element first before accessing it.  Always verify that an element exists before manipulating it to prevent unexpected errors.