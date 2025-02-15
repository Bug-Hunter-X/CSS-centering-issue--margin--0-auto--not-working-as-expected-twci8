# CSS Centering Bug

This repository demonstrates a common issue with CSS centering using `margin: 0 auto;`. The `bug.css` file contains the erroneous CSS, while `bugSolution.css` provides the corrected code.

## Problem

The provided CSS attempts to center a div horizontally. However, it will fail to center correctly if its parent element doesn't have an explicit width.

## Solution

Ensure the parent element of the div has a defined width. This allows the `margin: 0 auto;` to calculate the correct left and right margins for centering.