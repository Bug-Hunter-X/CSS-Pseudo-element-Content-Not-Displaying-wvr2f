# CSS Pseudo-element Content Not Displaying Bug
This repository demonstrates a common CSS bug where the content property of a pseudo-element (::before) fails to render as expected.  The issue occurs when the `::before` pseudo-element is applied to an element that already has content, or if the selector is not properly applied to the target elements.

The `bug.css` file contains the erroneous CSS, while `solution.css` provides a corrected version.

## Bug Details
The primary problem is the inconsistent rendering of the bullet point ("\2022").  The bullet might be missing, overridden, or hidden depending on the HTML structure and other CSS rules.