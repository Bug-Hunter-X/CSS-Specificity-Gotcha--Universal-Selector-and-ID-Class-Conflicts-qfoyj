# CSS Specificity Gotcha: Universal Selector and ID/Class Conflicts

This repository demonstrates a subtle issue related to CSS specificity when combining universal selectors with class and ID selectors. The unexpected behavior arises from the way CSS resolves conflicting styles based on selector specificity.

## Problem Description
The `bug.css` file contains CSS rules that lead to unexpected color assignments.  The interaction between the universal selector (`div`), class selector (`.special-div`), and ID selector (`#specific-div`) causes conflicts in style application. Understanding the order of precedence and specificity is key to resolving this.

## Solution
The `bugSolution.css` file provides a solution by restructuring the selectors or utilizing the `!important` flag (though using `!important` is generally discouraged unless absolutely necessary). The solution prioritizes clarity and maintainability over using `!important`.