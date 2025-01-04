# CSS Specificity Bug
This repository demonstrates a common CSS bug caused by specificity conflicts.  Inline styles override internal styles, which override external styles.  Understanding and managing CSS specificity is crucial for predictable styling.

## Bug
The bug is demonstrated in `bug.css`.  Inspect the elements in the example HTML to see how specificity affects styling.

## Solution
The solution is demonstrated in `bugSolution.css`. It shows the proper way to resolve these specificity issues through the use of !important statements, more specific selectors or restructuring of the CSS.