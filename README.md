# Calculator App

A responsive, web-based calculator built with vanilla HTML, CSS, and JavaScript.

## Features

- **Basic Operations**: Addition (+), Subtraction (−), Multiplication (×), Division (÷)
- **Clear Display**: Two-row display showing expression and result
- **Responsive Design**: Optimized for both mobile and desktop screens
- **Keyboard Support**: Full keyboard navigation and input
- **Error Handling**: Division by zero detection with clear error message
- **Smooth Animations**: subtle animations for button interactions and result updates

## How to Use

### Running the Calculator

Simply open `index.html` in any modern web browser:

1. Double-click `index.html`, or
2. Open it in your browser: File → Open File, or
3. Serve it locally (e.g., `python3 -m http.server 8000` and visit `http://localhost:8000`)

### Interaction

**Mouse/Touch:**
- Click or tap buttons to input numbers and operators
- The `C` button clears all
- The `⌫` button deletes the last digit
- The `=` button calculates the result

**Keyboard Shortcuts:**
- Digits: `0-9`
- Decimal: `.`
- Operators: `+`, `-`, `*`, `/`
- Calculate: `Enter` or `=`
- Clear: `Escape`
- Delete: `Backspace`

### Display

- **Top row** (gray): Shows the expression being built (e.g., "15 + ")
- **Bottom row** (white): Shows the current input or calculated result

### Error Handling

If you attempt to divide by zero, "Error" will appear in the result display. Press `C` or start typing a new number to continue.

## Browser Support

Works in all modern browsers that support:
- CSS Grid
- CSS Custom Properties
- ES6 JavaScript

Tested on Chrome, Firefox, Safari, and Edge.

## Technical Details

- **Single File**: All HTML, CSS, and JavaScript in one file
- **No Dependencies**: Pure vanilla JavaScript
- **Responsive**: Uses CSS Grid, clamp() for scalable fonts, and media queries
- **Accessibility**: ARIA labels and semantic HTML for screen reader support