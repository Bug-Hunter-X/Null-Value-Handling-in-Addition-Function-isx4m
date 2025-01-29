# JavaScript Bug: Null Value Handling in Addition Function

This repository demonstrates a common JavaScript bug related to null value handling in an addition function.

## Bug Description

The `foo` function is designed to add two numbers. However, it unexpectedly returns `null` if either input is `null`.  A more robust solution would treat `null` values as 0.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.js`.
3. Run the code using Node.js (or your preferred JavaScript environment).
4. Observe the unexpected `null` outputs.

## Solution

The `bugSolution.js` file provides a corrected version of the function that handles `null` values appropriately.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request if you have any suggestions or improvements.