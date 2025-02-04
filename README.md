# Unexpected Behavior with CSS `calc()` Function

This repository demonstrates some uncommon issues that can arise when using the `calc()` function in CSS.  The `bug.css` file shows examples of problematic `calc()` usage, while `bugSolution.css` provides corrected implementations.

The issues explored include:

* **Parent Width Dependency:**  `calc()`'s reliance on the parent element's width can lead to unexpected results if the parent width isn't explicitly defined or is dynamic.
* **Unit Mixing:** Incorrect mixing of different units (e.g., pixels and percentages) within a single `calc()` expression can cause errors.
* **Operator Precedence:** Incorrect order of operations can lead to wrong calculations.
* **Media Query Complications:** Using `calc()` within media queries needs careful consideration to avoid unexpected behavior.

This repository provides a clear understanding of these common pitfalls and illustrates effective solutions. 