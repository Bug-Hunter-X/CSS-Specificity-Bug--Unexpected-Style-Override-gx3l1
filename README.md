# CSS Specificity Bug: Unexpected Style Override

This repository demonstrates an uncommon CSS bug related to selector specificity.  The issue highlights how a less specific CSS rule can override a more specific one if not carefully considered.

## Bug Description
The CSS code attempts to style elements with the class `my-class` within a div with the id `my-div`. However, a less specific rule unintentionally overrides the intended styling.

## Solution
The solution involves understanding and adjusting CSS specificity to ensure the intended style is applied.