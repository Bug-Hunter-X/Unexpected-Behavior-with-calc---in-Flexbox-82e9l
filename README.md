# Unexpected Behavior with calc() in Flexbox

This repository demonstrates a common CSS issue involving the `calc()` function and flexbox layout. The problem arises from the order in which `calc()` calculations and flexbox layout are resolved.  Percentage values within `calc()` can behave unexpectedly in flexbox containers because they are determined before the flexbox layout is applied.

The `bug.css` file shows the flawed CSS, while `bugSolution.css` provides a solution.