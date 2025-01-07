# Homework Task: Simple Calculator with DOM Manipulation

Create a basic calculator that can perform arithmetic operators. The calculator should have an interface where users can input two numbers and select an operation. The result should be displayed on the page.

### Requirements

- Additional operations: multiplication, division, and modulus.
- Error handling for division by zero and invalid inputs.
- A "Clear" button to reset all inputs and the result.
- Use of template literals for result display.
- A switch statement to handle different operations.
- Improved styling for better user experience.

Here's the starter code for the task:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Enhanced Calculator</title>
    <style>
      /* Apply some basic styles */
    </style>
  </head>
  <body>
    <div class="calculator">
      <input type="number" id="num1" placeholder="Enter first number" />
      <select id="operation">
        <option value="add">+</option>
        <option value="subtract">-</option>
        <option value="multiply">×</option>
        <option value="divide">÷</option>
        <option value="modulus">%</option>
      </select>
      <input type="number" id="num2" placeholder="Enter second number" />
      <button onclick="calculate()">Calculate</button>
      <button onclick="clearCalculator()">Clear</button>
      <div id="result"></div>
    </div>

    <script>
      // Your code here
    </script>
  </body>
</html>
```

This task incorporates several key concepts from the lesson:

- Variables and data types
- Functions
- Conditional statements
- Basic math operations
- DOM manipulation (selecting elements, modifying content)
- Event handling (button click)

### Final output demo

<video width="100%" height="auto" controls>
  <source src="demo.mp4" type="video/mp4">
</video>
