# CSS :nth-child Selector Issue with Dynamic Content

This repository demonstrates an uncommon bug related to the CSS `:nth-child` selector and its unexpected behavior when dealing with dynamically added or removed elements. The bug arises because `:nth-child`'s evaluation is static, meaning it doesn't automatically recalculate after DOM changes.  This can lead to styling inconsistencies and visual discrepancies.

The `bug.css` file shows the problematic code, while `bugSolution.css` offers a solution using JavaScript to update the styling when the DOM is modified.