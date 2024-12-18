# Uncommon CSS Bug: Unexpected Styling from Specificity and Cascade

This repository demonstrates a common yet often overlooked issue in CSS: unexpected styling results stemming from the interplay of specificity and the cascading order of styles.  The `bug.css` file contains the problematic CSS, while `bugSolution.css` offers a resolution.

The bug is rooted in the complexities of CSS specificity and the cascade.  Understanding how specificity works and the order of stylesheets significantly impacts debugging.

## Setup

1. Clone this repository.
2. Open `index.html` in your web browser (you might need to create a simple HTML file to test the CSS).

## Bug Description

Unexpected styling results caused by CSS specificity and cascade issues. The goal is to understand how the rules interact and how to fix them for predictable styling.

## Solution

The `bugSolution.css` file demonstrates one possible solution. The primary approach involves careful consideration of selector specificity and the order of CSS rules to ensure that styles are applied as intended.