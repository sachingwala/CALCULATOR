# CALCULATOR
Calculator App
A simple yet functional calculator built with HTML, CSS, and JavaScript. This app performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

Features
Basic arithmetic operations: addition, subtraction, multiplication, division.
Responsive design for different screen sizes.
Clean and user-friendly interface.
Clear and error handling functionality.

File Overview
index.html: This is the main HTML file where the structure of the calculator is created. It includes references to the stylesheets and JavaScript files.

css/style.css: This file contains the core styles for the calculator, including button layouts, fonts, and the overall design.

css/utility.css: This file provides utility classes for layout, positioning, and responsiveness.

js/main.js: This file contains the logic for handling user input, interacting with the DOM, and making the calculator interactive.

js/calc.js: This file contains the core logic for performing arithmetic operations like addition, subtraction, multiplication, and division. It interacts with main.js to update the UI when calculations are performed.

How It Works
User Input:

Users can click on the calculator buttons to input numbers and operations.
Calculation:

When the user presses "=", the app calculates the result using the logic in calc.js.
Clear:

The user can press "C" to clear the display.
Error Handling:

If an error occurs (e.g., division by zero), the app will display an error message like "Error" or "Invalid Operation."
Example Usage
Input 2, then click +, then input 3 and press =, the result will be 5.
Press the C button to clear the display.
Code Structure
HTML (index.html): Contains the layout for the calculator's interface, including buttons for digits, operations, and clear functionality.

CSS (style.css and utility.css):

style.css: Provides styles for the calculator’s buttons, display, and overall layout.
utility.css: Adds helper classes for positioning and responsive design.
JavaScript (main.js and calc.js):

main.js: Manages the DOM and interacts with the HTML elements when a user clicks buttons.
calc.js: Implements the core functionality for performing calculations.
Technologies Used
HTML5 for structuring the web page.
CSS3 for styling the calculator.
JavaScript for interactivity and performing calculations.

