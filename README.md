# CSS `calc()` Function: Spaces Around Operators Cause Errors

This repository demonstrates a common but easily overlooked error when using the `calc()` function in CSS.  Improper spacing around the arithmetic operators (+, -, *, /) within the `calc()` function can lead to unexpected results or parsing errors in some browsers.

**Problem:**
The presence of unnecessary spaces around the operators inside the `calc()` function can cause it to not parse correctly, resulting in incorrect layout or even rendering errors. 

**Solution:**
Ensure that there are *no* spaces immediately before or after the plus (+), minus (-), multiplication (*), or division (/) operators within the `calc()` function.

The example files (`bug.css` and `bugSolution.css`) illustrate the problematic and corrected code, respectively.