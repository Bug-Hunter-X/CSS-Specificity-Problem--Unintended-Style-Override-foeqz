# CSS Specificity Bug

This repository demonstrates a common issue in CSS related to specificity.  The `bug.css` file contains CSS code where a more specific selector unintentionally overrides a less specific one, leading to unexpected styling results. The `bugSolution.css` file offers a solution to correct this behavior.

## Problem

The problem lies in how CSS handles specificity.  A more specific selector will always override a less specific one, even if it seems counterintuitive.  In this case, `.container .item` is more specific than `.item`, so its style for the `color` property takes precedence.

## Solution

The solution involves understanding and using CSS specificity correctly.  The `bugSolution.css` file provides a corrected version of the CSS.