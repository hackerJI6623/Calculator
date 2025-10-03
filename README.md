# Calculator

A simple web-based calculator built with HTML, CSS and JavaScript.

This project provides a small calculator UI with basic operations and a single-file JavaScript implementation.

## Files

- `index.html` — the webpage and calculator UI
- `style.css` — styles for the calculator
- `script.js` — logic for button clicks and expression evaluation

## How to run

1. Open `index.html` in your browser (double-click it or open it from your file manager).
2. Click the buttons or type into the input to build expressions.

## Notes & security

- The current `script.js` uses `eval()` to evaluate expressions. Using `eval()` on untrusted input is a security risk. If you plan to accept input from untrusted sources or extend this app, replace `eval()` with a safer expression parser (for example, math.js) or implement a custom parser.

## Recommended improvements

- Add keyboard support for typing numbers and operators.
- Add unit tests for the expression evaluation logic.
- Replace `eval()` with a safe parser.
- Improve accessibility (aria labels and focus management).

## License

MIT © Your Name
