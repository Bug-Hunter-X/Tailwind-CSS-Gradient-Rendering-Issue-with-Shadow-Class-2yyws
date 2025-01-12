# Tailwind CSS Gradient and Shadow Bug

This repository demonstrates a subtle bug related to the rendering of Tailwind CSS gradients when used in conjunction with the `shadow-md` class.  In some browsers, the shadow appears to overlap or distort the gradient, depending on the order of CSS classes.

## Problem

The issue occurs when a gradient background is applied to an element, and a shadow is added afterward.  This can lead to visual inconsistencies across different browsers.

## Solution

The solution involves carefully considering the order of classes and potentially using more specific Tailwind classes to better control the rendering behavior. For instance, adjusting the `z-index` or using `inset-shadow` can help.