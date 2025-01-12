# CSS `calc()` Function Bug

This repository demonstrates a bug related to the `calc()` function in CSS when combining percentage and pixel units. The expected behavior is that `width: calc(50% - 10px);` should calculate the width as 50% of the container's width minus 10 pixels. However, in some scenarios, this calculation might produce an incorrect result. 

## How to reproduce

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Observe the width of the element with the problematic `calc()` style. It may not match the expected width based on the container width.

## Solution

The solution file (`bugSolution.css`) provides possible solutions to mitigate this issue.  The approaches may include using alternative units, adjusting the calculation, or using JavaScript to perform the calculation and set the width dynamically.