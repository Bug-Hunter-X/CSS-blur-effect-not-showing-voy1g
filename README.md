# CSS Blur Effect Not Showing

This repository demonstrates a common issue encountered when using the `filter: blur()` property in CSS.  The blur effect appears to be applied, yet there's no visible change in the element's appearance. This often happens when there is no underlying content or color for the blur to affect.

The `bug.css` file contains the problematic code, while `bugSolution.css` provides a corrected version.

## Problem
The blur filter is applied, but it does not visibly affect the element, even though a background color is set.  This usually means the blur is only affecting the element's background and there's no underlying content to interact with the blur. 

## Solution
The solution involves ensuring there is something for the blur filter to impact.  This can be done by adding content behind the element that has a background or border.