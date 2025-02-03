# CSS Filter Bug: blur() on Background Images

This repository demonstrates a common issue where the CSS `filter: blur()` property fails to apply to background images.  The expected behavior is a blurred background image, but instead, the image remains sharp. This issue can also occur with other filter effects applied to elements with background images. The `bug.css` file shows the problem, while `solution.css` provides a possible solution.

**Problem:**  The blur effect is not applied to the background image.

**Solution:**  Use a pseudo-element (`::before` or `::after`) to create a blurred overlay on top of the background image.