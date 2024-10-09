# SIMPLE CALCULATOR
#### Video Demo:  <URL HERE>
#### Description:
Files Overview
1. index.html
The HTML file provides the structure of the calculator. It includes:

Input Fields: Two number inputs for users to enter values.
Operation Buttons: Four buttons (+, -, *, /) to select the arithmetic operation.
Result Display: An area where the result of the calculation is displayed dynamically.
This file also links to the styles.css and script.js files for styling and functionality.

2. styles.css
The CSS file is responsible for the design and layout. Key features include:

Centering and Layout: The calculator is centered on the page using Flexbox, ensuring it's responsive on different screen sizes.
Button and Input Styling: Buttons and input fields are styled for easy interaction, using hover effects and spacing for clarity.
Minimalist Design: The design is kept simple and clean to ensure a focus on usability.
3. script.js
The JavaScript file handles the logic behind the calculator:

calculate() Function: This function processes the user inputs and selected operation. It performs addition, subtraction, multiplication, or division, based on the button clicked.
Error Handling: It includes basic checks, such as preventing division by zero and ensuring valid number inputs. If invalid data is entered, an alert prompts the user.
The JavaScript code is designed to be efficient by using a single calculate() function to handle all operations, reducing redundancy and making it easier to maintain and extend in the future.

Design Considerations
Simplicity: I chose to keep the interface and functionality simple, focusing only on basic arithmetic. This decision ensures the application is easy to use and fast to load, without unnecessary features.

Consolidated JavaScript Logic: Instead of writing separate functions for each arithmetic operation, I used a single function to handle all calculations, making the code cleaner and more maintainable.

User Feedback: The application provides immediate feedback when invalid inputs are detected, such as trying to divide by zero or using non-numeric values. This improves the overall user experience.

Future Improvements
Future enhancements could include:

Support for advanced operations like exponents or square roots.
Adding keyboard support for entering numbers and selecting operations.
A history feature to track previous calculations.
