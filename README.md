# Uncommon HTML Bug: Unexpected innerHTML Behavior

This repository demonstrates a subtle bug related to the use of `innerHTML` in JavaScript within an HTML document.

## Bug Description
The bug involves unexpected behavior when appending to the `innerHTML` of an element. Incorrect usage can lead to unexpected results, especially when combining string concatenation and existing HTML content. The example shows how attempting to append text to existing HTML within an element using `innerHTML` can cause unexpected side effects.  The solution shows the safer method of using `insertAdjacentHTML`.

## Bug Reproduction
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected behavior.

## Solution
The solution file, `bugSolution.html`, demonstrates a safer and more predictable approach that does not use the problematic `innerHTML` append. Using `insertAdjacentHTML` provides better control and avoids many of the potential errors associated with modifying `innerHTML` directly.
