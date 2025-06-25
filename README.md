This project provides a utility function `first()` written in JavaScript that returns the first element or the first `n` elements from a given array.

Function Description

The `first()` function handles different use cases:

- Returns the **first element** if no second argument is provided.
- Returns the **first `n` elements** if a number is passed as the second argument.
- Returns an **empty array** for edge cases such as:
  - An empty input array.
  - A non-positive `n` (e.g., 0 or negative numbers).
  - A value of `n` greater than the array length (returns full array).
