# Tailwind CSS @apply Directive Error: Undefined or Misconfigured Class

This repository demonstrates a common yet easily missed error in Tailwind CSS related to the `@apply` directive. The error occurs when attempting to use a class within `@apply` that either doesn't exist in your Tailwind configuration or has a typo.

## Reproduction

1. Clone this repository.
2. Run `npm install` (or `yarn install`).
3. Attempt to build the project (if applicable). You'll encounter an error indicating that one or more of the classes are not defined.

## Solution

The solution is to ensure all classes used within the `@apply` directive are correctly defined in your `tailwind.config.js` and that any necessary plugins are properly included and configured.  Correct typos and ensure that the class names match exactly. 