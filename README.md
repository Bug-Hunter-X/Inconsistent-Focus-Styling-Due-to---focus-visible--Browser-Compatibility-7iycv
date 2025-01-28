# Inconsistent Focus Styling Due to ":focus-visible" Browser Compatibility

This repository demonstrates a common issue encountered when using the CSS `:focus-visible` pseudo-class: inconsistent focus styling across different browsers due to lack of support in older browsers.

## The Problem

The `:focus-visible` pseudo-class is designed to only style elements when they are focused and the focus is not programmatically triggered (e.g., by JavaScript).  However, older browsers do not support this pseudo-class, meaning that the focus styles might be applied even when the user is not actively interacting with the element, resulting in unexpected visual behavior.

## Solution

The provided solution shows how to apply a fallback styling that would work in older browsers. The main approach is to check for browser support using Javascript and adding classes. This allows a consistent focus indication across all supported browsers.