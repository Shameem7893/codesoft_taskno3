# Dark Theme Calculator

## Overview
This project is a **Dark Theme Calculator**, which provides basic arithmetic operations in a visually appealing and user-friendly interface. It is built using **HTML, CSS, and JavaScript**, showcasing a functional design with an interactive button layout.

## Features
- **Dark Theme Design**: A modern dark theme layout for a sleek and comfortable user experience.
- **Basic Arithmetic Operations**: Supports addition, subtraction, multiplication, division, and decimal points.
- **Clear and Backspace Functions**: Allows users to clear the display or delete the last entered digit.
- **Keyboard-Free Interaction**: All operations can be performed using on-screen buttons.

## File Structure
- `index.html`: The main HTML file for the calculator's structure and content.
- `styles.css`: An external CSS file for styling the calculator (not included in the provided code, but expected).
- `script.js`: A JavaScript file containing the logic for the calculator's functionality.

## How to Use
1. Clone or download the repository.
2. Place all files (`index.html`, `styles.css`, and `script.js`) in the same directory.
3. Open the `index.html` file in your browser to start using the calculator.

## Functions in `script.js`
1. **appendValue(value)**:
   - Appends the pressed button's value to the display.
2. **clearDisplay()**:
   - Clears the display completely.
3. **backspace()**:
   - Removes the last character from the display.
4. **calculateResult()**:
   - Evaluates the mathematical expression displayed.
   - Handles errors gracefully by displaying "Error" if the evaluation fails.

## How to Customize
1. **Style**:
   - Modify the `styles.css` file to change colors, fonts, or layout.
2. **Functionality**:
   - Extend the functionality by adding support for advanced operations like square root, percentage, or memory storage.
3. **Responsive Design**:
   - Make the calculator fully responsive for different screen sizes using media queries.

## Known Issues
- Using `eval()` in `calculateResult()`:
  - The `eval()` function is used to evaluate the entered expression. While convenient, it may pose security risks if user input is not properly sanitized.
  - To enhance security, consider using a math parser library like [math.js](https://mathjs.org/).

## Future Enhancements
- Add advanced calculator features such as trigonometric functions or scientific operations.
- Implement keyboard support for quicker input.
- Add animations to enhance user experience.

## License
This project is open-source and free to use. Feel free to modify and adapt it to your needs.
