# Unexpected Width Calculation using calc() in CSS

This repository demonstrates a common, yet subtle, error when using the `calc()` function in CSS. The issue arises from applying `calc()` to an element that doesn't have a correctly defined containing element's width. 

The `bug.css` file shows the incorrect implementation, while `bugSolution.css` provides a corrected version.  The core problem is addressed by explicitly setting the width of the parent container, ensuring accurate calculations using `calc()`. 