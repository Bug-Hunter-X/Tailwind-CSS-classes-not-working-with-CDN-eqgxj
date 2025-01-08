# Tailwind CSS CDN issue
This repository demonstrates a common issue encountered when using Tailwind CSS via CDN: classes not being applied correctly. The problem stems from improper configuration or integration of the CDN with the project.

## Problem Description
The provided index.html file uses Tailwind CSS classes directly via CDN.  However, the `bg-red-500` class is not being applied, resulting in a plain paragraph element with no styling. This often indicates a missing or incorrect setup.

## Solution
The problem is that while the CDN includes Tailwind's CSS, it doesn't automatically process your HTML to apply styles.  To fix this you will need a build process, or use a build system with Tailwind's build process.